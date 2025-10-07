<!-- 🌸 About Me - Nakano Miku Inspired Profile -->

<div align="center" style="background: linear-gradient(145deg, #ffd6eb, #c8e8ff); padding: 40px; border-radius: 30px; box-shadow: 0 8px 32px rgba(255,182,193,0.3); position: relative; overflow: hidden; max-width: 600px; margin: 0 auto; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">
  <!-- Subtle layered background for depth -->
  <div style="position: absolute; top: -50%; left: -50%; width: 200%; height: 200%; background: radial-gradient(ellipse at 30% 40%, rgba(255, 214, 235, 0.15) 0%, transparent 50%), radial-gradient(ellipse at 70% 60%, rgba(200, 232, 255, 0.15) 0%, transparent 50%); opacity: 0.8; pointer-events: none;"></div>
  
  <!-- Floating particles for gentle animation (CSS-only) -->
  <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; overflow: hidden; pointer-events: none;">
    <div style="position: absolute; width: 4px; height: 4px; background: #ff8eb8; border-radius: 50%; top: 20%; left: 10%; animation: float 8s ease-in-out infinite;"></div>
    <div style="position: absolute; width: 3px; height: 3px; background: #6fc2e0; border-radius: 50%; top: 60%; right: 15%; animation: float 10s ease-in-out infinite reverse;"></div>
    <div style="position: absolute; width: 5px; height: 5px; background: #8ac7db; border-radius: 50%; bottom: 30%; left: 70%; animation: float 7s ease-in-out infinite;"></div>
  </div>
  <style>
    @keyframes float {
      0%, 100% { transform: translateY(0px) rotate(0deg); opacity: 0.6; }
      50% { transform: translateY(-20px) rotate(180deg); opacity: 1; }
    }
    .hover-scale { transition: transform 0.3s ease, box-shadow 0.3s ease; }
    .hover-scale:hover { transform: scale(1.05); box-shadow: 0 4px 16px rgba(255, 182, 193, 0.4) !important; }
    .skill-item { transition: background 0.3s ease, transform 0.2s ease; border-radius: 20px; margin: 6px 0; padding: 8px 12px; background: rgba(255, 255, 255, 0.12); backdrop-filter: blur(10px); }
    .skill-item:hover { background: rgba(255, 255, 255, 0.25); transform: translateX(5px); }
    .tool-row { transition: background 0.3s ease, transform 0.2s ease; border-radius: 15px; margin: 4px 0; padding: 12px; background: rgba(255, 255, 255, 0.08); }
    .tool-row:hover { background: rgba(255, 255, 255, 0.18); transform: scale(1.02); }
    .circular-badge { border-radius: 50% !important; clip-path: circle(50% at 50% 50%) !important; object-fit: cover; transition: filter 0.3s ease; }
    .circular-badge:hover { filter: brightness(1.1) drop-shadow(0 0 8px currentColor); }
  </style>

  <!-- Avatar with enhanced glow -->
  <div style="position: relative; display: inline-block; margin-bottom: 20px;">
    <img src="https://files.catbox.moe/mq6x9a.png" width="200" style="border-radius: 50%; box-shadow: 0 0 0 4px #ffffff, 0 0 40px rgba(255,192,203,0.7); transition: all 0.4s ease;" class="hover-scale" alt="Avatar"/>
    <div style="position: absolute; top: -10px; left: -10px; right: -10px; bottom: -10px; border-radius: 50%; background: conic-gradient(from 0deg, #ff8eb8, #6fc2e0, #ff8eb8); opacity: 0.3; animation: rotate 10s linear infinite; z-index: -1;"></div>
  </div>
  <style>@keyframes rotate { 0% { transform: rotate(0deg); } 100% { transform: rotate(360deg); } }</style>

  <!-- Name & Role with gradient text effect -->
  <h1 style="background: linear-gradient(45deg, #ff8eb8, #6fc2e0); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; font-size: 2.2em; margin: 0 0 5px 0; text-shadow: none;">💖 Xin chào, tôi là <span style="background: linear-gradient(45deg, #6fc2e0, #ff8eb8); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;">TKhanh</span></h1>
  <h3 style="color:#8ac7db; font-size: 1.3em; margin: 0 0 15px 0; text-shadow: 0 2px 8px rgba(138, 199, 219, 0.3);">💻 Lập trình viên chuyên về JavaScript</h3>

  <p style="font-size: 1.1em; color: #ff8eb8; margin: 20px 0; line-height: 1.5; font-style: italic; text-shadow: 0 1px 4px rgba(255, 142, 184, 0.2);">
    “Tôi thích những dòng code gọn gàng, hiệu quả và có chút cảm xúc — như chính nhịp điệu của Nakano Miku.”
  </p>

  <!-- Elegant Divider -->
  <hr style="width: 70%; border: none; height: 2px; background: linear-gradient(90deg, transparent, #ffe1ef, transparent); box-shadow: 0 0 10px rgba(255, 225, 239, 0.6); margin: 30px 0;">

  <!-- Skills Section -->
  <h3 style="color:#ffb6c1; font-size: 1.4em; margin: 0 0 15px 0; text-shadow: 0 2px 4px rgba(255, 182, 193, 0.3);">⚙️ Kỹ năng chính</h3>
  <div style="display: flex; justify-content: center; flex-wrap: wrap; margin-bottom: 20px; gap: 10px;">
    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/javascript.svg" width="50" height="50" style="background: linear-gradient(145deg, #F7DF1E, #FFD700); border: 2px solid #ffffff; border-radius: 50%; padding: 5px; box-shadow: 0 4px 12px rgba(247, 223, 30, 0.4);" class="hover-scale circular-badge" alt="JavaScript"/>
    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/nodedotjs.svg" width="50" height="50" style="background: linear-gradient(145deg, #6cc24a, #90EE90); border: 2px solid #ffffff; border-radius: 50%; padding: 5px; box-shadow: 0 4px 12px rgba(108, 194, 74, 0.4);" class="hover-scale circular-badge" alt="Node.js"/>
    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/termux.svg" width="50" height="50" style="background: linear-gradient(145deg, #000000, #333333); border: 2px solid #ffffff; border-radius: 50%; padding: 5px; box-shadow: 0 4px 12px rgba(0, 0, 0, 0.4);" class="hover-scale circular-badge" alt="Termux"/>
  </div>

  <ul style="list-style: none; padding: 0; max-width: 450px; margin: 0 auto;">
    <li class="skill-item">🧩 <span style="color: #ff8eb8; font-weight: 500;">Viết script tiện ích gọn gàng, hiệu quả</span></li>
    <li class="skill-item">⚡ <span style="color: #6fc2e0; font-weight: 500;">Tối ưu hóa API và tự động hóa</span></li>
    <li class="skill-item">🎧 <span style="color: #8ac7db; font-weight: 500;">Làm việc tập trung trong môi trường Termux / Node.js</span></li>
  </ul>

  <!-- Tools Section -->
  <h3 style="color:#ffb6c1; font-size: 1.4em; margin: 30px 0 15px 0; text-shadow: 0 2px 4px rgba(255, 182, 193, 0.3);">🧰 Công cụ yêu thích</h3>
  <div style="max-width: 450px; margin: 0 auto;">
    <div class="tool-row">💠 <b style="color: #ff8eb8;">VS Code</b> <span style="color: #8ac7db; margin-left: 15px; font-weight: 400;">— Trình soạn thảo chính</span></div>
    <div class="tool-row">📦 <b style="color: #6fc2e0;">Node.js</b> <span style="color: #8ac7db; margin-left: 15px; font-weight: 400;">— Nền tảng lập trình chủ đạo</span></div>
    <div class="tool-row">🌀 <b style="color: #ff8eb8;">Termux</b> <span style="color: #8ac7db; margin-left: 15px; font-weight: 400;">— Môi trường thử nghiệm và automation</span></div>
    <div class="tool-row">🌐 <b style="color: #6fc2e0;">GitHub</b> <span style="color: #8ac7db; margin-left: 15px; font-weight: 400;">— Nơi lưu trữ và chia sẻ project</span></div>
  </div>

  <!-- Contact Section -->
  <h3 style="color:#6fc2e0; font-size: 1.4em; margin: 30px 0 15px 0; text-shadow: 0 2px 4px rgba(111, 194, 224, 0.3);">🌐 Liên hệ</h3>
  <div style="display: flex; justify-content: center; gap: 20px; margin-bottom: 25px;">
    <a href="https://github.com/<tên_github_của_bạn>" style="text-decoration: none; display: inline-block;">
      <img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/github.svg" width="60" height="60" style="background: linear-gradient(145deg, #6fc2e0, #87CEEB); border: 3px solid #ffffff; border-radius: 50%; padding: 6px; box-shadow: 0 6px 20px rgba(111, 194, 224, 0.5);" class="hover-scale circular-badge" alt="GitHub"/>
    </a>
    <a href="https://t.me/<tên_telegram_của_bạn>" style="text-decoration: none; display: inline-block;">
      <img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/telegram.svg" width="60" height="60" style="background: linear-gradient(145deg, #ffb6c1, #FF69B4); border: 3px solid #ffffff; border-radius: 50%; padding: 6px; box-shadow: 0 6px 20px rgba(255, 182, 193, 0.5);" class="hover-scale circular-badge" alt="Telegram"/>
    </a>
  </div>

  <!-- Quote with enhanced styling -->
  <blockquote style="color:#8ac7db; font-style: italic; font-size: 1.1em; text-shadow: 0 2px 8px rgba(138, 199, 219, 0.3); border-left: 5px solid #ffe1ef; padding: 20px; margin: 25px 0; background: rgba(255, 255, 255, 0.1); border-radius: 15px; backdrop-filter: blur(10px); position: relative; overflow: hidden;">
    <div style="position: absolute; top: 0; right: 0; width: 100px; height: 100px; background: radial-gradient(circle, rgba(255, 225, 239, 0.3) 0%, transparent 70%); transform: rotate(45deg); opacity: 0.5;"></div>
    “Code đơn giản, hiệu quả và thực dụng — đó là cách tôi làm việc.”
  </blockquote>

</div>

<p align="center" style="color: #ff8eb8; font-size: 0.95em; margin-top: 15px; font-style: italic; text-shadow: 0 1px 3px rgba(255, 142, 184, 0.2);">
  💙 Giao diện lấy cảm hứng từ Nakano Miku – Go-toubun no Hanayome 💖
</p>
