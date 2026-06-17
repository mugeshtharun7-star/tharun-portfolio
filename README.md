# tharun-portfolio
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mugesh Tharun | Portfolio</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body {
            background-color: #0B1120;
        }
        .glow-effect:hover {
            box-shadow: 0 0 20px rgba(56, 189, 248, 0.2);
        }
    </style>
</head>
<body class="text-slate-200 font-sans antialiased selection:bg-sky-500/30 selection:text-sky-400">

    <!-- Navbar -->
    <nav class="fixed top-0 left-0 w-full z-50 bg-[#0B1120]/80 backdrop-blur-md border-b border-slate-800">
        <div class="max-w-6xl mx-auto px-6 h-16 flex items-center justify-between">
            <a href="#" class="text-xl font-bold tracking-wider text-white">MT<span class="text-[#38BDF8]">.</span></a>
            <div class="hidden md:flex space-x-8 text-sm font-medium text-slate-400">
                <a href="#about" class="hover:text-[#38BDF8] transition-colors">About</a>
                <a href="#skills" class="hover:text-[#38BDF8] transition-colors">Skills</a>
                <a href="#projects" class="hover:text-[#38BDF8] transition-colors">Projects</a>
                <a href="#goals" class="hover:text-[#38BDF8] transition-colors">Goals</a>
                <a href="#contact" class="hover:text-[#38BDF8] transition-colors">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="min-h-screen flex items-center justify-center pt-16 px-6 relative overflow-hidden">
        <!-- Subtle Background Glow -->
        <div class="absolute top-1/4 left-1/2 -translate-x-1/2 w-[500px] h-[500px] bg-[#38BDF8]/5 rounded-full blur-[120px] pointer-events-none"></div>

        <div class="max-w-3xl text-center z-10">
            <p class="text-[#38BDF8] font-mono tracking-widest text-sm uppercase mb-3 animate-fade-in">Hi, my name is</p>
            <h1 class="text-5xl md:text-7xl font-extrabold text-white tracking-tight mb-4">
                Mugesh Tharun
            </h1>
            <h2 class="text-xl md:text-2xl text-slate-400 font-medium mb-6">
                IT Student <span class="text-slate-600">|</span> Python Learner <span class="text-slate-600">|</span> Aspiring Full Stack Developer
            </h2>
            <p class="text-slate-400 max-w-xl mx-auto mb-10 leading-relaxed">
                Passionate about technology, web development, and problem-solving. Currently building my skills in Python and Full Stack Development while pursuing my degree in Information Technology at SRMIST.
            </p>
            <div class="flex flex-col sm:flex-row justify-center items-center gap-4">
                <a href="#projects" class="w-full sm:w-auto px-8 py-3 rounded-lg bg-[#38BDF8] text-[#0B1120] font-semibold tracking-wide hover:bg-[#38BDF8]/90 transition-all transform hover:-translate-y-0.5 shadow-lg shadow-[#38BDF8]/20 text-center">
                    View Projects
                </a>
                <a href="#contact" class="w-full sm:w-auto px-8 py-3 rounded-lg border border-slate-700 text-slate-300 font-medium hover:bg-slate-800/50 hover:border-slate-500 transition-all text-center">
                    Contact Me
                </a>
            </div>
        </div>
    </section>

    <hr class="border-slate-900 max-w-5xl mx-auto">

    <!-- About & Education Section -->
    <section id="about" class="py-24 px-6 max-w-5xl mx-auto">
        <div class="grid grid-cols-1 md:grid-cols-5 gap-12 items-start">
            <div class="md:col-span-3">
                <h2 class="text-2xl font-bold text-white mb-6 flex items-center gap-3">
                    <span class="text-[#38BDF8] font-mono text-lg">01.</span> Who Am I?
                </h2>
                <div class="space-y-4 text-slate-400 leading-relaxed">
                    <p>
                        Hello! I'm Mugesh Tharun, an Information Technology student with a strong interest in software development and emerging technologies.
                    </p>
                    <p>
                        I enjoy learning new programming concepts, building practical projects, and continuously improving my technical skills. My current focus is on Python programming, web development, and automation.
                    </p>
                </div>
            </div>
            
            <div class="md:col-span-2 bg-[#111827]/60 border border-slate-800 rounded-xl p-6 glow-effect transition-all">
                <h3 class="text-xs font-mono uppercase tracking-widest text-[#38BDF8] mb-2">Education</h3>
                <h4 class="text-lg font-bold text-white">B.Tech Information Technology</h4>
                <p class="text-sm text-slate-400 mt-1">SRM Institute of Science and Technology</p>
                <div class="mt-4 inline-block bg-slate-800/80 text-slate-300 text-xs px-3 py-1 rounded-full font-medium">
                    First Year Student
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-24 bg-[#0f172a]/40 border-y border-slate-900 px-6">
        <div class="max-w-5xl mx-auto">
            <h2 class="text-2xl font-bold text-white mb-12 flex items-center gap-3">
                <span class="text-[#38BDF8] font-mono text-lg">02.</span> Technical Skills
            </h2>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Category 1 -->
                <div class="bg-[#111827]/40 border border-slate-800/80 rounded-xl p-6">
                    <div class="text-[#38BDF8] text-xl mb-4"><i class="fa-solid :fa-code"></i></div>
                    <h3 class="text-md font-semibold text-white mb-3">Programming</h3>
                    <ul class="space-y-2 text-sm text-slate-400">
                        <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-[#38BDF8]"></span> Python</li>
                        <li class="flex items-center gap-2 text-slate-500"><span class="w-1.5 h-1.5 rounded-full bg-slate-700"></span> JavaScript <span class="text-xs italic">(Learning)</span></li>
                    </ul>
                </div>
                <!-- Category 2 -->
                <div class="bg-[#111827]/40 border border-slate-800/80 rounded-xl p-6">
                    <div class="text-[#38BDF8] text-xl mb-4"><i class="fa-solid fa-layer-group"></i></div>
                    <h3 class="text-md font-semibold text-white mb-3">Web Development</h3>
                    <ul class="space-y-2 text-sm text-slate-400">
                        <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-[#38BDF8]"></span> HTML5 / CSS3</li>
                        <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-[#38BDF8]"></span> Responsive Web Design</li>
                    </ul>
                </div>
                <!-- Category 3 -->
                <div class="bg-[#111827]/40 border border-slate-800/80 rounded-xl p-6">
                    <div class="text-[#38BDF8] text-xl mb-4"><i class="fa-solid fa-screwdriver-wrench"></i></div>
                    <h3 class="text-md font-semibold text-white mb-3">Tools & Environment</h3>
                    <ul class="space-y-2 text-sm text-slate-400">
                        <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-[#38BDF8]"></span> Git / GitHub</li>
                        <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-[#38BDF8]"></span> VS Code</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-24 px-6 max-w-5xl mx-auto">
        <h2 class="text-2xl font-bold text-white mb-12 flex items-center gap-3">
            <span class="text-[#38BDF8] font-mono text-lg">03.</span> Featured Projects
        </h2>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <!-- Project 1 -->
            <div class="bg-[#111827]/80 border border-slate-850 rounded-xl p-6 flex flex-col justify-between glow-effect transition-all group">
                <div>
                    <div class="flex items-center justify-between text-slate-400 mb-6">
                        <i class="fa-regular fa-folder text-2xl text-[#38BDF8]"></i>
                        <div class="space-x-3 text-sm">
                            <a href="#" class="hover:text-white"><i class="fa-brands fa-github"></i></a>
                        </div>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2 group-hover:text-[#38BDF8] transition-colors">Personal Portfolio</h3>
                    <p class="text-xs text-slate-400 leading-relaxed mb-4">
                        My professional portfolio showcasing my skills, projects, and learning journey. Built with clean syntax and responsive layouts.
                    </p>
                </div>
                <div class="flex gap-2 text-[11px] font-mono text-slate-500">
                    <span>HTML5</span><span>CSS3</span><span>Tailwind</span>
                </div>
            </div>

            <!-- Project 2 -->
            <div class="bg-[#111827]/80 border border-slate-850 rounded-xl p-6 flex flex-col justify-between glow-effect transition-all group">
                <div>
                    <div class="flex items-center justify-between text-slate-400 mb-6">
                        <i class="fa-regular fa-folder text-2xl text-[#38BDF8]"></i>
                        <div class="space-x-3 text-sm">
                            <a href="#" class="hover:text-white"><i class="fa-brands fa-github"></i></a>
                        </div>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2 group-hover:text-[#38BDF8] transition-colors">Python Calculator</h3>
                    <p class="text-xs text-slate-400 leading-relaxed mb-4">
                        A simple calculator application built using Python focusing on backend logic execution and robust terminal/GUI handling.
                    </p>
                </div>
                <div class="flex gap-2 text-[11px] font-mono text-slate-500">
                    <span>Python</span><span>Logic</span>
                </div>
            </div>

            <!-- Project 3 -->
            <div class="bg-[#111827]/80 border border-slate-850 rounded-xl p-6 flex flex-col justify-between glow-effect transition-all group">
                <div>
                    <div class="flex items-center justify-between text-slate-400 mb-6">
                        <i class="fa-regular fa-folder text-2xl text-[#38BDF8]"></i>
                        <div class="space-x-3 text-sm">
                            <a href="#" class="hover:text-white"><i class="fa-brands fa-github"></i></a>
                        </div>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2 group-hover:text-[#38BDF8] transition-colors">Future Interns Projects</h3>
                    <p class="text-xs text-slate-400 leading-relaxed mb-4">
                        Projects completed as part of my Full Stack Development internship, targeting interactive real-world applications.
                    </p>
                </div>
                <div class="flex gap-2 text-[11px] font-mono text-slate-500">
                    <span>Full Stack</span><span>Web App</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Goals Section -->
    <section id="goals" class="py-24 bg-[#0f172a]/40 border-y border-slate-900 px-6">
        <div class="max-w-3xl mx-auto text-center">
            <h2 class="text-2xl font-bold text-white mb-4">Current Goals</h2>
            <p class="text-sm text-slate-400 mb-10">What I am actively aiming for this year</p>
            
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 max-w-2xl mx-auto text-left">
                <div class="flex items-center gap-3 p-4 bg-[#111827]/60 border border-slate-800 rounded-lg">
                    <i class="fa-solid fa-circle-check text-[#38BDF8]"></i>
                    <span class="text-sm text-slate-300">Learn Full Stack Development</span>
                </div>
                <div class="flex items-center gap-3 p-4 bg-[#111827]/60 border border-slate-800 rounded-lg">
                    <i class="fa-solid fa-circle-check text-[#38BDF8]"></i>
                    <span class="text-sm text-slate-300">Build Real-World Projects</span>
                </div>
                <div class="flex items-center gap-3 p-4 bg-[#111827]/60 border border-slate-800 rounded-lg">
                    <i class="fa-solid fa-circle-check text-[#38BDF8]"></i>
                    <span class="text-sm text-slate-300">Contribute to GitHub</span>
                </div>
                <div class="flex items-center gap-3 p-4 bg-[#111827]/60 border border-slate-800 rounded-lg">
                    <i class="fa-solid fa-circle-check text-[#38BDF8]"></i>
                    <span class="text-sm text-slate-300">Secure Development Internships</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-32 px-6 max-w-xl mx-auto text-center">
        <h2 class="text-3xl font-bold text-white mb-4 tracking-tight">Let's Connect</h2>
        <p class="text-slate-400 text-sm mb-8 leading-relaxed">
            Whether you are looking for a freelance collaborator, an intern, or just want to discuss interesting tech, drop me a line!
        </p>
        
        <div class="inline-flex flex-col gap-4 text-sm w-full bg-[#111827]/40 border border-slate-850 p-6 rounded-xl">
            <a href="mailto:mugeshtharun4@gmail.com" class="flex items-center justify-between p-3 rounded-lg bg-[#0B1120] hover:text-[#38BDF8] border border-slate-800/80 transition-colors">
                <span class="text-slate-400 font-mono"><i class="fa-regular fa-envelope mr-2"></i> Email</span>
                <span class="font-medium">mugeshtharun4@gmail.com</span>
            </a>
            <a href="https://github.com/mugeshtharun7-star" target="_blank" class="flex items-center justify-between p-3 rounded-lg bg-[#0B1120] hover:text-[#38BDF8] border border-slate-800/80 transition-colors">
                <span class="text-slate-400 font-mono"><i class="fa-brands fa-github mr-2"></i> GitHub</span>
                <span class="font-medium">mugeshtharun7-star</span>
            </a>
            <div class="flex items-center justify-between p-3 rounded-lg bg-[#0B1120] border border-slate-800/80">
                <span class="text-slate-400 font-mono"><i class="fa-brands fa-linkedin-in mr-2"></i> LinkedIn</span>
                <span class="font-medium text-slate-300">Mugesh tharun</span>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-8 text-center text-xs text-slate-600 border-t border-slate-900">
        <p>© 2026 Mugesh Tharun. Designed with a clean, minimal aesthetic.</p>
    </footer>

</body>
</html>
