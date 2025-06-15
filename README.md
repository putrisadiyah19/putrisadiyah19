<!-- README.md -->

<div style="position: relative;">

<!-- Sakura animation -->
<style>
  body {
    background-color: #fff0f5;
    overflow-x: hidden;
  }

  .sakura {
    position: fixed;
    top: -50px;
    z-index: 0;
    width: 20px;
    height: 20px;
    background-image: url('https://i.ibb.co/0s7fKvJ/sakura.png');
    background-size: cover;
    animation: fall linear infinite;
    opacity: 0.8;
  }

  @keyframes fall {
    0% {
      transform: translateY(0) rotate(0deg);
      opacity: 0.8;
    }
    100% {
      transform: translateY(100vh) rotate(360deg);
      opacity: 0.1;
    }
  }

  .clock {
    position: fixed;
    top: 10px;
    right: 20px;
    font-size: 16px;
    font-family: 'Segoe UI';
    background: #f8bbd0;
    color: #6a1b9a;
    padding: 8px 12px;
    border-radius: 12px;
    box-shadow: 0 0 5px rgba(0,0,0,0.1);
    z-index: 1;
  }
</style>

<script>
  // Sakura Drop Generator
  let total = 30;
  for (let i = 0; i < total; i++) {
    let sakura = document.createElement("div");
    sakura.classList.add("sakura");
    sakura.style.left = Math.random() * 100 + "vw";
    sakura.style.animationDuration = 5 + Math.random() * 5 + "s";
    sakura.style.animationDelay = Math.random() * 5 + "s";
    document.body.appendChild(sakura);
  }

  // Clock Script
  setInterval(() => {
    const clock = document.getElementById("clock");
    const now = new Date();
    clock.innerHTML =
      now.toLocaleTimeString("id-ID", { hour12: false }) +
      " 🕒";
  }, 1000);
</script>

<div id="clock" class="clock"></div>

</div>

---

# ✨ Hello World! I'm **Putri Sadiyah** 💕  
💻 *Informatics Student | 🌱 Frontend Developer Enthusiast*

<img src="https://media.giphy.com/media/xT9IgzoKnwFNmISR8I/giphy.gif" width="90" alt="waving hand" />

---

## 🌸 About Me

- 🔭 I’m currently working on a **PHP Web App** for login & register  
- 🌱 I’m learning **Vue.js & Laravel**  
- 👯 I’m open for **Frontend collaboration**  
- 📫 Contact me via **sadiyahputri32@gmail.com**  
- 💖 Pronouns: *She/Her*  

---

## 🧁 My Tech & Design Stack

<p>
  <img alt="HTML" src="https://img.shields.io/badge/HTML-e91e63?style=for-the-badge&logo=html5&logoColor=white" />
  <img alt="CSS" src="https://img.shields.io/badge/CSS-f48fb1?style=for-the-badge&logo=css3&logoColor=white" />
  <img alt="JS" src="https://img.shields.io/badge/JS-ce93d8?style=for-the-badge&logo=javascript&logoColor=white" />
  <img alt="PHP" src="https://img.shields.io/badge/PHP-ba68c8?style=for-the-badge&logo=php&logoColor=white" />
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-ab47bc?style=for-the-badge&logo=mysql&logoColor=white" />
  <img alt="Git" src="https://img.shields.io/badge/Git-9c27b0?style=for-the-badge&logo=git&logoColor=white" /><br/><br/>
  <img alt="Figma" src="https://img.shields.io/badge/Figma-f48fb1?style=for-the-badge&logo=figma&logoColor=white" />
  <img alt="CorelDRAW" src="https://img.shields.io/badge/CorelDRAW-d81b60?style=for-the-badge&logo=coreldraw&logoColor=white" />
  <img alt="Blender" src="https://img.shields.io/badge/Blender-ce93d8?style=for-the-badge&logo=blender&logoColor=white" />
</p>

---

## 📈 GitHub Stats

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=putrisadiyah19&show_icons=true&theme=rose_pine&hide_border=false" />
  <br />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=putrisadiyah19&layout=compact&theme=rose_pine&hide_border=false" />
</p>

---

## 📬 Let’s Connect!

<p>
  <a href="https://linkedin.com/in/putrisadiyah19">
    <img src="https://img.shields.io/badge/-LinkedIn-d81b60?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:sadiyahputri32@gmail.com">
    <img src="https://img.shields.io/badge/-Gmail-f8bbd0?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/putrisadiyah19">
    <img src="https://img.shields.io/badge/-GitHub-ab47bc?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

<p style="font-size:0.9rem; font-style:italic; color:#7b1fa2;">
Made with 💖 by Putri Sadiyah — Dream. Code. Glow ✨
</p>
