<style>
  /* Hide default Minimal theme header/footer */
  .site-header, .page-header, header, footer, .site-footer {
    display: none !important;
  }

  /* Ensure body and html take full height */
  html, body {
    margin: 0;
    padding: 0;
    height: 100%;
    width: 100%;
    overflow-x: hidden;
  }

  /* Hero section styling */
  .hero {
    position: relative;
    height: 100vh;
    width: 100%;
    background: url('/images/Scaffolding1.jpg') center/cover no-repeat fixed;
    display: flex;
    align-items: flex-start; /* Align title to top */
    justify-content: center;
    text-align: center;
    padding-top: 2rem; /* Add padding for top spacing */
  }

  /* Dark overlay */
  .hero-overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.5); /* Slightly darker overlay for better contrast */
  }

  /* Title styling */
  .hero-title {
    position: relative;
    color: #fff;
    font-size: clamp(36px, 7vw, 72px); /* Adjusted for better scaling */
    font-weight: 900;
    line-height: 1.2;
    text-shadow: 0 4px 12px rgba(0, 0, 0, 0.7);
    margin: 0;
    padding: 0 1rem; /* Prevent text cutoff on smaller screens */
    z-index: 1; /* Ensure title is above overlay */
  }

  /* Content section styling */
  .content {
    max-width: 800px;
    margin: 2rem auto;
    padding: 0 1rem;
    font-family: Arial, sans-serif;
  }

  /* Responsive adjustments */
  @media (max-width: 768px) {
    .hero-title {
      font-size: clamp(28px, 6vw, 48px);
    }
  }
</style>

<!-- Fullscreen hero background with overlay -->
<div class="hero">
  <!-- Dark overlay -->
  <div class="hero-overlay"></div>
  <!-- Title text -->
  <h1 class="hero-title">M Designs & Drafting Services</h1>
</div>

<!-- Content section -->
<div class="content">
  <h2>Services</h2>
  <ul>
    <li>2D CAD drafting (AutoCAD)</li>
    <li>3D modelling (SketchUp Pro)</li>
    <li>3D print prototypes</li>
    <li>Residential/basic structural calcs</li>
  </ul>
  <h2>Featured projects</h2>
  <ul>
    <li><a href="projects/example-project.md">Example Project</a></li>
  </ul>
  <h2>Contact</h2>
  <p><a href="mailto:Mdesigns.engineering@gmail.com">Mdesigns.engineering@gmail.com</a></p>
</div>
