<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <meta name="description" content="MT STORE - Hospedagem de servidores SAMP com qualidade e os melhores preços.">
  <meta name="theme-color" content="#c40000">
  <title>MT STORE</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #0e0e0e;
      color: #fff;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(to right, #c40000, #900000);
      padding: 20px;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0,0,0,0.4);
    }

    header h1 {
      font-size: 36px;
      letter-spacing: 1px;
    }

    nav {
      background-color: #1a1a1a;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      padding: 12px 0;
      position: sticky;
      top: 0;
      z-index: 100;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: 600;
      transition: 0.3s;
    }

    nav a:hover {
      color: #c40000;
    }

    main {
      padding: 40px 20px;
      text-align: center;
    }

    h2 {
      font-size: 28px;
      margin-bottom: 20px;
    }

    .accordion {
      max-width: 600px;
      margin: 0 auto;
      border: 1px solid #333;
      border-radius: 10px;
      overflow: hidden;
      background-color: #1a1a1a;
    }

    .accordion-header {
      padding: 20px;
      background-color: #292929;
      cursor: pointer;
      font-weight: bold;
      text-align: left;
      display: flex;
      justify-content: space-between;
      align-items: center;
      font-size: 18px;
    }

    .accordion-content {
      max-height: 0;
      overflow: hidden;
      transition: max-height 0.4s ease;
      padding: 0 20px;
    }

    .accordion-content.open {
      max-height: 400px;
      padding: 20px;
    }

    .accordion-content pre {
      font-family: monospace;
      white-space: pre-wrap;
      line-height: 1.6;
      color: #ccc;
    }

    .contato-box {
      max-width: 500px;
      margin: 40px auto;
      background-color: #1a1a1a;
      padding: 20px;
      border-radius: 10px;
      text-align: left;
    }

    .contato-box a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      display: flex;
      align-items: center;
      margin-bottom: 10px;
    }

    .contato-box a:hover {
      color: #c40000;
    }

    .contato-box img {
      width: 20px;
      height: 20px;
      margin-right: 10px;
    }

    footer {
      background-color: #111;
      text-align: center;
      padding: 20px;
      color: #888;
    }

    .contato-links a {
      display: inline-block;
      margin: 0 10px;
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }

    .contato-links a:hover {
      color: #c40000;
    }

    .contato-links img {
      vertical-align: middle;
      width: 20px;
      height: 20px;
      margin-right: 5px;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 28px;
      }

      h2 {
        font-size: 24px;
      }

      .accordion-header {
        font-size: 16px;
      }

      .contato-box {
        padding: 15px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>MT STORE</h1>
  </header>

  <nav>
    <a href="#">Início</a>
    <a href="#produtos">Produtos</a>
    <a href="#contato">Contato</a>
    <a href="#">Sobre</a>
  </nav>

  <main>
    <h2>Bem-vindo à MT STORE</h2>
    <p>Confira nossos produtos de qualidade com os melhores preços!</p>

    <section id="produtos">
      <h2 style="margin-top: 60px;">Produtos</h2>

      <div class="accordion">
        <div class="accordion-header" role="button" tabindex="0" aria-expanded="false">
          LOJA MT STORE <span class="arrow">▼</span>
        </div>
        <div class="accordion-content">
<pre>
╠ PING = BR
╠📦 50 slots - samp por | R$5,00
╠📦 100 slots - samp por | R$10,00
╠📦 150 slots - samp por | R$15,00
╠📦 200 slots - samp por | R$20,00
╠📦 250 slots - samp por | R$25,00
╠📦 300 slots - samp por | R$30,00
╠◈ ✧
╠◈ ✧ Atendimento das 08:00 às 23h59
╠◈ MT STORE AGRADECE SEU CONTATO
</pre>
        </div>
      </div>
    </section>

    <section id="contato">
      <h2 style="margin-top: 60px;">Entre em Contato</h2>
      <div class="contato-box">
        <a href="https://wa.me/5519992545529" target="_blank">
          <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/svg/1f4f2.svg" alt="WhatsApp"> WhatsApp (19) 99254-5529
        </a>
        <a href="https://wa.me/5531999145325" target="_blank">
          <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/svg/1f4f2.svg" alt="WhatsApp"> WhatsApp (31) 99914-5325
        </a>
        <a href="https://discord.gg/PpKB7d9DNv" target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/2111/2111370.png" alt="Discord"> Entrar no Discord
        </a>
      </div>
    </section>
  </main>

  <footer>
    &copy; 2025 MT STORE. Todos os direitos reservados.
    <div class="contato-links">
      <a href="https://wa.me/5519992545529" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/svg/1f4f2.svg" alt="WhatsApp"> WhatsApp
      </a>
      <a href="https://discord.gg/PpKB7d9DNv" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/2111/2111370.png" alt="Discord"> Discord
      </a>
    </div>
  </footer>

  <script>
    document.addEventListener("DOMContentLoaded", () => {
      document.querySelectorAll(".accordion-header").forEach(header => {
        header.addEventListener("click", () => {
          const content = header.nextElementSibling;
          const arrow = header.querySelector(".arrow");
          const isOpen = content.classList.toggle("open");

          arrow.textContent = isOpen ? "▲" : "▼";
          header.setAttribute("aria-expanded", isOpen);
        });
      });
    });
  </script>
</body>
</html>
