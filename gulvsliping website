<!DOCTYPE html>
<html lang="no">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Gulvsliping | Profesjonell sliping av parkettgulv</title>
  <meta
    name="description"
    content="Profesjonell gulvsliping, lakking, oljing og reparasjon av parkettgulv. Få et gratis tilbud i dag."
  />
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      color: #222;
      background: linear-gradient(to bottom, #f8f5ef, #ffffff, #f9f1e7);
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    img {
      max-width: 100%;
      display: block;
    }

    .container {
      width: 90%;
      max-width: 1200px;
      margin: 0 auto;
    }

    .topbar {
      position: sticky;
      top: 0;
      z-index: 1000;
      backdrop-filter: blur(10px);
      background: rgba(255, 255, 255, 0.9);
      border-bottom: 1px solid #eee;
    }

    .nav {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 18px 0;
    }

    .logo {
      font-size: 28px;
      font-weight: bold;
      color: #1e1e1e;
      letter-spacing: 0.5px;
    }

    .logo span {
      color: #b8860b;
    }

    .nav-links {
      display: flex;
      gap: 22px;
      flex-wrap: wrap;
    }

    .nav-links a {
      color: #333;
      font-weight: 600;
      transition: 0.2s;
    }

    .nav-links a:hover {
      color: #b8860b;
    }

    .btn {
      display: inline-block;
      padding: 14px 22px;
      border-radius: 14px;
      font-weight: bold;
      transition: 0.25s;
      cursor: pointer;
      border: none;
    }

    .btn-primary {
      background: #1f1f1f;
      color: #fff;
    }

    .btn-primary:hover {
      background: #000;
      transform: translateY(-1px);
    }

    .btn-secondary {
      background: #fff;
      color: #222;
      border: 1px solid #ddd;
    }

    .btn-secondary:hover {
      background: #f6f6f6;
    }

    .hero {
      padding: 70px 0 50px;
      position: relative;
      overflow: hidden;
    }

    .hero-grid {
      display: grid;
      grid-template-columns: 1.1fr 0.9fr;
      gap: 40px;
      align-items: center;
    }

    .badge {
      display: inline-block;
      background: #fff;
      color: #5a4a1b;
      border: 1px solid #eee;
      padding: 10px 14px;
      border-radius: 999px;
      font-size: 14px;
      margin-bottom: 18px;
      box-shadow: 0 8px 24px rgba(0,0,0,0.05);
    }

    .hero h1 {
      font-size: 52px;
      line-height: 1.1;
      margin-bottom: 20px;
      color: #171717;
    }

    .hero p {
      font-size: 18px;
      color: #555;
      max-width: 650px;
      margin-bottom: 28px;
    }

    .hero-buttons {
      display: flex;
      gap: 14px;
      flex-wrap: wrap;
    }

    .hero-card {
      background: rgba(255,255,255,0.75);
      border: 1px solid rgba(255,255,255,0.7);
      border-radius: 28px;
      padding: 14px;
      box-shadow: 0 25px 80px rgba(0,0,0,0.12);
      backdrop-filter: blur(8px);
    }

    .hero-card img {
      border-radius: 22px;
      min-height: 430px;
      object-fit: cover;
      width: 100%;
    }

    section {
      padding: 70px 0;
    }

    .section-head {
      text-align: center;
      margin-bottom: 40px;
    }

    .section-head span {
      display: inline-block;
      font-size: 13px;
      letter-spacing: 2px;
      text-transform: uppercase;
      color: #9a6f00;
      font-weight: bold;
      margin-bottom: 10px;
    }

    .section-head h2 {
      font-size: 38px;
      margin-bottom: 12px;
      color: #1f1f1f;
    }

    .section-head p {
      max-width: 760px;
      margin: 0 auto;
      color: #666;
      font-size: 17px;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 22px;
    }

    .card {
      background: rgba(255,255,255,0.92);
      border: 1px solid #f0e6cf;
      border-radius: 24px;
      padding: 26px;
      box-shadow: 0 10px 35px rgba(0,0,0,0.08);
      transition: 0.25s;
    }

    .card:hover {
      transform: translateY(-4px);
      box-shadow: 0 18px 45px rgba(0,0,0,0.12);
    }

    .accordion-button {
      width: 100%;
      background: transparent;
      border: none;
      text-align: left;
      cursor: pointer;
      font: inherit;
      color: inherit;
    }

    .accordion-top {
      display: flex;
      justify-content: space-between;
      align-items: flex-start;
      gap: 15px;
    }

    .accordion-top h3 {
      font-size: 22px;
      margin-bottom: 10px;
      color: #1d1d1d;
    }

    .accordion-top p {
      color: #666;
    }

    .plus {
      min-width: 40px;
      width: 40px;
      height: 40px;
      border-radius: 50%;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      background: #f5e5b9;
      color: #1d1d1d;
      font-size: 24px;
      font-weight: bold;
    }

    .accordion-content {
      display: none;
      margin-top: 18px;
      padding: 16px;
      background: linear-gradient(to right, #fff7e8, #f8f4ec);
      border-radius: 16px;
      color: #444;
    }

    .accordion-item.active .accordion-content {
      display: block;
    }

    .benefits-wrap {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 28px;
      align-items: start;
    }

    .benefits-text h2 {
      font-size: 38px;
      margin: 14px 0;
    }

    .benefits-text p {
      color: #666;
      font-size: 17px;
    }

    .benefits-box {
      background: linear-gradient(to bottom right, #faf7f1, #f9efd8);
      border: 1px solid #f0e2bb;
      padding: 26px;
      border-radius: 24px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.05);
    }

    .benefit {
      display: flex;
      gap: 14px;
      align-items: flex-start;
      background: rgba(255,255,255,0.85);
      padding: 16px;
      border-radius: 18px;
      border: 1px solid #f5f0e4;
      margin-bottom: 14px;
    }

    .benefit:last-child {
      margin-bottom: 0;
    }

    .check {
      min-width: 28px;
      width: 28px;
      height: 28px;
      border-radius: 50%;
      background: #1f1f1f;
      color: white;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      font-size: 14px;
      margin-top: 2px;
    }

    .dark-section {
      background: linear-gradient(to bottom right, #111, #1f1f1f, #3b3428);
      color: white;
      border-radius: 34px;
      padding: 40px;
      box-shadow: 0 25px 80px rgba(0,0,0,0.25);
    }

    .process-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 18px;
      margin-top: 24px;
    }

    .process-card {
      background: rgba(255,255,255,0.08);
      border-radius: 20px;
      padding: 22px;
    }

    .process-card .number {
      color: #f0c96b;
      font-size: 14px;
      margin-bottom: 6px;
    }

    .process-card h3 {
      margin-bottom: 8px;
      font-size: 21px;
    }

    .process-card p {
      color: #ddd;
    }

    .faq-list {
      max-width: 900px;
      margin: 0 auto;
    }

    .faq-item {
      background: rgba(255,255,255,0.92);
      border: 1px solid #f0e6cf;
      border-radius: 22px;
      box-shadow: 0 10px 35px rgba(0,0,0,0.06);
      margin-bottom: 14px;
      overflow: hidden;
    }

    .faq-button {
      width: 100%;
      border: none;
      background: transparent;
      text-align: left;
      padding: 22px;
      cursor: pointer;
      font: inherit;
    }

    .faq-top {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 14px;
    }

    .faq-top h3 {
      font-size: 20px;
      color: #1d1d1d;
    }

    .faq-content {
      display: none;
      padding: 0 22px 22px;
      color: #555;
    }

    .faq-item.active .faq-content {
      display: block;
    }

    .contact-section {
      background: linear-gradient(to bottom, #fbf3e3, #f4efe9);
    }

    .contact-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 28px;
      align-items: start;
    }

    .contact-box h2 {
      font-size: 38px;
      margin: 12px 0 14px;
    }

    .contact-box p {
      color: #666;
      max-width: 580px;
    }

    .contact-info {
      margin-top: 24px;
    }

    .contact-info p {
      margin-bottom: 8px;
      color: #333;
    }

    .form-card {
      background: rgba(255,255,255,0.92);
      border: 1px solid #f0e6cf;
      border-radius: 28px;
      padding: 28px;
      box-shadow: 0 20px 50px rgba(0,0,0,0.08);
    }

    .form-group {
      margin-bottom: 18px;
    }

    .form-group label {
      display: block;
      margin-bottom: 8px;
      font-weight: bold;
      color: #222;
    }

    .form-group input,
    .form-group textarea {
      width: 100%;
      padding: 14px 16px;
      border: 1px solid #d9d9d9;
      border-radius: 14px;
      font-size: 16px;
      outline: none;
    }

    .form-group input:focus,
    .form-group textarea:focus {
      border-color: #b8860b;
    }

    footer {
      background: rgba(255,255,255,0.85);
      border-top: 1px solid #eee;
      padding: 28px 0;
      text-align: center;
      color: #666;
    }

    @media (max-width: 900px) {
      .hero-grid,
      .benefits-wrap,
      .contact-grid,
      .cards,
      .process-grid {
        grid-template-columns: 1fr;
      }

      .hero h1,
      .section-head h2,
      .benefits-text h2,
      .contact-box h2 {
        font-size: 34px;
      }

      .nav {
        flex-direction: column;
        gap: 14px;
      }

      .nav-links {
        justify-content: center;
      }
    }

    @media (max-width: 600px) {
      .hero {
        padding-top: 40px;
      }

      .hero h1 {
        font-size: 28px;
      }

      .section-head h2,
      .benefits-text h2,
      .contact-box h2 {
        font-size: 28px;
      }

      .btn {
        width: 100%;
        text-align: center;
      }

      .hero-buttons {
        flex-direction: column;
      }

      .dark-section {
        padding: 24px;
      }
    }
  </style>
</head>
<body>
  <div class="topbar">
    <div class="container nav">
      <div class="logo">Gulv<span>sliping</span></div>
      <div class="nav-links">
        <a href="#tjenester">Tjenester</a>
        <a href="#fordeler">Fordeler</a>
        <a href="#prosess">Prosess</a>
        <a href="#faq">FAQ</a>
        <a href="#kontakt">Kontakt</a>
      </div>
    </div>
  </div>

  <header class="hero">
    <div class="container hero-grid">
      <div>
        <div class="badge">Profesjonell gulvsliping i Norge</div>
        <h1>Gulvsliping for parkett som ser ut som ny</h1>
        <p>
          Vi hjelper deg med sliping, behandling og fornyelse av parkettgulv.
          Enten du ønsker et moderne matt uttrykk eller en klassisk finish,
          leverer vi et resultat du kan være stolt av.
        </p>
        <div class="hero-buttons">
          <a href="#kontakt" class="btn btn-primary">Be om gratis tilbud</a>
          <a href="#tjenester" class="btn btn-secondary">Se våre tjenester</a>
        </div>
      </div>

      <div class="hero-card">
        <img
          src="https://images.unsplash.com/photo-1505693416388-ac5ce068fe85?auto=format&fit=crop&w=1200&q=80"
          alt="Nyslipt parkettgulv i stue"
        />
      </div>
    </div>
  </header>

  <section id="tjenester">
    <div class="container">
      <div class="section-head">
        <span>Tjenester</span>
        <h2>Hva vi tilbyr</h2>
        <p>
          Vi tilbyr komplette løsninger for deg som vil fornye gamle parkettgulv
          og få et varig og eksklusivt resultat.
        </p>
      </div>

      <div class="cards">
        <div class="card accordion-item">
          <button class="accordion-button">
            <div class="accordion-top">
              <div>
                <h3>Gulvsliping</h3>
                <p>
                  Vi sliper parkettgulv skånsomt og effektivt, slik at gulvet får
                  et nytt og jevnt uttrykk.
                </p>
              </div>
              <span class="plus">+</span>
            </div>
          </button>
          <div class="accordion-content">
            Vi bruker profesjonelt slipeutstyr som fjerner slitasje, små riper og
            ujevnheter. Dette gir gulvet en frisk overflate som er klar for ny
            behandling og lang levetid.
          </div>
        </div>

        <div class="card accordion-item">
          <button class="accordion-button">
            <div class="accordion-top">
              <div>
                <h3>Lakking og oljing</h3>
                <p>
                  Velg mellom slitesterk lakk eller naturlig olje for et resultat
                  som passer hjemmet ditt.
                </p>
              </div>
              <span class="plus">+</span>
            </div>
          </button>
          <div class="accordion-content">
            Vi hjelper deg å velge riktig finish basert på bruk, stil og ønsket
            vedlikehold. Lakk gir høy slitestyrke, mens olje gir et mer naturlig
            og varmt utseende.
          </div>
        </div>

        <div class="card accordion-item">
          <button class="accordion-button">
            <div class="accordion-top">
              <div>
                <h3>Reparasjon av parkett</h3>
                <p>
                  Vi utbedrer riper, hakk og mindre skader før overflatebehandling.
                </p>
              </div>
              <span class="plus">+</span>
            </div>
          </button>
          <div class="accordion-content">
            Før sliping vurderer vi skader i gulvet og utfører nødvendige
            utbedringer. Dette kan inkludere fylling av små sprekker, justering av
            løse bord og forbedring av helhetsinntrykket.
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="fordeler">
    <div class="container benefits-wrap">
      <div class="benefits-text">
        <span style="display:block;font-size:13px;letter-spacing:2px;text-transform:uppercase;color:#9a6f00;font-weight:bold;">
          Hvorfor velge oss
        </span>
        <h2>Trygg, effektiv og pen gulvfornyelse</h2>
        <p>
          Vi jobber med fokus på detaljer, rene linjer og et pent sluttresultat.
          Målet vårt er å gi nytt liv til gulvet ditt og samtidig gjøre prosessen
          enkel og forutsigbar.
        </p>
      </div>

      <div class="benefits-box">
        <div class="benefit">
          <span class="check">✓</span>
          <div>Gratis befaring og pristilbud</div>
        </div>
        <div class="benefit">
          <span class="check">✓</span>
          <div>Erfaring med parkett, tregulv og heltre</div>
        </div>
        <div class="benefit">
          <span class="check">✓</span>
          <div>Ryddig arbeid og høy kvalitet</div>
        </div>
        <div class="benefit">
          <span class="check">✓</span>
          <div>Rask respons og fleksible tider</div>
        </div>
      </div>
    </div>
  </section>

  <section id="prosess">
    <div class="container">
      <div class="dark-section">
        <div class="section-head" style="margin-bottom: 10px; text-align:left;">
          <span style="color:#f0c96b;">Prosess</span>
          <h2 style="color:white;">Slik jobber vi</h2>
          <p style="color:#d9d9d9; max-width:700px; margin:0;">
            Klikk på hvert trinn for å se mer informasjon om hvordan vi jobber fra
            befaring til ferdig resultat.
          </p>
        </div>

        <div class="process-grid">
          <div class="process-card accordion-item">
            <button class="accordion-button">
              <div class="accordion-top">
                <div>
                  <div class="number">1</div>
                  <h3>Befaring</h3>
                  <p>Vi vurderer gulvet og gir deg et tydelig tilbud.</p>
                </div>
                <span class="plus">+</span>
              </div>
            </button>
            <div class="accordion-content" style="background:rgba(255,255,255,0.08); color:#f2f2f2;">
              Under befaringen ser vi på gulvtype, slitasjegrad, tidligere
              behandling og eventuelle skader. Deretter gir vi anbefaling om
              løsning, tidsbruk og pris.
            </div>
          </div>

          <div class="process-card accordion-item">
            <button class="accordion-button">
              <div class="accordion-top">
                <div>
                  <div class="number">2</div>
                  <h3>Sliping</h3>
                  <p>Vi sliper gulvet jevnt og profesjonelt.</p>
                </div>
                <span class="plus">+</span>
              </div>
            </button>
            <div class="accordion-content" style="background:rgba(255,255,255,0.08); color:#f2f2f2;">
              Selve slipearbeidet utføres i flere trinn for å oppnå et jevnt og
              pent resultat. Vi jobber systematisk for å redusere støv og sikre
              høy kvalitet i hele rommet.
            </div>
          </div>

          <div class="process-card accordion-item">
            <button class="accordion-button">
              <div class="accordion-top">
                <div>
                  <div class="number">3</div>
                  <h3>Behandling</h3>
                  <p>Vi avslutter med ønsket overflate og finish.</p>
                </div>
                <span class="plus">+</span>
              </div>
            </button>
            <div class="accordion-content" style="background:rgba(255,255,255,0.08); color:#f2f2f2;">
              Når gulvet er ferdig slipt, påfører vi ønsket behandling som lakk
              eller olje. Dette beskytter overflaten og gir gulvet det uttrykket
              du ønsker.
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="faq">
    <div class="container">
      <div class="section-head">
        <span>FAQ</span>
        <h2>Ofte stilte spørsmål</h2>
        <p>
          Her finner du svar på vanlige spørsmål om parkettsliping, behandling og
          prosessen rundt arbeidet.
        </p>
      </div>

      <div class="faq-list">
        <div class="faq-item">
          <button class="faq-button">
            <div class="faq-top">
              <h3>Hvor lang tid tar gulvsliping?</h3>
              <span class="plus">+</span>
            </div>
          </button>
          <div class="faq-content">
            Tiden avhenger av areal, gulvtype og valgt behandling. For vanlige rom
            kan arbeidet ofte utføres i løpet av 1–2 dager, mens større prosjekter
            kan ta lenger tid.
          </div>
        </div>

        <div class="faq-item">
          <button class="faq-button">
            <div class="faq-top">
              <h3>Blir det mye støv under sliping?</h3>
              <span class="plus">+</span>
            </div>
          </button>
          <div class="faq-content">
            Vi bruker moderne slipeutstyr med effektiv støvoppsamling for å
            redusere støv mest mulig. Det vil alltid være noe arbeid rundt
            prosessen, men vi jobber ryddig og skånsomt.
          </div>
        </div>

        <div class="faq-item">
          <button class="faq-button">
            <div class="faq-top">
              <h3>Kan gammel parkett bli som ny igjen?</h3>
              <span class="plus">+</span>
            </div>
          </button>
          <div class="faq-content">
            I mange tilfeller ja. Sliping og riktig behandling kan gi gammel
            parkett et betydelig løft, så lenge gulvet har nok slitesjikt og ikke
            er for hardt skadet.
          </div>
        </div>

        <div class="faq-item">
          <button class="faq-button">
            <div class="faq-top">
              <h3>Hva er best – lakk eller olje?</h3>
              <span class="plus">+</span>
            </div>
          </button>
          <div class="faq-content">
            Det kommer an på ønsket uttrykk og vedlikehold. Lakk gir en slitesterk
            overflate som er enkel å rengjøre, mens olje gir et mer naturlig og
            eksklusivt preg med litt mer vedlikehold.
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="contact-section" id="kontakt">
    <div class="container contact-grid">
      <div class="contact-box">
        <span style="display:block;font-size:13px;letter-spacing:2px;text-transform:uppercase;color:#9a6f00;font-weight:bold;">
          Kontakt
        </span>
        <h2>Ta kontakt for gratis pristilbud</h2>
        <p>
          Fortell oss litt om gulvet ditt, størrelsen på området og hva du ønsker
          hjelp med. Vi svarer så raskt som mulig.
        </p>

        <div class="contact-info">
          <p><strong>Telefon:</strong> +47 99 99 99 99</p>
          <p><strong>E-post:</strong> post@gulvsliping.no</p>
          <p><strong>Område:</strong> Oslo og omegn</p>
        </div>
      </div>

      <div class="form-card">
        <form onsubmit="sendForm(event)">
          <div class="form-group">
            <label for="name">Navn</label>
            <input type="text" id="name" placeholder="Ditt navn" required />
          </div>

          <div class="form-group">
            <label for="phone">Telefon</label>
            <input type="text" id="phone" placeholder="Ditt telefonnummer" required />
          </div>

          <div class="form-group">
            <label for="message">Melding</label>
            <textarea id="message" rows="5" placeholder="Skriv litt om gulvet og hva du ønsker hjelp med" required></textarea>
          </div>

          <button type="submit" class="btn btn-primary" style="width:100%;">
            Send forespørsel
          </button>
        </form>
      </div>
    </div>
  </section>

  <footer>
    © 2026 Gulvsliping. Alle rettigheter forbeholdt.
  </footer>

  <script>
    const accordionItems = document.querySelectorAll('.accordion-item');

    accordionItems.forEach((item) => {
      const button = item.querySelector('.accordion-button');
      const plus = item.querySelector('.plus');

      button.addEventListener('click', () => {
        const isActive = item.classList.contains('active');

        accordionItems.forEach((other) => {
          other.classList.remove('active');
          const otherPlus = other.querySelector('.plus');
          if (otherPlus) otherPlus.textContent = '+';
        });

        if (!isActive) {
          item.classList.add('active');
          if (plus) plus.textContent = '−';
        }
      });
    });

    const faqItems = document.querySelectorAll('.faq-item');

    faqItems.forEach((item) => {
      const button = item.querySelector('.faq-button');
      const plus = item.querySelector('.plus');

      button.addEventListener('click', () => {
        const isActive = item.classList.contains('active');

        faqItems.forEach((other) => {
          other.classList.remove('active');
          const otherPlus = other.querySelector('.plus');
          if (otherPlus) otherPlus.textContent = '+';
        });

        if (!isActive) {
          item.classList.add('active');
          if (plus) plus.textContent = '−';
        }
      });
    });

    function sendForm(event) {
      event.preventDefault();
      alert('Takk! Forespørselen din er sendt.');
    }
  </script>
</body>
</html>
