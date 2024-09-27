<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Blog de Inteligência Artificial</title>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap">
  <style>
      body {
          font-family: 'Montserrat', sans-serif;
          margin: 0;
          padding: 0;
          background-color: #f3e5f5; /* Lilás claro */
          color: #333;
      }
      header {
          background-color: #ab47bc; /* Lilás vibrante */
          color: #fff;
          padding: 20px;
          text-align: center;
          box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      }
      header h1 {
          margin: 0;
          font-size: 2.5em;
          font-family: 'Great Vibes', cursive; /* Título em caligrafia */
      }
      nav {
          margin-top: 15px;
      }
      nav a {
          color: #fff;
          text-decoration: none;
          padding: 12px 25px;
          background-color: #ce93d8; /* Lilás médio */
          border-radius: 5px;
          margin: 0 5px;
          font-weight: bold;
      }
      nav a:hover {
          background-color: #8e24aa; /* Lilás escuro */
      }
      .container {
          width: 85%;
          margin: auto;
          overflow: hidden;
      }
      .post {
          background: #fff;
          padding: 30px;
          margin: 20px 0;
          border-radius: 10px;
          box-shadow: 0 6px 15px rgba(0, 0, 0, 0.1);
      }
      .post h2 {
          margin-top: 0;
          font-size: 2.2em;
          color: #ab47bc; /* Lilás vibrante */
          font-family: 'Great Vibes', cursive; /* Título em caligrafia */
      }
      .post p {
          line-height: 1.8;
          font-size: 1.1em;
      }
      .post img {
          max-width: 100%;
          border-radius: 8px;
          margin: 20px 0;
      }
      .author, .date {
          font-size: 0.9em;
          color: #555;
      }
      table {
          width: 100%;
          border-collapse: collapse;
          margin: 20px 0;
      }
      table, th, td {
          border: 1px solid #ddd; /* Cinza claro */
      }
      th, td {
          padding: 15px;
          text-align: left;
      }
      th {
          background-color: #f3e5f5; /* Lilás claro */
      }
      footer {
          background-color: #ab47bc; /* Lilás vibrante */
          color: #fff;
          text-align: center;
          padding: 20px;
          position: fixed;
          width: 100%;
          bottom: 0;
          box-shadow: 0 -4px 10px rgba(0, 0, 0, 0.1);
      }
      footer p {
          margin: 0;
      }
      a {
          color: #f48fb1; /* Rosa claro */
      }
      a:hover {
          color: #c2185b; /* Rosa escuro */
      }
  </style>
</head>
<body>
  <header>
      <div class="container">
          <h1>Blog de Inteligência Artificial</h1>
          <nav>
              <a href="#home">Início</a>
              <a href="#posts">Artigos</a>
              <a href="#about">Sobre</a>
              <a href="#contact">Contato</a>
          </nav>
      </div>
  </header>


  <div class="container">
      <section id="home">
          <div class="post">
              <h2>Bem-vindo ao Blog de Inteligência Artificial</h2>
              <p>Este blog oferece uma visão aprofundada sobre Inteligência Artificial, desde conceitos básicos até as mais recentes inovações e discussões éticas. Navegue pelos nossos artigos para entender melhor como a IA está moldando o futuro.</p>
              <img src="ia-tec.jpg" alt="Imagem sobre IA">
          </div>
      </section>


      <section id="posts">
          <div class="post">
              <h2>Avanços Recentes em IA</h2>
              <p class="date">Publicado em 15 de setembro de 2024</p>
              <p class="author">Autor: Dr. João Silva</p>
              <p>Nos últimos anos, a Inteligência Artificial tem avançado a passos largos. Novos algoritmos e técnicas estão sendo desenvolvidos para melhorar a capacidade das máquinas em reconhecer padrões e tomar decisões.</p>
              <img src="ia-tec.jpg" alt="Avanços em IA">
              <h3>Tabela de Avanços Tecnológicos</h3>
              <table>
                  <thead>
                      <tr>
                          <th>Tecnologia</th>
                          <th>Descrição</th>
                          <th>Impacto</th>
                      </tr>
                  </thead>
                  <tbody>
                      <tr>
                          <td>Aprendizado Profundo</td>
                          <td>Algoritmos que imitam a estrutura do cérebro humano.</td>
                          <td>Melhora na precisão de reconhecimento de imagem.</td>
                      </tr>
                      <tr>
                          <td>Redes Neurais Convolucionais</td>
                          <td>Redes projetadas para processar dados com uma estrutura de grade.</td>
                          <td>Avanços em processamento de imagem e vídeo.</td>
                      </tr>
                      <tr>
                          <td>IA Generativa</td>
                          <td>Modelos que criam novos dados com base em dados existentes.</td>
                          <td>Criação de conteúdo e design automatizado.</td>
                      </tr>
                  </tbody>
              </table>
          </div>


          <div class="post">
              <h2>Desafios Éticos na Inteligência Artificial</h2>
              <p class="date">Publicado em 10 de setembro de 2024</p>
              <p class="author">Autor: Ana Costa</p>
              <p>À medida que a IA se torna mais prevalente, surgem preocupações éticas significativas. Este artigo aborda os principais desafios éticos e as possíveis soluções para garantir que a tecnologia seja usada de forma responsável.</p>
              <img src="ima.jpg" alt="Desafios Éticos">
              <h3>Principais Questões Éticas</h3>
              <ul>
                  <li><strong>Privacidade:</strong> Como os dados pessoais são coletados e utilizados?</li>
                  <li><strong>Discriminação:</strong> Como evitar preconceitos em algoritmos?</li>
                  <li><strong>Responsabilidade:</strong> Quem é responsável por decisões tomadas por IA?</li>
              </ul>
          </div>


          <div class="post">
              <h2>Impactos da IA no Mercado de Trabalho</h2>
              <p class="date">Publicado em 5 de setembro de 2024</p>
              <p class="author">Autor: Roberto Lima</p>
              <p>A Inteligência Artificial está transformando o mercado de trabalho de diversas maneiras. Este artigo explora como a automação está substituindo alguns empregos e criando novas oportunidades.</p>
              <img src="imags.jpg" alt="Impactos da IA no Trabalho">
              <h3>Setores Afetados</h3>
              <ul>
                  <li><strong>Indústria:</strong> Automação de processos de produção.</li>
                  <li><strong>Serviços Financeiros:</strong> Análise preditiva e gestão de risco.</li>
                  <li><strong>Saúde:</strong> Diagnóstico assistido por IA e administração de tratamentos.</li>
              </ul>
          </div>
      </section>


      <section id="about">
          <div class="post">
              <h2>Sobre o Blog</h2>
              <p>Este blog foi criado para proporcionar uma análise detalhada sobre a Inteligência Artificial, abordando tanto aspectos técnicos quanto questões éticas e sociais. Nosso objetivo é informar e educar leitores interessados em entender o impacto desta tecnologia revolucionária.</p>
          </div>
      </section>


      <section id="contact">
          <div class="post">
              <h2>Contato</h2>
              <p>Para perguntas, sugestões ou colaborações, entre em contato conosco através do e-mail: <a href="mailto:contato@blogia.com">contato@blogia.com</a>.</p>
          </div>
      </section>
  </div>


  <footer>
      <p








