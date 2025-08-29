<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Jainil Panigrahi | Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    body {
      background: linear-gradient(135deg, #000000, #0a0f2c, #1a1a40);
      color: white;
      font-family: 'Poppins', sans-serif;
    }
    .gradient-text {
      background: linear-gradient(90deg, #ff00cc, #3333ff, #00ffcc);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-size: 300% 300%;
      animation: gradientShift 5s ease infinite;
    }
    @keyframes gradientShift {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
    .glass {
      background: rgba(255, 255, 255, 0.1);
      backdrop-filter: blur(10px);
      border: 1px solid rgba(255, 255, 255, 0.2);
      border-radius: 1rem;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .glass:hover {
      transform: scale(1.02);
      box-shadow: 0 0 25px rgba(255, 0, 200, 0.4);
    }
    .btn {
      background: linear-gradient(90deg, #ff00cc, #3333ff);
      color: white;
      font-weight: bold;
      padding: 10px 20px;
      border-radius: 9999px;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .btn:hover {
      transform: scale(1.1);
      box-shadow: 0 0 20px rgba(255, 0, 200, 0.6);
    }
  </style>
</head>
<body class="min-h-screen flex flex-col items-center">
  <!-- Header -->
  <header class="text-center mt-10">
    <h1 class="text-5xl font-bold gradient-text">Jainil Panigrahi</h1>
    <p class="mt-3 text-lg">B.Tech - Energy Science and Engineering, IIT Guwahati</p>
    <div class="flex justify-center gap-4 mt-5">
      <a href="https://github.com/jainil0803" target="_blank" class="btn">GitHub</a>
      <a href="https://www.linkedin.com/in/jainil-panigrahi" target="_blank" class="btn">LinkedIn</a>
      <a href="Jainil_Resume.pdf" class="btn">Download Resume</a>
    </div>
  </header>

  <!-- Projects -->
  <section class="mt-16 w-11/12 md:w-3/4">
    <h2 class="text-3xl font-semibold mb-6 gradient-text">Projects</h2>
    <div class="grid md:grid-cols-2 gap-6">
      <div class="glass p-6">
        <h3 class="text-xl font-bold">Web 3.0 Blockchain Application</h3>
        <p class="mt-2">Built a decentralized app with MetaMask, Solidity smart contracts, and Giphy API dashboard.</p>
      </div>
      <div class="glass p-6">
        <h3 class="text-xl font-bold">Airhawks</h3>
        <p class="mt-2">Full-stack flight booking app with JWT auth, SHA-256 hashing, Razorpay payments, React + Chakra UI.</p>
      </div>
      <div class="glass p-6">
        <h3 class="text-xl font-bold">Dynamic Pricing System</h3>
        <p class="mt-2">Real-time smart parking pricing using streaming, geospatial modeling, and visualization with Pathway.</p>
      </div>
    </div>
  </section>

  <!-- Skills -->
  <section class="mt-16 w-11/12 md:w-3/4">
    <h2 class="text-3xl font-semibold mb-6 gradient-text">Technical Skills</h2>
    <div class="glass p-6 grid grid-cols-2 gap-4 text-sm md:text-base">
      <p><b>Programming:</b> Python, C/C++, JavaScript, TypeScript</p>
      <p><b>Web Dev:</b> React, Tailwind, Node.js, Express.js</p>
      <p><b>Blockchain:</b> Solidity, Ethereum, IPFS, Truffle, ethers.js, web3.js</p>
      <p><b>Databases:</b> MongoDB, MySQL, PostgreSQL</p>
      <p><b>AI/ML:</b> TensorFlow, PyTorch, Keras, OpenCV</p>
      <p><b>Other:</b> Docker, GitHub, Alchemy, The Graph</p>
    </div>
  </section>

  <!-- Education -->
  <section class="mt-16 w-11/12 md:w-3/4">
    <h2 class="text-3xl font-semibold mb-6 gradient-text">Education</h2>
    <div class="glass p-6">
      <p><b>B.Tech Major:</b> IIT Guwahati — 7.55 CGPA (2021–2025)</p>
      <p><b>Senior Secondary:</b> CBSE Board — 85% (2023)</p>
      <p><b>Secondary:</b> CBSE Board — 94% (2021)</p>
    </div>
  </section>

  <!-- Achievements -->
  <section class="mt-16 w-11/12 md:w-3/4 mb-20">
    <h2 class="text-3xl font-semibold mb-6 gradient-text">Achievements</h2>
    <div class="glass p-6 space-y-2">
      <p>🏆 Blockchain Challenge (IITG Hostel Tech Fest) — 3rd Position (2024)</p>
      <p>🤖 Robotics Challenge (IITG Hostel Tech Fest) — 2nd Position (2024)</p>
      <p>🎭 Mime Competition (IITG Cultural Fest) — 2nd Position (2024)</p>
      <p>📊 MnAnalyse — 12th Rank among 2000+ participants (2025)</p>
      <p>📘 JEE Advanced 2021 — AIR 5462</p>
      <p>📘 JEE Mains 2021 — AIR 7422</p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-6 text-center text-gray-400 text-sm">
    © 2025 Jainil Panigrahi | Built with ❤️ using Tailwind CSS
  </footer>
</body>
</html>
