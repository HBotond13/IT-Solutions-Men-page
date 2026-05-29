# Bootstrap 5 demo contact page

## Development

    - Visual Studio Code

## Github

    - git init
    - git remote origin https://github.com/username/repo.git
    - git status
    - git add 
    - git commit -m "Message"
    - git push
    - git clone https://github.com/felhasznalo/repo-nev.git

h2 id="kapcsolat">Kapcsolat</h2>
2. Hivatkozz rá egy linkkel
HTML
<a href="#kapcsolat">Ugrás a Kapcsolat részhez</a>
    
:) 

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>

  <!-- Bootstrap CSS -->
  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
    rel="stylesheet"
  >

  <style>
    .hero-section {
      background: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e')
        center center/cover no-repeat;

      height: 100vh;
      position: relative;
      color: white;
    }

    .hero-overlay {
      background-color: rgba(0, 0, 0, 0.5);
      position: absolute;
      inset: 0;
    }

    .hero-content {
      position: relative;
      z-index: 2;
    }
  </style>

  <title>Bootstrap Hero Image</title>
</head>
<body>

  <section class="hero-section d-flex align-items-center text-center">
    <div class="hero-overlay"></div>

    <div class="container hero-content">
      <h1 class="display-3 fw-bold">Welcome</h1>
      <p class="lead">Build beautiful websites with Bootstrap</p>

      <a href="#" class="btn btn-primary btn-lg mt-3">
        Get Started
      </a>
    </div>
  </section>

</body>
</html>
