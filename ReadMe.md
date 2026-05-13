<div align="center">

<!--  DRAGON SVG HEADER — animated, renders natively on GitHub -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 860 220" width="860" height="220">
  <defs>
    <radialGradient id="bgGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#1a0000"/>
      <stop offset="100%" stop-color="#0a0a0a"/>
    </radialGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="softGlow">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <!-- Flame animation -->
    <animateTransform/>
  </defs>

  <!-- Background -->
  <rect width="860" height="220" fill="url(#bgGlow)" rx="12"/>

  <!-- Ink wash texture lines -->
  <g opacity="0.08" stroke="#cc2200" stroke-width="0.5">
    <line x1="0" y1="40" x2="860" y2="40"/>
    <line x1="0" y1="80" x2="860" y2="80"/>
    <line x1="0" y1="120" x2="860" y2="120"/>
    <line x1="0" y1="160" x2="860" y2="160"/>
    <line x1="0" y1="200" x2="860" y2="200"/>
  </g>

  <!-- Vertical red accent lines -->
  <rect x="0" y="0" width="4" height="220" fill="#cc2200" rx="2" opacity="0.9"/>
  <rect x="856" y="0" width="4" height="220" fill="#cc2200" rx="2" opacity="0.9"/>

  <!-- Animated ember particles -->
  <circle cx="80" cy="180" r="2" fill="#ff4400" opacity="0.8">
    <animate attributeName="cy" values="180;20;180" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.8;0;0.8" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="80;95;80" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="140" cy="160" r="1.5" fill="#ffaa00" opacity="0.6">
    <animate attributeName="cy" values="160;30;160" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0;0.6" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="140;125;140" dur="5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="720" cy="190" r="2" fill="#ff4400" opacity="0.7">
    <animate attributeName="cy" values="190;40;190" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.7;0;0.7" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="720;735;720" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="790" cy="170" r="1.5" fill="#ffaa00" opacity="0.5">
    <animate attributeName="cy" values="170;50;170" dur="4.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;0;0.5" dur="4.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="430" cy="200" r="1" fill="#ff6600" opacity="0.6">
    <animate attributeName="cy" values="200;60;200" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0;0.6" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="430;445;430" dur="6s" repeatCount="indefinite"/>
  </circle>

  <!-- Dragon silhouette (stylized serpentine path) -->
  <g filter="url(#glow)" opacity="0.85">
    <!-- Dragon body wave -->
    <path d="M 60 140 Q 120 90 180 130 Q 240 170 300 110 Q 360 50 420 100 Q 480 150 540 90 Q 600 30 660 80 Q 720 130 780 90 Q 810 70 840 60"
          stroke="#cc2200" stroke-width="3.5" fill="none" stroke-linecap="round">
      <animate attributeName="d"
        values="M 60 140 Q 120 90 180 130 Q 240 170 300 110 Q 360 50 420 100 Q 480 150 540 90 Q 600 30 660 80 Q 720 130 780 90 Q 810 70 840 60;
                M 60 130 Q 120 100 180 140 Q 240 160 300 100 Q 360 40 420 110 Q 480 160 540 100 Q 600 40 660 90 Q 720 140 780 80 Q 810 60 840 50;
                M 60 140 Q 120 90 180 130 Q 240 170 300 110 Q 360 50 420 100 Q 480 150 540 90 Q 600 30 660 80 Q 720 130 780 90 Q 810 70 840 60"
        dur="3s" repeatCount="indefinite"/>
    </path>
    <!-- Dragon scales dots along body -->
    <circle cx="180" cy="130" r="4" fill="#cc2200" opacity="0.9">
      <animate attributeName="cy" values="130;140;130" dur="3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="300" cy="110" r="4" fill="#cc2200" opacity="0.9">
      <animate attributeName="cy" values="110;100;110" dur="3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="420" cy="100" r="4" fill="#cc2200" opacity="0.9">
      <animate attributeName="cy" values="100;110;100" dur="3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="540" cy="90" r="4" fill="#cc2200" opacity="0.9">
      <animate attributeName="cy" values="90;100;90" dur="3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="660" cy="80" r="4" fill="#cc2200" opacity="0.9">
      <animate attributeName="cy" values="80;90;80" dur="3s" repeatCount="indefinite"/>
    </circle>
    <!-- Dragon head -->
    <ellipse cx="72" cy="138" rx="14" ry="9" fill="#cc2200" opacity="0.95">
      <animate attributeName="cy" values="138;128;138" dur="3s" repeatCount="indefinite"/>
    </ellipse>
    <!-- Eye glow -->
    <circle cx="67" cy="135" r="3" fill="#ffcc00" filter="url(#softGlow)">
      <animate attributeName="cy" values="135;125;135" dur="3s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="1;0.4;1" dur="1.5s" repeatCount="indefinite"/>
    </circle>
    <!-- Horn -->
    <line x1="72" y1="129" x2="68" y2="118" stroke="#ffaa00" stroke-width="2" stroke-linecap="round">
      <animate attributeName="y1" values="129;119;129" dur="3s" repeatCount="indefinite"/>
      <animate attributeName="y2" values="118;108;118" dur="3s" repeatCount="indefinite"/>
    </line>
    <!-- Tail tip -->
    <path d="M 840 60 Q 855 45 850 30" stroke="#cc2200" stroke-width="2" fill="none" stroke-linecap="round" opacity="0.7"/>
  </g>

  <!-- Japanese kanji accent -->
  <text x="40" y="38" font-family="serif" font-size="22" fill="#cc2200" opacity="0.5">龍</text>
  <text x="800" y="38" font-family="serif" font-size="22" fill="#cc2200" opacity="0.5">炎</text>
  <text x="420" y="28" font-family="serif" font-size="14" fill="#888" opacity="0.4" text-anchor="middle">エンジニア • 革新者</text>

  <!-- Main name -->
  <text x="430" y="105" font-family="Georgia, serif" font-size="38" font-weight="bold"
        fill="#ffffff" text-anchor="middle" filter="url(#glow)" letter-spacing="4">
    KONGPHOP K.
  </text>

  <!-- Subtitle with animated underline -->
  <text x="430" y="140" font-family="Georgia, serif" font-size="15"
        fill="#cc4400" text-anchor="middle" letter-spacing="6" opacity="0.9">
    SOFTWARE  ·  HARDWARE  ·  AI
  </text>
  <line x1="280" y1="148" x2="580" y2="148" stroke="#cc2200" stroke-width="0.8" opacity="0.5"/>

  <!-- Tagline -->
  <text x="430" y="175" font-family="Georgia, serif" font-size="12"
        fill="#888888" text-anchor="middle" letter-spacing="2" font-style="italic">
    Computer Engineering · MUIC · Building what's next
  </text>

  <!-- Animated bottom fire line -->
  <path d="M 0 210 Q 215 195 430 210 Q 645 225 860 210" stroke="#cc2200" stroke-width="1.5" fill="none" opacity="0.6">
    <animate attributeName="d"
      values="M 0 210 Q 215 195 430 210 Q 645 225 860 210;
              M 0 210 Q 215 220 430 210 Q 645 200 860 210;
              M 0 210 Q 215 195 430 210 Q 645 225 860 210"
      dur="4s" repeatCount="indefinite"/>
  </path>
</svg>

<br/>

<!-- Badges row -->
[![Portfolio](https://img.shields.io/badge/⛩%20Portfolio-0a0a0a?style=for-the-badge&logoColor=red)](https://jorvor37.github.io/My_Portfolio/)
[![Instagram](https://img.shields.io/badge/Instagram-cc2200?style=for-the-badge&logo=Instagram&logoColor=white)](https://instagram.com/k_kongphopp)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-8b0000?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/Jorvor37)
[![Email](https://img.shields.io/badge/Email-cc3300?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kongphop.kayoonvichien@gmail.com)

</div>

---

```
  伝説の始まり  ·  The legend begins
```

## `> whoami`

```yaml
name:     Kongphop Kayoonvichien
alias:    Jorvor37
degree:   B.Eng Computer Engineering — MUIC
focus:    [ Software Dev, Hardware Dev, AI & Machine Learning ]
mode:     always_learning: true
```

> *"The craftsman who masters the tool, masters the outcome."*

---

## `> current_quests`

```
▸ 🔥  Building AI-powered applications
▸ ⚔️  Exploring advanced algorithms and AI models
▸ 🐉  Connecting intelligence to everything
```

---

## `> tech_stack`

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-0a0a0a?style=for-the-badge&logo=python&logoColor=ffdd54)
![JavaScript](https://img.shields.io/badge/JavaScript-0a0a0a?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![C++](https://img.shields.io/badge/C++-0a0a0a?style=for-the-badge&logo=c%2B%2B&logoColor=cc2200)
![C](https://img.shields.io/badge/C-0a0a0a?style=for-the-badge&logo=c&logoColor=cc4400)
![Java](https://img.shields.io/badge/Java-0a0a0a?style=for-the-badge&logo=openjdk&logoColor=ED8B00)

**Frameworks & Tools**

![React](https://img.shields.io/badge/React-0a0a0a?style=for-the-badge&logo=react&logoColor=61DAFB)
![GitHub](https://img.shields.io/badge/GitHub-0a0a0a?style=for-the-badge&logo=github&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-0a0a0a?style=for-the-badge&logo=figma&logoColor=F24E1E)
![Lightroom](https://img.shields.io/badge/Lightroom-0a0a0a?style=for-the-badge&logo=Adobe%20Lightroom&logoColor=31A8FF)

**Certifications**

[![AWS Badge](https://img.shields.io/badge/AWS%20Certified-0a0a0a?style=for-the-badge&logo=amazonaws&logoColor=FF9900)](https://www.credly.com/badges/00aa69e1-72cb-4f25-a7f0-143f313a07c7/public_url)

</div>

---

## `> github_scrolls`

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=Jorvor37&theme=dark&hide_border=true&include_all_commits=false&count_private=false&bg_color=0a0a0a&title_color=cc2200&text_color=888888&icon_color=cc4400)

![Streak](https://github-readme-streak-stats.herokuapp.com/?user=Jorvor37&theme=dark&hide_border=true&background=0a0a0a&ring=cc2200&fire=ff4400&currStreakLabel=cc2200&sideLabels=888888&dates=666666)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Jorvor37&theme=dark&hide_border=true&bg_color=0a0a0a&title_color=cc2200&text_color=888888&layout=compact&hide=jupyter%20notebook)

</div>

---

<div align="center">

```
　　龍は眠らない　　
  The dragon never sleeps.
```

[![Visitors](https://visitcount.itsvg.in/api?id=Jorvor37&icon=5&color=6)](https://visitcount.itsvg.in)
&nbsp;&nbsp;
[![BuyMeACoffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-0a0a0a?style=for-the-badge&logo=buy-me-a-coffee&logoColor=ffdd00)](https://buymeacoffee.com/jorvor37)

</div>
