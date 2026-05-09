<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hamad Rajpoot | Senior WordPress Developer</title>

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- AOS Animation -->
    <link href="https://unpkg.com/aos@2.3.4/dist/aos.css" rel="stylesheet">

    <style>
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
            background: #0f172a;
            color: white;
        }

        .gradient-text {
            background: linear-gradient(to right, #60a5fa, #3b82f6);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .glass {
            background: rgba(255,255,255,0.05);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255,255,255,0.1);
        }
    </style>
</head>
<body>

    <!-- Navbar -->
    <header class="fixed w-full top-0 z-50 bg-slate-900/80 backdrop-blur-lg border-b border-slate-800">
        <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
            <h1 class="text-2xl font-bold gradient-text">Hamad Rajpoot</h1>

            <nav class="hidden md:flex gap-8 text-sm font-medium">
                <a href="#about" class="hover:text-blue-400 transition">About</a>
                <a href="#skills" class="hover:text-blue-400 transition">Skills</a>
                <a href="#experience" class="hover:text-blue-400 transition">Experience</a>
                <a href="#projects" class="hover:text-blue-400 transition">Projects</a>
                <a href="#contact" class="hover:text-blue-400 transition">Contact</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="min-h-screen flex items-center justify-center px-6">
        <div class="max-w-5xl text-center">

            <p class="text-blue-400 uppercase tracking-widest mb-4" data-aos="fade-up">
                Senior WordPress Developer
            </p>

            <h1 class="text-5xl md:text-7xl font-extrabold leading-tight mb-6" data-aos="fade-up" data-aos-delay="100">
                Building Modern <span class="gradient-text">WordPress</span> & Full-Stack Solutions
            </h1>

            <p class="text-slate-300 text-lg md:text-xl max-w-3xl mx-auto mb-10 leading-relaxed" data-aos="fade-up" data-aos-delay="200">
                Experienced Senior WordPress Developer with 5+ years of expertise in WordPress, WooCommerce, PHP, Laravel, React.js, and performance optimization. Specialized in custom plugins, scalable applications, and high-performance websites.
            </p>

            <div class="flex flex-col sm:flex-row justify-center gap-4" data-aos="fade-up" data-aos-delay="300">
                <a href="#projects" class="bg-blue-600 hover:bg-blue-700 px-8 py-4 rounded-xl font-semibold transition">
                    View Projects
                </a>

                <a href="https://github.com/Hamad-rajpoot" target="_blank" class="border border-slate-600 hover:border-blue-500 px-8 py-4 rounded-xl font-semibold transition">
                    GitHub Profile
                </a>
            </div>
        </div>
    </section>

    <!-- About -->
    <section id="about" class="py-24 px-6">
        <div class="max-w-6xl mx-auto grid md:grid-cols-2 gap-12 items-center">

            <div data-aos="fade-right">
                <h2 class="text-4xl font-bold mb-6">About Me</h2>

                <p class="text-slate-300 leading-relaxed mb-6">
                    I am a Senior WordPress Developer with 5+ years of experience building custom WordPress websites, WooCommerce stores, plugins, and scalable web applications.
                </p>

                <p class="text-slate-300 leading-relaxed">
                    My expertise includes custom theme development, API integrations, Laravel applications, performance optimization, Elementor, Avada, GeneratePress, React.js, and full-stack development.
                </p>
            </div>

            <div class="grid grid-cols-2 gap-6" data-aos="fade-left">

                <div class="glass p-6 rounded-2xl text-center">
                    <h3 class="text-4xl font-bold text-blue-400 mb-2">5+</h3>
                    <p class="text-slate-300">Years Experience</p>
                </div>

                <div class="glass p-6 rounded-2xl text-center">
                    <h3 class="text-4xl font-bold text-blue-400 mb-2">50+</h3>
                    <p class="text-slate-300">Projects Completed</p>
                </div>

                <div class="glass p-6 rounded-2xl text-center">
                    <h3 class="text-4xl font-bold text-blue-400 mb-2">2</h3>
                    <p class="text-slate-300">Published Plugins</p>
                </div>

                <div class="glass p-6 rounded-2xl text-center">
                    <h3 class="text-4xl font-bold text-blue-400 mb-2">100%</h3>
                    <p class="text-slate-300">Responsive Design</p>
                </div>

            </div>
        </div>
    </section>

    <!-- Skills -->
    <section id="skills" class="py-24 px-6 bg-slate-900">
        <div class="max-w-6xl mx-auto">

            <div class="text-center mb-16" data-aos="fade-up">
                <h2 class="text-4xl font-bold mb-4">Technical Skills</h2>
                <p class="text-slate-400">Technologies and tools I work with</p>
            </div>

            <div class="grid md:grid-cols-4 sm:grid-cols-2 gap-6">

                <div class="glass p-6 rounded-2xl">PHP</div>
                <div class="glass p-6 rounded-2xl">WordPress</div>
                <div class="glass p-6 rounded-2xl">WooCommerce</div>
                <div class="glass p-6 rounded-2xl">Laravel</div>
                <div class="glass p-6 rounded-2xl">React.js</div>
                <div class="glass p-6 rounded-2xl">JavaScript</div>
                <div class="glass p-6 rounded-2xl">MySQL</div>
                <div class="glass p-6 rounded-2xl">MongoDB</div>
                <div class="glass p-6 rounded-2xl">REST APIs</div>
                <div class="glass p-6 rounded-2xl">Elementor</div>
                <div class="glass p-6 rounded-2xl">Avada</div>
                <div class="glass p-6 rounded-2xl">GeneratePress</div>
                <div class="glass p-6 rounded-2xl">ACF</div>
                <div class="glass p-6 rounded-2xl">Gravity Forms</div>
                <div class="glass p-6 rounded-2xl">GitHub</div>
                <div class="glass p-6 rounded-2xl">Jira</div>

            </div>
        </div>
    </section>

    <!-- Experience -->
    <section id="experience" class="py-24 px-6">
        <div class="max-w-5xl mx-auto">

            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold mb-4">Work Experience</h2>
                <p class="text-slate-400">My professional journey</p>
            </div>

            <div class="space-y-8">

                <div class="glass p-8 rounded-2xl" data-aos="fade-up">
                    <div class="flex flex-col md:flex-row md:justify-between md:items-center mb-4">
                        <h3 class="text-2xl font-bold">SIGMA SQUARE</h3>
                        <span class="text-blue-400">Aug 2023 - Present</span>
                    </div>

                    <h4 class="text-lg text-slate-300 mb-4">WordPress Developer</h4>

                    <ul class="list-disc list-inside text-slate-400 space-y-2">
                        <li>Developed custom WordPress plugins and modules</li>
                        <li>Created admin settings pages and custom meta tables</li>
                        <li>Customized Avada, Elementor, and Divi themes</li>
                        <li>Integrated third-party APIs and REST endpoints</li>
                        <li>Built and maintained Laravel applications</li>
                        <li>Worked on theme support and client issue resolution</li>
                        <li>Optimized Core Web Vitals and performance</li>
                    </ul>
                </div>

                <div class="glass p-8 rounded-2xl" data-aos="fade-up" data-aos-delay="100">
                    <div class="flex flex-col md:flex-row md:justify-between md:items-center mb-4">
                        <h3 class="text-2xl font-bold">GAORFID</h3>
                        <span class="text-blue-400">Aug 2024 - Apr 2025</span>
                    </div>

                    <h4 class="text-lg text-slate-300 mb-4">WordPress Developer (Part-Time Remote)</h4>

                    <ul class="list-disc list-inside text-slate-400 space-y-2">
                        <li>Developed custom WooCommerce stores</li>
                        <li>Integrated payment gateways and plugins</li>
                        <li>Managed products and store configuration</li>
                        <li>Built responsive Elementor websites</li>
                        <li>Performed troubleshooting and testing</li>
                    </ul>
                </div>

            </div>
        </div>
    </section>

    <!-- Projects -->
    <section id="projects" class="py-24 px-6 bg-slate-900">
        <div class="max-w-7xl mx-auto">

            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold mb-4">Featured Projects</h2>
                <p class="text-slate-400">Selected websites and client work</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">

                <a href="https://proofid.com/" target="_blank" class="glass p-8 rounded-2xl hover:scale-105 transition duration-300">
                    <h3 class="text-2xl font-bold mb-3">ProofID</h3>
                    <p class="text-slate-400">Enterprise identity and access management website.</p>
                </a>

                <a href="https://www.estateresearch.co.uk/" target="_blank" class="glass p-8 rounded-2xl hover:scale-105 transition duration-300">
                    <h3 class="text-2xl font-bold mb-3">Estate Research</h3>
                    <p class="text-slate-400">Professional estate and property research platform.</p>
                </a>

                <a href="https://www.merudio.com/" target="_blank" class="glass p-8 rounded-2xl hover:scale-105 transition duration-300">
                    <h3 class="text-2xl font-bold mb-3">Merudio</h3>
                    <p class="text-slate-400">Modern digital business website with responsive architecture.</p>
                </a>

                <a href="https://rainfordhall.com/" target="_blank" class="glass p-8 rounded-2xl hover:scale-105 transition duration-300">
                    <h3 class="text-2xl font-bold mb-3">Rainford Hall</h3>
                    <p class="text-slate-400">Hospitality and event venue website.</p>
                </a>

                <a href="https://www.hamme.com.pk/" target="_blank" class="glass p-8 rounded-2xl hover:scale-105 transition duration-300">
                    <h3 class="text-2xl font-bold mb-3">Hamme</h3>
                    <p class="text-slate-400">E-commerce store with WooCommerce customization.</p>
                </a>

                <a href="https://radinmen.com/" target="_blank" class="glass p-8 rounded-2xl hover:scale-105 transition duration-300">
                    <h3 class="text-2xl font-bold mb-3">Radinmen</h3>
                    <p class="text-slate-400">Professional online shopping experience with responsive UI.</p>
                </a>

            </div>
        </div>
    </section>

    <!-- Plugins -->
    <section class="py-24 px-6">
        <div class="max-w-5xl mx-auto text-center">

            <h2 class="text-4xl font-bold mb-6">Published WordPress Plugins</h2>

            <div class="grid md:grid-cols-2 gap-8 mt-12">

                <a href="https://wordpress.org/plugins/hamada-smart-404-redirect-logger/" target="_blank" class="glass p-8 rounded-2xl hover:scale-105 transition duration-300">
                    <h3 class="text-2xl font-bold mb-3">Smart 404 Redirect Logger</h3>
                    <p class="text-slate-400">Advanced WordPress redirect and 404 monitoring plugin.</p>
                </a>

                <a href="https://wordpress.org/plugins/expirepress/" target="_blank" class="glass p-8 rounded-2xl hover:scale-105 transition duration-300">
                    <h3 class="text-2xl font-bold mb-3">ExpirePress</h3>
                    <p class="text-slate-400">WordPress content expiration and scheduling solution.</p>
                </a>

            </div>
        </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="py-24 px-6 bg-slate-900">
        <div class="max-w-4xl mx-auto text-center">

            <h2 class="text-5xl font-bold mb-6">Let's Work Together</h2>

            <p class="text-slate-400 text-lg mb-10">
                Available for WordPress development, WooCommerce projects, custom plugin development, and performance optimization.
            </p>

            <div class="flex flex-col md:flex-row justify-center gap-6">

                <a href="mailto:your-email@example.com" class="bg-blue-600 hover:bg-blue-700 px-8 py-4 rounded-xl font-semibold transition">
                    Email Me
                </a>

                <a href="https://github.com/Hamad-rajpoot" target="_blank" class="border border-slate-600 hover:border-blue-500 px-8 py-4 rounded-xl font-semibold transition">
                    GitHub
                </a>

            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-8 text-center border-t border-slate-800 text-slate-500">
        © 2026 Hamad Rajpoot — Senior WordPress Developer
    </footer>

    <!-- Scripts -->
    <script src="https://unpkg.com/aos@2.3.4/dist/aos.js"></script>

    <script>
        AOS.init({
            duration: 1000,
            once: true
        });
    </script>

</body>
</html>