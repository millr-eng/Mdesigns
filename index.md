<style>
  /* Hide default Minimal theme header/footer */
  .site-header, .page-header, header, footer, .site-footer {
    display: none !important;
  }

  /* Reset for full viewport and prevent layout shifts */
  html, body {
    margin: 0;
    padding: 0;
    height: 100%;
    width: 100%;
    overflow-x: hidden;
    box-sizing: border-box;
  }

  * {
    box-sizing: border-box;
  }

  /* Hero section styling - full screen with image background */
  .hero {
    position: relative;
    height: 100vh;
    width: 100vw; /* Use vw to ensure full width */
    margin: 0;
    padding: 0;
    background: url('/images/Scaffolding1.jpg') center/cover no-repeat;
    background-attachment: fixed; /* Optional: keeps background fixed on scroll */
    display: flex;
    align-items: flex-start; /* Title aligned to top */
    justify-content: center;
    text-align: center;
    overflow: hidden; /* Prevent any overflow issues */
  }

  /* Dark overlay for readability */
  .hero-overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.6); /* Darker for better contrast */
    z-index: 1;
  }

  /* Title styling - centered at top */
  .hero-title {
    position: relative;
    color: #fff;
    font-size: clamp(36px, 7vw, 72px);
    font-weight: 900;
    line-height: 1.2;
    text-shadow: 0 4px 12px rgba(0, 0, 0, 0.8);
    margin: 0;
    padding: 2rem 1rem 0; /* Top padding to position nicely from very top */
    z-index: 2; /* Above overlay */
    max-width: 100%;
  }

  /* Content section - below hero, with background for readability */
  .content {
    max-width: 800px;
    margin: 2rem auto;
    padding: 0 1rem;
    font-family: Arial, sans-serif;
    background: rgba(255, 255, 255, 0.95); /* Semi-transparent white for contrast */
    z-index: 3;
    position: relative;
  }

  /* Style lists and links for better appearance */
  .content h2 {
    color: #333;
    border-bottom: 2px solid #ddd;
    padding-bottom: 0.5rem;
  }

  .content ul {
    list-style-type: disc;
    padding-left: 1.5rem;
  }

  .content a {
    color: #007bff;
    text-decoration: none;
  }

  .content a:hover {
    text-decoration: underline;
  }

  /* Responsive tweaks */
  @media (max-width: 768px) {
    .hero {
      background-attachment: scroll; /* Disable fixed background on mobile for performance */
    }
    .hero-title {
      font-size: clamp(28px, 6vw, 48px);
      padding-top: 1rem;
    }
  }
</style>

<!-- Fullscreen hero with title at top -->
<div class="hero">
  <!-- Dark overlay -->
  <div class="hero-overlay"></div>
  <!-- Centered title -->
  <h1 class="hero-title">M Designs & Drafting Services</h1>
</div>

<!-- Main content -->
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
