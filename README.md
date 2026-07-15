<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1280 400" width="1280" height="400">
  <defs>
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;500;600&amp;display=swap');
      
      /* Light mode defaults */
      :root {
        --bg-color-start: #f4f4f5; /* zinc-100 */
        --bg-color-end: #ffffff;
        --text-color: #09090b; /* zinc-950 */
        --symbol-color: #a1a1aa; /* zinc-400 */
        --host-color: #27272a; /* zinc-800 */
        --letter-color: #09090b;
        --grid-color: #71717a; /* zinc-500 */
        --grid-opacity: 0.15;
      }

      /* Dark mode override */
      @media (prefers-color-scheme: dark) {
        :root {
          --bg-color-start: #18181b; /* zinc-900 */
          --bg-color-end: #09090b; /* zinc-950 */
          --text-color: #ffffff;
          --symbol-color: #52525b; /* zinc-600 */
          --host-color: #f4f4f5; /* zinc-100 */
          --letter-color: #ffffff;
          --grid-color: #27272a; /* zinc-800 */
          --grid-opacity: 0.5;
        }
      }

      .email-text {
        font-family: 'Outfit', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
        font-size: 32px;
        fill: var(--text-color);
        font-weight: 400;
        letter-spacing: 0.05em;
      }
      .email-username {
        fill: var(--text-color);
        font-weight: 500;
      }
      .email-symbol {
        fill: var(--symbol-color);
        font-weight: 300;
        font-size: 28px;
      }
      .email-host {
        fill: var(--host-color);
        font-weight: 400;
      }

      /* Force color reactive on SVGs child rects of #letters */
      #letters rect {
        fill: var(--letter-color) !important;
        transition: fill 0.3s ease;
      }
      
      .bg-rect {
        fill: url(#bg-glow);
        transition: fill 0.3s ease;
      }

      .grid-dot {
        fill: var(--grid-color);
        fill-opacity: var(--grid-opacity);
        transition: fill 0.3s ease, fill-opacity 0.3s ease;
      }
    </style>

    <!-- Reactive radial gradient background glow -->
    <radialGradient id="bg-glow" cx="75%" cy="50%" r="60%">
      <stop offset="0%" stop-color="var(--bg-color-start)" />
      <stop offset="100%" stop-color="var(--bg-color-end)" />
    </radialGradient>

    <!-- Subtle decorative dot grid pattern -->
    <pattern id="dot-grid" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
      <circle cx="2" cy="2" r="1.2" class="grid-dot" />
    </pattern>
  </defs>

  <!-- Background -->
  <rect width="1280" height="400" class="bg-rect" />
  <rect width="1280" height="400" fill="url(#dot-grid)" />

  <!-- Letters Group on the Left -->
  <g id="letters" transform="translate(44.75, -47.52) scale(0.55)">
    
    <rect x="143.73" y="256.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="27.73" y="295.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="66.40" y="295.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="105.07" y="295.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="143.73" y="295.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="182.40" y="295.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="27.73" y="334.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="66.40" y="334.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="105.07" y="334.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="143.73" y="334.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="182.40" y="334.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="27.73" y="372.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="66.40" y="372.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="105.07" y="372.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="143.73" y="372.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="182.40" y="372.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="66.40" y="411.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="259.73" y="256.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="298.40" y="256.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="337.07" y="256.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="259.73" y="295.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="298.40" y="295.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="337.07" y="295.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="259.73" y="334.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="298.40" y="334.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="337.07" y="334.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="259.73" y="372.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="298.40" y="372.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="337.07" y="372.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="259.73" y="411.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="298.40" y="411.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="337.07" y="411.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="414.40" y="256.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="453.07" y="256.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="530.40" y="256.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="414.40" y="295.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="453.07" y="295.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="530.40" y="295.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="414.40" y="334.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="453.07" y="334.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="491.73" y="334.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="530.40" y="334.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="414.40" y="372.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="453.07" y="372.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="569.07" y="372.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="414.40" y="411.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="453.07" y="411.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="569.07" y="411.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="646.40" y="256.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="685.07" y="256.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="723.73" y="256.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="646.40" y="295.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="685.07" y="295.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="723.73" y="295.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="646.40" y="334.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="685.07" y="334.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="723.73" y="334.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="646.40" y="372.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="685.07" y="372.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="723.73" y="372.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="646.40" y="411.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="685.07" y="411.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="723.73" y="411.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="801.07" y="256.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="839.73" y="256.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="878.40" y="256.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="917.07" y="256.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="955.73" y="256.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="839.73" y="295.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="878.40" y="295.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="917.07" y="295.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="839.73" y="334.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="878.40" y="334.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="917.07" y="334.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="839.73" y="372.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="878.40" y="372.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="917.07" y="372.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="839.73" y="411.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="878.40" y="411.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="917.07" y="411.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="994.40" y="256.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1033.07" y="256.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1071.73" y="256.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1110.40" y="256.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1149.07" y="256.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="994.40" y="295.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1033.07" y="295.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1071.73" y="295.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1110.40" y="295.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1149.07" y="295.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="994.40" y="334.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1033.07" y="334.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1071.73" y="334.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1110.40" y="334.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1149.07" y="334.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="994.40" y="372.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1033.07" y="372.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1071.73" y="372.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1110.40" y="372.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1149.07" y="372.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="994.40" y="411.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1149.07" y="411.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="66.40" y="450.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="105.07" y="450.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="143.73" y="450.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="182.40" y="450.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="66.40" y="488.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="105.07" y="488.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="143.73" y="488.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="182.40" y="488.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="66.40" y="527.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="105.07" y="527.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="143.73" y="527.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="27.73" y="566.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="66.40" y="566.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="105.07" y="566.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="143.73" y="566.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="27.73" y="604.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="66.40" y="604.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="105.07" y="604.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="143.73" y="604.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="221.07" y="450.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="259.73" y="450.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="298.40" y="450.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="337.07" y="450.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="375.73" y="450.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="259.73" y="488.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="298.40" y="488.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="337.07" y="488.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="259.73" y="527.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="298.40" y="527.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="337.07" y="527.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="259.73" y="566.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="298.40" y="566.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="337.07" y="566.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="259.73" y="604.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="298.40" y="604.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="337.07" y="604.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="414.40" y="450.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="453.07" y="450.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="491.73" y="450.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="530.40" y="450.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="414.40" y="488.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="453.07" y="488.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="491.73" y="488.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="530.40" y="488.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="414.40" y="527.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="453.07" y="527.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="491.73" y="527.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="530.40" y="527.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="414.40" y="566.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="569.07" y="566.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="414.40" y="604.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="569.07" y="604.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="646.40" y="450.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="685.07" y="450.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="723.73" y="450.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="646.40" y="488.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="685.07" y="488.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="723.73" y="488.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="646.40" y="527.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="685.07" y="527.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="723.73" y="527.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="646.40" y="566.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="685.07" y="566.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="723.73" y="566.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="646.40" y="604.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="685.07" y="604.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="723.73" y="604.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="801.07" y="450.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="839.73" y="450.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="917.07" y="450.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="801.07" y="488.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="839.73" y="488.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="917.07" y="488.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="801.07" y="527.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="839.73" y="527.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="878.40" y="527.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="917.07" y="527.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="801.07" y="566.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="839.73" y="566.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="955.73" y="566.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="801.07" y="604.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="839.73" y="604.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="955.73" y="604.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="994.40" y="450.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1033.07" y="450.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1071.73" y="450.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="994.40" y="488.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1033.07" y="488.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1071.73" y="488.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="994.40" y="527.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1033.07" y="527.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1071.73" y="527.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1110.40" y="527.33" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="994.40" y="566.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1033.07" y="566.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1071.73" y="566.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1110.40" y="566.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1149.07" y="566.00" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="994.40" y="604.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1033.07" y="604.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1071.73" y="604.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1110.40" y="604.67" width="23.20" height="38.67" fill="#ffffff" />
    <rect x="1149.07" y="604.67" width="23.20" height="38.67" fill="#ffffff" />
  
  </g>

  <!-- Email Text on the Right, centered in the remaining space -->
  <text x="985" y="200" text-anchor="middle" dominant-baseline="central" class="email-text">
    <tspan class="email-username">me</tspan> <tspan class="email-symbol">(at)</tspan> <tspan class="email-host">nikitastrike</tspan> <tspan class="email-symbol">(dot)</tspan> <tspan class="email-host">co</tspan>
  </text>
</svg>
