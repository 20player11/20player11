<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>20player11 | Software Engineer</title>
    <meta name="description" content="Portfolio of 20player11: AI enthusiast, Software Developer, and Cybersecurity researcher.">
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; background-color: #050505; color: #e5e5e5; }
        .font-mono { font-family: 'JetBrains Mono', monospace; }
        .glass { background: rgba(255, 255, 255, 0.03); backdrop-filter: blur(12px); border: 1px solid rgba(255, 255, 255, 0.05); }
        .gradient-text { background: linear-gradient(90deg, #3b82f6, #8b5cf6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .terminal-blink::after { content: '_'; animation: blink 1s infinite; }
        @keyframes blink { 50% { opacity: 0; } }
    </style>
</head>
<body>

    <!-- Navbar -->
    <nav class="fixed top-0 w-full z-50 glass border-b border-white/10 backdrop-blur-md">
        <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
            <span class="font-bold text-lg tracking-tight">20player11</span>
            <div class="hidden md:flex space-x-8 text-sm font-medium text-neutral-400">
                <a href="#about" class="hover:text-white transition">About</a>
                <a href="#projects" class="hover:text-white transition">Projects</a>
                <a href="#skills" class="hover:text-white transition">Skills</a>
            </div>
            <a href="mailto:info.20player11@seznam.cz" class="bg-white text-black text-sm px-4 py-2 rounded-full font-semibold hover:bg-neutral-200 transition">Contact</a>
        </div>
    </nav>

    <!-- Hero -->
    <main class="max-w-6xl mx-auto px-6 pt-32 pb-20">
        <section class="grid lg:grid-cols-2 gap-12 items-center min-h-[60vh]">
            <div>
                <h1 class="text-5xl md:text-7xl font-bold tracking-tighter mb-6">Building the Future,<br><span class="gradient-text">One Project at a Time.</span></h1>
                <p class="text-neutral-400 text-lg mb-8 leading-relaxed max-w-lg">Developer, AI enthusiast, and security researcher. Focused on building high-performance systems and robust, elegant software.</p>
                <div class="flex gap-4">
                    <a href="#projects" class="px-6 py-3 bg-blue-600 rounded-full font-semibold hover:bg-blue-500 transition">View Projects</a>
                    <a href="https://github.com/20player11" class="px-6 py-3 border border-white/10 rounded-full font-semibold hover:bg-white/5 transition">GitHub</a>
                </div>
            </div>
            
            <div class="glass p-6 rounded-2xl shadow-2xl">
                <div class="flex gap-2 mb-4">
                    <div class="w-3 h-3 rounded-full bg-red-500"></div>
                    <div class="w-3 h-3 rounded-full bg-yellow-500"></div>
                    <div class="w-3 h-3 rounded-full bg-green-500"></div>
                </div>
                <div class="font-mono text-sm text-blue-400 space-y-2">
                    <div>~/20player11 $ <span id="typing" class="text-white"></span><span class="terminal-blink"></span></div>
                    <div class="text-neutral-500"># Building robust solutions...</div>
                    <div class="text-neutral-500"># Optimizing for performance...</div>
                    <div class="text-neutral-500"># Ready for deployment.</div>
                </div>
            </div>
        </section>

        <!-- Projects -->
        <section id="projects" class="py-20">
            <h2 class="text-3xl font-bold mb-10">Selected Works</h2>
            <div class="grid md:grid-cols-3 gap-6">
                <!-- Project 1 -->
                <div class="glass p-6 rounded-2xl hover:border-blue-500/50 transition duration-300 group">
                    <i data-lucide="cpu" class="text-blue-500 mb-4 w-8 h-8"></i>
                    <h3 class="text-xl font-semibold mb-2">J.A.R.V.I.S AI</h3>
                    <p class="text-neutral-400 text-sm mb-4">Advanced desktop assistant with automation and computer vision integration.</p>
                    <div class="flex gap-2">
                        <span class="px-2 py-1 bg-white/5 rounded text-[10px] uppercase font-bold">Python</span>
                        <span class="px-2 py-1 bg-white/5 rounded text-[10px] uppercase font-bold">AI</span>
                    </div>
                </div>
                <!-- Project 2 -->
                <div class="glass p-6 rounded-2xl hover:border-blue-500/50 transition duration-300 group">
                    <i data-lucide="terminal" class="text-blue-500 mb-4 w-8 h-8"></i>
                    <h3 class="text-xl font-semibold mb-2">Cathartic</h3>
                    <p class="text-neutral-400 text-sm mb-4">Modern system utility for cleaning and maintaining Linux kernel environments.</p>
                    <div class="flex gap-2">
                        <span class="px-2 py-1 bg-white/5 rounded text-[10px] uppercase font-bold">Linux</span>
                        <span class="px-2 py-1 bg-white/5 rounded text-[10px] uppercase font-bold">CLI</span>
                    </div>
                </div>
                <!-- Project 3 -->
                <div class="glass p-6 rounded-2xl hover:border-blue-500/50 transition duration-300 group">
                    <i data-lucide="shield" class="text-blue-500 mb-4 w-8 h-8"></i>
                    <h3 class="text-xl font-semibold mb-2">Security Hub</h3>
                    <p class="text-neutral-400 text-sm mb-4">Toolkit for network analysis, bug hunting, and security research.</p>
                    <div class="flex gap-2">
                        <span class="px-2 py-1 bg-white/5 rounded text-[10px] uppercase font-bold">CyberSec</span>
                        <span class="px-2 py-1 bg-white/5 rounded text-[10px] uppercase font-bold">OSINT</span>
                    </div>
                </div>
            </div>
        </section>

<!-- Skills -->
<section id="skills" class="py-10">
    <h2 class="text-3xl font-bold mb-10">Core Stack</h2>
    <div class="flex flex-wrap gap-4">
        <div class="px-4 py-2 bg-white/5 border border-white/10 rounded-full text-sm hover:border-blue-500/50 transition cursor-default">Python</div>
        <div class="px-4 py-2 bg-white/5 border border-white/10 rounded-full text-sm hover:border-blue-500/50 transition cursor-default">JavaScript</div>
        <div class="px-4 py-2 bg-white/5 border border-white/10 rounded-full text-sm hover:border-blue-500/50 transition cursor-default">Linux</div>
        <div class="px-4 py-2 bg-white/5 border border-white/10 rounded-full text-sm hover:border-blue-500/50 transition cursor-default">Arch Linux</div>
        <div class="px-4 py-2 bg-white/5 border border-white/10 rounded-full text-sm hover:border-blue-500/50 transition cursor-default">Cybersecurity</div>
        <div class="px-4 py-2 bg-white/5 border border-white/10 rounded-full text-sm hover:border-blue-500/50 transition cursor-default">UI/UX</div>
        <div class="px-4 py-2 bg-white/5 border border-white/10 rounded-full text-sm hover:border-blue-500/50 transition cursor-default">Git</div>
        <div class="px-4 py-2 bg-white/5 border border-white/10 rounded-full text-sm hover:border-blue-500/50 transition cursor-default">Firebase</div>
    </div>
</section>

    </main>

    <footer class="text-center py-10 border-t border-white/5 text-neutral-600 text-sm">
        <p>© 2026 20player11. Built with passion. Powered by curiosity.</p>
    </footer>

    <script>
        // Initialize Icons
        lucide.createIcons();

        // Typing Effect
        const text = "sudo pacman -S innovation";
        const element = document.getElementById("typing");
        let i = 0;
        function type() {
            if (i < text.length) {
                element.innerHTML += text.charAt(i);
                i++;
                setTimeout(type, 100);
            }
        }
        type();
    </script>
</body>
</html>
