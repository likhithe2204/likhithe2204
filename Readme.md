<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Likhith Edupuganti | Portfolio</title>

  <!-- Bootstrap -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" />
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet" />
  <script src="https://cdn.jsdelivr.net/npm/tsparticles@2.11.1/tsparticles.bundle.min.js"></script>

  <style>
    * {
      font-family: 'Poppins', sans-serif;
    }

    body, html {
      margin: 0;
      padding: 0;
      height: 100%;
      background: transparent;
      color: #fff;
    }

    #tsparticles {
      position: fixed;
      width: 100%;
      height: 100%;
      top: 0;
      left: 0;
      z-index: -1;
    }

    .section {
      padding: 60px 20px;
      text-align: center;
    }

    h1, h3, h2 {
      margin-bottom: 20px;
    }

    .icons img {
      margin: 10px;
    }
  </style>
</head>

<body>
  <div id="tsparticles"></div>

  <section class="section bg-dark">
    <h1>Hi 👋, I'm Likhith Edupuganti</h1>
    <h3>Computer Science Student @ SRM University</h3>
    <p>Passionate about Web Development & Machine Learning</p>
    <p>CGPA: 8.80</p>
  </section>

  <section class="section bg-black">
    <p>
      <img src="https://komarev.com/ghpvc/?username=likhithe2204&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />
    </p>

    <p>
      <img src="https://github-profile-trophy.vercel.app/?username=likhithe2204&theme=onedark&row=1&column=6" alt="GitHub trophies" class="img-fluid" />
    </p>
  </section>

  <section class="section bg-dark">
    <h2>Experience & Learning</h2>
    <p>🔥 Working on Machine Learning & Web Projects</p>
    <p>📚 Learning Java</p>
    <p>💼 Internships: Edunet Foundation (AI/ML), Raise Digital (Frontend)</p>
    <p>📅 Portfolio: <a href="https://portfoliobylikhith.netlify.app/" target="_blank">My Portfolio</a></p>
    <p>💬 Email: likhith_edupuganti@srmap.edu.in</p>
  </section>

  <section class="section bg-black">
    <h2>🗺 LeetCode Highlights</h2>
    <div class="d-flex justify-content-center flex-wrap">
      <img src="https://assets.leetcode.com/static_assets/marketing/2024-50.gif" height="180" />
      <img src="https://assets.leetcode.com/static_assets/marketing/2024-100-new.gif" height="180" />
    </div>
    <br />
    <img src="https://leetcard.jacoblin.cool/notLikhith?theme=dark&font=Saira&ext=heatmap" class="img-fluid" />
  </section>

  <section class="section bg-dark">
    <h2>🔎 Connect with Me</h2>
    <div class="icons">
      <a href="https://www.linkedin.com/in/likhith-edupuganti-36a869258/" target="_blank">
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" height="30" />
      </a>
      <a href="https://leetcode.com/u/notLikhith/" target="_blank">
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" height="30" />
      </a>
    </div>
  </section>

  <section class="section bg-black">
    <h2>🛠 Languages & Tools</h2>
    <div class="icons d-flex justify-content-center flex-wrap">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="40" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" width="40" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" width="40" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" width="40" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" width="40" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="40" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" width="40" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" width="40" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" width="40" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" width="40" />
    </div>
  </section>

  <section class="section bg-dark">
    <h2>📊 GitHub Stats</h2>
    <div class="d-flex justify-content-center flex-wrap">
      <img src="https://github-readme-stats.vercel.app/api?username=likhithe2204&show_icons=true&theme=radical&hide_border=false&bg_color=00000000&rank_icon=github" width="47%" />
      <img src="https://streak-stats.demolab.com?user=likhithe2204&theme=radical" width="47%" />
    </div>
    <br />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=likhithe2204&layout=compact&theme=radical&hide_border=false" width="50%" />
  </section>

  <script>
    tsParticles.load("tsparticles", {
      particles: {
        number: { value: 70, density: { enable: true, area: 800 } },
        color: { value: "#ffffff" },
        shape: { type: "circle" },
        opacity: { value: 0.5 },
        size: { value: 3 },
        links: {
          enable: true,
          distance: 150,
          color: "#ffffff",
          opacity: 0.4,
          width: 1
        },
        move: { enable: true, speed: 2 }
      },
      interactivity: {
        events: {
          onhover: { enable: true, mode: "repulse" },
          onclick: { enable: true, mode: "push" }
        },
        modes: {
          repulse: { distance: 100 },
          push: { quantity: 4 }
        }
      },
      background: { color: "#000000" }
    });
  </script>
</body>
</html>
