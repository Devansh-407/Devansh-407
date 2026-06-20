<svg width="900" height="380" viewBox="0 0 900 380" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="fillGrad" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#ff7a59"/>
      <stop offset="100%" stop-color="#ff5c8a"/>
    </linearGradient>
    <style>
      .label { font-family: 'Courier New', monospace; font-size: 15px; fill: #c9c6d8; }
      .pct { font-family: 'Courier New', monospace; font-size: 13px; fill: #8b87a0; }
      .track { fill: #1c1a26; }
      .bar { fill: url(#fillGrad); }
    </style>
  </defs>

  <rect width="900" height="380" rx="14" fill="#0d0c12"/>
  <rect x="1" y="1" width="898" height="378" rx="13" fill="none" stroke="#2a2735" stroke-width="1"/>

  <text x="40" y="45" font-family="Courier New, monospace" font-size="15" fill="#5c5870">// skills.json (still compiling...)</text>

  <!-- Row template: label at x=40, track at x=40 y+15 w=520, pct at x=575 -->
  <g>
    <text x="40" y="85" class="label">HTML / CSS</text>
    <text x="800" y="85" class="pct" text-anchor="end">85%</text>
    <rect x="40" y="95" width="740" height="10" rx="5" class="track"/>
    <rect x="40" y="95" height="10" rx="5" class="bar">
      <animate attributeName="width" from="0" to="629" dur="1.2s" fill="freeze" />
    </rect>
  </g>

  <g>
    <text x="40" y="135" class="label">JavaScript</text>
    <text x="800" y="135" class="pct" text-anchor="end">75%</text>
    <rect x="40" y="145" width="740" height="10" rx="5" class="track"/>
    <rect x="40" y="145" height="10" rx="5" class="bar">
      <animate attributeName="width" from="0" to="555" dur="1.2s" fill="freeze" />
    </rect>
  </g>

  <g>
    <text x="40" y="185" class="label">React</text>
    <text x="800" y="185" class="pct" text-anchor="end">60%</text>
    <rect x="40" y="195" width="740" height="10" rx="5" class="track"/>
    <rect x="40" y="195" height="10" rx="5" class="bar">
      <animate attributeName="width" from="0" to="444" dur="1.2s" fill="freeze" />
    </rect>
  </g>

  <g>
    <text x="40" y="235" class="label">Node.js / Express</text>
    <text x="800" y="235" class="pct" text-anchor="end">50%</text>
    <rect x="40" y="245" width="740" height="10" rx="5" class="track"/>
    <rect x="40" y="245" height="10" rx="5" class="bar">
      <animate attributeName="width" from="0" to="370" dur="1.2s" fill="freeze" />
    </rect>
  </g>

  <g>
    <text x="40" y="285" class="label">MongoDB</text>
    <text x="800" y="285" class="pct" text-anchor="end">45%</text>
    <rect x="40" y="295" width="740" height="10" rx="5" class="track"/>
    <rect x="40" y="295" height="10" rx="5" class="bar">
      <animate attributeName="width" from="0" to="333" dur="1.2s" fill="freeze" />
    </rect>
  </g>

  <g>
    <text x="40" y="335" class="label">Git / GitHub</text>
    <text x="800" y="335" class="pct" text-anchor="end">70%</text>
    <rect x="40" y="345" width="740" height="10" rx="5" class="track"/>
    <rect x="40" y="345" height="10" rx="5" class="bar">
      <animate attributeName="width" from="0" to="518" dur="1.2s" fill="freeze" />
    </rect>
  </g>
</svg>
