# nexa-web-studio
web designing 
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nexa Web Studio | Professional Website Design & Development</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        darkBg: '#0a0a0a',
                        darkCard: '#121212',
                        darkBorder: '#1f1f1f',
                        accentMuted: '#888888'
                    }
                }
            }
        }
    </script>
    <style>
        /* Custom scrollbar to match dark aesthetic */
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: #0a0a0a; }
        ::-webkit-scrollbar-thumb { background: #222; border-radius: 4px; }
        ::-webkit-scrollbar-thumb:hover { background: #333; }
    </style>
</head>
<body class="bg-darkBg text-gray-100 font-sans antialiased selection:bg-white selection:text-black">

    <!-- HEADER / NAVIGATION -->
    <header class="sticky top-0 z-50 bg-darkBg/80 backdrop-blur-md border-b border-darkBorder">
        <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
            <a href="#home" class="text-xl font-black tracking-widest text-white uppercase">
                Nexa<span class="text-accentMuted">.</span>
            </a>
            
            <!-- Desktop Nav -->
            <nav class="hidden md:flex items-center space-x-8 text-sm font-medium tracking-wide text-gray-400">
                <a href="#home" class="hover:text-white transition-colors">Home</a>
                <a href="#about" class="hover:text-white transition-colors">About</a>
                <a href="#services" class="hover:text-white transition-colors">Services</a>
                <a href="#portfolio" class="hover:text-white transition-colors">Portfolio</a>
                <a href="#pricing" class="hover:text-white transition-colors">Pricing</a>
                <a href="#testimonials" class="hover:text-white transition-colors">Testimonials</a>
                <a href="#contact" class="hover:text-white transition-colors">Contact</a>
            </nav>

            <div class="hidden md:block">
                <a href="#contact" class="px-5 py-2.5 text-xs font-semibold tracking-wider uppercase border border-white text-white hover:bg-white hover:text-black transition-all duration-300">
                    Get a Quote
                </a>
            </div>

            <!-- Mobile Menu Button -->
            <button id="menu-btn" class="md:hidden text-white focus:outline-none">
                <i class="fa-solid fa-bars text-xl"></i>
            </button>
        </div>

        <!-- Mobile Nav Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-darkBg border-b border-darkBorder px-6 py-6 space-y-4 text-center">
            <a href="#home" class="block text-gray-400 hover:text-white transition-colors py-2">Home</a>
            <a href="#about" class="block text-gray-400 hover:text-white transition-colors py-2">About</a>
            <a href="#services" class="block text-gray-400 hover:text-white transition-colors py-2">Services</a>
            <a href="#portfolio" class="block text-gray-400 hover:text-white transition-colors py-2">Portfolio</a>
            <a href="#pricing" class="block text-gray-400 hover:text-white transition-colors py-2">Pricing</a>
            <a href="#testimonials" class="block text-gray-400 hover:text-white transition-colors py-2">Testimonials</a>
            <a href="#contact" class="block text-gray-400 hover:text-white transition-colors py-2">Contact</a>
            <a href="#contact" class="block w-full py-3 text-xs font-semibold tracking-wider uppercase border border-white text-white">Get a Quote</a>
        </div>
    </header>

    <!-- HERO SECTION -->
    <section id="home" class="min-h-[calc(100vh-80px)] flex items-center justify-center relative px-6 py-20 border-b border-darkBorder">
        <div class="max-w-4xl text-center space-y-8">
            <h1 class="text-4xl sm:text-6xl font-extrabold tracking-tight text-white leading-none">
                Professional Websites That <br class="hidden sm:inline">Grow Your Business.
            </h1>
            <p class="text-lg sm:text-xl text-gray-400 max-w-2xl mx-auto font-light leading-relaxed">
                Nexa Web Studio helps businesses establish a powerful online presence through modern website design and development.
            </p>
            <div class="pt-4 flex flex-col sm:flex-row items-center justify-center gap-4">
                <a href="#contact" class="w-full sm:w-auto px-8 py-4 bg-white text-black font-semibold text-sm tracking-wide rounded-none hover:bg-gray-200 transition-all text-center">
                    Get a Free Consultation
                </a>
                <a href="#portfolio" class="w-full sm:w-auto px-8 py-4 border border-darkBorder text-gray-300 hover:text-white hover:border-white font-semibold text-sm tracking-wide rounded-none transition-all text-center">
                    View Our Portfolio
                </a>
            </div>
        </div>
    </section>

    <!-- WHY CHOOSE US -->
    <section class="py-24 px-6 border-b border-darkBorder max-w-7xl mx-auto">
        <div class="text-center max-w-2xl mx-auto mb-16">
            <h2 class="text-xs uppercase tracking-widest text-accentMuted font-bold mb-3">Why Partner With Us</h2>
            <p class="text-2xl sm:text-3xl font-bold text-white">Engineered for Performance and Aesthetics</p>
        </div>
        <div class="grid grid-cols-1 md:grid-cols-5 gap-8">
            <div class="p-8 bg-darkCard border border-darkBorder space-y-4">
                <div class="text-white text-xl"><i class="fa-solid fa-wand-magic-sparkles"></i></div>
                <h3 class="text-lg font-bold text-white">Custom Design</h3>
                <p class="text-sm text-gray-400 leading-relaxed">Tailored entirely to match your brand identity and business objectives perfectly.</p>
            </div>
            <div class="p-8 bg-darkCard border border-darkBorder space-y-4">
                <div class="text-white text-xl"><i class="fa-solid fa-mobile-screen"></i></div>
                <h3 class="text-lg font-bold text-white">Mobile-Friendly</h3>
                <p class="text-sm text-gray-400 leading-relaxed">Flawless functionality across smartphones, tablets, and desktop displays.</p>
            </div>
            <div class="p-8 bg-darkCard border border-darkBorder space-y-4">
                <div class="text-white text-xl"><i class="fa-solid fa-bolt"></i></div>
                <h3 class="text-lg font-bold text-white">Fast Delivery</h3>
                <p class="text-sm text-gray-400 leading-relaxed">Swift turnaround schedules without sacrificing structural or visual quality.</p>
            </div>
            <div class="p-8 bg-darkCard border border-darkBorder space-y-4">
                <div class="text-white text-xl"><i class="fa-solid fa-tags"></i></div>
                <h3 class="text-lg font-bold text-white">Affordable Pricing</h3>
                <p class="text-sm text-gray-400 leading-relaxed">Premium, professional web solutions structured to maximize your business budget.</p>
            </div>
            <div class="p-8 bg-darkCard border border-darkBorder space-y-4">
                <div class="text-white text-xl"><i class="fa-solid fa-headset"></i></div>
                <h3 class="text-lg font-bold text-white">Ongoing Support</h3>
                <p class="text-sm text-gray-400 leading-relaxed">Continuous post-launch technical assistance keeping your system safe.</p>
            </div>
        </div>
    </section>

    <!-- ABOUT US -->
    <section id="about" class="py-24 px-6 border-b border-darkBorder bg-darkCard/30">
        <div class="max-w-7xl mx-auto grid grid-cols-1 lg:grid-cols-2 gap-16 items-center">
            <div class="space-y-6">
                <h2 class="text-xs uppercase tracking-widest text-accentMuted font-bold">About Nexa Web Studio</h2>
                <h3 class="text-3xl sm:text-4xl font-extrabold text-white tracking-tight">Crafting Digital Excellence Across Africa & Beyond</h3>
                <p class="text-gray-400 leading-relaxed">
                    Born out of a desire to bridge the gap between complex digital tech and business realities, Nexa Web Studio builds high-performing, beautiful online platforms. We believe a website shouldn't just exist—it should actively close deals for your brand.
                </p>
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-6 pt-4">
                    <div>
                        <h4 class="text-sm font-bold text-white uppercase tracking-wider mb-2">Our Mission</h4>
                        <p class="text-xs text-gray-400 leading-relaxed">To help businesses succeed online with professional, high-performing websites.</p>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold text-white uppercase tracking-wider mb-2">Our Vision</h4>
                        <p class="text-xs text-gray-400 leading-relaxed">To become a trusted web solutions partner for businesses across Africa and beyond.</p>
                    </div>
                </div>
            </div>
            <div class="border border-darkBorder p-8 bg-darkCard space-y-6">
                <h4 class="text-md font-bold uppercase tracking-wider text-white">Our Core Values</h4>
                <ul class="space-y-4 text-sm text-gray-400">
                    <li class="flex items-center gap-3"><i class="fa-solid fa-check text-xs text-white"></i> <span><strong>Creativity:</strong> Bold designs that break visual boundaries.</span></li>
                    <li class="flex items-center gap-3"><i class="fa-solid fa-check text-xs text-white"></i> <span><strong>Professionalism:</strong> Clear timelines, crisp execution.</span></li>
                    <li class="flex items-center gap-3"><i class="fa-solid fa-check text-xs text-white"></i> <span><strong>Reliability:</strong> Systems built to stay secure and functional.</span></li>
                    <li class="flex items-center gap-3"><i class="fa-solid fa-check text-xs text-white"></i> <span><strong>Innovation:</strong> Deploying modern tech stacks for optimal load speed.</span></li>
                    <li class="flex items-center gap-3"><i class="fa-solid fa-check text-xs text-white"></i> <span><strong>Customer Satisfaction:</strong> We scale only when our partners thrive.</span></li>
                </ul>
            </div>
        </div>
    </section>

    <!-- SERVICES -->
    <section id="services" class="py-24 px-6 border-b border-darkBorder max-w-7xl mx-auto">
        <div class="text-center max-w-2xl mx-auto mb-16">
            <h2 class="text-xs uppercase tracking-widest text-accentMuted font-bold mb-3">Expertise</h2>
            <p class="text-2xl sm:text-3xl font-bold text-white">Comprehensive Web Solutions</p>
        </div>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <!-- Box 1 -->
            <div class="p-8 bg-darkCard border border-darkBorder space-y-4">
                <h3 class="text-lg font-bold text-white">Website Design</h3>
                <ul class="text-sm text-gray-400 space-y-2">
                    <li>• Business & Corporate websites</li>
                    <li>• Portfolio & Showcase models</li>
                    <li>• Tailored Personal landing layouts</li>
                </ul>
            </div>
            <!-- Box 2 -->
            <div class="p-8 bg-darkCard border border-darkBorder space-y-4">
                <h3 class="text-lg font-bold text-white">E-commerce Development</h3>
                <ul class="text-sm text-gray-400 space-y-2">
                    <li>• High-conversion online retail storefronts</li>
                    <li>• Safe integrated secure payment systems</li>
                    <li>• Streamlined client product management portals</li>
                </ul>
            </div>
            <!-- Box 3 -->
            <div class="p-8 bg-darkCard border border-darkBorder space-y-4">
                <h3 class="text-lg font-bold text-white">Website Maintenance</h3>
                <ul class="text-sm text-gray-400 space-y-2">
                    <li>• Regular dynamic content updates & backups</li>
                    <li>• Active round-the-clock security monitoring</li>
                    <li>• Dedicated structural technical support</li>
                </ul>
            </div>
            <!-- Box 4 -->
            <div class="p-8 bg-darkCard border border-darkBorder space-y-4">
                <h3 class="text-lg font-bold text-white">Domain & Hosting Assistance</h3>
                <ul class="text-sm text-gray-400 space-y-2">
                    <li>• Smooth official custom domain registration setup</li>
                    <li>• Reliable optimized server hosting configurations</li>
                    <li>• Production deployment & live configuration management</li>
                </ul>
            </div>
            <!-- Box 5 -->
            <div class="p-8 bg-darkCard border border-darkBorder space-y-4">
                <h3 class="text-lg font-bold text-white">SEO Services</h3>
                <ul class="text-sm text-gray-400 space-y-2">
                    <li>• Comprehensive basic search engine optimization</li>
                    <li>• Direct verification Google Search indexation</li>
                    <li>• Technical core speed and runtime optimization</li>
                </ul>
            </div>
            <!-- Custom CTA -->
            <div class="p-8 bg-transparent border border-dashed border-darkBorder flex flex-col justify-between items-start">
                <p class="text-sm text-gray-400 font-light">Have a unique system architecture or custom platform build request?</p>
                <a href="#contact" class="text-sm font-bold text-white underline hover:text-gray-300 pt-4">Let's build a custom build blueprint <i class="fa-solid fa-arrow-right ml-1"></i></a>
            </div>
        </div>
    </section>

    <!-- PORTFOLIO PREVIEW -->
    <section id="portfolio" class="py-24 px-6 border-b border-darkBorder bg-darkCard/30">
        <div class="max-w-7xl mx-auto space-y-16">
            <div class="flex flex-col sm:flex-row items-start sm:items-end justify-between gap-4">
                <div>
                    <h2 class="text-xs uppercase tracking-widest text-accentMuted font-bold mb-3">Our Work</h2>
                    <p class="text-2xl sm:text-3xl font-bold text-white">Completed Digital Case Studies</p>
                </div>
                <a href="#contact" class="text-sm font-semibold tracking-wide border-b border-white pb-1 text-white hover:text-gray-400 hover:border-gray-400 transition-colors">Enquire About Custom Projects</a>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Case 1 -->
                <div class="group border border-darkBorder bg-darkBg overflow-hidden">
                    <div class="aspect-video w-full bg-neutral-900 border-b border-darkBorder flex items-center justify-center text-xs text-neutral-600 transition-all duration-500 group-hover:bg-neutral-800">
                        [ Project Screenshot Placeholder ]
                    </div>
                    <div class="p-6 space-y-2">
                        <span class="text-xs uppercase tracking-widest text-accentMuted font-medium">Retail Industry — E-commerce Architecture</span>
                        <h3 class="text-lg font-bold text-white">Vanguard Apparel Store</h3>
                        <p class="text-sm text-gray-400">Comprehensive custom e-commerce system integration featuring custom local payment gateways.</p>
                        <div class="pt-2 text-xs font-bold text-white tracking-wider uppercase flex items-center gap-2">
                            <span>Result: +45% Order volume scale post-launch</span>
                        </div>
                    </div>
                </div>
                <!-- Case 2 -->
                <div class="group border border-darkBorder bg-darkBg overflow-hidden">
                    <div class="aspect-video w-full bg-neutral-900 border-b border-darkBorder flex items-center justify-center text-xs text-neutral-600 transition-all duration-500 group-hover:bg-neutral-800">
                        [ Project Screenshot Placeholder ]
                    </div>
                    <div class="p-6 space-y-2">
                        <span class="text-xs uppercase tracking-widest text-accentMuted font-medium">Corporate — Custom Platform Redesign</span>
                        <h3 class="text-lg font-bold text-white">Apex Logistics Hub</h3>
                        <p class="text-sm text-gray-400">Complete performance re-architecture turning a sluggish legacy system into an optimized framework.</p>
                        <div class="pt-2 text-xs font-bold text-white tracking-wider uppercase flex items-center gap-2">
                            <span>Result: Reduced page weight load times down to 1.2s</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- PACKAGES & PRICING -->
    <section id="pricing" class="py-24 px-6 border-b border-darkBorder max-w-7xl mx-auto">
        <div class="text-center max-w-2xl mx-auto mb-16">
            <h2 class="text-xs uppercase tracking-widest text-accentMuted font-bold mb-3">Investment</h2>
            <p class="text-2xl sm:text-3xl font-bold text-white">Transparent Website Packages</p>
        </div>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Starter -->
            <div class="p-8 bg-darkCard border border-darkBorder flex flex-col justify-between space-y-8">
                <div class="space-y-4">
                    <h3 class="text-lg font-bold text-white uppercase tracking-wider">Starter Package</h3>
                    <p class="text-xs text-gray-400">Essential digital foundation setup for small operations or starting projects.</p>
                    <hr class="border-darkBorder">
                    <ul class="text-sm text-gray-400 space-y-3">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-xs text-white"></i> 1–5 Custom designed pages</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-xs text-white"></i> Mobile responsive architecture</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-xs text-white"></i> Secure contact form configuration</li>
                    </ul>
                </div>
                <a href="#contact" class="w-full text-center py-3 bg-transparent border border-darkBorder text-white text-xs uppercase tracking-wider font-bold hover:border-white transition-all">Get Starter Package</a>
            </div>
            <!-- Business -->
            <div class="p-8 bg-neutral-950 border-2 border-white flex flex-col justify-between space-y-8 relative">
                <span class="absolute -top-3 right-6 bg-white text-black text-[10px] font-black uppercase tracking-widest px-2 py-0.5">Most Popular</span>
                <div class="space-y-4">
                    <h3 class="text-lg font-bold text-white uppercase tracking-wider">Business Package</h3>
                    <p class="text-xs text-gray-400">Perfect infrastructure for scaling businesses requiring constant leads.</p>
                    <hr class="border-darkBorder">
                    <ul class="text-sm text-gray-400 space-y-3">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-xs text-white"></i> Up to 10 Tailored system pages</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-xs text-white"></i> Basic structural Search Engine Optimization</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-xs text-white"></i> Full content management blog system</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-xs text-white"></i> Advanced mobile UI enhancements</li>
                    </ul>
                </div>
                <a href="#contact" class="w-full text-center py-3 bg-white text-black text-xs uppercase tracking-wider font-bold hover:bg-gray-200 transition-all">Select Business Framework</a>
            </div>
            <!-- Premium -->
            <div class="p-8 bg-darkCard border border-darkBorder flex flex-col justify-between space-y-8">
                <div class="space-y-4">
                    <h3 class="text-lg font-bold text-white uppercase tracking-wider">Premium Package</h3>
                    <p class="text-xs text-gray-400">Enterprise grade systems for online retail and intensive integrations.</p>
                    <hr class="border-darkBorder">
                    <ul class="text-sm text-gray-400 space-y-3">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-xs text-white"></i> Unlimited fully tailored custom layout designs</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-xs text-white"></i> Advanced e-commerce capabilities</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-xs text-white"></i> Complete payment processing setup</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-xs text-white"></i> Priority architectural technical support</li>
                    </ul>
                </div>
                <a href="#contact" class="w-full text-center py-3 bg-transparent border border-darkBorder text-white text-xs uppercase tracking-wider font-bold hover:border-white transition-all">Acquire Premium Architecture</a>
            </div>
        </div>
        <div class="mt-12 text-center p-6 border border-dashed border-darkBorder max-w-xl mx-auto">
            <p class="text-sm text-gray-400">Looking for custom API connectivity or specific database builds? <a href="#contact" class="text-white underline font-bold">Request a Custom Quote</a></p>
        </div>
    </section>

    <!-- TESTIMONIALS -->
    <section id="testimonials" class="py-24 px-6 border-b border-darkBorder bg-darkCard/30">
        <div class="max-w-7xl mx-auto">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <h2 class="text-xs uppercase tracking-widest text-accentMuted font-bold mb-3">Validation</h2>
                <p class="text-2xl sm:text-3xl font-bold text-white">Reviews From Satisfied Clients</p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Card 1 -->
                <div class="p-8 bg-darkCard border border-darkBorder space-y-6">
                    <div class="flex text-white gap-1 text-xs"><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i></div>
                    <p class="text-sm text-gray-400 italic leading-relaxed">"The communication structure kept us updated at every major point. Nexa Web Studio delivered our complex corporate site on absolute schedule."</p>
                    <div>
                        <h4 class="text-sm font-bold text-white">Corporate Partner</h4>
                        <span class="text-[11px] text-accentMuted uppercase tracking-wider">Product Operations Executive</span>
                    </div>
                </div>
                <!-- Card 2 -->
                <div class="p-8 bg-darkCard border border-darkBorder space-y-6">
                    <div class="flex text-white gap-1 text-xs"><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i></div>
                    <p class="text-sm text-gray-400 italic leading-relaxed">"Our online store payment integration operates flawlessly. The technical backend structure cleared all past processing drop-offs instantly."</p>
                    <div>
                        <h4 class="text-sm font-bold text-white">E-commerce Brand Owner</h4>
                        <span class="text-[11px] text-accentMuted uppercase tracking-wider">Managing Director</span>
                    </div>
                </div>
                <!-- Card 3 -->
                <div class="p-8 bg-darkCard border border-darkBorder space-y-6">
                    <div class="flex text-white gap-1 text-xs"><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i></div>
                    <p class="text-sm text-gray-400 italic leading-relaxed">"Professionalism at its peak. They completely refreshed our stale digital layout and drastically enhanced local search index conversions."</p>
                    <div>
                        <h4 class="text-sm font-bold text-white">Local Retailer</h4>
                        <span class="text-[11px] text-accentMuted uppercase tracking-wider">Operations Lead</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CONTACT SECTION -->
    <section id="contact" class="py-24 px-6 border-b border-darkBorder max-w-7xl mx-auto">
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-16">
            <div class="space-y-8">
                <div class="space-y-3">
                    <h2 class="text-xs uppercase tracking-widest text-accentMuted font-bold">Initiate Intake</h2>
                    <p class="text-3xl font-extrabold text-white tracking-tight">Let's Build Something High-Performing</p>
                    <p class="text-sm text-gray-400 leading-relaxed max-w-md">Reach out through our direct pipeline channel channels or submit a comprehensive intake parameters message directly.</p>
                </div>
                
                <div class="space-y-4 text-sm text-gray-400">
                    <div class="flex items-center gap-4"><i class="fa-solid fa-envelope text-white w-5"></i> <span>info@nexawebstudio.com</span></div>
                    <div class="flex items-center gap-4"><i class="fa-solid fa-phone text-white w-5"></i> <span>+256 705 981 287</span></div>
                    <div class="flex items-center gap-4"><i class="fa-solid fa-clock text-white w-5"></i> <span>Mon - Fri: 9:00 AM - 6:00 PM (EAT)</span></div>
                </div>

                <div class="pt-4">
                    <a href="https://wa.me/256705981287?text=Hi%20Nexa%20Web%20Studio,%20I%20am%20interested%20in%20a%20professional%20website%20consultation." target="_blank" class="inline-flex items-center gap-3 px-6 py-4 bg-white text-black font-bold text-xs uppercase tracking-wider hover:bg-gray-200 transition-all">
                        <i class="fa-brands fa-whatsapp text-lg"></i> Chat via WhatsApp
                    </a>
                </div>
            </div>

            <!-- Contact Form -->
            <div class="bg-darkCard border border-darkBorder p-8">
                <form class="space-y-6" onsubmit="event.preventDefault(); alert('Consultation request captured! The Nexa team will touch base shortly.');">
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                        <div class="space-y-2">
                            <label class="text-xs uppercase tracking-wider text-gray-400 font-bold">Your Name</label>
                            <input type="text" required class="w-full bg-darkBg border border-darkBorder p-3 text-sm text-white focus:outline-none focus:border-white transition-colors">
                        </div>
                        <div class="space-y-2">
                            <label class="text-xs uppercase tracking-wider text-gray-400 font-bold">Email Address</label>
                            <input type="email" required class="w-full bg-darkBg border border-darkBorder p-3 text-sm text-white focus:outline-none focus:border-white transition-colors">
                        </div>
                    </div>
                    <div class="space-y-2">
                        <label class="text-xs uppercase tracking-wider text-gray-400 font-bold">Select Intended Framework</label>
                        <select class="w-full bg-darkBg border border-darkBorder p-3 text-sm text-white focus:outline-none focus:border-white transition-colors">
                            <option>Starter Framework Package</option>
                            <option>Business Scaling Architecture</option>
                            <option>Premium E-commerce Setup</option>
                            <option>Custom Architectural Integration Quote</option>
                        </select>
                    </div>
                    <div class="space-y-2">
                        <label class="text-xs uppercase tracking-wider text-gray-400 font-bold">Project Details</label>
                        <textarea rows="4" required placeholder="Outline core features needed..." class="w-full bg-darkBg border border-darkBorder p-3 text-sm text-white focus:outline-none focus:border-white transition-colors"></textarea>
                    </div>
                    <button type="submit" class="w-full py-4 bg-transparent border border-white text-white font-bold text-xs uppercase tracking-widest hover:bg-white hover:text-black transition-all">Submit Consultation Intake Form</button>
                </form>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-darkBg py-12 px-6 border-t border-darkBorder text-xs text-gray-500">
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-center gap-6">
            <span class="font-black text-sm tracking-widest text-white uppercase">Nexa<span class="text-accentMuted">.</span></span>
            
            <div class="flex flex-wrap justify-center gap-8 text-gray-400">
                <a href="#home" class="hover:text-white transition-colors">Home</a>
                <a href="#about" class="hover:text-white transition-colors">About</a>
                <a href="#services" class="hover:text-white transition-colors">Services</a>
                <a href="#portfolio" class="hover:text-white transition-colors">Portfolio</a>
                <a href="#pricing" class="hover:text-white transition-colors">Pricing</a>
                <a href="#contact" class="hover:text-white transition-colors">Contact</a>
            </div>

            <div class="flex gap-4 text-sm text-gray-400">
                <a href="#" class="hover:text-white"><i class="fa-brands fa-linkedin"></i></a>
                <a href="#" class="hover:text-white"><i class="fa-brands fa-twitter"></i></a>
                <a href="#" class="hover:text-white"><i class="fa-brands fa-instagram"></i></a>
            </div>
        </div>
        <div class="max-w-7xl mx-auto text-center mt-8 pt-8 border-t border-darkBorder/40 text-[11px] text-gray-600">
            &copy; Nexa Web Studio. All Rights Reserved.
        </div>
    </footer>

    <!-- STICKY FLOATING WHATSAPP CHAT WIDGET -->
    <a href="https://wa.me/256705981287?text=Hi%20Nexa%20Web%20Studio,%20I%20am%20interested%20in%20a%20professional%20website%20consultation." target="_blank" class="fixed bottom-6 right-6 z-50 bg-[#25D366] text-white w-14 h-14 rounded-full flex items-center justify-center text-2xl shadow-xl hover:scale-110 transition-transform duration-300" title="Chat on WhatsApp">
        <i class="fa-brands fa-whatsapp"></i>
    </a>

    <!-- MOBILE NAVIGATION MENU SCRIPT -->
    <script>
        const menuBtn = document.getElementById('menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Close menu instantly upon option link click selection
        document.querySelectorAll('#mobile-menu a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });
    </script>
</body>
</html>
