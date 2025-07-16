# Meena-Network-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meena Network - Official Portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Inter', sans-serif;
            background: #0a0a0a;
            color: #ffffff;
            overflow-x: hidden;
        }
        
        .cyberpunk-bg {
            background: linear-gradient(135deg, #1a1a2e 0%, #16213e 50%, #0f3460 100%);
            position: relative;
            min-height: 100vh;
        }
        
        .neon-text {
            text-shadow: 0 0 10px #00ff88, 0 0 20px #00ff88, 0 0 30px #00ff88;
        }
        
        .btn-neon {
            background: linear-gradient(45deg, #00ff88, #00cc6a);
            border: none;
            color: #000;
            font-weight: 600;
            transition: all 0.3s ease;
            box-shadow: 0 0 20px rgba(0, 255, 136, 0.3);
        }
        
        .btn-neon:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 30px rgba(0, 255, 136, 0.5);
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar fixed top-0 w-full z-50 px-6 py-4">
        <div class="max-w-7xl mx-auto flex justify-between items-center">
            <div class="text-2xl font-bold neon-text">Meena Network</div>
            <div class="hidden md:flex space-x-8">
                <a href="#home" class="hover:text-green-400 transition-colors">Home</a>
                <a href="#projects" class="hover:text-green-400 transition-colors">Projects</a>
                <a href="#about" class="hover:text-green-400 transition-colors">About</a>
                <a href="#contact" class="hover:text-green-400 transition-colors">Contact</a>
            </div>
            <div class="md:hidden">
                <button id="mobile-menu-button" class="text-white">
                    <i class="fas fa-bars"></i>
                </button>
            </div>
        </div>
        <div id="mobile-menu" class="hidden md:hidden mt-4 space-y-2">
            <a href="#home" class="block hover:text-green-400 transition-colors">Home</a>
            <a href="#projects" class="block hover:text-green-400 transition-colors">Projects</a>
            <a href="#about" class="block hover:text-green-400 transition-colors">About</a>
            <a href="#contact" class="block hover:text-green-400 transition-colors">Contact</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="cyberpunk-bg relative">
        <div class="hero-section min-h-screen flex items-center justify-center px-6">
            <div class="max-w-4xl mx-auto text-center">
                <h1 class="text-6xl md:text-8xl font-bold mb-4">
                    Hi, I'm <span class="neon-text">Meena Network</span>.
                </h1>
                <p class="text-xl md:text-2xl mb-8 text-gray-300">
                    I'm passionate about creating innovative digital solutions and exploring the power of tech.
                </p>
                <div class="flex flex-col sm:flex-row gap-4 justify-center">
                    <button class="btn-neon px-8 py-4 rounded-full text-lg font-semibold" onclick="scrollToSection('projects')">
                        View Projects
                    </button>
                    <button class="btn-outline-neon px-8 py-4 rounded-full text-lg font-semibold" onclick="scrollToSection('contact')">
                        Get in Touch
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section (Bio) -->
    <section id="about" class="py-20 px-6 bg-gray-900">
        <div class="max-w-4xl mx-auto">
            <h2 class="text-4xl font-bold text-center mb-12 neon-text">About Me</h2>
            <p class="text-gray-300 text-xl mb-8">
                🥀 ═════════ ❃ ════════<br>
                🚩😀 𝐌𝐄𝐄𝐍𝐀 𝐉𝐈'𝐒 𝐎𝐅𝐅𝐈𝐂𝐈𝐀𝐋 𝐁𝐈𝐎 👑🚩<br><br>

                😀 यह कोई मामूली Bio नहीं...<br>
                💣 ये है उस Legend की Story,<br>
                जो नाम से नहीं – 😀 काम से चलता है!<br><br>

                😀 About Me?<br>
                👇 नीचे आओ – आँखें खुली रखना,<br>
                क्योंकि हर Line में "Swag" टपकता है! 😎<br><br>

                「💸」 𝐍ᴀᴍᴇ ➪ 𝐍ᴀʜɪ 𝐁ᴀᴛᴀᴜɢᴀ ❤️‍🔥<br>
                「😀」 𝐔sᴇʀɴᴀᴍᴇ ➪ @Meena_ji_is_back 😎<br>
                「😀」 𝐀ɢᴇ ➪ 𝟏𝟗 𝐘𝐞𝐚𝐫𝐬 😀<br>
                「⭐」 𝐅ʀᴏᴍ ➪ 𝐈ɴ𝐝ɪᴀ 🇮🇳 [ RJ - 02 ] ✅<br>
                「😀」 𝐆ᴇɴᴅᴇʀ ➪ 𝐌ᴀʟᴇ 💸<br>
                「✅」 𝐑ᴇʟɪ𝐆ɪᴏɴ ➪ 𝐇𝐢𝐧𝐝𝐮 🚩<br>
                「👑」 𝐊ʜᴀᴀs 𝐃ᴏsᴛ ➪ ⚙️ (tg://settings)✅<br><br>

                😈  👥  𝐁𝐇𝐀𝐈𝐂𝐇𝐀𝐑𝐀 𝐎𝐍 𝐓𝐎𝐏  👥 😈<br>
                𝐁𝐑𝐎𝐓𝐇𝐄𝐑 𝐈𝐒 𝐁𝐀𝐂𝐊  :- @ANKIT_MEENA_07 🌟<br>
                𝐁𝐑𝐎𝐓𝐇𝐄𝐑 𝐈𝐒 𝐁𝐀𝐂𝐊  :- @Meena_ji_is_backk 💡<br><br>

                😀🔘 Lɪsᴛ Oғ CHANNELS 🔘😀 🔻<br><br>
                1️⃣ - 🔹👉 MAIN CHANNNEL 👉🔸<br>
                🔰 [—‌‌‌𝐌𝐄𝐄𝐍𝐀 —‌‌‌𝐍𝐄𝐓𝐖𝐎𝐑𝐊 🛜]  :- <a href="https://t.me/+gkuN84ZOWQpjYWU1">https://t.me/+gkuN84ZOWQpjYWU1</a> ✅<br>
                🛠️ [—‌‌‌𝙈𝙀𝙀𝙉𝘼 —‌‌‌𝙉𝙀𝙏𝙒𝙊𝙍𝙆 —‌‌‌𝘽𝘼𝘾𝙆𝙐𝙋 🛜]  :- <a href="https://t.me/+D4P-MD8w0wY0N2I1">https://t.me/+D4P-MD8w0wY0N2I1</a> ✅<br><br>
                ✅ 𝘾𝘽𝙊𝙏 ❤️‍🔥 :- @MeenaNetworkBot ➡️<br><br>
