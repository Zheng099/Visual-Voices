# Visual-Voices
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Visual Voices - The Sound of Art</title>
  <style>
    body {
      margin: 0;
      font-family: 'Helvetica Neue', sans-serif;
      background-color: #fafafa;
      color: #333;
    }
    header {
      background-color: #000;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    header h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }
    nav a {
      margin: 0 1rem;
      color: #fff;
      text-decoration: none;
    }
    .section {
      padding: 3rem 2rem;
      max-width: 1000px;
      margin: auto;
    }
    .artist-card {
      display: flex;
      flex-direction: row;
      align-items: center;
      gap: 2rem;
      margin-bottom: 3rem;
    }
    .artist-card img {
      width: 200px;
      height: auto;
      border-radius: 1rem;
    }
    .artist-info {
      max-width: 600px;
    }
    .artist-info h2 {
      margin-top: 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>Visual Voices - The Sound of Art</h1>
    <nav>
      <a href="#nara">Yoshitomo Nara</a>
      <a href="#kusama">Yayoi Kusama</a>
      <a href="#wu">Wu Chi-Tsung</a>
    </nav>
  </header>

  <section class="section">
    <div class="artist-card" id="nara">
      <img src="yoshitomo_nara_yokohama_2012.jpg" alt="Portrait of Yoshitomo Nara" />
      <div class="artist-info">
        <h2>Yoshitomo Nara</h2>
        <p>Yoshitomo Nara is a contemporary Japanese artist known for his depictions of solitary, rebellious children. His style blends pop culture, cartoons, and punk influences, often carrying deeper social and psychological critiques beneath a playful surface.</p>
      </div>
    </div>

    <div class="artist-card" id="kusama">
      <img src="yayoi_kusama.jpg" alt="Portrait of Yayoi Kusama" />
      <div class="artist-info">
        <h2>Yayoi Kusama</h2>
        <p>Yayoi Kusama is one of Japan's most iconic avant-garde artists. She is renowned for her use of polka dots and mirrored installations to create infinite visual experiences. Her work often reflects themes of psychological healing, self-identity, and feminism.</p>
      </div>
    </div>

    <div class="artist-card" id="wu">
      <img src="wu_chi_tsung.jpg" alt="Portrait of Wu Chi-Tsung" />
      <div class="artist-info">
        <h2>Wu Chi-Tsung</h2>
        <p>Wu Chi-Tsung is a contemporary Taiwanese artist known for his innovative use of light, shadow, and photography. His works, such as the "Cyano-Collage" series, integrate traditional Chinese ink aesthetics with modern technology, exploring time, nature, and perception.</p>
      </div>
    </div>
  </section>
</body>
</html>
