<div align="center">
<!-- ═══════════════════════════════════════════ -->
<!-- ║  CUSTOM ANIMATED HEADER - AYMANEXIAOMI07  ║ -->
<!-- ═══════════════════════════════════════════ -->
<svg width="100%" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Moroccan-inspired gradient -->
    <linearGradient id="moroccanGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#C41E3A"/>
      <stop offset="50%" style="stop-color:#D4A574"/>
      <stop offset="100%" style="stop-color:#1B4B5A"/>
    </linearGradient>
plain
Copy
<!-- Glow filter -->
<filter id="glow">
  <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
  <feMerge>
    <feMergeNode in="coloredBlur"/>
    <feMergeNode in="SourceGraphic"/>
  </feMerge>
</filter>

<!-- Animated pattern -->
<pattern id="zellige" x="0" y="0" width="40" height="40" patternUnits="userSpaceOnUse">
  <rect width="20" height="20" fill="#C41E3A" opacity="0.1"/>
  <rect x="20" y="20" width="20" height="20" fill="#1B4B5A" opacity="0.1"/>
  <circle cx="20" cy="0" r="8" fill="#D4A574" opacity="0.15"/>
  <circle cx="0" cy="20" r="8" fill="#D4A574" opacity="0.15"/>
</pattern>
  </defs>
  <!-- Background with animated pattern -->
  <rect width="800" height="200" fill="#0a0a0a"/>
  <rect width="800" height="200" fill="url(#zellige)">
    <animateTransform attributeName="transform" type="translate" from="0 0" to="40 40" dur="20s" repeatCount="indefinite"/>
  </rect>
  <!-- Decorative geometric frame - Moroccan Zellige inspired -->
  <g stroke="url(#moroccanGrad)" fill="none" stroke-width="2" opacity="0.6">
    <!-- Top-left corner pattern -->
    <path d="M 50 80 L 50 50 L 80 50">
      <animate attributeName="stroke-dasharray" from="0 100" to="100 0" dur="2s" fill="freeze"/>
    </path>
    <!-- Top-right corner pattern -->
    <path d="M 720 50 L 750 50 L 750 80">
      <animate attributeName="stroke-dasharray" from="0 100" to="100 0" dur="2s" fill="freeze"/>
    </path>
    <!-- Bottom-left corner pattern -->
    <path d="M 50 120 L 50 150 L 80 150">
      <animate attributeName="stroke-dasharray" from="0 100" to="100 0" dur="2s" fill="freeze"/>
    </path>
    <!-- Bottom-right corner pattern -->
    <path d="M 720 150 L 750 150 L 750 120">
      <animate attributeName="stroke-dasharray" from="0 100" to="100 0" dur="2s" fill="freeze"/>
    </path>
  </g>
  <!-- Center Star Pattern (Moroccan 8-point star) -->
  <g transform="translate(400, 100)">
    <g stroke="#D4A574" fill="none" stroke-width="1.5" opacity="0.4">
      <polygon points="0,-40 10,-10 40,0 10,10 0,40 -10,10 -40,0 -10,-10">
        <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="30s" repeatCount="indefinite"/>
      </polygon>
      <polygon points="0,-30 8,-8 30,0 8,8 0,30 -8,8 -30,0 -8,-8" stroke="#C41E3A" opacity="0.5">
        <animateTransform attributeName="transform" type="rotate" from="360" to="0" dur="20s" repeatCount="indefinite"/>
      </polygon>
    </g>
  </g>
  <!-- Main Name Text with typewriter effect simulation -->
  <text x="400" y="95" text-anchor="middle" font-family="'Courier New', monospace" font-size="42" font-weight="bold" fill="url(#moroccanGrad)" filter="url(#glow)">
    AIMANE
    <animate attributeName="opacity" values="0;1;1;0.8;1" dur="4s" repeatCount="indefinite"/>
  </text>
  <!-- Subtitle -->
  <text x="400" y="130" text-anchor="middle" font-family="'Courier New', monospace" font-size="16" fill="#D4A574" letter-spacing="8">
    FRONT-END ARCHITECT
    <animate attributeName="opacity" values="0.5;1;0.5" dur="3s" repeatCount="indefinite"/>
  </text>
  <!-- Animated line underneath -->
  <line x1="250" y1="145" x2="550" y2="145" stroke="url(#moroccanGrad)" stroke-width="2">
    <animate attributeName="x2" from="250" to="550" dur="2s" fill="freeze"/>
    <animate attributeName="opacity" values="0.3;1;0.3" dur="4s" repeatCount="indefinite"/>
  </line>
  <!-- Small decorative dots -->
  <circle cx="240" cy="145" r="3" fill="#C41E3A">
    <animate attributeName="opacity" values="0;1;0" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="560" cy="145" r="3" fill="#C41E3A">
    <animate attributeName="opacity" values="0;1;0" dur="2s" begin="1s" repeatCount="indefinite"/>
  </circle>
</svg>
<!-- ═══════════════════════════════════════════ -->
<!-- ║  THE ONLY ONE TAGLINE                     ║ -->
<!-- ═══════════════════════════════════════════ -->
plain
Copy
╔══════════════════════════════════════════════════════════════╗
║  "Code is modern Zellige — every piece must fit perfectly"   ║
╚══════════════════════════════════════════════════════════════╝
<!-- ═══════════════════════════════════════════ -->
<!-- ║  LIVE MOROCCAN TIME WIDGET                ║ -->
<!-- ═══════════════════════════════════════════ -->
<p align="center">
  <img src="https://img.shields.io/badge/🇲🇦_Morocco-Casablanca-1B4B5A?style=for-the-badge&labelColor=0a0a0a&color=C41E3A"/>
  <img src="https://img.shields.io/badge/Focus-Front--End_Development-D4A574?style=for-the-badge&labelColor=0a0a0a"/>
</p>
</div>
<!-- ═══════════════════════════════════════════ -->
<!-- ║  CUSTOM ASCII IDENTITY CARD               ║ -->
<!-- ═══════════════════════════════════════════ -->
<pre align="center">
┌─────────────── AYMANEXIAOMI07 ───────────────┐
│                                              │
│  👤 Name      :  Aimane                      │
│  🎯 Role      :  Web Developer               │
│  🗣️  Languages :  العربية | Français | English│
│  ⚡ Stack     :  HTML • CSS • JS • Figma    │
│  🧠 Mode      :  Always Learning             │
│  ☕ Fuel      :  Coffee & Curiosity          │
│                                              │
└──────────────────────────────────────────────┘
</pre>
<!-- ═══════════════════════════════════════════ -->
<!-- ║  ANIMATED SKILL PYRAMID (UNIQUE DESIGN)   ║ -->
<!-- ═══════════════════════════════════════════ -->
<h2 align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Fire.png" width="25"> 
  Craft Stack
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Fire.png" width="25">
</h2>
<div align="center">
<!-- HTML5 - Foundation Layer -->
plain
Copy
    ▲ HTML5
   ╱ ╲    ████████████████████  95%
  ╱   ╲   Structure & Semantics
 ╱─────╲
<!-- CSS3 - Style Layer -->
plain
Copy
   ▲ CSS3
  ╱ ╲     ██████████████████░  90%
 ╱   ╲    Animations & Layout
╱─────╲
<!-- JavaScript - Logic Layer -->
plain
Copy
  ▲ JavaScript
 ╱ ╲        ███████████████░░░  75%
╱   ╲       Interactivity & DOM
╱─────╲
<!-- Figma - Design Layer -->
plain
Copy
 ▲ Figma
╱ ╲       ██████████████░░░░  70%
╱   ╲      UI/UX Prototyping
╱─────╲
</div>
<!-- ═══════════════════════════════════════════ -->
<!-- ║  REPO SHOWCASE WITH CUSTOM CARDS          ║ -->
<!-- ═══════════════════════════════════════════ -->
<h2 align="center">⚒️ Featured Works</h2>
<div align="center">
<!-- Fitfitness -->
<a href="https://github.com/aymanexiaomi07-wq/Fitfitness">
<table>
<tr>
<td width="400">
plain
Copy
╔════════════════════╗
║   💪 Fitfitness    ║
╠════════════════════╣
║ Health & Fitness   ║
║ Website            ║
║                    ║
║ 🏷️  HTML • CSS     ║
╚════════════════════╝
</td>
</tr>
</table>
</a>
<!-- Cinevia -->
<a href="https://github.com/aymanexiaomi07-wq/cinevia">
<table>
<tr>
<td width="400">
plain
Copy
╔════════════════════╗
║   🎬 Cinevia       ║
╠════════════════════╣
║ Cinema & Movies    ║
║ Platform           ║
║                    ║
║ 🏷️  JavaScript    ║
╚════════════════════╝
</td>
</tr>
</table>
</a>
<!-- github-website -->
<a href="https://github.com/aymanexiaomi07-wq/github-website">
<table>
<tr>
<td width="400">
plain
Copy
╔════════════════════╗
║   🌐 Portfolio     ║
╠════════════════════╣
║ Personal Website   ║
║ Showcase           ║
║                    ║
║ 🏷️  JavaScript    ║
╚════════════════════╝
</td>
</tr>
</table>
</a>
<!-- zayfbs-website -->
<a href="https://github.com/aymanexiaomi07-wq/zayfbs-website">
<table>
<tr>
<td width="400">
plain
Copy
╔════════════════════╗
║   ⚡ Zayfbs        ║
╠════════════════════╣
║ Creative Website   ║
║ Project            ║
║                    ║
║ 🏷️  CSS           ║
╚════════════════════╝
</td>
</tr>
</table>
</a>
</div>
<!-- ═══════════════════════════════════════════ -->
<!-- ║  MOROCCAN-INSPIRED DIVIDER SVG            ║ -->
<!-- ═══════════════════════════════════════════ -->
<div align="center">
<svg width="100%" height="60" viewBox="0 0 800 60" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="dividerGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#0a0a0a"/>
      <stop offset="20%" style="stop-color:#C41E3A"/>
      <stop offset="50%" style="stop-color:#D4A574"/>
      <stop offset="80%" style="stop-color:#1B4B5A"/>
      <stop offset="100%" style="stop-color:#0a0a0a"/>
    </linearGradient>
  </defs>
  <!-- Center geometric motif -->
  <g transform="translate(400, 30)">
    <!-- Diamond shape -->
    <path d="M 0,-20 L 20,0 L 0,20 L -20,0 Z" fill="none" stroke="#D4A574" stroke-width="2">
      <animateTransform attributeName="transform" type="scale" values="1;1.2;1" dur="4s" repeatCount="indefinite"/>
    </path>
    <!-- Inner star -->
    <path d="M 0,-12 L 4,-4 L 12,0 L 4,4 L 0,12 L -4,4 L -12,0 L -4,-4 Z" fill="#C41E3A" opacity="0.8">
      <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="10s" repeatCount="indefinite"/>
    </path>
  </g>
  <!-- Animated lines flowing from center -->
  <line x1="0" y1="30" x2="360" y2="30" stroke="url(#dividerGrad)" stroke-width="2">
    <animate attributeName="stroke-dasharray" values="0 400;400 0" dur="3s" repeatCount="indefinite"/>
  </line>
  <line x1="440" y1="30" x2="800" y2="30" stroke="url(#dividerGrad)" stroke-width="2">
    <animate attributeName="stroke-dasharray" values="0 400;400 0" dur="3s" repeatCount="indefinite"/>
  </line>
  <!-- Small decorative circles -->
  <circle cx="100" cy="30" r="4" fill="#1B4B5A">
    <animate attributeName="opacity" values="0;1;0" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="700" cy="30" r="4" fill="#1B4B5A">
    <animate attributeName="opacity" values="0;1;0" dur="2s" begin="1s" repeatCount="indefinite"/>
  </circle>
</svg>
</div>
<!-- ═══════════════════════════════════════════ -->
<!-- ║  ACTIVITY JOURNAL (UNIQUE FORMAT)         ║ -->
<!-- ═══════════════════════════════════════════ -->
<h2 align="center">📜 Dev Journal</h2>
<div align="center">
plain
Copy
    2026
     │
     ├─── May ──────── 8 commits ──── github-website
     │
     ├─── April ────── learning ───── Advanced JS patterns
     │
     ├─── March ────── building ───── Fitfitness v2
     │
     └─── "Every line of code is a brick in the digital zellige"
</div>
<!-- ═══════════════════════════════════════════ -->
<!-- ║  CONNECT SECTION                          ║ -->
<!-- ═══════════════════════════════════════════ -->
<h2 align="center">📡 Connect</h2>
<div align="center">
plain
Copy
    ╭──────────────────────────────╮
    │                              │
    │   🐙  github.com/aymanexiaomi│
    │                              │
    │   📧  aimane.dev@email.com   │
    │                              │
    │   🌐  aymanexiaomi07-wq.dev  │
    │                              │
    ╰──────────────────────────────╯
</div>
<!-- ═══════════════════════════════════════════ -->
<!-- ║  FOOTER ANIMATION                         ║ -->
<!-- ═══════════════════════════════════════════ -->
<div align="center">
<svg width="100%" height="80" viewBox="0 0 800 80" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="footerGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0a0a"/>
      <stop offset="100%" style="stop-color:#1B4B5A"/>
    </linearGradient>
  </defs>
  <!-- Wave background -->
  <path d="M 0 40 Q 200 0 400 40 Q 600 80 800 40 L 800 80 L 0 80 Z" fill="url(#footerGrad)" opacity="0.5">
    <animate attributeName="d" 
      values="M 0 40 Q 200 0 400 40 Q 600 80 800 40 L 800 80 L 0 80 Z;
              M 0 40 Q 200 80 400 40 Q 600 0 800 40 L 800 80 L 0 80 Z;
              M 0 40 Q 200 0 400 40 Q 600 80 800 40 L 800 80 L 0 80 Z" 
      dur="6s" repeatCount="indefinite"/>
  </path>
  <!-- Text -->
  <text x="400" y="65" text-anchor="middle" font-family="monospace" font-size="14" fill="#D4A574" opacity="0.8">
    Built with patience, precision & Moroccan soul 🇲🇦
    <animate attributeName="opacity" values="0.5;1;0.5" dur="4s" repeatCount="indefinite"/>
  </text>
</svg>
</div>
<!-- ═══════════════════════════════════════════ -->
<!-- ║  END OF README                            ║ -->
<!-- ═══════════════════

