# 👤 Իմ Մասին

<style>
  .profile-container {
    display: grid;
    grid-template-columns: 280px 1fr;
    gap: 2rem;
    margin-top: 1.5rem;
    margin-bottom: 2.5rem;
  }

  @media (max-width: 768px) {
    .profile-container {
      grid-template-columns: 1fr;
    }
  }

  .profile-card {
    background: #18181b;
    border: 1px solid #27272a;
    border-radius: 16px;
    padding: 1.5rem;
    text-align: center;
  }

  .profile-img-placeholder {
    width: 100%;
    height: 240px;
    object-fit: cover;
    border-radius: 12px;
    border: 1px solid #3f3f46;
    margin-bottom: 1rem;
  }

  .profile-name {
    font-size: 1.5rem;
    font-weight: 800;
    color: #ffffff;
    margin: 0.5rem 0 0.2rem 0;
  }

  .profile-tag {
    color: #a1a1aa;
    font-size: 0.85rem;
    font-weight: 600;
    margin-bottom: 1rem;
  }

  .info-list {
    text-align: left;
    border-top: 1px solid #27272a;
    padding-top: 1rem;
    display: flex;
    flex-direction: column;
    gap: 0.6rem;
    font-size: 0.85rem;
    color: #d4d4d8;
  }

  .info-item {
    display: flex;
    justify-content: space-between;
  }

  .info-label {
    color: #a1a1aa;
  }

  .bio-content {
    display: flex;
    flex-direction: column;
    gap: 1.5rem;
  }

  .bio-box {
    background: #18181b;
    border: 1px solid #27272a;
    border-radius: 16px;
    padding: 1.5rem;
    color: #a1a1aa;
    line-height: 1.7;
  }

  .bio-box h3 {
    color: #ffffff;
    margin-top: 0;
    font-size: 1.3rem;
    border-bottom: 1px solid #27272a;
    padding-bottom: 0.5rem;
  }

  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(140px, 1fr));
    gap: 0.75rem;
    margin-top: 1rem;
  }

  .skill-badge {
    background: #27272a;
    border: 1px solid #3f3f46;
    color: #f4f4f5;
    padding: 0.5rem 0.75rem;
    border-radius: 8px;
    font-size: 0.85rem;
    font-weight: 600;
    text-align: center;
  }
</style>

<div class="profile-container">

  <!-- Left Column: Profile Card -->
  <div class="profile-card">
    <img src="../images/images(1).jpg" alt="Hayk Abrahamyan" class="profile-img-placeholder" onerror="this.src='https://via.placeholder.com/240x240/18181b/ffffff?text=Hayk+Abrahamyan'">
    
    <div class="profile-name">Հայկ Աբրահամյան</div>
    <div class="profile-tag">Fab Academy 2026 Student</div>

    <div class="info-list">
      <div class="info-item">
        <span class="info-label">📍 Ծննդավայր:</span>
        <span>Ճամբարակ</span>
      </div>
      <div class="info-item">
        <span class="info-label">🏫 Դպրոց:</span>
        <span>ԴԿԴ (2025-ից)</span>
      </div>
      <div class="info-item">
        <span class="info-label">🔬 ՖաբԼաբ:</span>
        <span>2026-ից</span>
      </div>
    </div>
  </div>

  <!-- Right Column: Story & Interests -->
  <div class="bio-content">

    <div class="bio-box">
      <h3>📖 Իմ Պատմությունը</h3>
      <p>
        Ես ծնվել և մեծացել եմ Գեղարքունիքի մարզի Ճամբարակ քաղաքում: 2025 թվականից սովորում եմ Դիլիջանի Կենտրոնական Դպրոցում, իսկ 2026-ին միացել եմ FabLab-ին:
      </p>
      <p>
        Իմ հիմնական հետաքրքրություններն են <strong>քիմիան</strong> և <strong>ինժեներիան</strong>: FabLab-ը ինձ հնարավորություն է տալիս համատեղել դպրոցում ձեռք բերած գիտական գիտելիքներս գործնական ինժեներական հմտությունների հետ՝ ապագա մասնագիտական ճանապարհս հարթելու համար:
      </p>
    </div>

    <div class="bio-box">
      <h3>🛠️ Հետաքրքրություններ և Հմտություններ</h3>
      <div class="skills-grid">
        <div class="skill-badge">🧪 Քիմիա</div>
        <div class="skill-badge">⚙️ Ինժեներիա</div>
        <div class="skill-badge">📐 3D Մոդելավորում</div>
        <div class="skill-badge">✂️ Լազերային Հատում</div>
        <div class="skill-badge">💻 Վեբ Մշակում</div>
        <div class="skill-badge">🔌 Էլեկտրոնիկա</div>
      </div>
    </div>

  </div>

</div>