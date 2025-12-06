<div align="center">

<!-- Theme Styling - Pink Orange Theme -->
<style>
  :root {
    --primary-pink: #FF6B9D;
    --primary-orange: #FF8C42;
    --accent-coral: #FF7F50;
    --dark-bg: #0D1117;
    --text-light: #FFFFFF;
  }
  
  h2, h3 {
    font-family: 'Fira Code', 'JetBrains Mono', 'Consolas', 'Monaco', monospace;
    font-weight: 600;
    letter-spacing: 0.5px;
    color: var(--primary-pink);
  }
  
  body {
    font-family: 'Fira Code', 'JetBrains Mono', 'Consolas', 'Monaco', monospace;
    background-color: var(--dark-bg);
  }
  
  /* Animations */
  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(-20px); }
    to { opacity: 1; transform: translateY(0); }
  }
  
  @keyframes slideIn {
    from { opacity: 0; transform: translateX(-30px); }
    to { opacity: 1; transform: translateX(0); }
  }
  
  @keyframes pulse {
    0%, 100% { transform: scale(1); }
    50% { transform: scale(1.05); }
  }
  
  @keyframes glow {
    0%, 100% { box-shadow: 0 0 10px rgba(255, 107, 157, 0.5); }
    50% { box-shadow: 0 0 20px rgba(255, 140, 66, 0.8); }
  }
  
  @keyframes gradient {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
  
  .fade-in {
    animation: fadeIn 1s ease-out;
  }
  
  .slide-in {
    animation: slideIn 0.8s ease-out;
  }
  
  .pulse {
    animation: pulse 2s ease-in-out infinite;
  }
  
  .glow {
    animation: glow 2s ease-in-out infinite;
  }
  
  /* GIF Container with animation */
  .gif-container {
    position: relative;
    display: inline-block;
    animation: fadeIn 1.5s ease-out;
  }
  
  .gif-container::before {
    content: '';
    position: absolute;
    top: -5px;
    left: -5px;
    right: -5px;
    bottom: -5px;
    background: linear-gradient(45deg, var(--primary-pink), var(--primary-orange), var(--accent-coral), var(--primary-pink));
    background-size: 400% 400%;
    animation: gradient 3s ease infinite;
    border-radius: 10px;
    z-index: -1;
    opacity: 0.3;
  }
  
  /* Badge hover effect */
  img[alt*="badge"] {
    transition: transform 0.3s ease, filter 0.3s ease;
  }
  
  img[alt*="badge"]:hover {
    transform: scale(1.1);
    filter: brightness(1.2);
  }
</style>

<!-- Header -->
<div class="fade-in">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=40&duration=3000&pause=1000&color=FF6B9D&center=true&vCenter=true&width=600&lines=Trung+Hieu+Tran;Software+Developer" alt="Typing Animation" />
</div>

<!-- Profile Badges -->
<div align="center" class="slide-in">

<a href="https://github.com/TranTrungHiu">
  <img src="https://img.shields.io/github/followers/TranTrungHiu?style=for-the-badge&logo=github&color=181717&labelColor=0D1117&logoColor=FFFFFF" alt="GitHub followers badge" />
</a>
<a href="https://github.com/TranTrungHiu">
  <img src="https://img.shields.io/github/stars/TranTrungHiu?style=for-the-badge&logo=github&color=FF8C42&labelColor=0D1117&logoColor=FFFFFF" alt="GitHub stars badge" />
</a>
<img src="https://komarev.com/ghpvc/?username=TranTrungHiu&color=FF6B9D&style=for-the-badge&labelColor=0D1117" alt="Profile Views badge" />

</div>

---

<!-- Profile GIF -->
<div align="center" class="gif-container">

<img src="resources/video_profile.gif" alt="Profile GIF" width="600" style="max-width: 100%; border-radius: 10px; box-shadow: 0 8px 32px rgba(255, 107, 157, 0.3);" />

<!-- GitHub link (use after pushing to repository) -->
<!-- <img src="https://raw.githubusercontent.com/TranTrungHiu/TranTrungHiu/main/resources/video_profile.gif" alt="Profile GIF" width="600" style="max-width: 100%; border-radius: 10px; box-shadow: 0 8px 32px rgba(255, 107, 157, 0.3);" /> -->

</div>

---

<!-- Tech Stack -->

## <img src="https://api.iconify.design/mdi:wrench.svg?color=white" width="25" height="25" style="vertical-align: middle;" /> <span style="font-family: 'Fira Code', 'JetBrains Mono', monospace; font-weight: 600; letter-spacing: 0.5px;">Tech Stack & Tools</span>

### <span style="font-family: 'Fira Code', 'JetBrains Mono', monospace; font-weight: 500; letter-spacing: 0.3px; color: #FF8C42;">Programming Languages</span>

<div align="center" class="slide-in">

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=FFFFFF&labelColor=0D1117" alt="JavaScript" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=FFFFFF&labelColor=0D1117" alt="TypeScript" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=FFFFFF&labelColor=0D1117" alt="Python" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=FFFFFF&labelColor=0D1117" alt="Java" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=FFFFFF&labelColor=0D1117" alt="HTML5" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=FFFFFF&labelColor=0D1117" alt="CSS3" />

</div>

### <span style="font-family: 'Fira Code', 'JetBrains Mono', monospace; font-weight: 500; letter-spacing: 0.3px; color: #FF8C42;">Frameworks & Libraries</span>

<div align="center" class="slide-in">

<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=FFFFFF&labelColor=0D1117" alt="React" />
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=FFFFFF&labelColor=0D1117" alt="Node.js" />
<img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=FFFFFF&labelColor=0D1117" alt="Express" />

</div>

### <span style="font-family: 'Fira Code', 'JetBrains Mono', monospace; font-weight: 500; letter-spacing: 0.3px; color: #FF8C42;">Tools & Technologies</span>

<div align="center" class="slide-in">

<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=FFFFFF&labelColor=0D1117" alt="Git" />
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=FFFFFF&labelColor=0D1117" alt="GitHub" />
<img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=FFFFFF&labelColor=0D1117" alt="VS Code" />

</div>

---

<!-- Contribution Graph -->

## <img src="https://api.iconify.design/mdi:git.svg?color=white" width="25" height="25" style="vertical-align: middle;" /> <span style="font-family: 'Fira Code', 'JetBrains Mono', monospace; font-weight: 600; letter-spacing: 0.5px;">Contribution Graph</span>

<div align="center">

<img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg" alt="Snake animation" />

</div>

---

<!-- GitHub Activity -->

## <img src="https://api.iconify.design/mdi:chart-line.svg?color=white" width="25" height="25" style="vertical-align: middle;" /> <span style="font-family: 'Fira Code', 'JetBrains Mono', monospace; font-weight: 600; letter-spacing: 0.5px;">GitHub Activity</span>

<div align="center">

![GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=TranTrungHiu&theme=radical&hide_border=true&bg_color=0D1117&color=FF6B9D&line=FF8C42&point=FFFFFF&area=true&area_color=FF6B9D)

</div>

---

<!-- Contact -->

## <img src="https://api.iconify.design/mdi:linkedin.svg?color=white" width="25" height="25" style="vertical-align: middle;" /> <span style="font-family: 'Fira Code', 'JetBrains Mono', monospace; font-weight: 600; letter-spacing: 0.5px;">Connect with me</span>

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117)](https://github.com/TranTrungHiu)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117)](mailto:your-email@example.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117)](https://linkedin.com/in/your-profile)

</div>

---

</div>
