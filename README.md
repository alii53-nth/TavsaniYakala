HEMEN BASLA 😔
import time
import sys

def yaz(mesaj, hiz=0.05):
    for harf in mesaj:
        sys.stdout.write(harf)
        sys.stdout.flush()
        time.sleep(hiz)
    print()

def kalp():
    print("❤️ " * 10)

def baslat():
    yaz("Merhaba Ceylin... 💬", 0.08)
    time.sleep(1)
    yaz("Sana uzun zamandır söylemek istediklerim var.", 0.07)
    yaz("Ama kelimeler yetmiyor bazen.", 0.07)
    time.sleep(1)
    yaz("O yüzden bir yol buldum kendimce...", 0.06)
    kalp()
    time.sleep(1)
    
    secim = input("Hazır mısın kalbimin kodlarına girmeye? (evet/hayır): ").lower()
    
    if secim == "evet":
        yaz("\nİşte başlıyoruz... 🎬", 0.06)
        time.sleep(1)
        yaz("Seninle konuşurken bile içim kıpır kıpır oluyor...", 0.06)
        yaz("Sesin arka planda çalan en güzel şarkı gibi...", 0.06)
        yaz("Ve gülüşün... ah Ceylin, gülüşün... 🌸", 0.07)
        kalp()
        yaz("Bu bir 'seni seviyorum' deme şekli...", 0.08)
        yaz("Hem kodla, hem kalple: S E N ❤️", 0.1)
    else:
        yaz("\nAnlıyorum... belki zamanı değildir.", 0.06)
        yaz("Ama bil ki bu kod her zaman senin için çalışır durumda olacak. 🕊️", 0.07)
        kalp()

baslat()
