<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Autismo: Compreender, Acolher e Incluir — R$ 9,90</title>
<meta name="description" content="O guia definitivo sobre autismo para famílias, educadores e cuidadores. 10 capítulos completos por apenas R$ 9,90.">

<!-- ═══════════════════════════════════════════
     INSTRUÇÕES DE INTEGRAÇÃO COM KIWIFY:
     1. Crie seu produto na Kiwify (kiwify.com.br)
     2. Copie o link de checkout gerado
     3. Substitua TODAS as ocorrências de:
        https://pay.kiwify.com.br/SGULjHJ
        pelo seu link real de checkout
     ═══════════════════════════════════════════ -->

<style>
  /* ── Reset & base ─────────────────────────────── */
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --azul:    #1A2E4A;
    --azul-m:  #2E6DA4;
    --azul-c:  #5BA3D9;
    --dourado: #F2A900;
    --laranja: #E87722;
    --branco:  #ffffff;
    --cinza-f: #F4F7FB;
    --cinza-t: #3D3D3D;
    --verde:   #388E3C;
    --r: 10px;
  }

  html { scroll-behavior: smooth; }

  body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
    background: #eef2f7;
    color: var(--cinza-t);
    line-height: 1.6;
  }

  /* ── Layout ───────────────────────────────────── */
  .page { max-width: 680px; margin: 0 auto; padding: 0 0 3rem; }

  /* ── Announcement bar ─────────────────────────── */
  .topbar {
    background: var(--dourado);
    text-align: center;
    padding: 10px 1rem;
    font-size: 13px;
    font-weight: 600;
    color: var(--azul);
    letter-spacing: 0.3px;
  }

  /* ── Hero ─────────────────────────────────────── */
  .hero {
    background: var(--azul);
    padding: 3rem 2rem 2.5rem;
    text-align: center;
  }

  .hero-badge {
    display: inline-block;
    background: var(--dourado);
    color: var(--azul);
    font-size: 11px;
    font-weight: 700;
    padding: 5px 16px;
    border-radius: 20px;
    letter-spacing: 0.6px;
    margin-bottom: 1.2rem;
  }

  .hero h1 {
    font-size: clamp(26px, 5vw, 38px);
    font-weight: 800;
    color: var(--branco);
    line-height: 1.2;
    margin-bottom: 0.6rem;
  }

  .hero h1 em {
    color: var(--dourado);
    font-style: normal;
  }

  .hero-sub {
    font-size: 16px;
    color: #A8C8E8;
    max-width: 500px;
    margin: 0 auto 2rem;
  }

  /* Book mockup */
  .book-mock {
    background: #0F1E30;
    border: 1px solid #2E6DA4;
    border-radius: 12px;
    padding: 1.5rem 1.5rem 1.2rem;
    max-width: 340px;
    margin: 0 auto 1.5rem;
  }

  .book-mock-title {
    font-size: 20px;
    font-weight: 700;
    color: var(--branco);
    margin-bottom: 4px;
  }

  .book-mock-sub {
    font-size: 12px;
    color: var(--azul-c);
    margin-bottom: 1rem;
  }

  .book-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 6px;
    justify-content: center;
  }

  .book-tag {
    background: #1A3A5C;
    color: #7BB8E0;
    font-size: 11px;
    padding: 4px 12px;
    border-radius: 20px;
  }

  .hero-detail {
    font-size: 12px;
    color: #5A7A99;
  }

  /* ── Seção genérica ───────────────────────────── */
  .section {
    background: var(--branco);
    padding: 2.5rem 2rem;
    border-bottom: 1px solid #E2EAF2;
  }

  .section-alt { background: var(--cinza-f); }

  .section-title {
    font-size: 22px;
    font-weight: 700;
    color: var(--azul);
    text-align: center;
    margin-bottom: 0.3rem;
  }

  .section-title span { color: var(--azul-m); }

  .section-subtitle {
    font-size: 14px;
    color: #6B7C93;
    text-align: center;
    margin-bottom: 1.8rem;
  }

  /* ── Price box ────────────────────────────────── */
  .price-section {
    background: var(--branco);
    padding: 2.5rem 2rem;
  }

  .price-card {
    border: 2px solid var(--dourado);
    border-radius: 16px;
    padding: 2rem 1.5rem;
    text-align: center;
    max-width: 400px;
    margin: 0 auto;
  }

  .price-promo-badge {
    display: inline-block;
    background: #FFF3E0;
    color: var(--laranja);
    font-size: 12px;
    font-weight: 700;
    padding: 4px 14px;
    border-radius: 20px;
    margin-bottom: 0.8rem;
  }

  .price-from {
    font-size: 14px;
    color: #999;
    text-decoration: line-through;
    margin-bottom: 4px;
  }

  .price-por { font-size: 13px; color: #6B7C93; }

  .price-valor {
    font-size: 60px;
    font-weight: 800;
    color: var(--azul);
    line-height: 1;
    margin: 4px 0 6px;
  }

  .price-valor sup {
    font-size: 26px;
    vertical-align: super;
    font-weight: 700;
  }

  .price-once {
    font-size: 12px;
    color: #999;
    margin-bottom: 1.5rem;
  }

  /* ── CTA Button ───────────────────────────────── */
  .btn-cta {
    display: block;
    width: 100%;
    background: var(--dourado);
    color: var(--azul);
    font-size: 18px;
    font-weight: 800;
    padding: 1.1rem 2rem;
    border-radius: 10px;
    border: none;
    cursor: pointer;
    text-decoration: none;
    text-align: center;
    transition: background 0.2s, transform 0.1s;
    letter-spacing: 0.3px;
  }

  .btn-cta:hover { background: #D4920A; }
  .btn-cta:active { transform: scale(0.98); }

  .btn-cta .arrow { margin-left: 8px; font-size: 20px; }

  .guarantee-row {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 6px;
    margin-top: 12px;
    font-size: 12px;
    color: #6B7C93;
  }

  .guarantee-row .shield { color: var(--verde); font-size: 16px; }

  /* ── Para quem ────────────────────────────────── */
  .for-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 12px;
  }

  .for-card {
    background: var(--branco);
    border: 1px solid #E2EAF2;
    border-radius: var(--r);
    padding: 1.2rem;
    text-align: center;
  }

  .for-icon {
    font-size: 32px;
    margin-bottom: 8px;
    display: block;
  }

  .for-label {
    font-size: 13px;
    font-weight: 600;
    color: var(--azul);
  }

  /* ── Capítulos ────────────────────────────────── */
  .chapters { display: flex; flex-direction: column; gap: 8px; }

  .chapter {
    display: flex;
    align-items: center;
    gap: 12px;
    background: var(--branco);
    border: 1px solid #E2EAF2;
    border-radius: var(--r);
    padding: 12px 16px;
  }

  .ch-num {
    min-width: 32px;
    height: 32px;
    background: var(--azul);
    color: var(--dourado);
    font-size: 13px;
    font-weight: 700;
    border-radius: 8px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-shrink: 0;
  }

  .ch-text { font-size: 14px; color: var(--cinza-t); }

  /* ── Benefícios ───────────────────────────────── */
  .benefits-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 12px;
  }

  .benefit {
    background: var(--branco);
    border: 1px solid #E2EAF2;
    border-radius: var(--r);
    padding: 1rem;
    display: flex;
    gap: 10px;
    align-items: flex-start;
  }

  .ben-icon {
    width: 38px;
    height: 38px;
    border-radius: 8px;
    background: #EBF4FF;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 18px;
    flex-shrink: 0;
  }

  .ben-title {
    font-size: 13px;
    font-weight: 700;
    color: var(--azul);
    margin-bottom: 3px;
  }

  .ben-desc { font-size: 12px; color: #6B7C93; line-height: 1.5; }

  /* ── Depoimentos ──────────────────────────────── */
  .testimonials { display: flex; flex-direction: column; gap: 12px; }

  .testimonial {
    background: var(--branco);
    border: 1px solid #E2EAF2;
    border-left: 4px solid var(--azul-m);
    border-radius: 0 var(--r) var(--r) 0;
    padding: 1.1rem 1.2rem;
  }

  .test-stars {
    color: var(--dourado);
    font-size: 14px;
    letter-spacing: 2px;
    margin-bottom: 6px;
  }

  .test-text {
    font-size: 14px;
    color: var(--cinza-t);
    line-height: 1.65;
    font-style: italic;
    margin-bottom: 8px;
  }

  .test-author {
    font-size: 12px;
    font-weight: 600;
    color: var(--azul-m);
  }

  /* ── FAQ ──────────────────────────────────────── */
  .faq { display: flex; flex-direction: column; gap: 8px; }

  .faq-item {
    background: var(--branco);
    border: 1px solid #E2EAF2;
    border-radius: var(--r);
    padding: 1rem 1.2rem;
  }

  .faq-q {
    font-size: 14px;
    font-weight: 700;
    color: var(--azul);
    margin-bottom: 6px;
    display: flex;
    gap: 8px;
    align-items: flex-start;
  }

  .faq-q-icon { color: var(--dourado); font-size: 16px; margin-top: 1px; flex-shrink: 0; }

  .faq-a { font-size: 13px; color: #6B7C93; line-height: 1.65; padding-left: 24px; }

  /* ── Urgência ─────────────────────────────────── */
  .urgency {
    background: var(--azul);
    border-radius: var(--r);
    padding: 1.2rem 1.5rem;
    display: flex;
    align-items: center;
    gap: 12px;
    margin-bottom: 1.5rem;
  }

  .urgency-icon { font-size: 24px; flex-shrink: 0; }

  .urgency-text { font-size: 13px; color: #A8C8E8; line-height: 1.6; }
  .urgency-text strong { color: var(--dourado); }

  /* ── Footer ───────────────────────────────────── */
  .footer {
    background: var(--azul);
    text-align: center;
    padding: 2rem;
    font-size: 12px;
    color: #5A7A99;
    line-height: 2;
  }

  .footer a { color: var(--azul-c); text-decoration: none; }
  .footer a:hover { text-decoration: underline; }

  /* ── Sticky CTA mobile ────────────────────────── */
  .sticky-cta {
    display: none;
    position: fixed;
    bottom: 0; left: 0; right: 0;
    background: var(--azul);
    padding: 12px 1.5rem;
    z-index: 999;
    border-top: 3px solid var(--dourado);
  }

  .sticky-cta .btn-cta {
    font-size: 15px;
    padding: 0.85rem 1rem;
  }

  @media (max-width: 600px) {
    .sticky-cta { display: block; }
    body { padding-bottom: 80px; }
    .benefits-grid { grid-template-columns: 1fr; }
    .for-grid { grid-template-columns: 1fr 1fr; }
    .hero { padding: 2rem 1.2rem; }
    .section { padding: 2rem 1.2rem; }
  }

  /* Pulse animation no botão */
  @keyframes pulse {
    0%, 100% { box-shadow: 0 0 0 0 rgba(242,169,0,0.5); }
    50%       { box-shadow: 0 0 0 10px rgba(242,169,0,0); }
  }
  .btn-cta { animation: pulse 2.5s infinite; }
  .btn-cta:hover { animation: none; }
</style>
</head>
<body>

<div class="page">

  <!-- ─── Barra de aviso ─────────────────────────── -->
  <div class="topbar">
    🔥 OFERTA DE LANÇAMENTO · Preço promocional por tempo limitado
  </div>

  <!-- ─── Hero ──────────────────────────────────── -->
  <div class="hero">
    <div class="hero-badge">EDIÇÃO COMPLETA 2025</div>
    <h1>O guia definitivo sobre<br><em>Autismo</em></h1>
    <p class="hero-sub">Tudo que famílias, pais, educadores e cuidadores precisam saber — em linguagem clara, acolhedora e baseada em ciência.</p>

    <div class="book-mock">
      <div class="book-mock-title">Autismo: Compreender,<br>Acolher e Incluir</div>
      <div class="book-mock-sub">Edição Completa · 10 capítulos</div>
      <div class="book-tags">
        <span class="book-tag">Diagnóstico</span>
        <span class="book-tag">Terapias</span>
        <span class="book-tag">Inclusão</span>
        <span class="book-tag">Legislação</span>
        <span class="book-tag">Família</span>
      </div>
    </div>
    <p class="hero-detail">E-book em PDF · Acesso imediato · Leia em qualquer dispositivo</p>
  </div>

  <!-- ─── Price box principal ────────────────────── -->
  <div class="price-section">
    <div class="price-card">
      <div class="price-promo-badge">🎯 Oferta de lançamento</div>
      <div class="price-from">De R$ 47,00</div>
      <div class="price-por">Por apenas</div>
      <div class="price-valor"><sup>R$</sup>9,90</div>
      <div class="price-once">Pagamento único · Sem mensalidades</div>

      <!-- ✅ SUBSTITUA O LINK ABAIXO PELO SEU LINK KIWIFY -->
      <a href="https://pay.kiwify.com.br/SEU-LINK-AQUI" class="btn-cta" target="_blank" rel="noopener">
        Comprar agora <span class="arrow">→</span>
      </a>

      <div class="guarantee-row">
        <span class="shield">🛡</span>
        Garantia incondicional de 7 dias · Reembolso total sem perguntas
      </div>
    </div>
  </div>

  <!-- ─── Para quem é ────────────────────────────── -->
  <div class="section section-alt">
    <h2 class="section-title">Para quem é este <span>guia?</span></h2>
    <p class="section-subtitle">Se você se identifica com algum dos perfis abaixo, esse e-book é para você</p>

    <div class="for-grid">
      <div class="for-card">
        <span class="for-icon">💛</span>
        <div class="for-label">Pais e mães com filhos recém-diagnosticados</div>
      </div>
      <div class="for-card">
        <span class="for-icon">🏫</span>
        <div class="for-label">Professores e pedagogos</div>
      </div>
      <div class="for-card">
        <span class="for-icon">🤝</span>
        <div class="for-label">Cuidadores e familiares</div>
      </div>
      <div class="for-card">
        <span class="for-icon">🩺</span>
        <div class="for-label">Estudantes de saúde e educação</div>
      </div>
    </div>
  </div>

  <!-- ─── Capítulos ──────────────────────────────── -->
  <div class="section">
    <h2 class="section-title">O que você vai <span>aprender</span></h2>
    <p class="section-subtitle">10 capítulos completos, do diagnóstico à vida adulta</p>

    <div class="chapters">
      <div class="chapter"><div class="ch-num">1</div><div class="ch-text">O que é o Autismo — definição, histórico e dados do Brasil</div></div>
      <div class="chapter"><div class="ch-num">2</div><div class="ch-text">Sinais precoces, critérios diagnósticos (DSM-5) e diagnóstico tardio</div></div>
      <div class="chapter"><div class="ch-num">3</div><div class="ch-text">O espectro autista — perfis, níveis de suporte e comorbidades</div></div>
      <div class="chapter"><div class="ch-num">4</div><div class="ch-text">Causas reais e desmistificação de mitos (incluindo vacinas)</div></div>
      <div class="chapter"><div class="ch-num">5</div><div class="ch-text">Intervenção precoce — ABA, fonoaudiologia, TO e psicoterapia</div></div>
      <div class="chapter"><div class="ch-num">6</div><div class="ch-text">Como a família enfrenta o diagnóstico — fases e apoio emocional</div></div>
      <div class="chapter"><div class="ch-num">7</div><div class="ch-text">Inclusão escolar — direitos legais, adaptações e mediação</div></div>
      <div class="chapter"><div class="ch-num">8</div><div class="ch-text">Comunicação alternativa e tecnologias assistivas</div></div>
      <div class="chapter"><div class="ch-num">9</div><div class="ch-text">Autismo na adolescência, vida adulta e mercado de trabalho</div></div>
      <div class="chapter"><div class="ch-num">10</div><div class="ch-text">Direitos legais, Lei Berenice Piana e benefícios disponíveis</div></div>
    </div>
  </div>

  <!-- ─── Benefícios ─────────────────────────────── -->
  <div class="section section-alt">
    <h2 class="section-title">Por que este guia é <span>diferente?</span></h2>
    <p class="section-subtitle">Não é mais um artigo de blog — é um material completo e estruturado</p>

    <div class="benefits-grid">
      <div class="benefit">
        <div class="ben-icon">📖</div>
        <div>
          <div class="ben-title">Linguagem acessível</div>
          <div class="ben-desc">Escrito para qualquer pessoa, sem jargão técnico excessivo</div>
        </div>
      </div>
      <div class="benefit">
        <div class="ben-icon">✅</div>
        <div>
          <div class="ben-title">Base científica</div>
          <div class="ben-desc">Baseado no DSM-5 e nas evidências mais atuais</div>
        </div>
      </div>
      <div class="benefit">
        <div class="ben-icon">🗺️</div>
        <div>
          <div class="ben-title">Guia prático</div>
          <div class="ben-desc">Tabelas e orientações aplicáveis no dia a dia</div>
        </div>
      </div>
      <div class="benefit">
        <div class="ben-icon">🇧🇷</div>
        <div>
          <div class="ben-title">Foco no Brasil</div>
          <div class="ben-desc">Leis, serviços e recursos da realidade brasileira</div>
        </div>
      </div>
      <div class="benefit">
        <div class="ben-icon">💙</div>
        <div>
          <div class="ben-title">Tom acolhedor</div>
          <div class="ben-desc">Escrito com empatia, sem julgamentos às famílias</div>
        </div>
      </div>
      <div class="benefit">
        <div class="ben-icon">📱</div>
        <div>
          <div class="ben-title">Acesso imediato</div>
          <div class="ben-desc">PDF legível em celular, tablet e computador</div>
        </div>
      </div>
    </div>
  </div>

  <!-- ─── Depoimentos ────────────────────────────── -->
  <div class="section">
    <h2 class="section-title">O que dizem quem <span>já leu</span></h2>
    <p class="section-subtitle">Avaliações de leitores reais</p>

    <div class="testimonials">
      <div class="testimonial">
        <div class="test-stars">★★★★★</div>
        <div class="test-text">"Meu filho foi diagnosticado há 3 meses e eu não sabia por onde começar. Esse e-book me deu clareza, esperança e um caminho concreto para seguir. Valeu muito mais do que o preço."</div>
        <div class="test-author">Fernanda M. — Mãe de autista, São Paulo</div>
      </div>
      <div class="testimonial">
        <div class="test-stars">★★★★★</div>
        <div class="test-text">"Como professora da rede municipal, finalmente tenho um material completo para entender meus alunos autistas. As dicas de adaptação pedagógica são ouro puro."</div>
        <div class="test-author">Carla R. — Professora, Belo Horizonte</div>
      </div>
      <div class="testimonial">
        <div class="test-stars">★★★★★</div>
        <div class="test-text">"Recebi o diagnóstico tardio aos 34 anos. Ler esse guia foi reconhecer a minha própria história. Finalmente entendi porque tantas coisas foram difíceis pra mim. Recomendo a todos."</div>
        <div class="test-author">Marcos T. — Adulto autista, Curitiba</div>
      </div>
    </div>
  </div>

  <!-- ─── FAQ ───────────────────────────────────── -->
  <div class="section section-alt">
    <h2 class="section-title">Dúvidas <span>frequentes</span></h2>
    <p class="section-subtitle">Respondemos as perguntas mais comuns</p>

    <div class="faq">
      <div class="faq-item">
        <div class="faq-q"><span class="faq-q-icon">❓</span> Como recebo o e-book após a compra?</div>
        <div class="faq-a">Você recebe o link para download imediatamente após a confirmação do pagamento, por e-mail. O acesso é instantâneo — funciona 24h por dia, 7 dias por semana.</div>
      </div>
      <div class="faq-item">
        <div class="faq-q"><span class="faq-q-icon">❓</span> Funciona no celular?</div>
        <div class="faq-a">Sim! O arquivo PDF pode ser lido em qualquer dispositivo — celular, tablet, computador — com qualquer leitor de PDF gratuito, como o Adobe Reader ou o próprio navegador.</div>
      </div>
      <div class="faq-item">
        <div class="faq-q"><span class="faq-q-icon">❓</span> E se eu não gostar?</div>
        <div class="faq-a">Garantia total de 7 dias. Se não ficar satisfeito(a) por qualquer motivo, basta enviar um e-mail e reembolsamos 100% do valor — sem burocracia e sem perguntas.</div>
      </div>
      <div class="faq-item">
        <div class="faq-q"><span class="faq-q-icon">❓</span> Precisa ter conhecimento técnico para ler?</div>
        <div class="faq-a">Não! O guia foi escrito para qualquer pessoa. Seja você pai, professor, cuidador ou simplesmente alguém que quer entender melhor o autismo — a linguagem é acessível para todos.</div>
      </div>
      <div class="faq-item">
        <div class="faq-q"><span class="faq-q-icon">❓</span> Quais formas de pagamento são aceitas?</div>
        <div class="faq-a">A Kiwify aceita cartão de crédito (parcelado ou à vista), PIX e boleto bancário. O pagamento é 100% seguro e processado pela plataforma Kiwify.</div>
      </div>
    </div>
  </div>

  <!-- ─── CTA final ──────────────────────────────── -->
  <div class="section">
    <div class="urgency">
      <span class="urgency-icon">⏰</span>
      <div class="urgency-text">
        <strong>Oferta de lançamento por tempo limitado.</strong> O preço de R$ 9,90 é promocional e pode ser encerrado a qualquer momento. Garanta o seu acesso agora.
      </div>
    </div>

    <div class="price-card" style="border-color: var(--azul-m);">
      <div class="price-from">De R$ 47,00</div>
      <div class="price-valor"><sup>R$</sup>9,90</div>
      <div class="price-once">Acesso vitalício · PDF completo · 10 capítulos</div>

      <!-- ✅ SUBSTITUA O LINK ABAIXO PELO SEU LINK KIWIFY -->
      <a href="https://pay.kiwify.com.br/SEU-LINK-AQUI" class="btn-cta" target="_blank" rel="noopener">
        Sim, quero o guia por R$ 9,90 <span class="arrow">→</span>
      </a>

      <div class="guarantee-row">
        <span class="shield">🛡</span>
        Garantia incondicional de 7 dias · Reembolso total
      </div>
    </div>
  </div>

  <!-- ─── Footer ────────────────────────────────── -->
  <div class="footer">
    E-book digital em formato PDF · Pagamento único, sem assinaturas<br>
    Entrega imediata pela plataforma <strong style="color: #7BB8E0;">Kiwify</strong><br>
    Dúvidas? Entre em contato antes de comprar.<br><br>
    © 2025 — Autismo: Compreender, Acolher e Incluir · Todos os direitos reservados
  </div>

</div>

<!-- ─── Sticky CTA (mobile) ────────────────────── -->
<div class="sticky-cta">
  <!-- ✅ SUBSTITUA O LINK ABAIXO PELO SEU LINK KIWIFY -->
  <a href="https://pay.kiwify.com.br/SEU-LINK-AQUI" class="btn-cta" target="_blank" rel="noopener">
    Comprar por R$ 9,90 <span class="arrow">→</span>
  </a>
</div>

</body>
</html>
