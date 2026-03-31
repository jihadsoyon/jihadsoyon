<div align="center">

<!--  ANIMATED SVG HEADER BANNER  -->
<svg width="100%" height="200" viewBox="0 0 900 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="100%" style="stop-color:#161b22"/>
    </linearGradient>
    <linearGradient id="lineGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00f5a0;stop-opacity:0"/>
      <stop offset="50%" style="stop-color:#00d9f5;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#00f5a0;stop-opacity:0"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="900" height="200" fill="url(#bg)" rx="12"/>

  <!-- Grid lines (subtle) -->
  <g stroke="#1f2937" stroke-width="0.5" opacity="0.6">
    <line x1="0" y1="50" x2="900" y2="50"/>
    <line x1="0" y1="100" x2="900" y2="100"/>
    <line x1="0" y1="150" x2="900" y2="150"/>
    <line x1="150" y1="0" x2="150" y2="200"/>
    <line x1="300" y1="0" x2="300" y2="200"/>
    <line x1="450" y1="0" x2="450" y2="200"/>
    <line x1="600" y1="0" x2="600" y2="200"/>
    <line x1="750" y1="0" x2="750" y2="200"/>
  </g>

  <!-- Glowing scan line -->
  <rect height="2" width="900" y="99" fill="url(#lineGrad)" opacity="0.8">
    <animate attributeName="y" values="0;200;0" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;0.8;0" dur="4s" repeatCount="indefinite"/>
  </rect>

  <!-- Corner accents -->
  <polyline points="12,40 12,12 40,12" stroke="#00d9f5" stroke-width="2" fill="none" filter="url(#glow)"/>
  <polyline points="860,12 888,12 888,40" stroke="#00f5a0" stroke-width="2" fill="none" filter="url(#glow)"/>
  <polyline points="12,160 12,188 40,188" stroke="#00f5a0" stroke-width="2" fill="none" filter="url(#glow)"/>
  <polyline points="860,188 888,188 888,160" stroke="#00d9f5" stroke-width="2" fill="none" filter="url(#glow)"/>

  <!-- Blinking dots -->
  <circle cx="30" cy="30" r="3" fill="#00d9f5" filter="url(#glow)">
    <animate attributeName="opacity" values="1;0;1" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="870" cy="170" r="3" fill="#00f5a0" filter="url(#glow)">
    <animate attributeName="opacity" values="0;1;0" dur="1.5s" repeatCount="indefinite"/>
  </circle>

  <!-- Main name text -->
  <text x="450" y="90" font-family="'Courier New', monospace" font-size="42" font-weight="bold"
        text-anchor="middle" fill="#ffffff" filter="url(#glow)" letter-spacing="6">
    JIHAD SOYON
    <animate attributeName="opacity" values="0;1" dur="1s" fill="freeze"/>
  </text>

  <!-- Accent underline -->
  <rect x="250" y="100" width="0" height="2" fill="url(#lineGrad)" rx="1">
    <animate attributeName="width" values="0;400" dur="1.2s" begin="0.8s" fill="freeze"/>
    <animate attributeName="x" values="450;250" dur="1.2s" begin="0.8s" fill="freeze"/>
  </rect>

  <!-- Subtitle -->
  <text x="450" y="135" font-family="'Courier New', monospace" font-size="15"
        text-anchor="middle" fill="#00d9f5" letter-spacing="4" opacity="0">
    &lt; MERN STACK DEVELOPER /&gt;
    <animate attributeName="opacity" values="0;1" dur="0.8s" begin="1.5s" fill="freeze"/>
  </text>

  <!-- Tags -->
  <text x="450" y="168" font-family="'Courier New', monospace" font-size="11"
        text-anchor="middle" fill="#8b949e" letter-spacing="2" opacity="0">
    Bangladesh 🇧🇩  ·  Open to Remote  ·  Building the Web
    <animate attributeName="opacity" values="0;1" dur="0.8s" begin="2s" fill="freeze"/>
  </text>
</svg>

<!-- Typing SVG -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=3000&pause=800&color=00D9F5&center=true&vCenter=true&width=600&lines=const+developer+%3D+%22Jihad+Soyon%22;import+%7B+passion%2C+code+%7D+from+'%40mern';while(true)+%7B+learn()%3B+build()%3B+%7D;Remote+Opportunities+%3D+true+%E2%9C%85" alt="Typing SVG" />

</div>

<br/>

## `$ whoami`

```ts
const jihad = {
  name      : "Jihad Soyon",
  location  : "Jamalpur, Bangladesh 🇧🇩",
  role      : "MERN Stack Developer",
  learning  : ["Problem Solving, MernStack"],
  contact   : "jihadsoyon@gmail.com",
  available : true,
};
```

<br/>

## `$ ls skills/`

<div align="center">

**Frontend**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)

**Backend & DB**

![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=flat-square&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404d59?style=flat-square&logo=express&logoColor=61DAFB)
![MongoDB](https://img.shields.io/badge/MongoDB-4ea94b?style=flat-square&logo=mongodb&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

**Tools**

![Git](https://img.shields.io/badge/Git-F05033?style=flat-square&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

</div>

<br/>

## `$ cat stats.json`

<div align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=jihadsoyon&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00d9f5&icon_color=00f5a0&text_color=c9d1d9&count_private=true" height="165"/>
  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=jihadsoyon&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00d9f5&text_color=c9d1d9&hide=html,css" height="165"/> 
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=jihadsoyon&theme=dark&hide_border=true&background=0d1117&stroke=00d9f5&ring=00f5a0&fire=00d9f5&currStreakLabel=00d9f5&sideLabels=8b949e&dates=8b949e" />
</div>

<br/>

## `$ git log --graph`

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=jihadsoyon&theme=github-compact&hide_border=true&bg_color=0d1117&color=00d9f5&line=00f5a0&point=ffffff" />
</div>

<br/>

## `$ ping connect`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jihad-soyon)
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://facebook.com/jihad.soyon)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jihadsoyon@gmail.com)
[![Behance](https://img.shields.io/badge/Behance-1769FF?style=for-the-badge&logo=behance&logoColor=white)](https://behance.net/jihadsoyon)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://jihadsoyon.medium.com)

</div>

<br/>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=jihadsoyon&label=Profile+Views&color=00d9f5&style=flat-square" />
  
  <br/><br/>
  
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12&height=80&section=footer&text=&fontSize=0" width="100%"/>
</div>
