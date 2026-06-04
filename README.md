<svg viewBox="0 0 800 650" xmlns="http://www.w3.org/2000/svg">
  <rect width="800" height="650" fill="#0a0a0a"/>
  
  <!-- 顶部版权栏 -->
  <rect x="0" y="0" width="800" height="40" fill="#111" stroke="#333" stroke-width="0.5"/>
  <text x="400" y="18" fill="#888" font-size="10" text-anchor="middle" font-family="monospace">COPYRIGHT 2026 CHAO MUHUA · ALL RIGHTS RESERVED</text>
  <text x="400" y="32" fill="#666" font-size="9" text-anchor="middle" font-family="monospace">CONTACT: 12809400@qq.com</text>
  
  <!-- 标题 -->
  <text x="400" y="65" fill="#555" font-size="11" text-anchor="middle" font-family="monospace">ZERO RING · ROOT CIRCUIT</text>
  
  <!-- ===== 主回路 ===== -->
  
  <!-- VCC -->
  <text x="400" y="95" fill="#00d2ff" font-size="10" text-anchor="middle" font-family="monospace">VCC</text>
  <line x1="400" y1="102" x2="400" y2="125" stroke="#00d2ff" stroke-width="1.5"/>
  <circle cx="400" cy="133" r="8" fill="none" stroke="#00d2ff" stroke-width="1.5"/>
  <line x1="392" y1="137" x2="408" y2="137" stroke="#00d2ff" stroke-width="1"/>
  <line x1="400" y1="141" x2="400" y2="160" stroke="#00d2ff" stroke-width="1.5"/>
  
  <!-- MCU -->
  <line x1="400" y1="160" x2="400" y2="175" stroke="#e94560" stroke-width="1.5"/>
  <rect x="355" y="175" width="90" height="30" fill="none" stroke="#e94560" stroke-width="1.5" rx="3"/>
  <text x="400" y="194" fill="#e94560" font-size="11" text-anchor="middle" font-family="monospace">MCU</text>
  <line x1="400" y1="205" x2="400" y2="230" stroke="#e94560" stroke-width="1.5"/>
  
  <!-- GPIO标注 -->
  <text x="450" y="185" fill="#e94560" font-size="8" font-family="monospace">GPIO5</text>
  <text x="450" y="375" fill="#00ff88" font-size="8" font-family="monospace">GPIO34</text>
  
  <!-- R1 -->
  <line x1="400" y1="230" x2="400" y2="250" stroke="#ffd700" stroke-width="1.5"/>
  <rect x="385" y="250" width="30" height="15" fill="none" stroke="#ffd700" stroke-width="1.5" rx="2"/>
  <text x="430" y="262" fill="#ffd700" font-size="9" font-family="monospace">R1 220Ω</text>
  <line x1="400" y1="265" x2="400" y2="290" stroke="#ffd700" stroke-width="1.5"/>
  
  <!-- LED -->
  <polygon points="400,290 385,310 415,310" fill="none" stroke="#ffd700" stroke-width="1.5"/>
  <line x1="385" y1="310" x2="415" y2="310" stroke="#ffd700" stroke-width="1.5"/>
  <text x="440" y="305" fill="#ffd700" font-size="9" font-family="monospace">LED</text>
  <line x1="400" y1="310" x2="400" y2="340" stroke="#ffd700" stroke-width="1.5"/>
  
  <!-- 光反馈路径 -->
  <path d="M400,295 Q365,295 365,325 Q365,355 395,355" fill="none" stroke="#ffd700" stroke-width="0.5" opacity="0.4" stroke-dasharray="3,3"/>
  <polygon points="395,355 392,350 398,350" fill="#ffd700" opacity="0.4"/>
  
  <!-- LDR -->
  <line x1="400" y1="340" x2="400" y2="355" stroke="#00ff88" stroke-width="1.5"/>
  <rect x="385" y="355" width="30" height="20" fill="none" stroke="#00ff88" stroke-width="1.5" rx="2"/>
  <text x="430" y="369" fill="#00ff88" font-size="9" font-family="monospace">LDR</text>
  <line x1="400" y1="375" x2="400" y2="400" stroke="#00ff88" stroke-width="1.5"/>
  
  <!-- 反馈回MCU -->
  <line x1="400" y1="400" x2="400" y2="430" stroke="#888" stroke-width="1"/>
  
  <!-- GND -->
  <line x1="400" y1="430" x2="400" y2="440" stroke="#888" stroke-width="1.5"/>
  <line x1="380" y1="440" x2="420" y2="440" stroke="#888" stroke-width="1.5"/>
  <line x1="390" y1="445" x2="410" y2="445" stroke="#888" stroke-width="1"/>
  <line x1="395" y1="450" x2="405" y2="450" stroke="#888" stroke-width="0.8"/>
  <text x="440" y="444" fill="#888" font-size="9" font-family="monospace">GND</text>
  
  <!-- ===== 三角稳定结构 ===== -->
  
  <circle cx="100" cy="380" r="12" fill="none" stroke="#00d2ff" stroke-width="1"/>
  <text x="100" y="384" fill="#00d2ff" font-size="8" text-anchor="middle" font-family="monospace">NO-SELF</text>
  <line x1="112" y1="380" x2="355" y2="390" stroke="#00d2ff" stroke-width="0.5" opacity="0.2"/>
  
  <circle cx="700" cy="380" r="12" fill="none" stroke="#00d2ff" stroke-width="1"/>
  <text x="700" y="384" fill="#00d2ff" font-size="8" text-anchor="middle" font-family="monospace">AUTO-EXEC</text>
  <line x1="688" y1="380" x2="445" y2="390" stroke="#00d2ff" stroke-width="0.5" opacity="0.2"/>
  
  <line x1="100" y1="392" x2="700" y2="392" stroke="#00d2ff" stroke-width="0.5" opacity="0.1"/>
  <text x="400" y="406" fill="#00d2ff" font-size="7" text-anchor="middle" font-family="monospace" opacity="0.3">CLOSED LOOP · ROOT</text>
  
  <!-- 底部法印 -->
  <rect x="0" y="570" width="800" height="80" fill="#111" stroke="#333" stroke-width="0.5"/>
  <text x="400" y="592" fill="#00d2ff" font-size="14" text-anchor="middle" font-family="monospace" font-weight="bold">VACUUM · NO-SELF · AUTO-EXECUTION</text>
  <text x="400" y="612" fill="#888" font-size="10" text-anchor="middle" font-family="monospace">COPYRIGHT 2026 CHAO MUHUA · ALL RIGHTS RESERVED</text>
  <text x="400" y="630" fill="#666" font-size="9" text-anchor="middle" font-family="monospace">12809400@qq.com · ZERO RING ROOT · 法印认证 盗用必究</text>
  
</svg>
