# Portofolio-vano
Portofolio
/portofolio
├── index.html
└── style.css
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portofolio Vano</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Welcome To My Portofolio</h1>
    <div class="profile-img">
      <img src="foto-kamu.jpg" alt="Foto Vano">
    </div>
    <h2>Vano Irmawan</h2>
    <p>Script Developer | Creator</p>
  </header>

  <section class="about">
    <h3>Tentang Saya</h3>
    <p>
      Halo! Saya adalah script developer yang fokus membuat dan mengembangkan bot WhatsApp. Saya senang mengotak-atik kode, bereksperimen dengan teknologi baru, dan membangun solusi kreatif untuk komunitas.
    </p>
  </section>

  <section class="skills">
    <h3>Bahasa yang Dipelajari</h3>
    <div class="badge-container">
      <span class="badge">JavaScript</span>
      <span class="badge">Node.js</span>
      <span class="badge">HTML</span>
      <span class="badge">CSS</span>
      <span class="badge">Python</span>
      <span class="badge">PHP</span>
    </div>
  </section>

  <section class="projects">
    <h3>Project Saya</h3>
    <div class="project-card">
      <h4>Script Bot Otomatis</h4>
      <p>Sebuah bot WhatsApp untuk membantu pengguna mengelola pesan, auto-reply, dan banyak fitur lainnya.</p>
      <button>Lihat Script</button>
    </div>
  </section>

  <section class="thanks">
    <h3>Thanks To</h3>
    <div class="badge-container">
      <span class="badge">CodeBaseID</span>
      <span class="badge">DevXTeam</span>
      <span class="badge">BotZone</span>
      <span class="badge">Tim Support</span>
      <span class="badge">You!</span>
    </div>
  </section>

  <section class="contact">
    <h3>Contact Person</h3>
    <div class="badge-container">
      <a class="badge link" href="https://wa.me/6281234567890" target="_blank">WhatsApp</a>
      <a class="badge link" href="https://instagram.com/vanoirmawan" target="_blank">Instagram</a>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Vano Irmawan | All Rights Reserved.</p>
  </footer>
</body>
</html>
body {
  font-family: 'Arial', sans-serif;
  background-color: #f0f8ff;
  color: #1c1c1c;
  margin: 0;
  padding: 0;
}

header {
  background-color: #0077cc;
  color: white;
  text-align: center;
  padding: 40px 20px;
}

.profile-img img {
  width: 120px;
  height: 120px;
  border-radius: 100px;
  border: 3px solid white;
  margin-top: 15px;
}

section {
  background: white;
  padding: 30px 20px;
  margin: 20px;
  border-radius: 12px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.05);
  max-width: 800px;
  margin-left: auto;
  margin-right: auto;
}

h3 {
  color: #0077cc;
}

.badge-container {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 10px;
}

.badge {
  background-color: #3399ff;
  color: white;
  padding: 10px 15px;
  border-radius: 20px;
  font-size: 14px;
}

.project-card {
  background-color: #e6f2ff;
  padding: 20px;
  border-radius: 12px;
  margin-top: 10px;
}

.project-card button {
  background-color: #0077cc;
  color: white;
  border: none;
  padding: 10px 15px;
  border-radius: 20px;
  cursor: pointer;
  margin-top: 10px;
}

.link {
  text-decoration: none;
  display: inline-block;
}

footer {
  background-color: #0077cc;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 30px;
}
