<!-- 🐍 Nokia Style Moving Snake Border Animation -->
<p align="center">
<svg width="100%" height="140" viewBox="0 0 900 140" xmlns="http://www.w3.org/2000/svg">

  <!-- Border -->
  <rect x="5" y="5" width="890" height="130"
        fill="none" stroke="#2f81f7" stroke-width="2" rx="12"/>

  <!-- Snake head -->
  <rect width="16" height="16" fill="#7ee787">
    <animateMotion
      dur="10s"
      repeatCount="indefinite"
      path="
        M 10 10
        L 880 10
        L 880 120
        L 10 120
        L 10 10
      " />
  </rect>

  <!-- Snake body (follows head) -->
  <rect width="14" height="14" fill="#58a6ff">
    <animateMotion
      dur="10s"
      begin="0.4s"
      repeatCount="indefinite"
      path="
        M 10 10
        L 880 10
        L 880 120
        L 10 120
        L 10 10
      " />
  </rect>

  <rect width="12" height="12" fill="#58a6ff">
    <animateMotion
      dur="10s"
      begin="0.8s"
      repeatCount="indefinite"
      path="
        M 10 10
        L 880 10
        L 880 120
        L 10 120
        L 10 10
      " />
  </rect>

</svg>
</p>

<p align="center"><i>Nokia-style snake moving endlessly around the border</i></p>
