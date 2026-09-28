<style>
  /* Base styles for dark theme look */
  .hero-card {
    background: #18181b;
    border: 1px solid #27272a;
    border-radius: 16px;
    padding: 2.5rem;
    margin-bottom: 2rem;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-between;
    gap: 2rem;
    color: #f4f4f5;
  }

  .hero-content {
    flex: 1;
    min-width: 280px;
  }

  .badge {
    display: inline-block;
    background: #27272a;
    color: #a1a1aa;
    font-size: 0.75rem;
    font-weight: 600;
    padding: 0.25rem 0.75rem;
    border-radius: 9999px;
    letter-spacing: 0.05em;
    text-transform: uppercase;
    margin-bottom: 1rem;
  }

  .hero-title {
    font-size: 2.8rem;
    font-weight: 800;
    line-height: 1.1;
    margin: 0 0 1rem 0;
    color: #ffffff;
  }

  .hero-subtitle {
    font-size: 1.2rem;
    font-weight: 600;
    color: #e4e4e7;
    margin-bottom: 0.75rem;
  }

  .hero-text {
    color: #a1a1aa;
    font-size: 0.95rem;
    line-height: 1.6;
    margin-bottom: 1.5rem;
  }

  .hero-buttons {
    display: flex;
    gap: 0.75rem;
    flex-wrap: wrap;
  }

  .btn-primary {
    background: #ffffff;
    color: #09090b !important;
    padding: 0.6rem 1.2rem;
    border-radius: 8px;
    font-weight: 600;
    text-decoration: none !important;
    transition: all 0.2s ease;
  }

  .btn-primary:hover {
    background: #e4e4e7;
  }

  .btn-secondary {
    background: #27272a;
    color: #f4f4f5 !important;
    padding: 0.6rem 1.2rem;
    border-radius: 8px;
    font-weight: 600;
    text-decoration: none !important;
    transition: all 0.2s ease;
  }

  .btn-secondary:hover {
    background: #3f3f46;
  }

  .hero-avatar-container {
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    width: 220px;
    height: 220px;
  }

  .avatar-circle {
    width: 140px;
    height: 140px;
    border-radius: 50%;
    background: linear-gradient(135deg, #27272a 0%, #09090b 100%);
    border: 2px solid #3f3f46;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 3rem;
    font-weight: 800;
    color: #ffffff;
    box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.5);
  }

  .tag-top {
    position: absolute;
    top: 0;
    right: 0;
    background: #27272a;
    color: #d4d4d8;
    font-size: 0.7rem;
    font-weight: 700;
    padding: 0.3rem 0.6rem;
    border-radius: 6px;
    border: 1px solid #3f3f46;
  }

  .tag-bottom {
    position: absolute;
    bottom: 10px;
    left: -10px;
    background: #27272a;
    color: #d4d4d8;
    font-size: 0.7rem;
    font-weight: 700;
    padding: 0.3rem 0.6rem;
    border-radius: 6px;
    border: 1px solid #3f3f46;
  }

  /* Split layout section */
  .grid-2col {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1.5rem;
    margin-bottom: 2.5rem;
  }

  @media (max-width: 768px) {
    .grid-2col {
      grid-template-columns: 1fr;
    }
  }

  .info-box {
    background: #18181b;
    border: 1px solid #27272a;
    border-radius: 12px;
    padding: 1.5rem;
    color: #a1a1aa;
    line-height: 1.6;
  }

  .steps-container {
    display: flex;
    flex-direction: column;
    gap: 0.75rem;
  }

  .step-card {
    background: #18181b;
    border: 1px solid #27272a;
    border-radius: 12px;
    padding: 1rem;
    display: flex;
    align-items: center;
    gap: 1rem;
  }

  .step-num {
    background: #27272a;
    color: #ffffff;
    font-weight: 700;
    width: 36px;
    height: 36px;
    border-radius: 8px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-shrink: 0;
  }

  .step-title {
    color: #ffffff;
    font-weight: 700;
    margin-bottom: 0.1rem;
  }

  .step-desc {
    color: #a1a1aa;
    font-size: 0.85rem;
  }

  .section-label {
    color: #a1a1aa;
    font-size: 0.8rem;
    font-weight: 700;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    margin-bottom: 0.5rem;
  }

  .section-heading {
    font-size: 2rem;
    font-weight: 800;
    color: #ffffff;
    margin-top: 0;
  }
</style>

<!-- Hero Banner Section -->
<div class="hero-card">
  <div class="hero-content">
    <span class="badge">• Fab Academy • Պորտֆոլիո</span>
    <h1 class="hero-title">Ես Հայկն եմ:</h1>
    <div class="hero-subtitle">Բարի գալուստ իմ Ֆաբ-Դպրոց ճանապարհորդություն:</div>
    <p class="hero-text">
      Այստեղ հավաքված են իմ շաբաթական աշխատանքները, փորձերը, նախագծերը, սովորած տեխնոլոգիաները և այն ամենը, ինչ ստեղծում եմ Ֆաբ-Դպրոցում:
    </p>
    <div class="hero-buttons">
      <a href="assignments/index.md" class="btn-primary">Դիտել առաջադրանքները →</a>
      <a href="about/index.md" class="btn-secondary">Իմ մասին</a>
    </div>
  </div>
  <div class="hero-avatar-container">
    <div class="tag-top">20 WEEKS</div>
    <div class="avatar-circle">H</div>
    <div class="tag-bottom">DIGITAL MAKER</div>
  </div>
</div>

<!-- Section 2: Journey & Steps -->
<h1 class="section-heading" style="margin-top: 2rem;">Իմ Ֆաբ—Դպրոցի ճանապարհորդությունը</h1>

<div class="grid-2col">
  <div class="info-box">
    <p><strong>Ես սովորում եմ՝ փորձելով, ստեղծելով և սխալներից սովորելով:</strong></p>
    <p>Այս կայքը իմ աշխատանքի թվային պորտֆոլիոն է:</p>
    <p>Յուրաքանչյուր շաբաթ այստեղ ավելացնում եմ նոր աշխատանքներ, փորձեր, նկարներ, կոդ և նախագծերի արդյունքներ:</p>
  </div>
  
  <div class="steps-container">
    <div class="step-card">
      <div class="step-num">01</div>
      <div>
        <div class="step-title">Փորձել</div>
        <div class="step-desc">Նոր գաղափարներ և տեխնոլոգիաներ:</div>
      </div>
    </div>
    <div class="step-card">
      <div class="step-num">02</div>
      <div>
        <div class="step-title">Ստեղծել</div>
        <div class="step-desc">Գաղափարները դարձնել իրական նախագծեր:</div>
      </div>
    </div>
    <div class="step-card">
      <div class="step-num">03</div>
      <div>
        <div class="step-title">Սովորել</div>
        <div class="step-desc">Ամեն աշխատանքից վերցնել նոր փորձ:</div>
      </div>
    </div>
  </div>
</div>

<!-- Section 3: Explore Header -->
<div class="section-label">EXPLORE</div>
<h2 class="section-heading">Ի՞նչ կարող ես գտնել այստեղ</h2>