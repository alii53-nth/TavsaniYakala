<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <title>🐇 Mesaj Var!</title>
  <style>
    body {
      background: #111;
      color: #fff;
      font-family: 'Courier New', monospace;
      padding: 30px;
      font-size: 20px;
    }
    #terminal {
      white-space: pre-wrap;
      line-height: 1.5;
    }
    input {
      background: #222;
      color: #fff;
      border: 1px solid #555;
      padding: 8px;
      font-size: 18px;
      width: 300px;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <div id="terminal"></div>
  <input type="text" id="cevap" placeholder="cevabını yaz..." style="display:none;" />

  <script>
    const mesajlar = [
      "Hey Seyran, naber? 😊",
      "Seni gördüğümden beri aklımdan çıkmıyorsun.",
      "Adın kadar güzel bir gülüşün var, inan bana.",
      "Sana bir sır vereyim...",
      "Seninle konuşmak için sabırsızlanıyorum.",
      "Bana cevap vermek ister misin? (kesinlikle / belki sonra)"
    ];

    const terminal = document.getElementById("terminal");
    const input = document.getElementById("cevap");

    let index = 0;

    function yaz(text, delay = 50) {
      return new Promise(resolve => {
        let i = 0;
        let yazInterval = setInterval(() => {
          terminal.innerHTML += text[i];
          i++;
          if (i >= text.length) {
            clearInterval(yazInterval);
            terminal.innerHTML += "\n\n";
            resolve();
          }
        }, delay);
      });
    }

    async function basla() {
      for (const mesaj of mesajlar.slice(0, -1)) {
        await yaz(mesaj);
        await new Promise(r => setTimeout(r, 1000));
      }

      await yaz(mesajlar[mesajlar.length - 1]);
      input.style.display = "block";
      input.focus();

      input.addEventListener("keydown", function handler(e) {
        if (e.key === "Enter") {
          const cevap = input.value.trim().toLowerCase();
          input.removeEventListener("keydown", handler);
          input.style.display = "none";

          if (cevap === "kesinlikle") {
            yaz("Vay be, seninle sohbet etmek için sabırsızlanıyorum! 🚀");
          } else if (cevap === "belki sonra") {
            yaz("Anladım, acele yok, ne zaman istersen buradayım! 😉");
          } else {
            yaz("Hmm, cevabını anlayamadım ama yine de teşekkürler! 😊");
          }
        }
      });
    }

    basla();
  </script>
</body>
</html>
