<svg width="1180" height="610" viewBox="0 0 1180 610" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
  <defs>
    <clipPath id="rounded"><rect x="0" y="0" width="1180" height="610" rx="28" ry="28"/></clipPath>
    <clipPath id="roundedLeft"><rect x="24" y="24" width="424" height="562" rx="20" ry="20"/></clipPath>
    <clipPath id="roundedRight"><rect x="496" y="24" width="660" height="562" rx="20" ry="20"/></clipPath>

    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#FFFFFF"/>
      <stop offset="100%" stop-color="#FFFFFF"/>
    </linearGradient>

    <linearGradient id="accentGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#2563EB"/>
      <stop offset="50%" stop-color="#06B6D4"/>
      <stop offset="100%" stop-color="#10B981"/>
      <animate attributeName="x1" values="0%;100%;0%" dur="8s" repeatCount="indefinite"/>
      <animate attributeName="x2" values="100%;200%;100%" dur="8s" repeatCount="indefinite"/>
    </linearGradient>

    <linearGradient id="asciiGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#2563EB"/>
      <stop offset="50%" stop-color="#06B6D4"/>
      <stop offset="100%" stop-color="#10B981"/>
      <animate attributeName="x1" values="0%;100%;0%" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="y1" values="0%;60%;0%" dur="6s" repeatCount="indefinite"/>
    </linearGradient>

    <linearGradient id="roleGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#06B6D4"/>
      <stop offset="100%" stop-color="#2563EB"/>
    </linearGradient>

    <linearGradient id="pillStroke" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#2563EB" stop-opacity="0.7"/>
      <stop offset="100%" stop-color="#10B981" stop-opacity="0.7"/>
    </linearGradient>

    <radialGradient id="glowBlue" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#93C5FD" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#93C5FD" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glowPurple" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#C4B5FD" stop-opacity="0.30"/>
      <stop offset="100%" stop-color="#C4B5FD" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glowEmerald" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#6EE7B7" stop-opacity="0.25"/>
      <stop offset="100%" stop-color="#6EE7B7" stop-opacity="0"/>
    </radialGradient>

    <linearGradient id="panelGlass" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#F8FAFC" stop-opacity="0.65"/>
      <stop offset="100%" stop-color="#F8FAFC" stop-opacity="0.82"/>
    </linearGradient>

    <linearGradient id="reflection" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#FFFFFF" stop-opacity="0.07"/>
      <stop offset="60%" stop-color="#FFFFFF" stop-opacity="0.015"/>
      <stop offset="100%" stop-color="#FFFFFF" stop-opacity="0"/>
    </linearGradient>

    <filter id="softBlur" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="40"/>
    </filter>
    <filter id="glowFilter" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="3.2" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>

    <pattern id="noise" width="120" height="120" patternUnits="userSpaceOnUse">
      <rect width="120" height="120" fill="transparent"/>
      <circle cx="10" cy="14" r="0.6" fill="#0F172A" opacity="0.02"/>
      <circle cx="55" cy="70" r="0.5" fill="#0F172A" opacity="0.02"/>
      <circle cx="90" cy="30" r="0.7" fill="#0F172A" opacity="0.02"/>
      <circle cx="30" cy="95" r="0.5" fill="#0F172A" opacity="0.02"/>
      <circle cx="105" cy="100" r="0.6" fill="#0F172A" opacity="0.02"/>
    </pattern>
  </defs>

  <g clip-path="url(#rounded)">
    <rect width="1180" height="610" fill="#FFFFFF"/>
    <rect width="1180" height="610" fill="url(#noise)"/>

    <!-- floating background glows -->
    <circle cx="140" cy="120" r="220" fill="url(#glowPurple)" filter="url(#softBlur)">
      <animateTransform attributeName="transform" type="translate" values="0,0; 30,25; 0,0" dur="14s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1020" cy="470" r="260" fill="url(#glowBlue)" filter="url(#softBlur)">
      <animateTransform attributeName="transform" type="translate" values="0,0; -25,-20; 0,0" dur="16s" repeatCount="indefinite"/>
    </circle>
    <circle cx="860" cy="90" r="180" fill="url(#glowEmerald)" filter="url(#softBlur)">
      <animateTransform attributeName="transform" type="translate" values="0,0; -20,30; 0,0" dur="12s" repeatCount="indefinite"/>
    </circle>

    
    <circle cx="748.9" cy="34.3" r="1.33" fill="#2563EB" opacity="0">
      <animate attributeName="opacity" values="0;0.6514808054671803;0" dur="7.3s" begin="3.4s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-42; 0,0" dur="7.3s" begin="3.4s" repeatCount="indefinite"/>
    </circle>

    <circle cx="119.1" cy="260.5" r="1.04" fill="#06B6D4" opacity="0">
      <animate attributeName="opacity" values="0;0.3394769428089918;0" dur="7.3s" begin="0.1s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-35; 0,0" dur="7.3s" begin="0.1s" repeatCount="indefinite"/>
    </circle>

    <circle cx="760.9" cy="330.6" r="1.26" fill="#10B981" opacity="0">
      <animate attributeName="opacity" values="0;0.6126186633247634;0" dur="9.5s" begin="0.0s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-44; 0,0" dur="9.5s" begin="0.0s" repeatCount="indefinite"/>
    </circle>

    <circle cx="815.9" cy="213.9" r="1.19" fill="#2563EB" opacity="0">
      <animate attributeName="opacity" values="0;0.2935223695750588;0" dur="11.7s" begin="0.5s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-30; 0,0" dur="11.7s" begin="0.5s" repeatCount="indefinite"/>
    </circle>

    <circle cx="986.1" cy="364.1" r="1.97" fill="#06B6D4" opacity="0">
      <animate attributeName="opacity" values="0;0.42034046974375905;0" dur="10.4s" begin="4.9s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-36; 0,0" dur="10.4s" begin="4.9s" repeatCount="indefinite"/>
    </circle>

    <circle cx="649.3" cy="492.8" r="1.74" fill="#10B981" opacity="0">
      <animate attributeName="opacity" values="0;0.270620972645048;0" dur="11.2s" begin="3.5s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-37; 0,0" dur="11.2s" begin="3.5s" repeatCount="indefinite"/>
    </circle>

    <circle cx="279.8" cy="185.0" r="1.10" fill="#2563EB" opacity="0">
      <animate attributeName="opacity" values="0;0.5360579999189801;0" dur="7.4s" begin="1.4s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-23; 0,0" dur="7.4s" begin="1.4s" repeatCount="indefinite"/>
    </circle>

    <circle cx="435.9" cy="231.0" r="1.25" fill="#06B6D4" opacity="0">
      <animate attributeName="opacity" values="0;0.5241089525501447;0" dur="7.6s" begin="3.2s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-48; 0,0" dur="7.6s" begin="3.2s" repeatCount="indefinite"/>
    </circle>

    <circle cx="215.1" cy="435.6" r="1.20" fill="#10B981" opacity="0">
      <animate attributeName="opacity" values="0;0.5006273846985908;0" dur="8.3s" begin="3.2s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-50; 0,0" dur="8.3s" begin="3.2s" repeatCount="indefinite"/>
    </circle>

    <circle cx="800.5" cy="500.4" r="1.93" fill="#2563EB" opacity="0">
      <animate attributeName="opacity" values="0;0.37048339418906623;0" dur="7.4s" begin="1.6s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-21; 0,0" dur="7.4s" begin="1.6s" repeatCount="indefinite"/>
    </circle>

    <circle cx="260.5" cy="557.5" r="2.05" fill="#06B6D4" opacity="0">
      <animate attributeName="opacity" values="0;0.6615464153832445;0" dur="7.9s" begin="2.0s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-40; 0,0" dur="7.9s" begin="2.0s" repeatCount="indefinite"/>
    </circle>

    <circle cx="543.1" cy="171.0" r="1.30" fill="#10B981" opacity="0">
      <animate attributeName="opacity" values="0;0.6540202976211146;0" dur="9.4s" begin="2.9s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-28; 0,0" dur="9.4s" begin="2.9s" repeatCount="indefinite"/>
    </circle>

    <circle cx="475.3" cy="145.0" r="2.20" fill="#2563EB" opacity="0">
      <animate attributeName="opacity" values="0;0.2993421086577966;0" dur="9.1s" begin="0.2s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-23; 0,0" dur="9.1s" begin="0.2s" repeatCount="indefinite"/>
    </circle>

    <circle cx="735.3" cy="471.5" r="1.51" fill="#06B6D4" opacity="0">
      <animate attributeName="opacity" values="0;0.48810145529461163;0" dur="6.4s" begin="5.0s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-31; 0,0" dur="6.4s" begin="5.0s" repeatCount="indefinite"/>
    </circle>

    <circle cx="1127.0" cy="510.6" r="1.01" fill="#10B981" opacity="0">
      <animate attributeName="opacity" values="0;0.37007133547864424;0" dur="10.3s" begin="2.7s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-40; 0,0" dur="10.3s" begin="2.7s" repeatCount="indefinite"/>
    </circle>

    <circle cx="750.7" cy="83.6" r="1.52" fill="#2563EB" opacity="0">
      <animate attributeName="opacity" values="0;0.36852507283799085;0" dur="8.7s" begin="4.4s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-49; 0,0" dur="8.7s" begin="4.4s" repeatCount="indefinite"/>
    </circle>

    <circle cx="590.7" cy="121.8" r="2.10" fill="#06B6D4" opacity="0">
      <animate attributeName="opacity" values="0;0.5240365951471775;0" dur="11.2s" begin="3.2s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-29; 0,0" dur="11.2s" begin="3.2s" repeatCount="indefinite"/>
    </circle>

    <circle cx="194.2" cy="454.6" r="1.65" fill="#10B981" opacity="0">
      <animate attributeName="opacity" values="0;0.39587022565210284;0" dur="10.7s" begin="0.0s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-36; 0,0" dur="10.7s" begin="0.0s" repeatCount="indefinite"/>
    </circle>

    <circle cx="42.2" cy="549.6" r="2.05" fill="#2563EB" opacity="0">
      <animate attributeName="opacity" values="0;0.6451043196418182;0" dur="11.0s" begin="0.3s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-29; 0,0" dur="11.0s" begin="0.3s" repeatCount="indefinite"/>
    </circle>

    <circle cx="1099.5" cy="68.8" r="1.58" fill="#06B6D4" opacity="0">
      <animate attributeName="opacity" values="0;0.30777615902489325;0" dur="6.4s" begin="3.8s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-43; 0,0" dur="6.4s" begin="3.8s" repeatCount="indefinite"/>
    </circle>

    <circle cx="561.8" cy="333.4" r="1.32" fill="#10B981" opacity="0">
      <animate attributeName="opacity" values="0;0.49268323995075625;0" dur="11.2s" begin="1.1s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-33; 0,0" dur="11.2s" begin="1.1s" repeatCount="indefinite"/>
    </circle>

    <circle cx="852.1" cy="134.7" r="1.37" fill="#2563EB" opacity="0">
      <animate attributeName="opacity" values="0;0.48290912846601575;0" dur="12.0s" begin="2.2s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-39; 0,0" dur="12.0s" begin="2.2s" repeatCount="indefinite"/>
    </circle>

    <!-- scanline sweep -->
    <rect x="0" y="0" width="1180" height="4" fill="#06B6D4" opacity="0.025">
      <animate attributeName="y" values="0;610;0" dur="9s" repeatCount="indefinite"/>
    </rect>

    <!-- outer border shimmer -->
    <rect x="1.5" y="1.5" width="1177" height="607" rx="27" ry="27" fill="none" stroke="url(#accentGrad)" stroke-width="1.4" opacity="0.55"/>
    <rect x="1.5" y="1.5" width="1177" height="607" rx="27" ry="27" fill="none" stroke="#E2E8F0" stroke-width="1"/>

    <!-- ============ LEFT PANEL ============ -->
    <g>
      <rect x="24" y="24" width="424" height="562" rx="20" ry="20" fill="url(#panelGlass)" stroke="#E2E8F0" stroke-width="1"/>
      <rect x="24" y="24" width="424" height="236" rx="20" ry="20" fill="url(#reflection)" clip-path="url(#roundedLeft)"/>
      <rect x="25" y="25" width="422" height="560" rx="19" ry="19" fill="none" stroke="url(#accentGrad)" stroke-width="1" opacity="0.5">
        <animate attributeName="opacity" values="0.25;0.6;0.25" dur="4s" repeatCount="indefinite"/>
      </rect>

      <g clip-path="url(#roundedLeft)">
        <g filter="url(#glowFilter)">
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-6; 0,0" dur="5s" repeatCount="indefinite"/>
          
      <text x="119" y="150" font-family="'JetBrains Mono','Fira Code',monospace"
        font-size="20" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">     .-"""""-.     <animate attributeName="opacity" attributeType="XML" begin="0.5s" dur="0.5s" fill="freeze" values="0;1"/></text>

      <text x="119" y="175" font-family="'JetBrains Mono','Fira Code',monospace"
        font-size="20" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">    /  ◉   ◉  \    <animate attributeName="opacity" attributeType="XML" begin="0.85s" dur="0.5s" fill="freeze" values="0;1"/></text>

      <text x="119" y="200" font-family="'JetBrains Mono','Fira Code',monospace"
        font-size="20" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">   |     ▽      |   <animate attributeName="opacity" attributeType="XML" begin="1.2s" dur="0.5s" fill="freeze" values="0;1"/></text>

      <text x="119" y="225" font-family="'JetBrains Mono','Fira Code',monospace"
        font-size="20" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">   |   ‿‿‿‿‿    |   <animate attributeName="opacity" attributeType="XML" begin="1.5499999999999998s" dur="0.5s" fill="freeze" values="0;1"/></text>

      <text x="119" y="250" font-family="'JetBrains Mono','Fira Code',monospace"
        font-size="20" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">    \ ._____. /    <animate attributeName="opacity" attributeType="XML" begin="1.9s" dur="0.5s" fill="freeze" values="0;1"/></text>

      <text x="119" y="275" font-family="'JetBrains Mono','Fira Code',monospace"
        font-size="20" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">     '-.....-'     <animate attributeName="opacity" attributeType="XML" begin="2.25s" dur="0.5s" fill="freeze" values="0;1"/></text>

      <text x="119" y="300" font-family="'JetBrains Mono','Fira Code',monospace"
        font-size="20" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">   &lt; KIRTAN.DEV &gt;  <animate attributeName="opacity" attributeType="XML" begin="2.5999999999999996s" dur="0.5s" fill="freeze" values="0;1"/></text>

      <text x="119" y="325" font-family="'JetBrains Mono','Fira Code',monospace"
        font-size="20" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">   [ CSE // 2028 ] <animate attributeName="opacity" attributeType="XML" begin="2.9499999999999997s" dur="0.5s" fill="freeze" values="0;1"/></text>
        </g>

        <!-- terminal chrome dots -->
        <circle cx="52" cy="56" r="6" fill="#EF4444" opacity="0.85"/>
        <circle cx="72" cy="56" r="6" fill="#F59E0B" opacity="0.85"/>
        <circle cx="92" cy="56" r="6" fill="#10B981" opacity="0.85"/>
        <text x="208" y="60" text-anchor="middle" font-family="'JetBrains Mono',monospace" font-size="12" fill="#475569">portrait.sh</text>

        <!-- scanline inside portrait -->
        <rect x="24" y="90" width="378" height="2.4" fill="#06B6D4" opacity="0.18">
          <animate attributeName="y" values="90;520;90" dur="5.5s" repeatCount="indefinite"/>
        </rect>

        <text x="208" y="540" text-anchor="middle" font-family="'JetBrains Mono',monospace" font-size="12" fill="#475569" opacity="0">
          building things that matter_
          <animate attributeName="opacity" begin="4.2s" dur="0.6s" fill="freeze" values="0;1"/>
        </text>
      </g>
    </g>

    <!-- ============ RIGHT PANEL (terminal) ============ -->
    <g>
      <rect x="496" y="24" width="660" height="562" rx="20" ry="20" fill="url(#panelGlass)" stroke="#E2E8F0" stroke-width="1"/>
      <rect x="496" y="24" width="660" height="236" rx="20" ry="20" fill="url(#reflection)" clip-path="url(#roundedRight)"/>
      <rect x="497" y="25" width="658" height="560" rx="19" ry="19" fill="none" stroke="url(#accentGrad)" stroke-width="1" opacity="0.5">
        <animate attributeName="opacity" values="0.25;0.6;0.25" dur="4s" begin="1s" repeatCount="indefinite"/>
      </rect>

      <g clip-path="url(#roundedRight)">
        <!-- chrome bar -->
        <circle cx="530" cy="56" r="6" fill="#EF4444" opacity="0.85"/>
        <circle cx="550" cy="56" r="6" fill="#F59E0B" opacity="0.85"/>
        <circle cx="570" cy="56" r="6" fill="#10B981" opacity="0.85"/>
        <text x="826" y="60" text-anchor="middle" font-family="'JetBrains Mono',monospace" font-size="12" fill="#475569">~/kirtan — zsh</text>
        <line x1="496" y1="76" x2="1156" y2="76" stroke="#E2E8F0" stroke-width="1"/>

        <!-- greeting -->
        <text x="520" y="118" font-family="'JetBrains Mono',monospace" font-size="15" fill="#10B981" opacity="0">
          $ whoami
          <animate attributeName="opacity" begin="0.2s" dur="0.4s" fill="freeze" values="0;1"/>
        </text>
        <text x="520" y="150" font-family="'Inter','Segoe UI',sans-serif" font-size="26" font-weight="700" fill="#0F172A" opacity="0">
          Hi 👋
          <animate attributeName="opacity" begin="0.7s" dur="0.4s" fill="freeze" values="0;1"/>
        </text>
        <text x="520" y="190" font-family="'Inter','Segoe UI',sans-serif" font-size="30" font-weight="800" opacity="0">
          <tspan fill="#0F172A">I'm </tspan><tspan fill="url(#accentGrad)">Kirtan Kumar Sanghi</tspan>
          <animate attributeName="opacity" begin="1.1s" dur="0.5s" fill="freeze" values="0;1"/>
        </text>

        <text x="520" y="232" font-family="'JetBrains Mono',monospace" font-size="16" fill="#06B6D4" opacity="0">
          &gt;
          <animate attributeName="opacity" begin="1.7s" dur="0.3s" fill="freeze" values="0;1"/>
        </text>
        
    <g opacity="0">
      <animate attributeName="opacity" dur="15.999999999999998s" repeatCount="indefinite"
        keyTimes="0.00000;0.00030;0.18125;0.18155;1.00000"
        values="0;1;1;0;0" calcMode="discrete"/>
      <clipPath id="clipRole0">
        <rect x="562" y="206" height="38" width="0">
          <animate attributeName="width" dur="15.999999999999998s" repeatCount="indefinite"
            keyTimes="0.00000;0.05625;0.15000;0.18125;1.00000"
            values="0;326.0;326.0;0;0" calcMode="linear"/>
        </rect>
      </clipPath>
      <g clip-path="url(#clipRole0)">
        <text x="562" y="232" font-family="'JetBrains Mono','Fira Code',monospace"
          font-size="26" font-weight="600" fill="url(#roleGrad)">Full-Stack Developer</text>
      </g>
      <rect x="562" y="210" width="3" height="26" fill="url(#roleGrad)">
        <animate attributeName="x" dur="15.999999999999998s" repeatCount="indefinite"
          keyTimes="0.00000;0.05625;0.15000;0.18125;1.00000"
          values="562.0;888.0;888.0;562.0;562.0" calcMode="linear"/>
        <animate attributeName="opacity" values="1;0.15;1" dur="0.85s" repeatCount="indefinite"/>
      </rect>
    </g>

    <g opacity="0">
      <animate attributeName="opacity" dur="15.999999999999998s" repeatCount="indefinite"
        keyTimes="0.00000;0.20000;0.20030;0.38125;0.38155;1.00000"
        values="0;0;1;1;0;0" calcMode="discrete"/>
      <clipPath id="clipRole1">
        <rect x="562" y="206" height="38" width="0">
          <animate attributeName="width" dur="15.999999999999998s" repeatCount="indefinite"
            keyTimes="0.00000;0.20000;0.25625;0.35000;0.38125;1.00000"
            values="0;0;341.6;341.6;0;0" calcMode="linear"/>
        </rect>
      </clipPath>
      <g clip-path="url(#clipRole1)">
        <text x="562" y="232" font-family="'JetBrains Mono','Fira Code',monospace"
          font-size="26" font-weight="600" fill="url(#roleGrad)">AI &amp; Cloud Enthusiast</text>
      </g>
      <rect x="562" y="210" width="3" height="26" fill="url(#roleGrad)">
        <animate attributeName="x" dur="15.999999999999998s" repeatCount="indefinite"
          keyTimes="0.00000;0.20000;0.25625;0.35000;0.38125;1.00000"
          values="562.0;562.0;903.6;903.6;562.0;562.0" calcMode="linear"/>
        <animate attributeName="opacity" values="1;0.15;1" dur="0.85s" repeatCount="indefinite"/>
      </rect>
    </g>

    <g opacity="0">
      <animate attributeName="opacity" dur="15.999999999999998s" repeatCount="indefinite"
        keyTimes="0.00000;0.40000;0.40030;0.58125;0.58155;1.00000"
        values="0;0;1;1;0;0" calcMode="discrete"/>
      <clipPath id="clipRole2">
        <rect x="562" y="206" height="38" width="0">
          <animate attributeName="width" dur="15.999999999999998s" repeatCount="indefinite"
            keyTimes="0.00000;0.40000;0.45625;0.55000;0.58125;1.00000"
            values="0;0;372.8;372.8;0;0" calcMode="linear"/>
        </rect>
      </clipPath>
      <g clip-path="url(#clipRole2)">
        <text x="562" y="232" font-family="'JetBrains Mono','Fira Code',monospace"
          font-size="26" font-weight="600" fill="url(#roleGrad)">Open Source Contributor</text>
      </g>
      <rect x="562" y="210" width="3" height="26" fill="url(#roleGrad)">
        <animate attributeName="x" dur="15.999999999999998s" repeatCount="indefinite"
          keyTimes="0.00000;0.40000;0.45625;0.55000;0.58125;1.00000"
          values="562.0;562.0;934.8;934.8;562.0;562.0" calcMode="linear"/>
        <animate attributeName="opacity" values="1;0.15;1" dur="0.85s" repeatCount="indefinite"/>
      </rect>
    </g>

    <g opacity="0">
      <animate attributeName="opacity" dur="15.999999999999998s" repeatCount="indefinite"
        keyTimes="0.00000;0.60000;0.60030;0.78125;0.78155;1.00000"
        values="0;0;1;1;0;0" calcMode="discrete"/>
      <clipPath id="clipRole3">
        <rect x="562" y="206" height="38" width="0">
          <animate attributeName="width" dur="15.999999999999998s" repeatCount="indefinite"
            keyTimes="0.00000;0.60000;0.65625;0.75000;0.78125;1.00000"
            values="0;0;294.8;294.8;0;0" calcMode="linear"/>
        </rect>
      </clipPath>
      <g clip-path="url(#clipRole3)">
        <text x="562" y="232" font-family="'JetBrains Mono','Fira Code',monospace"
          font-size="26" font-weight="600" fill="url(#roleGrad)">B.Tech CSE Student</text>
      </g>
      <rect x="562" y="210" width="3" height="26" fill="url(#roleGrad)">
        <animate attributeName="x" dur="15.999999999999998s" repeatCount="indefinite"
          keyTimes="0.00000;0.60000;0.65625;0.75000;0.78125;1.00000"
          values="562.0;562.0;856.8;856.8;562.0;562.0" calcMode="linear"/>
        <animate attributeName="opacity" values="1;0.15;1" dur="0.85s" repeatCount="indefinite"/>
      </rect>
    </g>

    <g opacity="0">
      <animate attributeName="opacity" dur="15.999999999999998s" repeatCount="indefinite"
        keyTimes="0.00000;0.80000;0.80030;0.98125;0.98155;1.00000"
        values="0;0;1;1;0;0" calcMode="discrete"/>
      <clipPath id="clipRole4">
        <rect x="562" y="206" height="38" width="0">
          <animate attributeName="width" dur="15.999999999999998s" repeatCount="indefinite"
            keyTimes="0.00000;0.80000;0.85625;0.95000;0.98125;1.00000"
            values="0;0;232.4;232.4;0;0" calcMode="linear"/>
        </rect>
      </clipPath>
      <g clip-path="url(#clipRole4)">
        <text x="562" y="232" font-family="'JetBrains Mono','Fira Code',monospace"
          font-size="26" font-weight="600" fill="url(#roleGrad)">Problem Solver</text>
      </g>
      <rect x="562" y="210" width="3" height="26" fill="url(#roleGrad)">
        <animate attributeName="x" dur="15.999999999999998s" repeatCount="indefinite"
          keyTimes="0.00000;0.80000;0.85625;0.95000;0.98125;1.00000"
          values="562.0;562.0;794.4;794.4;562.0;562.0" calcMode="linear"/>
        <animate attributeName="opacity" values="1;0.15;1" dur="0.85s" repeatCount="indefinite"/>
      </rect>
    </g>

        <line x1="520" y1="256" x2="1132" y2="256" stroke="#E2E8F0" stroke-width="1" opacity="0.7"/>

        
    <g opacity="0">
      <animate attributeName="opacity" begin="4.2s" dur="0.5s" fill="freeze" values="0;1"/>
      <text x="520" y="288" font-family="'JetBrains Mono',monospace" font-size="16" fill="#06B6D4">›</text>
      <text x="538" y="288" font-family="'JetBrains Mono',monospace" font-size="16" fill="#475569">Location:</text>
      <text x="670" y="288" font-family="'JetBrains Mono',monospace" font-size="16" font-weight="600" fill="#0F172A">Hyderabad, India</text>
    </g>

    <g opacity="0">
      <animate attributeName="opacity" begin="4.55s" dur="0.5s" fill="freeze" values="0;1"/>
      <text x="520" y="322" font-family="'JetBrains Mono',monospace" font-size="16" fill="#06B6D4">›</text>
      <text x="538" y="322" font-family="'JetBrains Mono',monospace" font-size="16" fill="#475569">Education:</text>
      <text x="670" y="322" font-family="'JetBrains Mono',monospace" font-size="16" font-weight="600" fill="#0F172A">B.Tech CSE @ Manipal University Jaipur</text>
    </g>

    <g opacity="0">
      <animate attributeName="opacity" begin="4.9s" dur="0.5s" fill="freeze" values="0;1"/>
      <text x="520" y="356" font-family="'JetBrains Mono',monospace" font-size="16" fill="#06B6D4">›</text>
      <text x="538" y="356" font-family="'JetBrains Mono',monospace" font-size="16" fill="#475569">Focus:</text>
      <text x="670" y="356" font-family="'JetBrains Mono',monospace" font-size="16" font-weight="600" fill="#0F172A">AI Governance &amp; Cloud-Native Systems</text>
    </g>

    <g opacity="0">
      <animate attributeName="opacity" begin="5.25s" dur="0.5s" fill="freeze" values="0;1"/>
      <text x="520" y="390" font-family="'JetBrains Mono',monospace" font-size="16" fill="#06B6D4">›</text>
      <text x="538" y="390" font-family="'JetBrains Mono',monospace" font-size="16" fill="#475569">Portfolio:</text>
      <text x="670" y="390" font-family="'JetBrains Mono',monospace" font-size="16" font-weight="600" fill="#0F172A">github.com/kirtankumarsanghi</text>
    </g>

    <g opacity="0">
      <animate attributeName="opacity" begin="5.6s" dur="0.5s" fill="freeze" values="0;1"/>
      <text x="520" y="424" font-family="'JetBrains Mono',monospace" font-size="16" fill="#06B6D4">›</text>
      <text x="538" y="424" font-family="'JetBrains Mono',monospace" font-size="16" fill="#475569">Email:</text>
      <text x="670" y="424" font-family="'JetBrains Mono',monospace" font-size="16" font-weight="600" fill="#0F172A">kirtansanghi@gmail.com</text>
    </g>

        <line x1="520" y1="440" x2="1132" y2="440" stroke="#E2E8F0" stroke-width="1" opacity="0.7"/>

        <text x="520" y="462" font-family="'JetBrains Mono',monospace" font-size="14" fill="#475569" opacity="0">
          $ ls ./skills
          <animate attributeName="opacity" begin="5.7s" dur="0.4s" fill="freeze" values="0;1"/>
        </text>
        
    <g opacity="0" transform="translate(0,0)">
      <animate attributeName="opacity" begin="6.0s" dur="0.4s" fill="freeze" values="0;1"/>
      <rect x="520" y="470" rx="16" ry="16" width="72.0" height="30" fill="#F8FAFC"
        fill-opacity="0.7" stroke="url(#pillStroke)" stroke-width="1">
        <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" begin="6.0s" repeatCount="indefinite"/>
      </rect>
      <rect x="520" y="470" rx="16" ry="16" width="72.0" height="30" fill="none"
        stroke="#06B6D4" stroke-width="0" opacity="0">
        <animate attributeName="stroke-width" values="0;1.4;0" dur="2.4s" begin="6.0s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.7;0" dur="2.4s" begin="6.0s" repeatCount="indefinite"/>
      </rect>
      <text x="556.0" y="490" text-anchor="middle" font-family="'Inter','Segoe UI',sans-serif"
        font-size="13.5" font-weight="500" fill="#0F172A">React</text>
    </g>

    <g opacity="0" transform="translate(0,0)">
      <animate attributeName="opacity" begin="6.12s" dur="0.4s" fill="freeze" values="0;1"/>
      <rect x="602.0" y="470" rx="16" ry="16" width="112.0" height="30" fill="#F8FAFC"
        fill-opacity="0.7" stroke="url(#pillStroke)" stroke-width="1">
        <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" begin="6.12s" repeatCount="indefinite"/>
      </rect>
      <rect x="602.0" y="470" rx="16" ry="16" width="112.0" height="30" fill="none"
        stroke="#06B6D4" stroke-width="0" opacity="0">
        <animate attributeName="stroke-width" values="0;1.4;0" dur="2.4s" begin="6.12s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.7;0" dur="2.4s" begin="6.12s" repeatCount="indefinite"/>
      </rect>
      <text x="658.0" y="490" text-anchor="middle" font-family="'Inter','Segoe UI',sans-serif"
        font-size="13.5" font-weight="500" fill="#0F172A">TypeScript</text>
    </g>

    <g opacity="0" transform="translate(0,0)">
      <animate attributeName="opacity" begin="6.24s" dur="0.4s" fill="freeze" values="0;1"/>
      <rect x="724.0" y="470" rx="16" ry="16" width="80.0" height="30" fill="#F8FAFC"
        fill-opacity="0.7" stroke="url(#pillStroke)" stroke-width="1">
        <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" begin="6.24s" repeatCount="indefinite"/>
      </rect>
      <rect x="724.0" y="470" rx="16" ry="16" width="80.0" height="30" fill="none"
        stroke="#06B6D4" stroke-width="0" opacity="0">
        <animate attributeName="stroke-width" values="0;1.4;0" dur="2.4s" begin="6.24s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.7;0" dur="2.4s" begin="6.24s" repeatCount="indefinite"/>
      </rect>
      <text x="764.0" y="490" text-anchor="middle" font-family="'Inter','Segoe UI',sans-serif"
        font-size="13.5" font-weight="500" fill="#0F172A">Python</text>
    </g>

    <g opacity="0" transform="translate(0,0)">
      <animate attributeName="opacity" begin="6.36s" dur="0.4s" fill="freeze" values="0;1"/>
      <rect x="814.0" y="470" rx="16" ry="16" width="88.0" height="30" fill="#F8FAFC"
        fill-opacity="0.7" stroke="url(#pillStroke)" stroke-width="1">
        <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" begin="6.36s" repeatCount="indefinite"/>
      </rect>
      <rect x="814.0" y="470" rx="16" ry="16" width="88.0" height="30" fill="none"
        stroke="#06B6D4" stroke-width="0" opacity="0">
        <animate attributeName="stroke-width" values="0;1.4;0" dur="2.4s" begin="6.36s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.7;0" dur="2.4s" begin="6.36s" repeatCount="indefinite"/>
      </rect>
      <text x="858.0" y="490" text-anchor="middle" font-family="'Inter','Segoe UI',sans-serif"
        font-size="13.5" font-weight="500" fill="#0F172A">FastAPI</text>
    </g>

    <g opacity="0" transform="translate(0,0)">
      <animate attributeName="opacity" begin="6.48s" dur="0.4s" fill="freeze" values="0;1"/>
      <rect x="912.0" y="470" rx="16" ry="16" width="88.0" height="30" fill="#F8FAFC"
        fill-opacity="0.7" stroke="url(#pillStroke)" stroke-width="1">
        <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" begin="6.48s" repeatCount="indefinite"/>
      </rect>
      <rect x="912.0" y="470" rx="16" ry="16" width="88.0" height="30" fill="none"
        stroke="#06B6D4" stroke-width="0" opacity="0">
        <animate attributeName="stroke-width" values="0;1.4;0" dur="2.4s" begin="6.48s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.7;0" dur="2.4s" begin="6.48s" repeatCount="indefinite"/>
      </rect>
      <text x="956.0" y="490" text-anchor="middle" font-family="'Inter','Segoe UI',sans-serif"
        font-size="13.5" font-weight="500" fill="#0F172A">Node.js</text>
    </g>

    <g opacity="0" transform="translate(0,0)">
      <animate attributeName="opacity" begin="6.6s" dur="0.4s" fill="freeze" values="0;1"/>
      <rect x="1010.0" y="470" rx="16" ry="16" width="80.0" height="30" fill="#F8FAFC"
        fill-opacity="0.7" stroke="url(#pillStroke)" stroke-width="1">
        <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" begin="6.6s" repeatCount="indefinite"/>
      </rect>
      <rect x="1010.0" y="470" rx="16" ry="16" width="80.0" height="30" fill="none"
        stroke="#06B6D4" stroke-width="0" opacity="0">
        <animate attributeName="stroke-width" values="0;1.4;0" dur="2.4s" begin="6.6s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.7;0" dur="2.4s" begin="6.6s" repeatCount="indefinite"/>
      </rect>
      <text x="1050.0" y="490" text-anchor="middle" font-family="'Inter','Segoe UI',sans-serif"
        font-size="13.5" font-weight="500" fill="#0F172A">Docker</text>
    </g>

    <g opacity="0" transform="translate(0,0)">
      <animate attributeName="opacity" begin="6.72s" dur="0.4s" fill="freeze" values="0;1"/>
      <rect x="520" y="508" rx="16" ry="16" width="112.0" height="30" fill="#F8FAFC"
        fill-opacity="0.7" stroke="url(#pillStroke)" stroke-width="1">
        <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" begin="6.72s" repeatCount="indefinite"/>
      </rect>
      <rect x="520" y="508" rx="16" ry="16" width="112.0" height="30" fill="none"
        stroke="#06B6D4" stroke-width="0" opacity="0">
        <animate attributeName="stroke-width" values="0;1.4;0" dur="2.4s" begin="6.72s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.7;0" dur="2.4s" begin="6.72s" repeatCount="indefinite"/>
      </rect>
      <text x="576.0" y="528" text-anchor="middle" font-family="'Inter','Segoe UI',sans-serif"
        font-size="13.5" font-weight="500" fill="#0F172A">Kubernetes</text>
    </g>

    <g opacity="0" transform="translate(0,0)">
      <animate attributeName="opacity" begin="6.84s" dur="0.4s" fill="freeze" values="0;1"/>
      <rect x="642.0" y="508" rx="16" ry="16" width="112.0" height="30" fill="#F8FAFC"
        fill-opacity="0.7" stroke="url(#pillStroke)" stroke-width="1">
        <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" begin="6.84s" repeatCount="indefinite"/>
      </rect>
      <rect x="642.0" y="508" rx="16" ry="16" width="112.0" height="30" fill="none"
        stroke="#06B6D4" stroke-width="0" opacity="0">
        <animate attributeName="stroke-width" values="0;1.4;0" dur="2.4s" begin="6.84s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.7;0" dur="2.4s" begin="6.84s" repeatCount="indefinite"/>
      </rect>
      <text x="698.0" y="528" text-anchor="middle" font-family="'Inter','Segoe UI',sans-serif"
        font-size="13.5" font-weight="500" fill="#0F172A">PostgreSQL</text>
    </g>

    <g opacity="0" transform="translate(0,0)">
      <animate attributeName="opacity" begin="6.96s" dur="0.4s" fill="freeze" values="0;1"/>
      <rect x="764.0" y="508" rx="16" ry="16" width="88.0" height="30" fill="#F8FAFC"
        fill-opacity="0.7" stroke="url(#pillStroke)" stroke-width="1">
        <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" begin="6.96s" repeatCount="indefinite"/>
      </rect>
      <rect x="764.0" y="508" rx="16" ry="16" width="88.0" height="30" fill="none"
        stroke="#06B6D4" stroke-width="0" opacity="0">
        <animate attributeName="stroke-width" values="0;1.4;0" dur="2.4s" begin="6.96s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.7;0" dur="2.4s" begin="6.96s" repeatCount="indefinite"/>
      </rect>
      <text x="808.0" y="528" text-anchor="middle" font-family="'Inter','Segoe UI',sans-serif"
        font-size="13.5" font-weight="500" fill="#0F172A">MongoDB</text>
    </g>

    <g opacity="0" transform="translate(0,0)">
      <animate attributeName="opacity" begin="7.08s" dur="0.4s" fill="freeze" values="0;1"/>
      <rect x="862.0" y="508" rx="16" ry="16" width="56.0" height="30" fill="#F8FAFC"
        fill-opacity="0.7" stroke="url(#pillStroke)" stroke-width="1">
        <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" begin="7.08s" repeatCount="indefinite"/>
      </rect>
      <rect x="862.0" y="508" rx="16" ry="16" width="56.0" height="30" fill="none"
        stroke="#06B6D4" stroke-width="0" opacity="0">
        <animate attributeName="stroke-width" values="0;1.4;0" dur="2.4s" begin="7.08s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.7;0" dur="2.4s" begin="7.08s" repeatCount="indefinite"/>
      </rect>
      <text x="890.0" y="528" text-anchor="middle" font-family="'Inter','Segoe UI',sans-serif"
        font-size="13.5" font-weight="500" fill="#0F172A">Git</text>
    </g>

        <line x1="520" y1="554" x2="1132" y2="554" stroke="#E2E8F0" stroke-width="1" opacity="0.7"/>

        
    <a href="https://github.com/kirtankumarsanghi" target="_blank">
    <g opacity="0" transform="translate(541,566)">
      <animate attributeName="opacity" begin="8.0s" dur="0.5s" fill="freeze" values="0;1"/>
      <circle cx="0" cy="0" r="21" fill="#F8FAFC" fill-opacity="0.7" stroke="url(#pillStroke)" stroke-width="1.2"/>
      <circle cx="0" cy="0" r="21" fill="none" stroke="#06B6D4" stroke-width="0" opacity="0">
        <animate attributeName="stroke-width" values="0;2;0" dur="2.6s" begin="8.0s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.8;0" dur="2.6s" begin="8.0s" repeatCount="indefinite"/>
      </circle>
      <g transform="translate(-10,-10) scale(0.83)" fill="#0F172A">
        <path d="M12 1C5.9 1 1 5.9 1 12c0 4.9 3.2 9 7.6 10.5.6.1.8-.3.8-.6v-2.1c-3.1.7-3.8-1.5-3.8-1.5-.5-1.3-1.2-1.6-1.2-1.6-1-.7.1-.7.1-.7 1.1.1 1.7 1.1 1.7 1.1 1 1.7 2.6 1.2 3.2.9.1-.7.4-1.2.7-1.5-2.5-.3-5.1-1.2-5.1-5.5 0-1.2.4-2.2 1.1-3-.1-.3-.5-1.4.1-3 0 0 .9-.3 3 1.1.9-.2 1.8-.4 2.7-.4.9 0 1.8.1 2.7.4 2.1-1.4 3-1.1 3-1.1.6 1.6.2 2.7.1 3 .7.8 1.1 1.8 1.1 3 0 4.3-2.6 5.2-5.1 5.5.4.4.8 1.1.8 2.2v3.3c0 .3.2.7.8.6C19.8 21 23 16.9 23 12c0-6.1-4.9-11-11-11z"/>
      </g>
      <title>GitHub</title>
    </g>
    </a>

    <a href="https://linkedin.com/in/kirtan-kumar-sanghi" target="_blank">
    <g opacity="0" transform="translate(605,566)">
      <animate attributeName="opacity" begin="8.15s" dur="0.5s" fill="freeze" values="0;1"/>
      <circle cx="0" cy="0" r="21" fill="#F8FAFC" fill-opacity="0.7" stroke="url(#pillStroke)" stroke-width="1.2"/>
      <circle cx="0" cy="0" r="21" fill="none" stroke="#06B6D4" stroke-width="0" opacity="0">
        <animate attributeName="stroke-width" values="0;2;0" dur="2.6s" begin="8.15s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.8;0" dur="2.6s" begin="8.15s" repeatCount="indefinite"/>
      </circle>
      <g transform="translate(-10,-10) scale(0.83)" fill="#0F172A">
        <path d="M6.94 5a2 2 0 11-4-.002 2 2 0 014 .002zM7 8.48H3V21h4V8.48zm6.32 0H9.34V21h3.94v-6.57c0-3.66 4.77-3.96 4.77 0V21H22v-7.93c0-6.17-7.06-5.94-8.68-2.91V8.48z"/>
      </g>
      <title>LinkedIn</title>
    </g>
    </a>

    <a href="mailto:kirtansanghi@gmail.com" target="_blank">
    <g opacity="0" transform="translate(669,566)">
      <animate attributeName="opacity" begin="8.3s" dur="0.5s" fill="freeze" values="0;1"/>
      <circle cx="0" cy="0" r="21" fill="#F8FAFC" fill-opacity="0.7" stroke="url(#pillStroke)" stroke-width="1.2"/>
      <circle cx="0" cy="0" r="21" fill="none" stroke="#06B6D4" stroke-width="0" opacity="0">
        <animate attributeName="stroke-width" values="0;2;0" dur="2.6s" begin="8.3s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.8;0" dur="2.6s" begin="8.3s" repeatCount="indefinite"/>
      </circle>
      <g transform="translate(-10,-10) scale(0.83)" fill="#0F172A">
        <path d="M2 4h20v16H2V4zm2 2v.01L12 13l8-6.99V6H4zm16 2.24l-7.4 6.46a1 1 0 01-1.2 0L4 8.24V18h16V8.24z"/>
      </g>
      <title>Email</title>
    </g>
    </a>
      </g>
    </g>
  </g>
</svg>
