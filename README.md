<template>
  <div id="app" class="container">
    <header>
      <h1>Hi 👋, I'm <span class="highlight">Putri Sadiyah</span></h1>
      <h3>💻 Informatics Student | 🌱 Frontend Developer Enthusiast</h3>
      <img
        src="https://media.giphy.com/media/xT9IgzoKnwFNmISR8I/giphy.gif"
        alt="Waving Hand"
        class="waving-gif"
      />
    </header>

    <section class="about">
      <ul>
        <li>🔭 Currently working on <strong>a PHP Web App for login & register</strong></li>
        <li>🌱 Learning <strong>Vue.js & Laravel</strong></li>
        <li>👯 Looking to collaborate on <strong>frontend projects</strong></li>
        <li>📫 Reach me: <a href="mailto:sadiyahputri32@gmail.com">sadiyahputri32@gmail.com</a></li>
        <li>💖 Pronouns: <strong>She/Her</strong></li>
      </ul>
    </section>

    <section class="skills">
      <h2>🧁 My Tech & Design Stack</h2>
      <div class="badges">
        <span class="badge html">HTML</span>
        <span class="badge css">CSS</span>
        <span class="badge js">JavaScript</span>
        <span class="badge php">PHP</span>
        <span class="badge mysql">MySQL</span>
        <span class="badge git">Git</span>
        <span class="badge figma">Figma</span>
        <span class="badge coreldraw">CorelDRAW</span>
        <span class="badge blender">Blender</span>
      </div>
    </section>

    <section class="stats">
      <h2>📊 GitHub Stats</h2>
      <div class="stat-cards">
        <div class="card github-stats">
          <h3>📈 Contributions</h3>
          <img
            src="https://github-readme-stats.vercel.app/api?username=putrisadiyah19&show_icons=true&theme=rose_pine&hide_border=false"
            alt="GitHub Stats"
          />
        </div>
        <div class="card top-langs">
          <h3>📚 Top Languages</h3>
          <img
            src="https://github-readme-stats.vercel.app/api/top-langs/?username=putrisadiyah19&layout=compact&theme=rose_pine&hide_border=false"
            alt="Top Languages"
          />
        </div>
      </div>
    </section>

    <section class="contact">
      <h2>📬 Let’s Connect!</h2>
      <div class="social-buttons">
        <a
          href="https://linkedin.com/in/putrisadiyah19"
          target="_blank"
          rel="noopener noreferrer"
          class="btn linkedin"
        >LinkedIn</a>
        <a
          href="mailto:sadiyahputri32@gmail.com"
          class="btn gmail"
        >Gmail</a>
        <a
          href="https://github.com/putrisadiyah19"
          target="_blank"
          rel="noopener noreferrer"
          class="btn github"
        >GitHub</a>
      </div>
    </section>

    <footer>
      <p>Made with 💖 by Putri Sadiyah — Dream. Code. Glow ✨</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap");

.container {
  max-width: 750px;
  margin: 2rem auto;
  padding: 0 24px;
  font-family: "Poppins", sans-serif;
  background: #fce4ec;
  color: #6a1b9a;
  border-radius: 25px;
  box-shadow: 0 6px 16px rgba(216, 27, 96, 0.2);
}

header {
  text-align: center;
  margin-bottom: 2rem;
}

header h1 {
  font-weight: 600;
  font-size: 2.5rem;
  color: #d81b60;
}

header h1 .highlight {
  color: #f48fb1;
}

header h3 {
  font-weight: 300;
  font-size: 1.25rem;
  color: #ce93d8;
  margin-top: 0.3rem;
}

.waving-gif {
  margin-top: 15px;
  width: 60px;
  animation: float 3s ease-in-out infinite;
}

@keyframes float {
  0%, 100% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-10px);
  }
}

.about ul {
  list-style-type: none;
  padding: 0;
  font-size: 1.1rem;
  line-height: 1.6;
}

.about ul li {
  margin-bottom: 10px;
}

.about strong {
  color: #d81b60;
}

.about a {
  color: #ab47bc;
  text-decoration: none;
}

.skills {
  margin-top: 2rem;
  text-align: center;
}

.skills h2 {
  font-weight: 600;
  color: #9c27b0;
  margin-bottom: 1rem;
}

.badges {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 10px;
}

.badge {
  padding: 10px 18px;
  border-radius: 30px;
  font-weight: 600;
  color: white;
  font-size: 0.9rem;
  user-select: none;
  box-shadow: 0 3px 6px rgba(216, 27, 96, 0.3);
  transition: transform 0.2s ease;
}

.badge:hover {
  transform: scale(1.1);
}

.html { background: #e91e63; }
.css { background: #f48fb1; }
.js { background: #ce93d8; color: #333; }
.php { background: #ba68c8; }
.mysql { background: #ab47bc; }
.git { background: #9c27b0; }
.figma { background: #f48fb1; }
.coreldraw { background: #d81b60; }
.blender { background: #ce93d8; }

.stats {
  margin-top: 2.5rem;
  text-align: center;
}

.stats h2 {
  font-weight: 600;
  color: #d81b60;
  margin-bottom: 1rem;
}

.stat-cards {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 25px;
}

.card {
  background: white;
  border-radius: 15px;
  box-shadow: 0 4px 10px rgba(216, 27, 96, 0.15);
  padding: 20px;
  width: 270px;
  text-align: center;
  color: #6a1b9a;
  transition: box-shadow 0.3s ease;
}

.card:hover {
  box-shadow: 0 8px 18px rgba(216, 27, 96, 0.3);
}

.card h3 {
  margin-bottom: 15px;
}

.card img {
  border-radius: 12px;
  max-width: 100%;
}

.contact {
  margin: 3rem 0 2rem;
  text-align: center;
}

.contact h2 {
  font-weight: 600;
  color: #9c27b0;
  margin-bottom: 1.5rem;
}

.social-buttons {
  display: flex;
  justify-content: center;
  gap: 20px;
  flex-wrap: wrap;
}

.btn {
  padding: 12px 24px;
  border-radius: 30px;
  font-weight: 600;
  text-decoration: none;
  color: white;
  box-shadow: 0 4px 12px rgba(216, 27, 96, 0.3);
  transition: background-color 0.3s ease, transform 0.2s ease;
}

.btn:hover {
  transform: scale(1.1);
}

.linkedin {
  background: #d81b60;
}

.linkedin:hover {
  background: #f48fb1;
  color: #6a1b9a;
}

.gmail {
  background: #f48fb1;
  color: #6a1b9a;
}

.gmail:hover {
  background: #d81b60;
  color: white;
}

.github {
  background: #9c27b0;
}

.github:hover {
  background: #ba68c8;
}

footer {
  margin-top: 2rem;
  text-align: center;
  font-size: 0.9rem;
  font-style: italic;
  color: #7b1fa2;
}
</style>
