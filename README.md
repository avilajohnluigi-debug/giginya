<svg xmlns="http://www.w3.org/2000/svg" width="600" height="340" viewBox="0 0 600 340">
  <defs>
    <style>
      /* Main Background & Mac OS Window Styling */
      .bg { fill: #1e1e1e; rx: 8px; }
      .bar { fill: #2d2d2d; }
      .red { fill: #ff5f56; }
      .yellow { fill: #ffbd2e; }
      .green { fill: #27c93f; }
      .title { fill: #858585; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif; font-size: 13px; text-anchor: middle; font-weight: 500; }
      
      /* Code Font Formatting */
      .code { font-family: 'Fira Code', 'Courier New', Courier, monospace; font-size: 15px; fill: #d4d4d4; }
      .keyword { fill: #c678dd; }
      .variable { fill: #e5c07b; }
      .string { fill: #98c379; }
      .property { fill: #e06c75; }
      .operator { fill: #56b6c2; }
      .boolean { fill: #d19a66; }
      
      /* Typing Animation Timing  */
      .line { opacity: 0; animation: fadeIn 0.1s forwards; }
      .l1 { animation-delay: 0.5s; }
      .l2 { animation-delay: 1.3s; }
      .l3 { animation-delay: 2.1s; }
      .l4 { animation-delay: 2.9s; }
      .l5 { animation-delay: 3.7s; }
      .l6 { animation-delay: 4.5s; }
      .l7 { animation-delay: 5.3s; }
      .l8 { animation-delay: 6.1s; }
      .l9 { animation-delay: 6.9s; }

      /* Blinking Cursor Styling */
      .cursor {
        display: inline-block;
        fill: #528bff;
        animation: blink 1s step-end infinite;
      }

      /* Hiding individual cursors as new lines appear to simulate moving terminal cursor */
      .c1 { animation: hideCursor 0.1s forwards; animation-delay: 1.3s; }
      .c2 { opacity: 0; animation: showAndHideCursor 0.8s forwards; animation-delay: 1.3s; }
      .c3 { opacity: 0; animation: showAndHideCursor 0.8s forwards; animation-delay: 2.1s; }
      .c4 { opacity: 0; animation: showAndHideCursor 0.8s forwards; animation-delay: 2.9s; }
      .c5 { opacity: 0; animation: showAndHideCursor 0.8s forwards; animation-delay: 3.7s; }
      .c6 { opacity: 0; animation: showAndHideCursor 0.8s forwards; animation-delay: 4.5s; }
      .c7 { opacity: 0; animation: showAndHideCursor 0.8s forwards; animation-delay: 5.3s; }
      .c8 { opacity: 0; animation: showAndHideCursor 0.8s forwards; animation-delay: 6.1s; }
      
      /* The final cursor just stays visible and blinks */
      .c9 { opacity: 0; animation: fadeIn 0.1s forwards; animation-delay: 6.9s; }

      /* Keyframes */
      @keyframes fadeIn { to { opacity: 1; } }
      @keyframes hideCursor { to { opacity: 0; } }
      @keyframes showAndHideCursor { 
        0%   { opacity: 1; }
        99%  { opacity: 1; }
        100% { opacity: 0; }
      }
      @keyframes blink { 0%, 100% { opacity: 1; } 50% { opacity: 0; } }
    </style>
  </defs>
  
  <rect class="bg" width="100%" height="100%" />
  
  <!-- Mac OS Header Window -->
  <path class="bar" d="M 0 8 A 8 8 0 0 1 8 0 L 592 0 A 8 8 0 0 1 600 8 L 600 35 L 0 35 Z" />
  <circle class="red" cx="20" cy="18" r="6" />
  <circle class="yellow" cx="40" cy="18" r="6" />
  <circle class="green" cx="60" cy="18" r="6" />
  <text class="title" x="300" y="23">developer.ts</text>
  
  <!-- Code Formatting and Content -->
  <g class="code" transform="translate(25, 75)">
    <g class="line l1">
      <text y="0">
        <tspan class="keyword">const</tspan> <tspan class="variable">developer</tspan> <tspan class="operator">=</tspan> {<tspan class="cursor c1">_</tspan>
      </text>
    </g>
    <g class="line l2">
      <text y="30" x="20">
        <tspan class="property">name</tspan>: <tspan class="string">'Your Name'</tspan>,<tspan class="cursor c2">_</tspan>
      </text>
    </g>
    <g class="line l3">
      <text y="60" x="20">
        <tspan class="property">role</tspan>: <tspan class="string">'Fullstack Developer'</tspan>,<tspan class="cursor c3">_</tspan>
      </text>
    </g>
    <g class="line l4">
      <text y="90" x="20">
        <tspan class="property">skills</tspan>: [<tspan class="string">'React'</tspan>, <tspan class="string">'TypeScript'</tspan>, <tspan class="string">'Node.js'</tspan>],<tspan class="cursor c4">_</tspan>
      </text>
    </g>
    <g class="line l5">
      <text y="120" x="20">
        <tspan class="property">coffeeIntake</tspan>: <tspan class="boolean">Infinity</tspan>,<tspan class="cursor c5">_</tspan>
      </text>
    </g>
    <g class="line l6">
      <text y="150" x="20">
        <tspan class="keyword">isAvailable</tspan><tspan class="operator">()</tspan> {<tspan class="cursor c6">_</tspan>
      </text>
    </g>
    <g class="line l7">
      <text y="180" x="40">
        <tspan class="keyword">return</tspan> <tspan class="boolean">true</tspan>;<tspan class="cursor c7">_</tspan>
      </text>
    </g>
    <g class="line l8">
      <text y="210" x="20">
        }<tspan class="cursor c8">_</tspan>
      </text>
    </g>
    <g class="line l9">
      <text y="240">
        };<tspan class="cursor c9">_</tspan>
      </text>
    </g>
  </g>
</svg>
