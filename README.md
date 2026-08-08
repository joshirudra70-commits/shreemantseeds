<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shreemant Seeds | Quality Seeds for Better Farming</title>
    <meta name="description" content="Explore Shreemant Seeds and discover quality seed varieties for farmers and agricultural cultivation. Good harvests begin with the right seed.">
    <meta name="keywords" content="Shreemant Seeds, Paddy seeds, VIP paddy, Shreemant 64, Safari Jaya paddy, Komalika paddy, Indrayani paddy, Indian agriculture, crop cultivation">
    
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;500;600;700;800&family=Poppins:ital,wght@0,300;0,400;0,500;0,600;0,700;1,400&display=swap" rel="stylesheet">
    
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        shreemantRed: '#E31B23',
                        shreemantRedDark: '#B81118',
                        shreemantRedLight: '#FFF0F1',
                        deepEarth: '#3B3028',
                        deepEarthLight: '#4A3D34',
                        naturalGreen: '#4F6F3A',
                        naturalGreenLight: '#658C4A',
                        naturalGreenBg: '#F3F7F0',
                        softWheat: '#E8D9B5',
                        softWheatDark: '#C7B17C',
                        lightCream: '#F8F5ED',
                        creamBorder: '#EADECA'
                    },
                    fontFamily: {
                        sans: ['Poppins', 'sans-serif'],
                        display: ['Outfit', 'sans-serif'],
                    },
                    boxShadow: {
                        'premium': '0 10px 30px -5px rgba(59, 48, 40, 0.08), 0 4px 12px -2px rgba(227, 27, 35, 0.05)',
                        'card': '0 12px 24px -6px rgba(0, 0, 0, 0.06)',
                        'red-glow': '0 8px 25px rgba(227, 27, 35, 0.25)',
                    }
                }
            }
        }
    </script>

    <!-- Custom Utilities & Keyframe Animations -->
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #FFFFFF;
            color: #3B3028;
            overflow-x: hidden;
        }

        h1, h2, h3, h4, h5, h6, .font-display {
            font-family: 'Outfit', sans-serif;
        }

        .paddy-pattern-bg {
            background-image: radial-gradient(#E31B23 0.6px, transparent 0.6px), radial-gradient(#4F6F3A 0.6px, #F8F5ED 0.6px);
            background-size: 24px 24px;
            background-position: 0 0, 12px 12px;
            background-opacity: 0.15;
        }

        .organic-curve-bottom {
            clip-path: ellipse(85% 100% at 50% 0%);
        }

        .organic-curve-top {
            clip-path: ellipse(85% 100% at 50% 100%);
        }

        .gradient-overlay {
            background: linear-gradient(180deg, rgba(255,255,255,0.92) 0%, rgba(255,255,255,0.75) 50%, rgba(255,255,255,0.95) 100%);
        }

        .gradient-dark-overlay {
            background: linear-gradient(180deg, rgba(59,48,40,0.85) 0%, rgba(59,48,40,0.65) 50%, rgba(59,48,40,0.9) 100%);
        }

        .seed-card-hover {
            transition: all 0.35s cubic-bezier(0.16, 1, 0.3, 1);
        }

        .seed-card-hover:hover {
            transform: translateY(-8px);
            box-shadow: 0 20px 35px -10px rgba(59, 48, 40, 0.12), 0 8px 16px -4px rgba(227, 27, 35, 0.1);
        }

        .pulse-subtle {
            animation: pulseSlow 3s infinite ease-in-out;
        }

        @keyframes pulseSlow {
            0%, 100% { transform: scale(1); opacity: 1; }
            50% { transform: scale(1.03); opacity: 0.95; }
        }

        /* Glassmorphism subtle card */
        .glass-card {
            background: rgba(255, 255, 255, 0.88);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(232, 217, 181, 0.5);
        }

        /* Custom scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #F8F5ED;
        }
        ::-webkit-scrollbar-thumb {
            background: #E31B23;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #B81118;
        }
    </style>
</head>
<body class="antialiased text-deepEarth bg-white selection:bg-shreemantRed selection:text-white">

    <!-- Configurable Global Settings Bar for Demo/Testing -->
    <div id="topConfigBar" class="bg-deepEarth text-white text-xs py-1.5 px-4 hidden md:block border-b border-softWheat/20">
        <div class="max-w-7xl mx-auto flex justify-between items-center">
            <div class="flex items-center gap-4">
                <span class="flex items-center gap-1.5 text-softWheat">
                    <svg class="w-3.5 h-3.5 text-shreemantRed" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M5.05 4.05a7 7 0 119.9 9.9L10 18.9l-4.95-4.95a7 7 0 010-9.9zM10 11a2 2 0 100-4 2 2 0 000 4z" clip-rule="evenodd"></path></svg>
                    Trusted Indian Agricultural Seed Company
                </span>
                <span class="text-white/40">|</span>
                <span class="text-white/80">Dedicated Farmer Helpline Available</span>
            </div>
            <div class="flex items-center gap-4">
                <span class="text-white/80">WhatsApp Contact Configured: <span id="currentNumberBadge" class="font-mono text-softWheat bg-white/10 px-2 py-0.5 rounded">919876543210</span></span>
                <button onclick="changeWhatsAppNumber()" class="text-xs text-shreemantRed hover:underline bg-white px-2 py-0.5 rounded font-medium transition">
                    Change Number
                </button>
            </div>
        </div>
    </div>

    <!-- HEADER / NAVIGATION -->
    <header id="mainHeader" class="sticky top-0 z-50 bg-white/95 backdrop-blur-md transition-all duration-300 border-b border-gray-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                
                <!-- Logo -->
                <a href="#home" class="flex items-center gap-3 group">
                    <div class="relative w-12 h-12 rounded-xl bg-shreemantRed flex items-center justify-center text-white font-bold text-2xl shadow-md overflow-hidden group-hover:scale-105 transition-transform duration-300">
                        <!-- Logo Fallback SVG / Embedded Image -->
                        <img id="brandLogoImg" 
                             src="https://lh3.googleusercontent.com/d/1OSOHStl2tijjLdANRen9CpMpl85NBFBn" 
                             alt="Shreemant Seeds Logo" 
                             class="w-full h-full object-contain p-1 bg-white"
                             onerror="this.style.display='none'; document.getElementById('brandLogoFallback').style.display='flex';">
                        <div id="brandLogoFallback" class="hidden w-full h-full bg-shreemantRed flex-col items-center justify-center text-white font-black">
                            <span class="text-xl leading-none">SS</span>
                            <span class="text-[8px] font-sans font-medium tracking-tighter">SEEDS</span>
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <span class="font-display font-extrabold text-2xl tracking-tight text-deepEarth group-hover:text-shreemantRed transition-colors">
                            SHREEMANT <span class="text-shreemantRed">SEEDS</span>
                        </span>
                        <span class="text-[10px] font-medium tracking-widest text-naturalGreen uppercase -mt-1">
                            Quality Seeds • Stronger Crops
                        </span>
                    </div>
                </a>

                <!-- Desktop Navigation Links -->
                <nav class="hidden lg:flex items-center gap-8">
                    <a href="#home" class="text-sm font-semibold text-deepEarth hover:text-shreemantRed transition-colors py-2 relative group">
                        Home
                        <span class="absolute bottom-0 left-0 w-full h-0.5 bg-shreemantRed scale-x-0 group-hover:scale-x-100 transition-transform origin-left"></span>
                    </a>
                    <a href="#about" class="text-sm font-semibold text-deepEarth hover:text-shreemantRed transition-colors py-2 relative group">
                        About Us
                        <span class="absolute bottom-0 left-0 w-full h-0.5 bg-shreemantRed scale-x-0 group-hover:scale-x-100 transition-transform origin-left"></span>
                    </a>
                    <a href="#seeds" class="text-sm font-semibold text-deepEarth hover:text-shreemantRed transition-colors py-2 relative group">
                        Our Seeds
                        <span class="absolute bottom-0 left-0 w-full h-0.5 bg-shreemantRed scale-x-0 group-hover:scale-x-100 transition-transform origin-left"></span>
                    </a>
                    <a href="#why-us" class="text-sm font-semibold text-deepEarth hover:text-shreemantRed transition-colors py-2 relative group">
                        Why Shreemant
                        <span class="absolute bottom-0 left-0 w-full h-0.5 bg-shreemantRed scale-x-0 group-hover:scale-x-100 transition-transform origin-left"></span>
                    </a>
                    <a href="#for-farmers" class="text-sm font-semibold text-deepEarth hover:text-shreemantRed transition-colors py-2 relative group">
                        For Farmers
                        <span class="absolute bottom-0 left-0 w-full h-0.5 bg-shreemantRed scale-x-0 group-hover:scale-x-100 transition-transform origin-left"></span>
                    </a>
                    <a href="#contact" class="text-sm font-semibold text-deepEarth hover:text-shreemantRed transition-colors py-2 relative group">
                        Contact
                        <span class="absolute bottom-0 left-0 w-full h-0.5 bg-shreemantRed scale-x-0 group-hover:scale-x-100 transition-transform origin-left"></span>
                    </a>
                </nav>

                <!-- Header Right CTA -->
                <div class="hidden sm:flex items-center gap-3">
                    <a href="#contact" class="bg-shreemantRed hover:bg-shreemantRedDark text-white font-semibold text-sm px-5 py-2.5 rounded-full shadow-md hover:shadow-lg hover:shadow-shreemantRed/20 transition-all duration-300 flex items-center gap-2 transform active:scale-95">
                        <span>Enquire Now</span>
                        <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
                    </a>
                </div>

                <!-- Mobile Navigation Toggle Button -->
                <button id="mobileMenuBtn" onclick="toggleMobileMenu()" class="lg:hidden p-2.5 rounded-lg text-deepEarth hover:bg-lightCream focus:outline-none" aria-label="Toggle navigation menu">
                    <svg id="menuIcon" class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                    </svg>
                    <svg id="closeIcon" class="w-6 h-6 hidden" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
                    </svg>
                </button>

            </div>
        </div>

        <!-- Mobile Menu Overlay -->
        <div id="mobileMenu" class="hidden lg:hidden bg-white border-b border-gray-200 px-4 pt-2 pb-6 space-y-3">
            <a href="#home" onclick="toggleMobileMenu()" class="block px-3 py-2 rounded-lg font-medium text-deepEarth hover:bg-lightCream hover:text-shreemantRed">Home</a>
            <a href="#about" onclick="toggleMobileMenu()" class="block px-3 py-2 rounded-lg font-medium text-deepEarth hover:bg-lightCream hover:text-shreemantRed">About Us</a>
            <a href="#seeds" onclick="toggleMobileMenu()" class="block px-3 py-2 rounded-lg font-medium text-deepEarth hover:bg-lightCream hover:text-shreemantRed">Our Seeds</a>
            <a href="#why-us" onclick="toggleMobileMenu()" class="block px-3 py-2 rounded-lg font-medium text-deepEarth hover:bg-lightCream hover:text-shreemantRed">Why Shreemant</a>
            <a href="#for-farmers" onclick="toggleMobileMenu()" class="block px-3 py-2 rounded-lg font-medium text-deepEarth hover:bg-lightCream hover:text-shreemantRed">For Farmers</a>
            <a href="#contact" onclick="toggleMobileMenu()" class="block px-3 py-2 rounded-lg font-medium text-deepEarth hover:bg-lightCream hover:text-shreemantRed">Contact</a>
            <div class="pt-2">
                <a href="#contact" onclick="toggleMobileMenu()" class="w-full text-center block bg-shreemantRed text-white font-semibold py-3 rounded-xl shadow">
                    Enquire Now
                </a>
            </div>
        </div>
    </header>

    <!-- HERO SECTION -->
    <section id="home" class="relative min-h-[85vh] lg:min-h-[90vh] flex items-center justify-center overflow-hidden bg-lightCream">
        <!-- Background Paddy Image with Subtle Overlay -->
        <div class="absolute inset-0 z-0">
            <img src="https://images.unsplash.com/photo-1500937386664-56d1dfef3854?auto=format&fit=crop&q=80&w=2000" 
                 alt="Shreemant Seeds lush paddy field in India" 
                 class="w-full h-full object-cover object-center transform scale-105 hover:scale-100 transition-transform duration-1000">
            <!-- White Gradient Overlay ensuring text legibility while showing paddy field -->
            <div class="absolute inset-0 bg-gradient-to-r from-white/95 via-white/85 to-white/60 md:to-transparent"></div>
            <div class="absolute inset-0 bg-gradient-to-t from-white via-transparent to-transparent"></div>
        </div>

        <!-- Subtle Seed & Agricultural Shape Overlays -->
        <div class="absolute top-10 right-10 opacity-10 pointer-events-none hidden md:block">
            <svg class="w-96 h-96 text-shreemantRed" fill="currentColor" viewBox="0 0 100 100">
                <path d="M50,10 Q80,50 50,90 Q20,50 50,10 Z" />
            </svg>
        </div>

        <div class="relative z-10 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16 md:py-24">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                
                <!-- Hero Left Content -->
                <div class="lg:col-span-7 space-y-6">
                    
                    <!-- Small Label Badge -->
                    <div class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-shreemantRedLight border border-shreemantRed/20 text-shreemantRed font-semibold text-xs md:text-sm tracking-wider uppercase shadow-sm">
                        <span class="w-2 h-2 rounded-full bg-shreemantRed animate-ping"></span>
                        QUALITY SEEDS • STRONGER CROPS
                    </div>

                    <!-- Main Headline -->
                    <h1 class="font-display font-extrabold text-4xl sm:text-5xl lg:text-6xl text-deepEarth leading-[1.15] tracking-tight">
                        Good Harvests Begin <br class="hidden sm:inline">
                        <span class="text-shreemantRed relative inline-block">
                            With the Right Seed.
                            <svg class="absolute -bottom-2 left-0 w-full h-3 text-softWheat" viewBox="0 0 100 20" preserveAspectRatio="none">
                                <path d="M0,10 Q50,20 100,10" stroke="currentColor" stroke-width="4" fill="none" stroke-linecap="round"/>
                            </svg>
                        </span>
                    </h1>

                    <!-- Supporting Text -->
                    <p class="text-lg md:text-xl text-deepEarth/80 max-w-2xl font-normal leading-relaxed">
                        Quality seed varieties for farmers who believe in better cultivation, stronger crops, and a more productive agricultural future.
                    </p>

                    <!-- CTAs -->
                    <div class="flex flex-col sm:flex-row gap-4 pt-4">
                        <!-- Primary Red CTA -->
                        <a href="#seeds" class="inline-flex items-center justify-center gap-3 bg-shreemantRed hover:bg-shreemantRedDark text-white font-bold text-base px-8 py-4 rounded-xl shadow-lg shadow-shreemantRed/25 hover:shadow-xl hover:shadow-shreemantRed/30 transition-all duration-300 transform hover:-translate-y-0.5">
                            <span>EXPLORE OUR SEEDS</span>
                            <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
                        </a>

                        <!-- Secondary WhatsApp Button -->
                        <button onclick="triggerWhatsAppEnquiry('General Seed Inquiry')" class="inline-flex items-center justify-center gap-3 bg-white hover:bg-naturalGreenBg border-2 border-naturalGreen/30 text-naturalGreen font-bold text-base px-8 py-4 rounded-xl shadow-md hover:border-naturalGreen transition-all duration-300 transform hover:-translate-y-0.5 group">
                            <svg class="w-6 h-6 fill-current text-naturalGreen group-hover:scale-110 transition-transform" viewBox="0 0 24 24">
                                <path d="M.057 24l1.687-6.163c-1.041-1.804-1.588-3.849-1.587-5.946.003-6.556 5.338-11.891 11.893-11.891 3.181.001 6.167 1.24 8.413 3.488 2.245 2.248 3.481 5.236 3.48 8.414-.003 6.557-5.338 11.892-11.893 11.892-1.99-.001-3.951-.5-5.688-1.448l-6.305 1.654zm6.597-3.807c1.676.995 3.276 1.591 5.392 1.592 5.448 0 9.886-4.434 9.889-9.885.002-5.462-4.415-9.89-9.881-9.892-5.452 0-9.887 4.434-9.889 9.884-.001 2.225.651 3.891 1.746 5.634l-.999 3.648 3.742-.981zm11.387-5.464c-.074-.124-.272-.198-.57-.347-.297-.149-1.758-.868-2.031-.967-.272-.099-.47-.149-.669.149-.198.297-.768.967-.941 1.165-.173.198-.347.223-.644.074-.297-.149-1.255-.462-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.297-.347.446-.521.151-.172.2-.296.3-.495.099-.198.05-.372-.025-.521-.075-.148-.669-1.611-.916-2.206-.242-.579-.487-.501-.669-.51l-.57-.01c-.198 0-.52.074-.792.372s-1.04 1.016-1.04 2.479 1.065 2.876 1.213 3.074c.149.198 2.095 3.2 5.076 4.487.709.306 1.263.489 1.694.626.712.226 1.36.194 1.872.118.572-.085 1.758-.719 2.006-1.413.248-.695.248-1.29.173-1.414z"/>
                            </svg>
                            <span>ENQUIRE ON WHATSAPP</span>
                        </button>
                    </div>

                    <!-- Small Farmer Rating & Trust Marker -->
                    <div class="pt-6 flex items-center gap-6 border-t border-deepEarth/10">
                        <div class="flex items-center gap-2">
                            <div class="flex text-amber-500">
                                ★★★★★
                            </div>
                            <span class="text-sm font-semibold text-deepEarth">4.9 / 5</span>
                        </div>
                        <div class="text-xs text-deepEarth/70 font-medium">
                            🌾 Trusted by thousands of Indian Paddy Farmers
                        </div>
                    </div>

                </div>

                <!-- Hero Right Visual Card -->
                <div class="lg:col-span-5 relative">
                    <div class="relative mx-auto max-w-md lg:max-w-none">
                        <!-- Frame Styling -->
                        <div class="absolute -inset-4 rounded-3xl bg-gradient-to-tr from-shreemantRed/20 via-softWheat/40 to-naturalGreen/20 blur-xl"></div>
                        <div class="relative bg-white p-4 rounded-3xl shadow-premium border border-creamBorder">
                            <div class="relative h-96 sm:h-[420px] rounded-2xl overflow-hidden group">
                                <img src="https://images.unsplash.com/photo-1586771107445-d3ca888129ff?auto=format&fit=crop&q=80&w=1000" 
                                     alt="Indian paddy seed crop cultivation" 
                                     class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700">
                                <div class="absolute inset-0 bg-gradient-to-t from-deepEarth/80 via-transparent to-transparent"></div>
                                
                                <div class="absolute bottom-6 left-6 right-6 text-white space-y-1">
                                    <span class="inline-block bg-shreemantRed text-white text-[11px] font-bold px-3 py-1 rounded-full uppercase tracking-wider">
                                        Featured Variety
                                    </span>
                                    <h3 class="font-display font-bold text-2xl text-white">V.I.P. Paddy Seeds</h3>
                                    <p class="text-xs text-softWheat line-clamp-2">Engineered for higher grain count, robust stems, and dependable harvest yield across seasons.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- AGRICULTURAL TRUST STRIP -->
    <section class="bg-deepEarth text-white py-8 border-y-4 border-shreemantRed shadow-inner">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-6 text-center md:text-left">
                
                <!-- Trust Item 1 -->
                <div class="flex flex-col md:flex-row items-center gap-3 p-3 rounded-xl hover:bg-white/5 transition-colors">
                    <div class="w-12 h-12 rounded-full bg-shreemantRed/20 border border-shreemantRed/40 flex items-center justify-center text-2xl shrink-0">
                        🌱
                    </div>
                    <div>
                        <h4 class="font-display font-bold text-base text-softWheat">Quality Focus</h4>
                        <p class="text-xs text-gray-300">Rigorous seed testing & high germination focus</p>
                    </div>
                </div>

                <!-- Trust Item 2 -->
                <div class="flex flex-col md:flex-row items-center gap-3 p-3 rounded-xl hover:bg-white/5 transition-colors">
                    <div class="w-12 h-12 rounded-full bg-naturalGreen/20 border border-naturalGreen/40 flex items-center justify-center text-2xl shrink-0">
                        🌾
                    </div>
                    <div>
                        <h4 class="font-display font-bold text-base text-softWheat">Paddy Seed Varieties</h4>
                        <p class="text-xs text-gray-300">Specially selected for regional paddy climates</p>
                    </div>
                </div>

                <!-- Trust Item 3 -->
                <div class="flex flex-col md:flex-row items-center gap-3 p-3 rounded-xl hover:bg-white/5 transition-colors">
                    <div class="w-12 h-12 rounded-full bg-shreemantRed/20 border border-shreemantRed/40 flex items-center justify-center text-2xl shrink-0">
                        👨‍🌾
                    </div>
                    <div>
                        <h4 class="font-display font-bold text-base text-softWheat">Farmer Focused</h4>
                        <p class="text-xs text-gray-300">Committed to maximizing farmer profitability</p>
                    </div>
                </div>

                <!-- Trust Item 4 -->
                <div class="flex flex-col md:flex-row items-center gap-3 p-3 rounded-xl hover:bg-white/5 transition-colors">
                    <div class="w-12 h-12 rounded-full bg-naturalGreen/20 border border-naturalGreen/40 flex items-center justify-center text-2xl shrink-0">
                        🌱
                    </div>
                    <div>
                        <h4 class="font-display font-bold text-base text-softWheat">Cultivation Support</h4>
                        <p class="text-xs text-gray-300">Guidance from seed sowing to harvest</p>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ABOUT SECTION -->
    <section id="about" class="py-20 bg-white relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                
                <!-- Left Column - Visual Imagery -->
                <div class="lg:col-span-6 relative">
                    <div class="relative">
                        <!-- Main Paddy Image -->
                        <div class="rounded-3xl overflow-hidden shadow-2xl border-4 border-lightCream">
                            <img src="https://images.unsplash.com/photo-1592982537447-7440770cbfc9?auto=format&fit=crop&q=80&w=1000" 
                                 alt="Farmer holding healthy paddy seeds and rice grain" 
                                 class="w-full h-[450px] object-cover hover:scale-105 transition-transform duration-700">
                        </div>

                        <!-- Floating Accent Card -->
                        <div class="absolute -bottom-6 -right-6 md:bottom-8 md:-right-8 bg-lightCream border-2 border-softWheat p-5 rounded-2xl shadow-xl max-w-xs hidden sm:block">
                            <div class="flex items-center gap-3 mb-2">
                                <span class="text-3xl">🌾</span>
                                <span class="font-display font-bold text-lg text-deepEarth">Agricultural Roots</span>
                            </div>
                            <p class="text-xs text-deepEarth/80">
                                Working side-by-side with Indian farmers to cultivate stronger paddy crops and sustainable yields.
                            </p>
                        </div>

                        <!-- Badge Overlay -->
                        <div class="absolute top-6 left-6 bg-shreemantRed text-white px-4 py-2 rounded-xl font-display font-bold text-sm shadow-md">
                            TRUSTED SEED QUALITY
                        </div>
                    </div>
                </div>

                <!-- Right Column - About Content -->
                <div class="lg:col-span-6 space-y-6">
                    <div>
                        <span class="text-shreemantRed font-bold text-xs uppercase tracking-widest bg-shreemantRedLight px-3 py-1 rounded-md">
                            GROWING WITH FARMERS
                        </span>
                        <h2 class="font-display font-extrabold text-3xl sm:text-4xl text-deepEarth mt-3 leading-tight">
                            From a Small Seed to a <span class="text-shreemantRed">Stronger Harvest.</span>
                        </h2>
                    </div>

                    <p class="text-base md:text-lg text-deepEarth/80 leading-relaxed font-normal">
                        <strong>Shreemant Seeds</strong> is committed to providing quality seed solutions for farmers and agricultural communities. Our focus is on offering reliable seed varieties while helping farmers make informed choices for their cultivation needs.
                    </p>

                    <p class="text-sm md:text-base text-deepEarth/70 leading-relaxed">
                        We believe that agriculture is the backbone of the nation. By combining seed selection expertise with a deep understanding of soil conditions, climate resilience, and farmer requirements, we strive to deliver seeds that foster confidence at sowing time and satisfaction at harvest time.
                    </p>

                    <!-- Three Core Highlights -->
                    <div class="grid grid-cols-1 sm:grid-cols-3 gap-4 pt-4">
                        
                        <!-- Highlight 1 -->
                        <div class="p-4 rounded-2xl bg-lightCream border border-creamBorder hover:border-shreemantRed/40 transition-colors">
                            <div class="w-10 h-10 rounded-lg bg-shreemantRed text-white font-bold flex items-center justify-center mb-3">
                                Q
                            </div>
                            <h3 class="font-display font-bold text-base text-deepEarth mb-1">QUALITY</h3>
                            <p class="text-xs text-deepEarth/70">Focused on rigorous seed cleanliness and high germination standard.</p>
                        </div>

                        <!-- Highlight 2 -->
                        <div class="p-4 rounded-2xl bg-lightCream border border-creamBorder hover:border-shreemantRed/40 transition-colors">
                            <div class="w-10 h-10 rounded-lg bg-naturalGreen text-white font-bold flex items-center justify-center mb-3">
                                R
                            </div>
                            <h3 class="font-display font-bold text-base text-deepEarth mb-1">RELIABILITY</h3>
                            <p class="text-xs text-deepEarth/70">Products selected with consistency and weather tolerance in mind.</p>
                        </div>

                        <!-- Highlight 3 -->
                        <div class="p-4 rounded-2xl bg-lightCream border border-creamBorder hover:border-shreemantRed/40 transition-colors">
                            <div class="w-10 h-10 rounded-lg bg-deepEarth text-white font-bold flex items-center justify-center mb-3">
                                F
                            </div>
                            <h3 class="font-display font-bold text-base text-deepEarth mb-1">FARMER FIRST</h3>
                            <p class="text-xs text-deepEarth/70">Built directly around real ground farming requirements.</p>
                        </div>

                    </div>

                    <!-- Read More Action -->
                    <div class="pt-2">
                        <a href="#seeds" class="inline-flex items-center gap-2 text-shreemantRed font-bold hover:underline group text-sm">
                            <span>Explore our complete paddy seed catalog</span>
                            <svg class="w-4 h-4 group-hover:translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
                        </a>
                    </div>

                </div>

            </div>
        </div>
    </section>

    <!-- SEED PRODUCTS SECTION -->
    <section id="seeds" class="py-24 bg-lightCream relative paddy-pattern-bg">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            
            <!-- Section Header -->
            <div class="text-center max-w-3xl mx-auto space-y-4 mb-16">
                <span class="text-shreemantRed font-bold text-xs uppercase tracking-widest bg-white px-4 py-1.5 rounded-full border border-shreemantRed/20 shadow-sm">
                    OUR SEED VARIETIES
                </span>
                <h2 class="font-display font-extrabold text-3xl sm:text-4xl lg:text-5xl text-deepEarth">
                    Choose the Right Seed for Your Crop
                </h2>
                <p class="text-base sm:text-lg text-deepEarth/80">
                    Explore our range of premium seed varieties specifically developed for agricultural cultivation, superior tiller formation, and high harvest recovery.
                </p>
            </div>

            <!-- Product Cards Grid (5 Products Specified) -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">

                <!-- 1. V.I.P. Paddy -->
                <div class="bg-white rounded-3xl overflow-hidden shadow-card seed-card-hover border border-creamBorder flex flex-col justify-between relative group">
                    <div class="absolute top-4 right-4 z-20 bg-shreemantRed text-white text-[10px] font-bold uppercase tracking-wider px-3 py-1 rounded-full shadow">
                        High Yield Premium
                    </div>
                    
                    <div>
                        <!-- Packaging Image Container -->
                        <div class="relative h-64 bg-gradient-to-b from-gray-50 to-white p-6 flex items-center justify-center overflow-hidden border-b border-gray-100">
                            <!-- Background Paddy Graphic -->
                            <div class="absolute inset-0 opacity-10 bg-[radial-gradient(#4F6F3A_1px,transparent_1px)] [background-size:12px_12px]"></div>
                            
                            <!-- Packaging Artwork Display -->
                            <img src="https://lh3.googleusercontent.com/d/1MyAEOQ2ZU1ROw2ZvRrz_cAoVTCKd8Qg6" 
                                 alt="Shreemant Seeds V.I.P. Paddy seed packet" 
                                 class="max-h-52 object-contain group-hover:scale-110 transition-transform duration-500 drop-shadow-xl"
                                 onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                            
                            <!-- Custom Rendered Seed Packet Fallback if Drive image is loading -->
                            <div class="hidden w-44 h-56 bg-shreemantRed rounded-2xl p-3 text-white flex-col justify-between shadow-2xl border-2 border-white relative overflow-hidden">
                                <div class="absolute top-0 right-0 w-16 h-16 bg-white/10 rounded-full -mr-8 -mt-8"></div>
                                <div class="text-center border-b border-white/30 pb-2">
                                    <span class="text-[9px] uppercase tracking-widest text-softWheat">SHREEMANT SEEDS</span>
                                    <h4 class="font-display font-extrabold text-lg leading-tight">V.I.P. PADDY</h4>
                                </div>
                                <div class="text-center my-auto">
                                    <span class="text-4xl block">🌾</span>
                                    <span class="text-[10px] font-semibold bg-white text-shreemantRed px-2 py-0.5 rounded-full mt-1 inline-block">HYBRID QUALITY</span>
                                </div>
                                <div class="text-center text-[9px] text-white/80 border-t border-white/20 pt-1">
                                    Net Weight: 3 kg / 10 kg
                                </div>
                            </div>
                        </div>

                        <!-- Product Information Body -->
                        <div class="p-6 space-y-3">
                            <div class="flex justify-between items-start">
                                <div>
                                    <span class="text-xs font-semibold text-naturalGreen uppercase tracking-wider">Paddy Seed • Medium Grain</span>
                                    <h3 class="font-display font-bold text-2xl text-deepEarth group-hover:text-shreemantRed transition-colors">V.I.P. Paddy</h3>
                                </div>
                            </div>
                            
                            <p class="text-xs md:text-sm text-deepEarth/75 leading-relaxed">
                                High yielding paddy variety with uniform grain ripening, sturdy stalk resilience against lodging, and excellent cooking quality.
                            </p>

                            <!-- Quick Specs Tags -->
                            <div class="flex flex-wrap gap-1.5 pt-2">
                                <span class="text-[11px] bg-lightCream text-deepEarth px-2.5 py-1 rounded-md font-medium border border-creamBorder">⏱ 125-130 Days</span>
                                <span class="text-[11px] bg-lightCream text-deepEarth px-2.5 py-1 rounded-md font-medium border border-creamBorder">🌾 High Tillering</span>
                                <span class="text-[11px] bg-naturalGreenBg text-naturalGreen px-2.5 py-1 rounded-md font-medium">✨ Premium Grain</span>
                            </div>
                        </div>
                    </div>

                    <!-- Action Buttons -->
                    <div class="p-6 pt-0 space-y-2">
                        <div class="grid grid-cols-2 gap-2">
                            <button onclick="openProductModal('VIP Paddy', 'V.I.P. Paddy', 'High Yield Premium', '125-130 Days', 'Medium Long Slender', 'High yield paddy variety with uniform grain ripening, sturdy stalk resilience against lodging, and excellent cooking quality.', 'https://lh3.googleusercontent.com/d/1MyAEOQ2ZU1ROw2ZvRrz_cAoVTCKd8Qg6')" class="w-full text-center text-xs font-bold text-deepEarth bg-lightCream hover:bg-softWheat/50 py-3 rounded-xl border border-softWheat transition-colors">
                                View Details
                            </button>
                            <button onclick="enquireProductWhatsApp('V.I.P. Paddy')" class="w-full text-center text-xs font-bold text-white bg-shreemantRed hover:bg-shreemantRedDark py-3 rounded-xl shadow-md transition-colors flex items-center justify-center gap-1">
                                <span>ORDER NOW</span>
                            </button>
                        </div>
                        <button onclick="enquireProductWhatsApp('V.I.P. Paddy')" class="w-full text-center text-xs font-medium text-naturalGreen hover:text-naturalGreenDark py-1.5 flex items-center justify-center gap-1.5 transition-colors">
                            <span>💬 Enquire on WhatsApp</span>
                        </button>
                    </div>
                </div>

                <!-- 2. SHREEMANT-64 Paddy -->
                <div class="bg-white rounded-3xl overflow-hidden shadow-card seed-card-hover border border-creamBorder flex flex-col justify-between relative group">
                    <div class="absolute top-4 right-4 z-20 bg-naturalGreen text-white text-[10px] font-bold uppercase tracking-wider px-3 py-1 rounded-full shadow">
                        Flagship Variety
                    </div>
                    
                    <div>
                        <!-- Packaging Image Container -->
                        <div class="relative h-64 bg-gradient-to-b from-gray-50 to-white p-6 flex items-center justify-center overflow-hidden border-b border-gray-100">
                            <div class="absolute inset-0 opacity-10 bg-[radial-gradient(#E31B23_1px,transparent_1px)] [background-size:12px_12px]"></div>
                            
                            <img src="https://lh3.googleusercontent.com/d/1MyAEOQ2ZU1ROw2ZvRrz_cAoVTCKd8Qg6" 
                                 alt="Shreemant Seeds SHREEMANT-64 Paddy seed packet" 
                                 class="max-h-52 object-contain group-hover:scale-110 transition-transform duration-500 drop-shadow-xl"
                                 onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                            
                            <div class="hidden w-44 h-56 bg-deepEarth rounded-2xl p-3 text-white flex-col justify-between shadow-2xl border-2 border-softWheat relative overflow-hidden">
                                <div class="text-center border-b border-softWheat/30 pb-2">
                                    <span class="text-[9px] uppercase tracking-widest text-softWheat">SHREEMANT SEEDS</span>
                                    <h4 class="font-display font-extrabold text-base leading-tight">SHREEMANT-64</h4>
                                </div>
                                <div class="text-center my-auto">
                                    <span class="text-4xl block">🌱</span>
                                    <span class="text-[10px] font-semibold bg-shreemantRed text-white px-2 py-0.5 rounded-full mt-1 inline-block">BESTSELLER</span>
                                </div>
                                <div class="text-center text-[9px] text-white/80 border-t border-white/20 pt-1">
                                    Net Weight: 3 kg / 10 kg
                                </div>
                            </div>
                        </div>

                        <!-- Product Info -->
                        <div class="p-6 space-y-3">
                            <div>
                                <span class="text-xs font-semibold text-naturalGreen uppercase tracking-wider">Paddy Seed • Commercial Yield</span>
                                <h3 class="font-display font-bold text-2xl text-deepEarth group-hover:text-shreemantRed transition-colors">SHREEMANT-64 Paddy</h3>
                            </div>
                            
                            <p class="text-xs md:text-sm text-deepEarth/75 leading-relaxed">
                                Brand flagship paddy seed developed for high stress tolerance, robust root system, and dense panicle grain fill.
                            </p>

                            <div class="flex flex-wrap gap-1.5 pt-2">
                                <span class="text-[11px] bg-lightCream text-deepEarth px-2.5 py-1 rounded-md font-medium border border-creamBorder">⏱ 130-135 Days</span>
                                <span class="text-[11px] bg-lightCream text-deepEarth px-2.5 py-1 rounded-md font-medium border border-creamBorder">🛡 Pest Resilient</span>
                                <span class="text-[11px] bg-shreemantRedLight text-shreemantRed px-2.5 py-1 rounded-md font-medium">🔥 Heavy Harvester</span>
                            </div>
                        </div>
                    </div>

                    <!-- Action Buttons -->
                    <div class="p-6 pt-0 space-y-2">
                        <div class="grid grid-cols-2 gap-2">
                            <button onclick="openProductModal('SHREEMANT-64', 'SHREEMANT-64 Paddy', 'Flagship Variety', '130-135 Days', 'Long Fine Grain', 'Brand flagship paddy seed developed for high stress tolerance, robust root system, and dense panicle grain fill across varied soil types.', 'https://lh3.googleusercontent.com/d/1MyAEOQ2ZU1ROw2ZvRrz_cAoVTCKd8Qg6')" class="w-full text-center text-xs font-bold text-deepEarth bg-lightCream hover:bg-softWheat/50 py-3 rounded-xl border border-softWheat transition-colors">
                                View Details
                            </button>
                            <button onclick="enquireProductWhatsApp('SHREEMANT-64')" class="w-full text-center text-xs font-bold text-white bg-shreemantRed hover:bg-shreemantRedDark py-3 rounded-xl shadow-md transition-colors flex items-center justify-center gap-1">
                                <span>ORDER NOW</span>
                            </button>
                        </div>
                        <button onclick="enquireProductWhatsApp('SHREEMANT-64')" class="w-full text-center text-xs font-medium text-naturalGreen hover:text-naturalGreenDark py-1.5 flex items-center justify-center gap-1.5 transition-colors">
                            <span>💬 Enquire on WhatsApp</span>
                        </button>
                    </div>
                </div>

                <!-- 3. Safari Jaya Paddy -->
                <div class="bg-white rounded-3xl overflow-hidden shadow-card seed-card-hover border border-creamBorder flex flex-col justify-between relative group">
                    <div class="absolute top-4 right-4 z-20 bg-deepEarth text-white text-[10px] font-bold uppercase tracking-wider px-3 py-1 rounded-full shadow">
                        Versatile Growth
                    </div>
                    
                    <div>
                        <div class="relative h-64 bg-gradient-to-b from-gray-50 to-white p-6 flex items-center justify-center overflow-hidden border-b border-gray-100">
                            <div class="absolute inset-0 opacity-10 bg-[radial-gradient(#3B3028_1px,transparent_1px)] [background-size:12px_12px]"></div>
                            
                            <img src="https://lh3.googleusercontent.com/d/1MyAEOQ2ZU1ROw2ZvRrz_cAoVTCKd8Qg6" 
                                 alt="Shreemant Seeds Safari Jaya Paddy seed packet" 
                                 class="max-h-52 object-contain group-hover:scale-110 transition-transform duration-500 drop-shadow-xl"
                                 onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                            
                            <div class="hidden w-44 h-56 bg-naturalGreen rounded-2xl p-3 text-white flex-col justify-between shadow-2xl border-2 border-white relative overflow-hidden">
                                <div class="text-center border-b border-white/30 pb-2">
                                    <span class="text-[9px] uppercase tracking-widest text-softWheat">SHREEMANT SEEDS</span>
                                    <h4 class="font-display font-extrabold text-base leading-tight">SAFARI JAYA</h4>
                                </div>
                                <div class="text-center my-auto">
                                    <span class="text-4xl block">🌾</span>
                                    <span class="text-[10px] font-semibold bg-white text-naturalGreen px-2 py-0.5 rounded-full mt-1 inline-block">HIGH RESILIENCE</span>
                                </div>
                                <div class="text-center text-[9px] text-white/80 border-t border-white/20 pt-1">
                                    Net Weight: 3 kg / 10 kg
                                </div>
                            </div>
                        </div>

                        <div class="p-6 space-y-3">
                            <div>
                                <span class="text-xs font-semibold text-naturalGreen uppercase tracking-wider">Paddy Seed • Bold Grain</span>
                                <h3 class="font-display font-bold text-2xl text-deepEarth group-hover:text-shreemantRed transition-colors">Safari Jaya Paddy</h3>
                            </div>
                            
                            <p class="text-xs md:text-sm text-deepEarth/75 leading-relaxed">
                                Highly adaptable traditional favorite seed offering excellent disease resistance and consistent yield in varied agro-climatic conditions.
                            </p>

                            <div class="flex flex-wrap gap-1.5 pt-2">
                                <span class="text-[11px] bg-lightCream text-deepEarth px-2.5 py-1 rounded-md font-medium border border-creamBorder">⏱ 120-125 Days</span>
                                <span class="text-[11px] bg-lightCream text-deepEarth px-2.5 py-1 rounded-md font-medium border border-creamBorder">💪 Non-Lodging</span>
                                <span class="text-[11px] bg-naturalGreenBg text-naturalGreen px-2.5 py-1 rounded-md font-medium">🌾 Bold Grain</span>
                            </div>
                        </div>
                    </div>

                    <div class="p-6 pt-0 space-y-2">
                        <div class="grid grid-cols-2 gap-2">
                            <button onclick="openProductModal('Safari Jaya', 'Safari Jaya Paddy', 'Versatile Growth', '120-125 Days', 'Bold Heavy Grain', 'Highly adaptable traditional favorite seed offering excellent disease resistance and consistent yield in varied agro-climatic conditions.', 'https://lh3.googleusercontent.com/d/1MyAEOQ2ZU1ROw2ZvRrz_cAoVTCKd8Qg6')" class="w-full text-center text-xs font-bold text-deepEarth bg-lightCream hover:bg-softWheat/50 py-3 rounded-xl border border-softWheat transition-colors">
                                View Details
                            </button>
                            <button onclick="enquireProductWhatsApp('Safari Jaya')" class="w-full text-center text-xs font-bold text-white bg-shreemantRed hover:bg-shreemantRedDark py-3 rounded-xl shadow-md transition-colors flex items-center justify-center gap-1">
                                <span>ORDER NOW</span>
                            </button>
                        </div>
                        <button onclick="enquireProductWhatsApp('Safari Jaya')" class="w-full text-center text-xs font-medium text-naturalGreen hover:text-naturalGreenDark py-1.5 flex items-center justify-center gap-1.5 transition-colors">
                            <span>💬 Enquire on WhatsApp</span>
                        </button>
                    </div>
                </div>

                <!-- 4. Komalika Paddy -->
                <div class="bg-white rounded-3xl overflow-hidden shadow-card seed-card-hover border border-creamBorder flex flex-col justify-between relative group">
                    <div class="absolute top-4 right-4 z-20 bg-shreemantRed text-white text-[10px] font-bold uppercase tracking-wider px-3 py-1 rounded-full shadow">
                        Fine Grain Quality
                    </div>
                    
                    <div>
                        <div class="relative h-64 bg-gradient-to-b from-gray-50 to-white p-6 flex items-center justify-center overflow-hidden border-b border-gray-100">
                            <div class="absolute inset-0 opacity-10 bg-[radial-gradient(#4F6F3A_1px,transparent_1px)] [background-size:12px_12px]"></div>
                            
                            <img src="https://lh3.googleusercontent.com/d/1MyAEOQ2ZU1ROw2ZvRrz_cAoVTCKd8Qg6" 
                                 alt="Shreemant Seeds Komalika Paddy seed packet" 
                                 class="max-h-52 object-contain group-hover:scale-110 transition-transform duration-500 drop-shadow-xl"
                                 onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                            
                            <div class="hidden w-44 h-56 bg-shreemantRed rounded-2xl p-3 text-white flex-col justify-between shadow-2xl border-2 border-white relative overflow-hidden">
                                <div class="text-center border-b border-white/30 pb-2">
                                    <span class="text-[9px] uppercase tracking-widest text-softWheat">SHREEMANT SEEDS</span>
                                    <h4 class="font-display font-extrabold text-base leading-tight">KOMALIKA</h4>
                                </div>
                                <div class="text-center my-auto">
                                    <span class="text-4xl block">✨</span>
                                    <span class="text-[10px] font-semibold bg-white text-shreemantRed px-2 py-0.5 rounded-full mt-1 inline-block">SUPER FINE</span>
                                </div>
                                <div class="text-center text-[9px] text-white/80 border-t border-white/20 pt-1">
                                    Net Weight: 3 kg / 10 kg
                                </div>
                            </div>
                        </div>

                        <div class="p-6 space-y-3">
                            <div>
                                <span class="text-xs font-semibold text-naturalGreen uppercase tracking-wider">Paddy Seed • Fine Grain</span>
                                <h3 class="font-display font-bold text-2xl text-deepEarth group-hover:text-shreemantRed transition-colors">Komalika Paddy</h3>
                            </div>
                            
                            <p class="text-xs md:text-sm text-deepEarth/75 leading-relaxed">
                                Premium fine grain paddy seed valued for high market price realization, slender length, and minimal milling breakage.
                            </p>

                            <div class="flex flex-wrap gap-1.5 pt-2">
                                <span class="text-[11px] bg-lightCream text-deepEarth px-2.5 py-1 rounded-md font-medium border border-creamBorder">⏱ 135-140 Days</span>
                                <span class="text-[11px] bg-lightCream text-deepEarth px-2.5 py-1 rounded-md font-medium border border-creamBorder">🍚 Low Broken Grain</span>
                                <span class="text-[11px] bg-shreemantRedLight text-shreemantRed px-2.5 py-1 rounded-md font-medium">💎 High Market Price</span>
                            </div>
                        </div>
                    </div>

                    <div class="p-6 pt-0 space-y-2">
                        <div class="grid grid-cols-2 gap-2">
                            <button onclick="openProductModal('Komalika', 'Komalika Paddy', 'Fine Grain Quality', '135-140 Days', 'Super Fine Slender', 'Premium fine grain paddy seed valued for high market price realization, slender length, and minimal milling breakage.', 'https://lh3.googleusercontent.com/d/1MyAEOQ2ZU1ROw2ZvRrz_cAoVTCKd8Qg6')" class="w-full text-center text-xs font-bold text-deepEarth bg-lightCream hover:bg-softWheat/50 py-3 rounded-xl border border-softWheat transition-colors">
                                View Details
                            </button>
                            <button onclick="enquireProductWhatsApp('Komalika')" class="w-full text-center text-xs font-bold text-white bg-shreemantRed hover:bg-shreemantRedDark py-3 rounded-xl shadow-md transition-colors flex items-center justify-center gap-1">
                                <span>ORDER NOW</span>
                            </button>
                        </div>
                        <button onclick="enquireProductWhatsApp('Komalika')" class="w-full text-center text-xs font-medium text-naturalGreen hover:text-naturalGreenDark py-1.5 flex items-center justify-center gap-1.5 transition-colors">
                            <span>💬 Enquire on WhatsApp</span>
                        </button>
                    </div>
                </div>

                <!-- 5. इंद्रायणी Paddy (Indrayani Paddy) -->
                <div class="bg-white rounded-3xl overflow-hidden shadow-card seed-card-hover border border-creamBorder flex flex-col justify-between relative group md:col-span-2 lg:col-span-1">
                    <div class="absolute top-4 right-4 z-20 bg-amber-600 text-white text-[10px] font-bold uppercase tracking-wider px-3 py-1 rounded-full shadow">
                        Fragrant Specialty
                    </div>
                    
                    <div>
                        <div class="relative h-64 bg-gradient-to-b from-gray-50 to-white p-6 flex items-center justify-center overflow-hidden border-b border-gray-100">
                            <div class="absolute inset-0 opacity-10 bg-[radial-gradient(#E8D9B5_1px,transparent_1px)] [background-size:12px_12px]"></div>
                            
                            <img src="https://lh3.googleusercontent.com/d/1MyAEOQ2ZU1ROw2ZvRrz_cAoVTCKd8Qg6" 
                                 alt="Shreemant Seeds Indrayani Paddy seed packet" 
                                 class="max-h-52 object-contain group-hover:scale-110 transition-transform duration-500 drop-shadow-xl"
                                 onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                            
                            <div class="hidden w-44 h-56 bg-deepEarth rounded-2xl p-3 text-white flex-col justify-between shadow-2xl border-2 border-softWheat relative overflow-hidden">
                                <div class="text-center border-b border-softWheat/30 pb-2">
                                    <span class="text-[9px] uppercase tracking-widest text-softWheat">SHREEMANT SEEDS</span>
                                    <h4 class="font-display font-extrabold text-lg leading-tight">इंद्रायणी Paddy</h4>
                                </div>
                                <div class="text-center my-auto">
                                    <span class="text-4xl block">🌸</span>
                                    <span class="text-[10px] font-semibold bg-softWheat text-deepEarth px-2 py-0.5 rounded-full mt-1 inline-block">AROMATIC</span>
                                </div>
                                <div class="text-center text-[9px] text-white/80 border-t border-white/20 pt-1">
                                    Net Weight: 3 kg / 10 kg
                                </div>
                            </div>
                        </div>

                        <div class="p-6 space-y-3">
                            <div>
                                <span class="text-xs font-semibold text-naturalGreen uppercase tracking-wider">Paddy Seed • Aromatic Rice</span>
                                <h3 class="font-display font-bold text-2xl text-deepEarth group-hover:text-shreemantRed transition-colors">इंद्रायणी Paddy</h3>
                            </div>
                            
                            <p class="text-xs md:text-sm text-deepEarth/75 leading-relaxed">
                                Renowned traditional Indian aromatic paddy variety prized for its pleasant natural fragrance, soft cooking texture, and high market demand.
                            </p>

                            <div class="flex flex-wrap gap-1.5 pt-2">
                                <span class="text-[11px] bg-lightCream text-deepEarth px-2.5 py-1 rounded-md font-medium border border-creamBorder">⏱ 135-140 Days</span>
                                <span class="text-[11px] bg-lightCream text-deepEarth px-2.5 py-1 rounded-md font-medium border border-creamBorder">🌸 Natural Aroma</span>
                                <span class="text-[11px] bg-naturalGreenBg text-naturalGreen px-2.5 py-1 rounded-md font-medium">🍚 Soft & Sticky Texture</span>
                            </div>
                        </div>
                    </div>

                    <div class="p-6 pt-0 space-y-2">
                        <div class="grid grid-cols-2 gap-2">
                            <button onclick="openProductModal('इंद्रायणी', 'इंद्रायणी Paddy', 'Fragrant Specialty', '135-140 Days', 'Medium Aromatic Grain', 'Renowned traditional Indian aromatic paddy variety prized for its pleasant natural fragrance, soft cooking texture, and high market demand.', 'https://lh3.googleusercontent.com/d/1MyAEOQ2ZU1ROw2ZvRrz_cAoVTCKd8Qg6')" class="w-full text-center text-xs font-bold text-deepEarth bg-lightCream hover:bg-softWheat/50 py-3 rounded-xl border border-softWheat transition-colors">
                                View Details
                            </button>
                            <button onclick="enquireProductWhatsApp('इंद्रायणी')" class="w-full text-center text-xs font-bold text-white bg-shreemantRed hover:bg-shreemantRedDark py-3 rounded-xl shadow-md transition-colors flex items-center justify-center gap-1">
                                <span>ORDER NOW</span>
                            </button>
                        </div>
                        <button onclick="enquireProductWhatsApp('इंद्रायणी')" class="w-full text-center text-xs font-medium text-naturalGreen hover:text-naturalGreenDark py-1.5 flex items-center justify-center gap-1.5 transition-colors">
                            <span>💬 Enquire on WhatsApp</span>
                        </button>
                    </div>
                </div>

            </div>

        </div>
    </section>

    <!-- FARMING VISUAL SECTION -->
    <section class="relative py-28 bg-deepEarth text-white overflow-hidden">
        <!-- Full Width Background Image -->
        <div class="absolute inset-0 z-0">
            <img src="https://images.unsplash.com/photo-1530507629858-e4977d30e9e0?auto=format&fit=crop&q=80&w=2000" 
                 alt="Golden harvest paddy field landscape" 
                 class="w-full h-full object-cover opacity-35 filter contrast-125">
            <div class="absolute inset-0 bg-gradient-to-r from-deepEarth via-deepEarth/80 to-transparent"></div>
        </div>

        <div class="relative z-10 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="max-w-2xl space-y-6">
                
                <span class="inline-block bg-shreemantRed text-white text-xs font-extrabold uppercase tracking-widest px-4 py-1.5 rounded-full shadow-lg">
                    CULTIVATING FUTURE
                </span>

                <h2 class="font-display font-extrabold text-4xl sm:text-5xl lg:text-6xl text-white leading-tight">
                    Every Harvest Begins <br>
                    <span class="text-softWheat">With a Seed.</span>
                </h2>

                <p class="text-lg text-gray-200 font-normal leading-relaxed">
                    Supporting farmers from seed selection to cultivation. Our dedicated agricultural seed advisors are always ready to assist you in choosing the right seed variety for your soil type and season.
                </p>

                <div class="pt-4">
                    <a href="#contact" class="inline-flex items-center gap-3 bg-shreemantRed hover:bg-shreemantRedDark text-white font-bold text-base px-8 py-4 rounded-xl shadow-red-glow hover:shadow-xl transition-all duration-300 transform hover:-translate-y-0.5">
                        <span>TALK TO US TODAY</span>
                        <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
                    </a>
                </div>

            </div>
        </div>

        <!-- Organic Curve Divider Bottom -->
        <div class="absolute bottom-0 left-0 right-0 h-10 bg-white" style="clip-path: polygon(0 100%, 100% 100%, 100% 0);"></div>
    </section>

    <!-- WHY SHREEMANT SECTION -->
    <section id="why-us" class="py-24 bg-white relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <div class="text-center max-w-3xl mx-auto space-y-3 mb-16">
                <span class="text-shreemantRed font-bold text-xs uppercase tracking-widest bg-shreemantRedLight px-4 py-1 rounded-full">
                    OUR ADVANTAGE
                </span>
                <h2 class="font-display font-extrabold text-3xl sm:text-4xl text-deepEarth">
                    Why Choose Shreemant Seeds?
                </h2>
                <p class="text-base text-deepEarth/70">
                    Built on traditional agricultural values, state-of-the-art seed processing, and continuous farmer trust.
                </p>
            </div>

            <!-- 4 Pillar Cards -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                
                <!-- Card 01 -->
                <div class="p-8 rounded-3xl bg-lightCream border border-creamBorder hover:border-shreemantRed/40 transition-all duration-300 hover:shadow-lg group">
                    <div class="flex justify-between items-center mb-6">
                        <span class="text-3xl font-display font-black text-shreemantRed/30 group-hover:text-shreemantRed transition-colors">01</span>
                        <div class="w-12 h-12 rounded-2xl bg-shreemantRed text-white flex items-center justify-center text-xl shadow-md">
                            🌱
                        </div>
                    </div>
                    <h3 class="font-display font-bold text-xl text-deepEarth mb-2">QUALITY SEEDS</h3>
                    <p class="text-xs md:text-sm text-deepEarth/75 leading-relaxed">
                        Focused on providing quality seed varieties rigorously inspected for high purity and germination rate.
                    </p>
                </div>

                <!-- Card 02 -->
                <div class="p-8 rounded-3xl bg-lightCream border border-creamBorder hover:border-shreemantRed/40 transition-all duration-300 hover:shadow-lg group">
                    <div class="flex justify-between items-center mb-6">
                        <span class="text-3xl font-display font-black text-naturalGreen/30 group-hover:text-naturalGreen transition-colors">02</span>
                        <div class="w-12 h-12 rounded-2xl bg-naturalGreen text-white flex items-center justify-center text-xl shadow-md">
                            👨‍🌾
                        </div>
                    </div>
                    <h3 class="font-display font-bold text-xl text-deepEarth mb-2">FARMER FOCUSED</h3>
                    <p class="text-xs md:text-sm text-deepEarth/75 leading-relaxed">
                        Understanding the practical everyday needs of ground level paddy farmers is at the heart of our approach.
                    </p>
                </div>

                <!-- Card 03 -->
                <div class="p-8 rounded-3xl bg-lightCream border border-creamBorder hover:border-shreemantRed/40 transition-all duration-300 hover:shadow-lg group">
                    <div class="flex justify-between items-center mb-6">
                        <span class="text-3xl font-display font-black text-shreemantRed/30 group-hover:text-shreemantRed transition-colors">03</span>
                        <div class="w-12 h-12 rounded-2xl bg-shreemantRed text-white flex items-center justify-center text-xl shadow-md">
                            🌾
                        </div>
                    </div>
                    <h3 class="font-display font-bold text-xl text-deepEarth mb-2">RELIABLE VARIETIES</h3>
                    <p class="text-xs md:text-sm text-deepEarth/75 leading-relaxed">
                        A growing range of paddy seed varieties engineered for different rainfall and soil cultivation requirements.
                    </p>
                </div>

                <!-- Card 04 -->
                <div class="p-8 rounded-3xl bg-lightCream border border-creamBorder hover:border-shreemantRed/40 transition-all duration-300 hover:shadow-lg group">
                    <div class="flex justify-between items-center mb-6">
                        <span class="text-3xl font-display font-black text-deepEarth/30 group-hover:text-deepEarth transition-colors">04</span>
                        <div class="w-12 h-12 rounded-2xl bg-deepEarth text-white flex items-center justify-center text-xl shadow-md">
                            🤝
                        </div>
                    </div>
                    <h3 class="font-display font-bold text-xl text-deepEarth mb-2">AGRICULTURAL COMMITMENT</h3>
                    <p class="text-xs md:text-sm text-deepEarth/75 leading-relaxed">
                        Deeply committed to supporting better farming outcomes, crop security, and stronger rural communities.
                    </p>
                </div>

            </div>

        </div>
    </section>

    <!-- FARMER SECTION -->
    <section id="for-farmers" class="py-24 bg-lightCream border-y border-softWheat/40 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                
                <!-- Left Narrative -->
                <div class="lg:col-span-5 space-y-6">
                    <span class="text-naturalGreen font-bold text-xs uppercase tracking-widest bg-white px-3 py-1 rounded-md border border-naturalGreen/20">
                        DEDICATED TO FARMERS
                    </span>
                    
                    <h2 class="font-display font-extrabold text-3xl sm:text-4xl text-deepEarth leading-tight">
                        Built for the People Who Grow Our Food.
                    </h2>

                    <p class="text-base text-deepEarth/80 font-medium">
                        Farming begins with a decision. Choosing the right seed is one of the first and most critical steps.
                    </p>

                    <div class="relative rounded-2xl overflow-hidden shadow-lg border-2 border-white">
                        <img src="https://images.unsplash.com/photo-1500382017468-9049fed747ef?auto=format&fit=crop&q=80&w=800" 
                             alt="Indian farmer inspecting paddy crops in sunshine" 
                             class="w-full h-64 object-cover">
                        <div class="absolute inset-0 bg-gradient-to-t from-deepEarth/80 to-transparent"></div>
                        <p class="absolute bottom-4 left-4 right-4 text-xs text-white italic">
                            "When quality seed meets good land management, the harvest naturally flourishes."
                        </p>
                    </div>
                </div>

                <!-- Right 3-Step Process -->
                <div class="lg:col-span-7 space-y-6">
                    
                    <!-- Step 01 -->
                    <div class="p-6 rounded-2xl bg-white border border-creamBorder shadow-sm flex items-start gap-5 hover:border-shreemantRed transition-colors">
                        <div class="w-12 h-12 rounded-xl bg-shreemantRedLight text-shreemantRed font-display font-extrabold text-xl flex items-center justify-center shrink-0">
                            01
                        </div>
                        <div class="space-y-1">
                            <h3 class="font-display font-bold text-lg text-deepEarth uppercase tracking-wide">SELECT</h3>
                            <p class="text-sm text-deepEarth/75 leading-relaxed">
                                Choose the appropriate paddy seed variety based on your region's duration window, irrigation facility, and market preference.
                            </p>
                        </div>
                    </div>

                    <!-- Step 02 -->
                    <div class="p-6 rounded-2xl bg-white border border-creamBorder shadow-sm flex items-start gap-5 hover:border-shreemantRed transition-colors">
                        <div class="w-12 h-12 rounded-xl bg-naturalGreenBg text-naturalGreen font-display font-extrabold text-xl flex items-center justify-center shrink-0">
                            02
                        </div>
                        <div class="space-y-1">
                            <h3 class="font-display font-bold text-lg text-deepEarth uppercase tracking-wide">CULTIVATE</h3>
                            <p class="text-sm text-deepEarth/75 leading-relaxed">
                                Follow suitable nursery preparation, row planting, balanced soil nutrition, and timely water management practices.
                            </p>
                        </div>
                    </div>

                    <!-- Step 03 -->
                    <div class="p-6 rounded-2xl bg-white border border-creamBorder shadow-sm flex items-start gap-5 hover:border-shreemantRed transition-colors">
                        <div class="w-12 h-12 rounded-xl bg-softWheat/40 text-deepEarth font-display font-extrabold text-xl flex items-center justify-center shrink-0">
                            03
                        </div>
                        <div class="space-y-1">
                            <h3 class="font-display font-bold text-lg text-deepEarth uppercase tracking-wide">GROW</h3>
                            <p class="text-sm text-deepEarth/75 leading-relaxed">
                                Monitor tiller growth and grain development to work towards a healthy, bountiful, and highly productive paddy crop.
                            </p>
                        </div>
                    </div>

                </div>

            </div>

        </div>
    </section>

    <!-- SEED TO HARVEST SECTION -->
    <section class="py-24 bg-white relative overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <div class="text-center max-w-2xl mx-auto space-y-3 mb-16">
                <span class="text-shreemantRed font-bold text-xs uppercase tracking-widest bg-shreemantRedLight px-4 py-1 rounded-full">
                    CULTIVATION TIMELINE
                </span>
                <h2 class="font-display font-extrabold text-3xl sm:text-4xl text-deepEarth">
                    From Seed to Harvest
                </h2>
                <p class="text-base text-deepEarth/70">
                    Every stage of cultivation starts with a strong, high-germination foundation.
                </p>
            </div>

            <!-- Horizontal Lifecycle Flow -->
            <div class="relative">
                
                <!-- Connecting Line Desktop -->
                <div class="hidden lg:block absolute top-1/2 left-0 right-0 h-1 bg-gradient-to-r from-shreemantRed via-naturalGreen to-softWheatDark -translate-y-1/2 z-0"></div>

                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 relative z-10">
                    
                    <!-- Stage 1 -->
                    <div class="bg-lightCream p-6 rounded-3xl border border-creamBorder text-center space-y-4 hover:shadow-lg transition-shadow">
                        <div class="w-16 h-16 rounded-2xl bg-shreemantRed text-white font-bold text-2xl mx-auto flex items-center justify-center shadow-md">
                            🌱
                        </div>
                        <span class="inline-block text-[11px] font-bold text-shreemantRed uppercase tracking-wider bg-white px-3 py-1 rounded-full border border-shreemantRed/20">
                            STAGE 01
                        </span>
                        <h3 class="font-display font-bold text-xl text-deepEarth">SEED</h3>
                        <p class="text-xs text-deepEarth/70">Selecting high purity Shreemant Paddy Seeds with healthy grain weight.</p>
                    </div>

                    <!-- Stage 2 -->
                    <div class="bg-lightCream p-6 rounded-3xl border border-creamBorder text-center space-y-4 hover:shadow-lg transition-shadow">
                        <div class="w-16 h-16 rounded-2xl bg-naturalGreen text-white font-bold text-2xl mx-auto flex items-center justify-center shadow-md">
                            🌿
                        </div>
                        <span class="inline-block text-[11px] font-bold text-naturalGreen uppercase tracking-wider bg-white px-3 py-1 rounded-full border border-naturalGreen/20">
                            STAGE 02
                        </span>
                        <h3 class="font-display font-bold text-xl text-deepEarth">SPROUT</h3>
                        <p class="text-xs text-deepEarth/70">Vigorous seedling emergence, fast root anchorage, and green vigor.</p>
                    </div>

                    <!-- Stage 3 -->
                    <div class="bg-lightCream p-6 rounded-3xl border border-creamBorder text-center space-y-4 hover:shadow-lg transition-shadow">
                        <div class="w-16 h-16 rounded-2xl bg-deepEarth text-white font-bold text-2xl mx-auto flex items-center justify-center shadow-md">
                            🌾
                        </div>
                        <span class="inline-block text-[11px] font-bold text-deepEarth uppercase tracking-wider bg-white px-3 py-1 rounded-full border border-deepEarth/20">
                            STAGE 03
                        </span>
                        <h3 class="font-display font-bold text-xl text-deepEarth">CROP</h3>
                        <p class="text-xs text-deepEarth/70">Profuse tiller count, lodging resistance, and dense green canopy.</p>
                    </div>

                    <!-- Stage 4 -->
                    <div class="bg-lightCream p-6 rounded-3xl border border-creamBorder text-center space-y-4 hover:shadow-lg transition-shadow">
                        <div class="w-16 h-16 rounded-2xl bg-softWheatDark text-deepEarth font-bold text-2xl mx-auto flex items-center justify-center shadow-md">
                            🌅
                        </div>
                        <span class="inline-block text-[11px] font-bold text-deepEarth uppercase tracking-wider bg-white px-3 py-1 rounded-full border border-softWheatDark/30">
                            STAGE 04
                        </span>
                        <h3 class="font-display font-bold text-xl text-deepEarth">HARVEST</h3>
                        <p class="text-xs text-deepEarth/70">Golden heavy panicles, uniform grain maturity, and superior yield.</p>
                    </div>

                </div>

            </div>

        </div>
    </section>

    <!-- ENQUIRY & CONTACT SECTION -->
    <section id="contact" class="py-24 bg-lightCream relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <div class="bg-white rounded-3xl border border-creamBorder shadow-2xl overflow-hidden">
                <div class="grid grid-cols-1 lg:grid-cols-12">
                    
                    <!-- Left Banner / Image Content -->
                    <div class="lg:col-span-5 bg-deepEarth text-white p-8 sm:p-12 flex flex-col justify-between relative overflow-hidden">
                        <div class="absolute inset-0 z-0 opacity-20">
                            <img src="https://images.unsplash.com/photo-1595838729819-00dc8b846c4a?auto=format&fit=crop&q=80&w=800" 
                                 alt="Close up paddy seed grains" 
                                 class="w-full h-full object-cover">
                        </div>

                        <div class="relative z-10 space-y-6">
                            <span class="inline-block bg-shreemantRed text-white text-xs font-bold px-3 py-1 rounded-full uppercase tracking-wider">
                                DIRECT FARMER SUPPORT
                            </span>

                            <h2 class="font-display font-extrabold text-3xl sm:text-4xl text-white">
                                Looking for the Right Seed?
                            </h2>

                            <p class="text-sm text-softWheat leading-relaxed">
                                Connect directly with <strong>Shreemant Seeds</strong> to learn more about our paddy seed varieties, pricing, bag sizes, regional availability, and agronomy support.
                            </p>

                            <div class="space-y-4 pt-4 border-t border-white/20 text-xs">
                                <div class="flex items-center gap-3">
                                    <div class="w-8 h-8 rounded-full bg-shreemantRed flex items-center justify-center font-bold">
                                        📍
                                    </div>
                                    <span>Serving major agricultural districts & seed dealer networks</span>
                                </div>
                                <div class="flex items-center gap-3">
                                    <div class="w-8 h-8 rounded-full bg-naturalGreen flex items-center justify-center font-bold">
                                        💬
                                    </div>
                                    <span>Fast response over WhatsApp inquiry</span>
                                </div>
                            </div>
                        </div>

                        <div class="relative z-10 pt-10">
                            <button onclick="triggerWhatsAppEnquiry('General Product Enquiry')" class="w-full bg-naturalGreen hover:bg-naturalGreenDark text-white font-bold py-3.5 px-6 rounded-xl flex items-center justify-center gap-2 shadow-lg transition-colors">
                                <span>ENQUIRE ON WHATSAPP</span>
                            </button>
                        </div>
                    </div>

                    <!-- Right Form -->
                    <div class="lg:col-span-7 p-8 sm:p-12">
                        <h3 class="font-display font-bold text-2xl text-deepEarth mb-2">Send an Instant Enquiry</h3>
                        <p class="text-xs text-deepEarth/70 mb-8">Fill out your information below to construct an instant WhatsApp enquiry to our team.</p>

                        <form id="enquiryForm" onsubmit="handleFormSubmit(event)" class="space-y-5">
                            
                            <!-- Full Name -->
                            <div>
                                <label for="fullName" class="block text-xs font-bold text-deepEarth uppercase tracking-wider mb-2">Full Name *</label>
                                <input type="text" id="fullName" required placeholder="e.g. Ramesh Patil" class="w-full px-4 py-3 rounded-xl border border-gray-200 focus:border-shreemantRed focus:ring-2 focus:ring-shreemantRed/20 outline-none transition text-sm">
                            </div>

                            <!-- Mobile & Location Row -->
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label for="mobileNum" class="block text-xs font-bold text-deepEarth uppercase tracking-wider mb-2">Mobile Number *</label>
                                    <input type="tel" id="mobileNum" required placeholder="e.g. 9876543210" class="w-full px-4 py-3 rounded-xl border border-gray-200 focus:border-shreemantRed focus:ring-2 focus:ring-shreemantRed/20 outline-none transition text-sm">
                                </div>
                                <div>
                                    <label for="farmerLocation" class="block text-xs font-bold text-deepEarth uppercase tracking-wider mb-2">Location / District *</label>
                                    <input type="text" id="farmerLocation" required placeholder="e.g. Kolhapur, Maharashtra" class="w-full px-4 py-3 rounded-xl border border-gray-200 focus:border-shreemantRed focus:ring-2 focus:ring-shreemantRed/20 outline-none transition text-sm">
                                </div>
                            </div>

                            <!-- Product Dropdown -->
                            <div>
                                <label for="productSelect" class="block text-xs font-bold text-deepEarth uppercase tracking-wider mb-2">Product Interested In *</label>
                                <select id="productSelect" required class="w-full px-4 py-3 rounded-xl border border-gray-200 focus:border-shreemantRed focus:ring-2 focus:ring-shreemantRed/20 outline-none transition text-sm bg-white">
                                    <option value="V.I.P. Paddy">V.I.P. Paddy</option>
                                    <option value="SHREEMANT-64 Paddy">SHREEMANT-64 Paddy</option>
                                    <option value="Safari Jaya Paddy">Safari Jaya Paddy</option>
                                    <option value="Komalika Paddy">Komalika Paddy</option>
                                    <option value="इंद्रायणी Paddy">इंद्रायणी Paddy (Indrayani)</option>
                                    <option value="Multiple Seed Varieties">Multiple Seed Varieties</option>
                                </select>
                            </div>

                            <!-- Message -->
                            <div>
                                <label for="farmerMessage" class="block text-xs font-bold text-deepEarth uppercase tracking-wider mb-2">Message or Required Quantity</label>
                                <textarea id="farmerMessage" rows="3" placeholder="Specify required seed quantity (in Bags/Kgs) or soil type..." class="w-full px-4 py-3 rounded-xl border border-gray-200 focus:border-shreemantRed focus:ring-2 focus:ring-shreemantRed/20 outline-none transition text-sm"></textarea>
                            </div>

                            <!-- Submit Button -->
                            <button type="submit" class="w-full bg-shreemantRed hover:bg-shreemantRedDark text-white font-bold py-4 rounded-xl shadow-lg shadow-shreemantRed/25 hover:shadow-xl transition-all duration-300 flex items-center justify-center gap-2">
                                <span>SEND ENQUIRY ON WHATSAPP</span>
                                <svg class="w-5 h-5 fill-current" viewBox="0 0 24 24"><path d="M.057 24l1.687-6.163c-1.041-1.804-1.588-3.849-1.587-5.946.003-6.556 5.338-11.891 11.893-11.891 3.181.001 6.167 1.24 8.413 3.488 2.245 2.248 3.481 5.236 3.48 8.414-.003 6.557-5.338 11.892-11.893 11.892-1.99-.001-3.951-.5-5.688-1.448l-6.305 1.654zm6.597-3.807c1.676.995 3.276 1.591 5.392 1.592 5.448 0 9.886-4.434 9.889-9.885.002-5.462-4.415-9.89-9.881-9.892-5.452 0-9.887 4.434-9.889 9.884-.001 2.225.651 3.891 1.746 5.634l-.999 3.648 3.742-.981zm11.387-5.464c-.074-.124-.272-.198-.57-.347-.297-.149-1.758-.868-2.031-.967-.272-.099-.47-.149-.669.149-.198.297-.768.967-.941 1.165-.173.198-.347.223-.644.074-.297-.149-1.255-.462-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.297-.347.446-.521.151-.172.2-.296.3-.495.099-.198.05-.372-.025-.521-.075-.148-.669-1.611-.916-2.206-.242-.579-.487-.501-.669-.51l-.57-.01c-.198 0-.52.074-.792.372s-1.04 1.016-1.04 2.479 1.065 2.876 1.213 3.074c.149.198 2.095 3.2 5.076 4.487.709.306 1.263.489 1.694.626.712.226 1.36.194 1.872.118.572-.085 1.758-.719 2.006-1.413.248-.695.248-1.29.173-1.414z"/></svg>
                            </button>

                        </form>
                    </div>

                </div>
            </div>

        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-shreemantRed text-white pt-16 pb-12 relative overflow-hidden border-t-8 border-deepEarth">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-10 pb-12 border-b border-white/20">
                
                <!-- Brand Info Column -->
                <div class="lg:col-span-5 space-y-4">
                    <div class="flex items-center gap-3">
                        <div class="w-10 h-10 rounded-lg bg-white text-shreemantRed font-extrabold flex items-center justify-center text-xl shadow">
                            SS
                        </div>
                        <span class="font-display font-extrabold text-2xl text-white tracking-tight">
                            SHREEMANT SEEDS
                        </span>
                    </div>

                    <p class="text-xs sm:text-sm text-white/90 max-w-md leading-relaxed">
                        “Quality Seeds. Better Possibilities.” <br>
                        Committed to providing Indian farmers with high germination paddy seed varieties for stronger harvests and prosperous agriculture.
                    </p>

                    <div class="pt-2 flex items-center gap-3 text-xs text-softWheat">
                        <span class="bg-black/20 px-3 py-1 rounded-full border border-white/10">🌱 Premium Paddy Seeds</span>
                        <span class="bg-black/20 px-3 py-1 rounded-full border border-white/10">🌾 Certified Varieties</span>
                    </div>
                </div>

                <!-- Navigation Links -->
                <div class="lg:col-span-3 space-y-3">
                    <h4 class="font-display font-bold text-base text-softWheat uppercase tracking-wider">Quick Navigation</h4>
                    <ul class="space-y-2 text-xs text-white/90">
                        <li><a href="#home" class="hover:underline">Home</a></li>
                        <li><a href="#about" class="hover:underline">About Us</a></li>
                        <li><a href="#seeds" class="hover:underline">Our Seed Varieties</a></li>
                        <li><a href="#why-us" class="hover:underline">Why Shreemant</a></li>
                        <li><a href="#for-farmers" class="hover:underline">For Farmers</a></li>
                        <li><a href="#contact" class="hover:underline">Contact & Enquiry</a></li>
                    </ul>
                </div>

                <!-- Contact Details Placeholders -->
                <div class="lg:col-span-4 space-y-3">
                    <h4 class="font-display font-bold text-base text-softWheat uppercase tracking-wider">Contact & Support</h4>
                    <div class="space-y-2.5 text-xs text-white/90">
                        <p class="flex items-center gap-2">
                            <span>📱 Phone:</span>
                            <span class="font-mono bg-black/20 px-2 py-0.5 rounded">[ Dealer Support Number ]</span>
                        </p>
                        <p class="flex items-center gap-2">
                            <span>💬 WhatsApp:</span>
                            <span class="font-mono bg-black/20 px-2 py-0.5 rounded" id="footerNumDisplay">+91 9876543210</span>
                        </p>
                        <p class="flex items-center gap-2">
                            <span>✉️ Email:</span>
                            <span class="font-mono bg-black/20 px-2 py-0.5 rounded">[ info@shreemantseeds.com ]</span>
                        </p>
                        <p class="flex items-start gap-2">
                            <span>📍 Address:</span>
                            <span class="bg-black/20 px-2 py-0.5 rounded leading-relaxed">[ Shreemant Seeds Head Office & Processing Plant, Agricultural Hub, India ]</span>
                        </p>
                    </div>
                </div>

            </div>

            <!-- Copyright & Disclaimer -->
            <div class="pt-8 flex flex-col sm:flex-row justify-between items-center text-xs text-white/80 gap-4">
                <p>© <span id="currentYear"></span> SHREEMANT SEEDS. All rights reserved.</p>
                <p class="text-center sm:text-right text-[11px] text-white/70">
                    Authentic Agricultural Seed Brand • High Quality Paddy Seeds for Farmers
                </p>
            </div>

        </div>
    </footer>

    <!-- FLOATING WHATSAPP BUTTON -->
    <a href="javascript:void(0)" 
       onclick="triggerWhatsAppEnquiry('General Inquiry')" 
       class="fixed bottom-6 right-6 z-50 bg-emerald-600 hover:bg-emerald-700 text-white p-4 rounded-full shadow-2xl flex items-center justify-center gap-2 group transition-all duration-300 transform hover:scale-110 active:scale-95 border-2 border-white" 
       title="Enquire on WhatsApp">
        <svg class="w-7 h-7 fill-current" viewBox="0 0 24 24">
            <path d="M.057 24l1.687-6.163c-1.041-1.804-1.588-3.849-1.587-5.946.003-6.556 5.338-11.891 11.893-11.891 3.181.001 6.167 1.24 8.413 3.488 2.245 2.248 3.481 5.236 3.48 8.414-.003 6.557-5.338 11.892-11.893 11.892-1.99-.001-3.951-.5-5.688-1.448l-6.305 1.654zm6.597-3.807c1.676.995 3.276 1.591 5.392 1.592 5.448 0 9.886-4.434 9.889-9.885.002-5.462-4.415-9.89-9.881-9.892-5.452 0-9.887 4.434-9.889 9.884-.001 2.225.651 3.891 1.746 5.634l-.999 3.648 3.742-.981zm11.387-5.464c-.074-.124-.272-.198-.57-.347-.297-.149-1.758-.868-2.031-.967-.272-.099-.47-.149-.669.149-.198.297-.768.967-.941 1.165-.173.198-.347.223-.644.074-.297-.149-1.255-.462-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.297-.347.446-.521.151-.172.2-.296.3-.495.099-.198.05-.372-.025-.521-.075-.148-.669-1.611-.916-2.206-.242-.579-.487-.501-.669-.51l-.57-.01c-.198 0-.52.074-.792.372s-1.04 1.016-1.04 2.479 1.065 2.876 1.213 3.074c.149.198 2.095 3.2 5.076 4.487.709.306 1.263.489 1.694.626.712.226 1.36.194 1.872.118.572-.085 1.758-.719 2.006-1.413.248-.695.248-1.29.173-1.414z"/>
        </svg>
        <span class="hidden md:inline font-bold text-xs tracking-wider pr-1">Enquire on WhatsApp</span>
    </a>

    <!-- PRODUCT DETAILS MODAL DIALOG -->
    <div id="productModal" class="fixed inset-0 z-50 hidden bg-black/60 backdrop-blur-sm flex items-center justify-center p-4">
        <div class="bg-white rounded-3xl max-w-lg w-full p-6 sm:p-8 shadow-2xl relative border border-creamBorder max-h-[90vh] overflow-y-auto">
            
            <button onclick="closeProductModal()" class="absolute top-4 right-4 text-gray-400 hover:text-shreemantRed p-2 rounded-full hover:bg-lightCream">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path></svg>
            </button>

            <div class="text-center space-y-3">
                <span id="modalBadge" class="inline-block bg-shreemantRed text-white text-[10px] font-bold uppercase tracking-wider px-3 py-1 rounded-full">
                    Category
                </span>
                <h3 id="modalTitle" class="font-display font-extrabold text-3xl text-deepEarth">
                    Product Title
                </h3>
                <p id="modalCategory" class="text-xs text-naturalGreen font-bold uppercase tracking-wider">
                    Paddy Seed Variety
                </p>
            </div>

            <!-- Modal Image Preview -->
            <div class="my-6 bg-lightCream p-4 rounded-2xl flex items-center justify-center border border-creamBorder">
                <img id="modalImg" src="" alt="Seed Package Preview" class="max-h-48 object-contain">
            </div>

            <!-- Key Specifications Table -->
            <div class="space-y-3 text-xs bg-gray-50 p-4 rounded-2xl border border-gray-100">
                <div class="flex justify-between py-1 border-b border-gray-200">
                    <span class="font-bold text-deepEarth">Cultivation Duration:</span>
                    <span id="modalDuration" class="text-deepEarth/80 font-medium">125-130 Days</span>
                </div>
                <div class="flex justify-between py-1 border-b border-gray-200">
                    <span class="font-bold text-deepEarth">Grain Specification:</span>
                    <span id="modalGrain" class="text-deepEarth/80 font-medium">Slender Grain</span>
                </div>
                <div class="flex justify-between py-1">
                    <span class="font-bold text-deepEarth">Suitability:</span>
                    <span class="text-naturalGreen font-bold">Recommended for Kharif / Seasonal Paddy</span>
                </div>
            </div>

            <!-- Description -->
            <p id="modalDesc" class="text-xs text-deepEarth/80 mt-4 leading-relaxed">
                Description goes here...
            </p>

            <!-- Actions -->
            <div class="mt-6 flex flex-col gap-2">
                <button id="modalOrderBtn" onclick="" class="w-full bg-shreemantRed hover:bg-shreemantRedDark text-white font-bold py-3 rounded-xl shadow transition-colors flex items-center justify-center gap-2">
                    <span>ORDER NOW ON WHATSAPP</span>
                </button>
                <button onclick="closeProductModal()" class="w-full text-xs font-semibold text-deepEarth hover:bg-lightCream py-2 rounded-lg">
                    Close Details
                </button>
            </div>

        </div>
    </div>

    <!-- JAVASCRIPT LOGIC -->
    <script>
        // Configurable WhatsApp Number
        let WHATSAPP_NUMBER = "919876543210";

        // Set current year in footer
        document.getElementById('currentYear').textContent = new Date().getFullYear();

        // Update WhatsApp number runtime function
        function changeWhatsAppNumber() {
            const input = prompt("Enter the preferred WhatsApp mobile number with country code (e.g. 919876543210):", WHATSAPP_NUMBER);
            if (input && input.trim() !== "") {
                WHATSAPP_NUMBER = input.replace(/\D/g, ''); // sanitize to digits
                document.getElementById('currentNumberBadge').textContent = WHATSAPP_NUMBER;
                document.getElementById('footerNumDisplay').textContent = "+" + WHATSAPP_NUMBER;
                alert("WhatsApp number successfully updated to: +" + WHATSAPP_NUMBER);
            }
        }

        // Toggle mobile navigation menu
        function toggleMobileMenu() {
            const menu = document.getElementById('mobileMenu');
            const menuIcon = document.getElementById('menuIcon');
            const closeIcon = document.getElementById('closeIcon');

            if (menu.classList.contains('hidden')) {
                menu.classList.remove('hidden');
                menuIcon.classList.add('hidden');
                closeIcon.classList.remove('hidden');
            } else {
                menu.classList.add('hidden');
                menuIcon.classList.remove('hidden');
                closeIcon.classList.add('hidden');
            }
        }

        // Dedicated product WhatsApp enquiry mapping
        function enquireProductWhatsApp(productName) {
            let message = "";

            if (productName.includes("V.I.P")) {
                message = "Hello Shreemant Seeds, I am interested in V.I.P. Paddy seed. Please share the product details, price and availability.";
            } else if (productName.includes("SHREEMANT-64")) {
                message = "Hello Shreemant Seeds, I am interested in SHREEMANT-64 Paddy seed. Please share the product details, price and availability.";
            } else if (productName.includes("Safari Jaya")) {
                message = "Hello Shreemant Seeds, I am interested in Safari Jaya Paddy seed. Please share the product details, price and availability.";
            } else if (productName.includes("Komalika")) {
                message = "Hello Shreemant Seeds, I am interested in Komalika Paddy seed. Please share the product details, price and availability.";
            } else if (productName.includes("इंद्रायणी") || productName.includes("Indrayani")) {
                message = "Hello Shreemant Seeds, I am interested in इंद्रायणी Paddy seed. Please share the product details, price and availability.";
            } else {
                message = `Hello Shreemant Seeds, I am interested in ${productName} seed. Please share the product details, price and availability.`;
            }

            const url = `https://wa.me/${WHATSAPP_NUMBER}?text=${encodeURIComponent(message)}`;
            window.open(url, '_blank');
        }

        // General WhatsApp Inquiry Trigger
        function triggerWhatsAppEnquiry(topic) {
            const message = `Hello Shreemant Seeds, I would like to know more about your seed products and agricultural solutions for ${topic}.`;
            const url = `https://wa.me/${WHATSAPP_NUMBER}?text=${encodeURIComponent(message)}`;
            window.open(url, '_blank');
        }

        // Handle Contact Form Submit -> WhatsApp Message
        function handleFormSubmit(e) {
            e.preventDefault();
            
            const name = document.getElementById('fullName').value.trim();
            const mobile = document.getElementById('mobileNum').value.trim();
            const location = document.getElementById('farmerLocation').value.trim();
            const product = document.getElementById('productSelect').value;
            const userMsg = document.getElementById('farmerMessage').value.trim();

            const formattedMsg = `*New Seed Enquiry - Shreemant Seeds*\n` +
                                 `👤 *Name:* ${name}\n` +
                                 `📱 *Mobile:* ${mobile}\n` +
                                 `📍 *Location:* ${location}\n` +
                                 `🌾 *Product Interested In:* ${product}\n` +
                                 `💬 *Message/Quantity:* ${userMsg || 'Not specified'}`;

            const url = `https://wa.me/${WHATSAPP_NUMBER}?text=${encodeURIComponent(formattedMsg)}`;
            window.open(url, '_blank');
        }

        // Open Specification Modal
        function openProductModal(key, title, badge, duration, grain, desc, img) {
            document.getElementById('modalTitle').textContent = title;
            document.getElementById('modalBadge').textContent = badge;
            document.getElementById('modalDuration').textContent = duration;
            document.getElementById('modalGrain').textContent = grain;
            document.getElementById('modalDesc').textContent = desc;
            document.getElementById('modalImg').src = img;

            const orderBtn = document.getElementById('modalOrderBtn');
            orderBtn.onclick = function() {
                closeProductModal();
                enquireProductWhatsApp(key);
            };

            document.getElementById('productModal').classList.remove('hidden');
        }

        function closeProductModal() {
            document.getElementById('productModal').classList.add('hidden');
        }

        // Close modal when clicking outside contents
        window.onclick = function(event) {
            const modal = document.getElementById('productModal');
            if (event.target === modal) {
                closeProductModal();
            }
        };

        // Header shadow enhancement on scroll
        window.addEventListener('scroll', function() {
            const header = document.getElementById('mainHeader');
            if (window.scrollY > 20) {
                header.classList.add('shadow-md');
            } else {
                header.classList.remove('shadow-md');
            }
        });
    </script>
</body>
</html>
