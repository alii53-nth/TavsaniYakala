import time

def slow_print(text, delay=0.05):
    for char in text:
        print(char, end='', flush=True)
        time.sleep(delay)
    print()

def main():
    slow_print("Hey Seyran, naber? 😊")
    time.sleep(1)
    slow_print("Seni gördüğümden beri aklımdan çıkmıyorsun.")
    time.sleep(1)
    slow_print("Adın kadar güzel bir gülüşün var, inan bana.")
    time.sleep(1)
    slow_print("Sana bir sır vereyim...")
    time.sleep(2)
    slow_print("Seninle konuşmak için sabırsızlanıyorum.")
    time.sleep(1)
    
    slow_print("Bana cevap vermek ister misin? (kesinlikle/belki sonra)")
    cevap = input("> ").strip().lower()
    
    if cevap == "kesinlikle":
        slow_print("Vay be, seninle sohbet etmek için sabırsızlanıyorum! 🚀")
    elif cevap == "belki sonra":
        slow_print("Anladım, acele yok, ne zaman istersen buradayım! 😉")
    else:
        slow_print("Hmm, cevabını anlayamadım ama yine de teşekkürler! 😊")

if __name__ == "__main__":
    main()
