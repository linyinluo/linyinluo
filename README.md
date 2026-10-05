<svg width="100%" height="360" viewBox="0 0 1200 360" xmlns="http://www.w3.org/2000/svg">

<defs>

  <!-- 蓝白条纹背景 -->
  <pattern id="stripes"
           width="100"
           height="100"
           patternUnits="userSpaceOnUse"
           patternTransform="rotate(25)">

    <rect width="100" height="100" fill="#f8feff"/>

    <rect width="45"
          height="100"
          fill="#d9f4f8"/>

  </pattern>

  <!-- 气泡渐变 -->
  <radialGradient id="bubble">

    <stop offset="0%"
          stop-color="#ffffff"
          stop-opacity="0.95"/>

    <stop offset="55%"
          stop-color="#d8f7fb"
          stop-opacity="0.65"/>

    <stop offset="100%"
          stop-color="#8bd8e6"
          stop-opacity="0.12"/>

  </radialGradient>

  <!-- 玻璃高光 -->
  <linearGradient id="glass"
                  x1="0"
                  y1="0"
                  x2="1"
                  y2="1">

    <stop offset="0%"
          stop-color="#ffffff"
          stop-opacity="0.75"/>

    <stop offset="50%"
          stop-color="#ffffff"
          stop-opacity="0.15"/>

    <stop offset="100%"
          stop-color="#ffffff"
          stop-opacity="0.4"/>

  </linearGradient>

</defs>


<!-- ===================== -->
<!-- 蓝白苏打水背景 -->
<!-- ===================== -->

<rect
  x="0"
  y="0"
  width="1200"
  height="360"
  rx="32"
  fill="url(#stripes)"
/>


<!-- ===================== -->
<!-- 玻璃层 -->
<!-- ===================== -->

<rect
  x="18"
  y="18"
  width="1164"
  height="324"
  rx="28"
  fill="url(#glass)"
  stroke="#ffffff"
  stroke-width="2"
  opacity="0.8"
/>


<!-- ===================== -->
<!-- 装饰花纹 -->
<!-- ===================== -->

<path
  d="M45 75
     C85 35 125 115 165 75
     S245 35 285 75"
  fill="none"
  stroke="#8bd5e1"
  stroke-width="3"
  opacity="0.45"
/>

<path
  d="M915 285
     C955 245 995 325 1035 285
     S1115 245 1155 285"
  fill="none"
  stroke="#8bd5e1"
  stroke-width="3"
  opacity="0.45"
/>


<!-- 小星星 -->

<text
  x="90"
  y="145"
  font-size="25"
  fill="#78cbd8"
  opacity="0.65">
  ✦
</text>

<text
  x="1080"
  y="130"
  font-size="22"
  fill="#78cbd8"
  opacity="0.65">
  ✦
</text>

<text
  x="1020"
  y="85"
  font-size="14"
  fill="#78cbd8"
  opacity="0.55">
  ✧
</text>

<text
  x="155"
  y="275"
  font-size="16"
  fill="#78cbd8"
  opacity="0.55">
  ✧
</text>


<!-- ===================== -->
<!-- 动态泡泡 -->
<!-- ===================== -->

<circle
  cx="120"
  cy="330"
  r="13"
  fill="url(#bubble)">

  <animate
    attributeName="cy"
    from="340"
    to="-30"
    dur="6s"
    repeatCount="indefinite"/>

  <animate
    attributeName="cx"
    values="120;135;110;125"
    dur="6s"
    repeatCount="indefinite"/>

</circle>


<circle
  cx="230"
  cy="340"
  r="8"
  fill="url(#bubble)">

  <animate
    attributeName="cy"
    from="340"
    to="-20"
    dur="5s"
    begin="1s"
    repeatCount="indefinite"/>

</circle>


<circle
  cx="350"
  cy="330"
  r="18"
  fill="url(#bubble)">

  <animate
    attributeName="cy"
    from="340"
    to="-40"
    dur="7s"
    begin="2s"
    repeatCount="indefinite"/>

  <animate
    attributeName="cx"
    values="350;365;340;355"
    dur="7s"
    repeatCount="indefinite"/>

</circle>


<circle
  cx="500"
  cy="340"
  r="7"
  fill="url(#bubble)">

  <animate
    attributeName="cy"
    from="340"
    to="-20"
    dur="4.5s"
    begin="0.5s"
    repeatCount="indefinite"/>

</circle>


<circle
  cx="650"
  cy="340"
  r="12"
  fill="url(#bubble)">

  <animate
    attributeName="cy"
    from="340"
    to="-30"
    dur="6.5s"
    begin="1.5s"
    repeatCount="indefinite"/>

</circle>


<circle
  cx="780"
  cy="340"
  r="20"
  fill="url(#bubble)">

  <animate
    attributeName="cy"
    from="340"
    to="-45"
    dur="7.5s"
    begin="0.8s"
    repeatCount="indefinite"/>

  <animate
    attributeName="cx"
    values="780;800;765;785"
    dur="7.5s"
    repeatCount="indefinite"/>

</circle>


<circle
  cx="920"
  cy="340"
  r="8"
  fill="url(#bubble)">

  <animate
    attributeName="cy"
    from="340"
    to="-20"
    dur="5.5s"
    begin="2s"
    repeatCount="indefinite"/>

</circle>


<circle
  cx="1050"
  cy="340"
  r="14"
  fill="url(#bubble)">

  <animate
    attributeName="cy"
    from="340"
    to="-30"
    dur="6s"
    begin="1s"
    repeatCount="indefinite"/>

</circle>


<!-- ===================== -->
<!-- 主标题 -->
<!-- ===================== -->

<text
  x="600"
  y="145"
  text-anchor="middle"
  font-family="Trebuchet MS, Arial, sans-serif"
  font-size="58"
  font-weight="600"
  letter-spacing="5"
  fill="#55b6c5">

  linyinluo

</text>


<!-- ===================== -->
<!-- 副标题 -->
<!-- ===================== -->

<text
  x="600"
  y="180"
  text-anchor="middle"
  font-family="Trebuchet MS, Arial, sans-serif"
  font-size="16"
  letter-spacing="6"
  fill="#72bfc9">

  INFORMATION SYSTEMS

</text>


<!-- ===================== -->
<!-- Soda Soda 风格小字 -->
<!-- ===================== -->

<text
  x="600"
  y="215"
  text-anchor="middle"
  font-family="Trebuchet MS, Arial, sans-serif"
  font-size="14"
  letter-spacing="4"
  fill="#91cbd3">

  ✦ stay curious · stay sparkling ✦

</text>


<!-- ===================== -->
<!-- 底部波纹 -->
<!-- ===================== -->

<path
  d="M300 285
     Q350 265 400 285
     T500 285
     T600 285
     T700 285
     T800 285
     T900 285"
  fill="none"
  stroke="#ffffff"
  stroke-width="3"
  opacity="0.7">

  <animate
    attributeName="d"
    values="
    M300 285 Q350 265 400 285 T500 285 T600 285 T700 285 T800 285 T900 285;
    M300 285 Q350 300 400 285 T500 285 T600 285 T700 285 T800 285 T900 285;
    M300 285 Q350 265 400 285 T500 285 T600 285 T700 285 T800 285 T900 285"
    dur="4s"
    repeatCount="indefinite"/>

</path>

</svg>
