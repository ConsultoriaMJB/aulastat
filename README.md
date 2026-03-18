<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Aulastat | Treinamentos em Análise de Dados</title>
  <meta
    name="description"
    content="Aulastat - Treinamentos em análise de dados com diversos softwares estatísticos."
  />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f8fafc;
      color: #1e293b;
      line-height: 1.6;
    }

    .container {
      width: 90%;
      max-width: 1100px;
      margin: 0 auto;
    }

    header {
      background: #0f172a;
      color: white;
      padding: 18px 0;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    .nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 20px;
      flex-wrap: wrap;
    }

    .brand h1 {
      font-size: 28px;
      margin-bottom: 4px;
    }

    .brand p {
      font-size: 14px;
      color: #cbd5e1;
    }

    .nav-actions {
      display: flex;
      gap: 12px;
      flex-wrap: wrap;
    }

    .btn {
      display: inline-block;
      padding: 12px 20px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s ease;
    }

    .btn-primary {
      background: #2563eb;
      color: white;
    }

    .btn-primary:hover {
      background: #1d4ed8;
    }

    .btn-secondary {
      background: white;
      color: #0f172a;
      border: 1px solid #cbd5e1;
    }

    .btn-secondary:hover {
      background: #f1f5f9;
    }

    .hero {
      background: linear-gradient(135deg, #0f172a, #1d4ed8);
      color: white;
      padding: 80px 0;
    }

    .hero-content {
      max-width: 760px;
    }

    .hero h2 {
      font-size: 42px;
      margin-bottom: 18px;
      line-height: 1.2;
    }

    .hero p {
      font-size: 18px;
      margin-bottom: 26px;
      color: #e2e8f0;
    }

    .hero-badges {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      margin-top: 18px;
    }

    .badge {
      background: rgba(255, 255, 255, 0.12);
      border: 1px solid rgba(255, 255, 255, 0.2);
      padding: 10px 14px;
      border-radius: 999px;
      font-size: 14px;
    }

    section {
      padding: 70px 0;
    }

    .section-title {
      font-size: 32px;
      margin-bottom: 14px;
      color: #0f172a;
    }

    .section-subtitle {
      color: #475569;
      margin-bottom: 32px;
      max-width: 760px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 22px;
    }

    .card {
      background: white;
      border-radius: 14px;
      padding: 24px;
      box-shadow: 0 8px 24px rgba(15, 23, 42, 0.07);
      border: 1px solid #e2e8f0;
    }

    .card h3 {
      margin-bottom: 12px;
      color: #0f172a;
      font-size: 22px;
    }

    .card p {
      color: #475569;
      margin-bottom: 14px;
    }

    .status {
      display: inline-block;
      padding: 8px 12px;
      border-radius: 999px;
      font-size: 13px;
      font-weight: bold;
    }

    .status.available {
      background: #dcfce7;
      color: #166534;
    }

    .status.soon {
      background: #fef3c7;
      color: #92400e;
    }

    .highlight-box {
      background: #eff6ff;
      border: 1px solid #bfdbfe;
      padding: 28px;
      border-radius: 14px;
    }

    .highlight-box h3 {
      margin-bottom: 12px;
      color: #1d4ed8;
    }

    .highlight-box p {
      color: #334155;
      margin-bottom: 10px;
    }

    .faq-item {
      background: white;
      border-radius: 12px;
      padding: 22px;
      margin-bottom: 18px;
      box-shadow: 0 6px 18px rgba(15, 23, 42, 0.05);
      border: 1px solid #e2e8f0;
    }

    .faq-item h4 {
      margin-bottom: 10px;
      color: #0f172a;
      font-size: 20px;
    }

    .cta-box {
      background: #0f172a;
      color: white;
      padding: 40px;
      border-radius: 18px;
      text-align: center;
    }

    .cta-box h2 {
      font-size: 30px;
      margin-bottom: 14px;
    }

    .cta-box p {
      color: #cbd5e1;
      margin-bottom: 22px;
    }

    footer {
      background: #020617;
      color: #cbd5e1;
      text-align: center;
      padding: 24px 12px;
      font-size: 14px;
    }

    ul.clean-list {
      padding-left: 18px;
      color: #475569;
    }

    ul.clean-list li {
      margin-bottom: 8px;
    }

    @media (max-width: 768px) {
      .hero h2 {
        font-size: 32px;
      }

      .section-title {
        font-size: 28px;
      }

      .cta-box {
        padding: 28px 20px;
      }
    }
  </style>
</head>
<body id="top">
  <header>
    <div class="container nav">
      <div class="brand">
        <h1>Aulastat</h1>
        <p>Treinamentos em análise de dados com diversos softwares estatísticos</p>
      </div>

      <div class="nav-actions">
        <a class="btn btn-secondary" href="#cursos">Cursos</a>
        <a class="btn btn-secondary" href="#faq">FAQ</a>
        <a
          class="btn btn-primary"
          href="https://wa.me/861421450?text=Olá,%20quero%20saber%20mais%20sobre%20os%20treinamentos%20da%20Aulastat."
          target="_blank"
          rel="noopener"
        >
          Falar no WhatsApp
        </a>
      </div>
    </div>
  </header>

  <section class="hero">
    <div class="container">
      <div class="hero-content">
        <h2>Aprenda análise de dados com mais direção, prática e clareza</h2>
        <p>
          A Aulastat é uma plataforma de treinamentos focada em softwares estatísticos e
          ferramentas de pesquisa, pensada para estudantes, pesquisadores e profissionais
          que desejam dominar análise de dados de forma aplicada.
        </p>

        <div class="nav-actions">
          <a
            class="btn btn-primary"
            href="https://wa.me/861421450?text=Olá,%20quero%20me%20inscrever%20ou%20receber%20informações%20sobre%20os%20cursos%20da%20Aulastat."
            target="_blank"
            rel="noopener"
          >
            Pedir informações
          </a>
          <a class="btn btn-secondary" href="#cursos">Ver cursos</a>
        </div>

        <div class="hero-badges">
          <div class="badge">100% online</div>
          <div class="badge">Foco prático</div>
          <div class="badge">Acompanhamento orientado</div>
          <div class="badge">Voltado para pesquisa e trabalhos académicos</div>
        </div>
      </div>
    </div>
  </section>

  <section id="cursos">
    <div class="container">
      <h2 class="section-title">Cursos disponíveis</h2>
      <p class="section-subtitle">
        Abaixo estão os cursos da Aulastat. O treinamento de SPSS já está disponível.
        Os demais cursos estarão disponíveis dentro de 20 dias.
      </p>

      <div class="grid">
        <div class="card">
          <h3>SPSS</h3>
          <p>
            Treinamento já disponível para estudantes, pesquisadores e profissionais que
            desejam aprender análise de dados de forma prática.
          </p>
          <span class="status available">Disponível agora</span>
        </div>

        <div class="card">
          <h3>R</h3>
          <p>Curso em preparação para análise estatística, visualização de dados e pesquisa aplicada.</p>
          <span class="status soon">Disponível em até 20 dias</span>
        </div>

        <div class="card">
          <h3>STATA</h3>
          <p>Curso em preparação com foco em econometria, análise quantitativa e investigação científica.</p>
          <span class="status soon">Disponível em até 20 dias</span>
        </div>

        <div class="card">
          <h3>Excel</h3>
          <p>Curso em preparação para organização, tratamento e análise de dados em ambiente profissional.</p>
          <span class="status soon">Disponível em até 20 dias</span>
        </div>

        <div class="card">
          <h3>NVivo</h3>
          <p>Curso em preparação para análise de dados qualitativos, codificação e interpretação temática.</p>
          <span class="status soon">Disponível em até 20 dias</span>
        </div>

        <div class="card">
          <h3>Atlas.ti</h3>
          <p>Curso em preparação para análise qualitativa e organização de evidências em pesquisas.</p>
          <span class="status soon">Disponível em até 20 dias</span>
        </div>

        <div class="card">
          <h3>KoboToolbox</h3>
          <p>Curso em preparação para recolha de dados digitais, formulários e monitoria em campo.</p>
          <span class="status soon">Disponível em até 20 dias</span>
        </div>

        <div class="card">
          <h3>Google Forms</h3>
          <p>Curso em preparação para criação de formulários, questionários e recolha de dados online.</p>
          <span class="status soon">Disponível em até 20 dias</span>
        </div>
      </div>
    </div>
  </section>

  <section>
    <div class="container">
      <div class="highlight-box">
        <h3>Treinamento de SPSS já disponível</h3>
        <p>
          O curso de SPSS é atualmente o treinamento com inscrições abertas na Aulastat.
        </p>
        <ul class="clean-list">
          <li>Duração de 10 dias de aulas gravadas</li>
          <li>30 dias de acompanhamento com tutor</li>
          <li>Acesso às aulas gravadas por um ano</li>
          <li>Modalidade 100% online</li>
          <li>Certificado incluído conforme as condições da organização</li>
        </ul>
      </div>
    </div>
  </section>

  <section id="faq">
    <div class="container">
      <h2 class="section-title">Perguntas frequentes</h2>

      <div class="faq-item">
        <h4>Qual é a duração do curso de SPSS?</h4>
        <p>
          A duração é de 10 dias de aulas gravadas e 30 dias de acompanhamento com o tutor.
          O estudante também terá acesso às aulas gravadas por um ano.
        </p>
      </div>

      <div class="faq-item">
        <h4>Qual é a modalidade?</h4>
        <p>
          O treinamento é 100% online, com aulas gravadas organizadas por módulos e
          acompanhamento com tutor, permitindo maior flexibilidade no processo de aprendizagem.
        </p>
      </div>

      <div class="faq-item">
        <h4>Preciso já dominar estatística?</h4>
        <p>
          Não. Os treinamentos são pensados para permitir evolução progressiva, com foco na prática.
        </p>
      </div>

      <div class="faq-item">
        <h4>O certificado está incluído?</h4>
        <p>
          Sim. O certificado faz parte do treinamento, de acordo com as condições definidas pela organização.
        </p>
      </div>

      <div class="faq-item">
        <h4>Os outros cursos já estão disponíveis?</h4>
        <p>
          Neste momento, o curso de SPSS já está disponível. Os cursos de R, STATA, Excel,
          NVivo, Atlas.ti, KoboToolbox e Google Forms estarão disponíveis dentro de 20 dias.
        </p>
      </div>

      <div class="faq-item">
        <h4>Como faço para me inscrever ou pedir informações?</h4>
        <p>
          Basta clicar no botão abaixo para falar diretamente connosco no WhatsApp
          e receber as orientações.
        </p>
        <div style="margin-top: 16px;">
          <a
            class="btn btn-primary"
            href="https://wa.me/861421450?text=Olá,%20quero%20receber%20informações%20sobre%20os%20treinamentos%20da%20Aulastat."
            target="_blank"
            rel="noopener"
          >
            Falar no WhatsApp
          </a>
        </div>
      </div>
    </div>
  </section>

  <section>
    <div class="container">
      <div class="cta-box">
        <h2>Pronto para começar?</h2>
        <p>
          Receba agora informações sobre inscrições, datas, pagamento e funcionamento
          dos treinamentos da Aulastat diretamente no WhatsApp.
        </p>
        <div class="nav-actions" style="justify-content: center;">
          <a
            class="btn btn-primary"
            href="https://wa.me/861421450?text=Olá,%20quero%20entrar%20nos%20treinamentos%20da%20Aulastat."
            target="_blank"
            rel="noopener"
          >
            Falar no WhatsApp
          </a>
          <a class="btn btn-secondary" href="#top">Voltar ao início</a>
        </div>
      </div>
    </div>
  </section>

  <footer>
    © 2026 Aulastat — Treinamentos em análise de dados com diversos softwares estatísticos
  </footer>
</body>
</html>
