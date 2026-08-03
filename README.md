<svg width="760" height="300" viewBox="0 0 760 300" xmlns="http://www.w3.org/2000/svg" font-family="'Cascadia Code','Fira Code',Consolas,'Courier New',monospace">

  <defs>
    <linearGradient id="panelGrad" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#0e1420"/>
      <stop offset="100%" stop-color="#0a0d13"/>
    </linearGradient>

    <linearGradient id="glintGrad" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0"/>
      <stop offset="50%" stop-color="#ffffff" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#ffffff" stop-opacity="0"/>
    </linearGradient>

    <linearGradient id="sheenGrad" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0"/>
      <stop offset="50%" stop-color="#ffffff" stop-opacity="0.06"/>
      <stop offset="100%" stop-color="#ffffff" stop-opacity="0"/>
    </linearGradient>

    <linearGradient id="asciiGrad" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#7ee787"/>
      <stop offset="100%" stop-color="#58a6ff"/>
    </linearGradient>

    <clipPath id="panelClip">
      <rect x="1" y="1" width="758" height="298" rx="12"/>
    </clipPath>

    <clipPath id="clipLine1"><rect x="30" y="26" height="20" width="0">
      <animate attributeName="width" dur="14s" repeatCount="indefinite"
        keyTimes="0;0.0214;0.1143;0.7643;0.8071;1"
        values="0;0;185;185;0;0"/>
    </rect></clipPath>

    <clipPath id="clipLine2"><rect x="30" y="50" height="20" width="0">
      <animate attributeName="width" dur="14s" repeatCount="indefinite"
        keyTimes="0;0.1429;0.2429;0.7643;0.8071;1"
        values="0;0;380;380;0;0"/>
    </rect></clipPath>

    <clipPath id="clipLine3"><rect x="30" y="76" height="20" width="0">
      <animate attributeName="width" dur="14s" repeatCount="indefinite"
        keyTimes="0;0.2786;0.3893;0.7643;0.8071;1"
        values="0;0;265;265;0;0"/>
    </rect></clipPath>

    <clipPath id="clipClear"><rect x="30" y="210" height="20" width="0">
      <animate attributeName="width" dur="14s" repeatCount="indefinite"
        keyTimes="0;0.6429;0.7329;0.7643;0.8071;1"
        values="0;0;176;176;0;0"/>
    </rect></clipPath>

    <clipPath id="asciiBox"><rect x="20" y="108" width="470" height="100"/></clipPath>
  </defs>

  <!-- panel -->
  <g clip-path="url(#panelClip)">
    <rect x="0" y="0" width="760" height="300" fill="url(#panelGrad)"/>

    <!-- header bar -->
    <rect x="0" y="0" width="760" height="36" fill="#131a24"/>
    <line x1="0" y1="36" x2="760" y2="36" stroke="#232b36" stroke-width="1"/>

    <circle cx="20" cy="18" r="6" fill="#ff5f56">
      <animate attributeName="opacity" values="1;0.55;1" dur="2.6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="40" cy="18" r="6" fill="#ffbd2e">
      <animate attributeName="opacity" values="1;0.55;1" dur="2.6s" begin="0.3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="60" cy="18" r="6" fill="#27c93f">
      <animate attributeName="opacity" values="1;0.55;1" dur="2.6s" begin="0.6s" repeatCount="indefinite"/>
    </circle>

    <text x="380" y="23" text-anchor="middle" font-size="12.5" fill="#7d8590">bilal@estin: ~ — zsh</text>

    <!-- terminal body -->
    <g font-size="14">

      <!-- line 1 -->
      <text clip-path="url(#clipLine1)" x="30" y="40" xml:space="preserve"><tspan fill="#7ee787">bilal</tspan><tspan fill="#7d8590">@</tspan><tspan fill="#58a6ff">estin</tspan><tspan fill="#7d8590">:~$ </tspan><tspan fill="#e6edf3">whoami</tspan></text>

      <!-- line 2 (output) -->
      <text clip-path="url(#clipLine2)" x="30" y="64" xml:space="preserve"><tspan fill="#7d8590">&gt; </tspan><tspan fill="#c9d1d9">bilal segaa — AI/ML &amp; Full-Stack Engineer</tspan></text>

      <!-- line 3 -->
      <text clip-path="url(#clipLine3)" x="30" y="90" xml:space="preserve"><tspan fill="#7ee787">bilal</tspan><tspan fill="#7d8590">@</tspan><tspan fill="#58a6ff">estin</tspan><tspan fill="#7d8590">:~$ </tspan><tspan fill="#e6edf3">cat mission.txt</tspan></text>

      <!-- ascii art reveal, staggered -->
      <g font-size="13.5" font-weight="bold" fill="url(#asciiGrad)" xml:space="preserve">
        <g>
          <animate attributeName="opacity" dur="14s" repeatCount="indefinite"
            keyTimes="0;0.4107;0.4321;0.7643;0.8071;1" values="0;0;1;1;0;0"/>
          <text x="30" y="118">  ____  _ _         _   </text>
        </g>
        <g>
          <animate attributeName="opacity" dur="14s" repeatCount="indefinite"
            keyTimes="0;0.4214;0.4429;0.7643;0.8071;1" values="0;0;1;1;0;0"/>
          <text x="30" y="134"> | __ )(_) |  __ _  | |  </text>
        </g>
        <g>
          <animate attributeName="opacity" dur="14s" repeatCount="indefinite"
            keyTimes="0;0.4321;0.4536;0.7643;0.8071;1" values="0;0;1;1;0;0"/>
          <text x="30" y="150"> |  _ \| | | / _` | | |  </text>
        </g>
        <g>
          <animate attributeName="opacity" dur="14s" repeatCount="indefinite"
            keyTimes="0;0.4429;0.4643;0.7643;0.8071;1" values="0;0;1;1;0;0"/>
          <text x="30" y="166"> | |_) | | | | (_| | | |__</text>
        </g>
        <g>
          <animate attributeName="opacity" dur="14s" repeatCount="indefinite"
            keyTimes="0;0.4536;0.4750;0.7643;0.8071;1" values="0;0;1;1;0;0"/>
          <text x="30" y="182"> |____/|_|_|\__,_| |____|</text>
        </g>
      </g>

      <g font-size="12.5" font-weight="normal" fill="#7ee787">
        <animate attributeName="opacity" dur="14s" repeatCount="indefinite"
          keyTimes="0;0.4643;0.4857;0.7643;0.8071;1" values="0;0;1;1;0;0"/>
        <text x="30" y="200">AI / ML Engineer &amp; Full-Stack Developer</text>
      </g>

      <!-- glint sweep across the ascii block -->
      <g clip-path="url(#asciiBox)">
        <rect y="105" width="120" height="105" fill="url(#glintGrad)" style="mix-blend-mode:screen">
          <animate attributeName="x" dur="14s" repeatCount="indefinite"
            keyTimes="0;0.4929;0.5786;1" values="-150;-150;460;-150"/>
          <animate attributeName="opacity" dur="14s" repeatCount="indefinite"
            keyTimes="0;0.4929;0.4929;0.5786;0.5786;1" values="0;0;1;1;0;0"/>
        </rect>
      </g>

      <!-- clear command -->
      <text clip-path="url(#clipClear)" x="30" y="224" xml:space="preserve"><tspan fill="#7ee787">bilal</tspan><tspan fill="#7d8590">@</tspan><tspan fill="#58a6ff">estin</tspan><tspan fill="#7d8590">:~$ </tspan><tspan fill="#e6edf3">clear</tspan></text>

      <!-- block cursor -->
      <rect width="9" height="16" fill="#7ee787">
        <animate attributeName="x" dur="14s" repeatCount="indefinite"
          keyTimes="0;0.0214;0.1143;0.1429;0.1429;0.2429;0.2786;0.2786;0.3893;0.4107;0.6429;0.6429;0.7329;0.7643;0.8071;1"
          values="30;30;215;215;30;410;410;30;295;295;295;30;206;206;30;30"/>
        <animate attributeName="y" dur="14s" repeatCount="indefinite"
          keyTimes="0;0.1429;0.1429;0.2786;0.2786;0.6429;0.6429;1"
          values="27;27;51;51;77;77;211;27"/>
        <animate attributeName="opacity" dur="14s" repeatCount="indefinite"
          keyTimes="0;0.4107;0.4107;0.6429;0.6429;0.7643;0.8071;1"
          values="1;1;0;0;1;1;0;0"/>
      </rect>

    </g>

    <!-- ambient sheen sweep across whole panel -->
    <g transform="skewX(-18)">
      <rect y="-40" width="140" height="380" fill="url(#sheenGrad)" style="mix-blend-mode:screen">
        <animate attributeName="x" dur="14s" repeatCount="indefinite"
          keyTimes="0;1" values="-300;1000"/>
      </rect>
    </g>

    <!-- pulsing accent border -->
    <rect x="1" y="1" width="758" height="298" rx="12" fill="none" stroke="#7ee787" stroke-width="1">
      <animate attributeName="stroke-opacity" values="0.15;0.5;0.15" dur="3.4s" repeatCount="indefinite"/>
    </rect>
    <rect x="1" y="1" width="758" height="298" rx="12" fill="none" stroke="#30363d" stroke-width="1"/>
  </g>
</svg>
