<svg viewBox="0 0 760 480" xmlns="http://www.w3.org/2000/svg">
  <style>
    a text { cursor: pointer; }
    a:hover text { text-decoration: underline; }
  </style>

  <!-- Main line -->
  <path d="M 50 450 L 590 230" fill="none" stroke="#718096" stroke-width="3"/>

  <!-- UBC branch + sub-branch -->
  <g fill="none" stroke="#718096" stroke-width="3">
    <path d="M 235 375 L 80 190"/>
  </g>
  <path d="M 157 282 L 250 160" fill="none" stroke="#A0AEC0" stroke-width="2"/>

  <!-- PhD branch -->
  <path d="M 590 230 L 510 100" fill="none" stroke="#718096" stroke-width="3"/>

  <!-- Nodes -->
  <g fill="#3569A8">
    <circle cx="235" cy="375" r="6"/>
    <circle cx="590" cy="230" r="6"/>
    <circle cx="157" cy="282" r="5"/>
  </g>
  <circle cx="50" cy="450" r="6" fill="#4A5568"/>

  <!-- Labels (wrap each in <a href="..."> to make it a link) -->
  <g font-family="Arial, sans-serif" fill="currentColor">

    <!-- UBC -->
    <text x="245" y="410" font-size="20" font-weight="bold">UBC</text>
    <text x="245" y="428" font-size="12">BSc</text>

    <!-- UBC projects -->
    <a href="#arctic-plant-genomics">
      <text x="80" y="172" font-size="13" text-anchor="middle">Arctic plant genomics</text>
    </a>
    <a href="#fish-pop-genetics">
      <text x="250" y="142" font-size="13" text-anchor="middle">Rainbow Trout Population genetics</text>
    </a>

    <!-- PhD -->
    <text x="530" y="270" font-size="20" font-weight="bold">PhD</text>
    <a href="#conscient-lab">
      <text x="530" y="288" font-size="12">Conscient Lab</text>
    </a>
    <a href="#evolutionary-models">
      <text x="510" y="82" font-size="13" text-anchor="middle">Evolutionary based models</text>
    </a>
  </g>
</svg>
