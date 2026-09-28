# 📚 Weekly Assignments Dashboard

Select a module below to explore the detailed documentation, code, and CAD models.

---

<style>
  .assignments-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 1.5rem;
    margin-top: 1.5rem;
  }

  .card-item {
    background: #18181b;
    border: 1px solid #27272a;
    border-radius: 12px;
    padding: 1.5rem;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    transition: transform 0.2s ease, border-color 0.2s ease;
  }

  .card-item:hover {
    transform: translateY(-4px);
    border-color: #3f3f46;
  }

  .card-header {
    font-size: 1.25rem;
    font-weight: 700;
    color: #ffffff;
    margin-bottom: 0.5rem;
  }

  .card-subtitle {
    color: #e4e4e7;
    font-size: 0.95rem;
    font-weight: 600;
    margin-bottom: 0.5rem;
  }

  .card-desc {
    color: #a1a1aa;
    font-size: 0.85rem;
    line-height: 1.5;
    margin-bottom: 1.25rem;
  }

  .card-link {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    color: #ffffff !important;
    background: #27272a;
    padding: 0.5rem 1rem;
    border-radius: 6px;
    font-size: 0.85rem;
    font-weight: 600;
    text-decoration: none !important;
    width: fit-content;
    transition: background 0.2s ease;
  }

  .card-link:hover {
    background: #3f3f46;
  }
</style>

<div class="assignments-grid">

  <div class="card-item">
    <div>
      <div class="card-header">🛠️ Week 01</div>
      <div class="card-subtitle">Principles, Practices & Web Setup</div>
      <div class="card-desc">Git, VS Code, MkDocs-Material, GitHub Pages setup and documentation workflow.</div>
    </div>
    <a href="../week01/" class="card-link">Open Week 01 →</a>
  </div>

  <div class="card-item">
    <div>
      <div class="card-header">🧊 Week 02</div>
      <div class="card-subtitle">Computer-Aided Design (CAD)</div>
      <div class="card-desc">2D & 3D Modeling with Fusion 360, raster and vector graphics workflows.</div>
    </div>
    <a href="../week02/" class="card-link">Open Week 02 →</a>
  </div>

  <div class="card-item">
    <div>
      <div class="card-header">✂️ Week 03</div>
      <div class="card-subtitle">Computer-Controlled Cutting</div>
      <div class="card-desc">Parametric press-fit construction kits using laser and vinyl cutters.</div>
    </div>
    <a href="../week03/" class="card-link">Open Week 03 →</a>
  </div>

  <div class="card-item">
    <div>
      <div class="card-header">🔌 Week 04</div>
      <div class="card-subtitle">Electronics Production</div>
      <div class="card-desc">PCB milling, surface-mount soldering (SMD), and testing techniques.</div>
    </div>
    <a href="../week04/" class="card-link">Open Week 04 →</a>
  </div>

  <div class="card-item">
    <div>
      <div class="card-header">🁢 Week 05</div>
      <div class="card-subtitle">3D Scanning & Printing</div>
      <div class="card-desc">Additive manufacturing capabilities, design rules, and 3D scanning.</div>
    </div>
    <a href="../week05/" class="card-link">Open Week 05 →</a>
  </div>

  <div class="card-item">
    <div>
      <div class="card-header">⚡ Week 06</div>
      <div class="card-subtitle">Embedded Programming</div>
      <div class="card-desc">Microcontroller architecture, C/C++ firmware, and hardware programming.</div>
    </div>
    <a href="../week06/" class="card-link">Open Week 06 →</a>
  </div>

</div>