<div align="center" style="background: linear-gradient(to right, #1e1e2f, #232f45, #1c2331); padding: 30px 10px; border-radius: 12px; color: #ffffff; font-family: 'Segoe UI', sans-serif;">

  <h1 align="center">👋 Hey there, I'm <strong><code>Mohsin Bin Ramzan</code></strong></h1>

  <!-- Typing effect container -->
  <div style="display: inline-block; font-size: 20px; font-weight: 500; white-space: nowrap; border-right: 2px solid #61dafb; overflow: hidden; animation: typing 4s steps(40, end) infinite, blink 0.75s step-end infinite;">
    <span id="typing-text"></span>
  </div>

  <script>
    const phrases = [
      "Data Analyst | Power BI Developer",
      "Machine Learning | Computer Vision Fan",
      "Automation | Open Source | NLP Learner"
    ];
    let i = 0, j = 0, currentPhrase = [], isDeleting = false, isEnd = false;
    const element = document.getElementById('typing-text');

    function loop() {
      isEnd = false;
      element.innerHTML = currentPhrase.join('');
      if (i < phrases.length) {
        if (!isDeleting && j <= phrases[i].length) {
          currentPhrase.push(phrases[i][j]);
          j++;
          element.innerHTML = currentPhrase.join('');
        }
        if (isDeleting && j <= phrases[i].length) {
          currentPhrase.pop();
          j--;
          element.innerHTML = currentPhrase.join('');
        }
        if (j === phrases[i].length) {
          isEnd = true;
          isDeleting = true;
          setTimeout(loop, 1200);
          return;
        }
        if (isDeleting && j === 0) {
          currentPhrase = [];
          isDeleting = false;
          i++;
          if (i === phrases.length) i = 0;
        }
      }
      const speed = isEnd ? 100 : isDeleting ? 50 : 100;
      setTimeout(loop, speed);
    }
    loop();
  </script>

  <style>
    @keyframes blink {
      0% { border-color: transparent; }
      50% { border-color: #61dafb; }
      100% { border-color: transparent; }
    }
  </style>

  <p align="center">
    <img src="https://komarev.com/ghpvc/?username=MOHSINBINRAMZAN&label=👁️%20Profile%20Views&color=61dafb&style=flat-square" />
    <img src="https://img.shields.io/github/followers/MOHSINBINRAMZAN?label=🙌%20Followers&style=flat-square&color=A349A4" />
    <img src="https://img.shields.io/badge/Pronouns-He%2FHim-8e44ad?style=flat-square" />
    <img src="https://img.shields.io/badge/📍%20Location-Rawalpindi%2C%20PK-f5c518?style=flat-square" />
  </p>

  <hr>

  <h2>🔍 About Me</h2>
  <ul align="left" style="max-width: 600px; margin: auto;">
    <li>💼 <strong>Self-employed Data Analyst</strong> | <strong>Power BI Developer</strong></li>
    <li>🤖 Passionate about <strong>Machine Learning</strong>, <strong>Computer Vision</strong>, and <strong>Database Administration</strong></li>
    <li>📘 Currently learning <strong>NLP</strong>, <strong>Speech Processing</strong>, and <strong>Data Mining</strong></li>
    <li>⚙️ I enjoy automating workflows and building smart, data-driven systems</li>
    <li>🧠 Always up for new challenges and learning opportunities</li>
  </ul>

  <hr>

  <h2>💬 Let's Connect</h2>
  <ul align="left" style="max-width: 600px; margin: auto;">
    <li>📬 Email: <strong>mohsinramzan248@gmail.com</strong></li>
    <li>🌐 Portfolio: <a href="https://mohsinbinramzan.github.io" style="color: #61dafb;">mohsinbinramzan.github.io</a></li>
    <li>💼 LinkedIn: <a href="https://www.linkedin.com/in/mohsin-bin-ramzan-7022827271/" style="color: #61dafb;">Mohsin Bin Ramzan</a></li>
    <li>🛠️ Tools: Python, Power BI, SQL, Jupyter, OpenCV, Matplotlib, Pandas</li>
  </ul>

  <hr>

  <h2>📊 GitHub Stats & Languages</h2>
  <p align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=MOHSINBINRAMZAN&show_icons=true&theme=tokyonight&hide_border=true" width="47%" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MOHSINBINRAMZAN&layout=compact&theme=dracula&hide_border=true" width="47%" />
  </p>

  <hr>

  <h2>🏆 GitHub Achievements</h2>
  <p align="center">
    <img src="https://github-profile-trophy.vercel.app/?username=MOHSINBINRAMZAN&theme=monokai&margin-w=10&no-frame=true" />
  </p>

  <hr>

  <h2>📈 Visitor Counter</h2>
  <p align="center">
    <img src="https://profile-counter.glitch.me/MOHSINBINRAMZAN/count.svg" />
  </p>

  <hr>

  <h2>✨ Fun Fact</h2>
  <blockquote style="font-style: italic;">
    I love simplifying complex tech, visualizing data beautifully, and turning ideas into reality — with a touch of humor whenever possible 😄
  </blockquote>

  <p align="center"><i>🕒 Last updated: May 2, 2025</i></p>

</div>
