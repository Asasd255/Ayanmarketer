<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Asadullah - Digital Marketing Specialist</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        
        :root {
            --primary: #4f46e5;
            --secondary: #7c3aed;
            --dark: #1e293b;
            --light: #f8fafc;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            scroll-behavior: smooth;
        }
        
        .hero {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
        }
        
        .service-card, .portfolio-card {
            transition: all 0.3s ease;
        }
        
        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 25px rgba(0, 0, 0, 0.1);
        }
        
        .portfolio-card:hover {
            transform: scale(1.03);
        }
        
        .nav-link.active {
            color: var(--primary);
            font-weight: 600;
        }
        
        .stats-item {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Navigation -->
    <nav class="bg-white shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-6 py-3">
            <div class="flex justify-between items-center">
                <div class="text-2xl font-bold text-indigo-600">Asadullah</div>
                <div class="hidden md:flex space-x-8">
                    <a href="#home" class="nav-link active text-gray-800 hover:text-indigo-600">Home</a>
                    <a href="#about" class="nav-link text-gray-800 hover:text-indigo-600">About</a>
                    <a href="#services" class="nav-link text-gray-800 hover:text-indigo-600">Services</a>
                    <a href="#portfolio" class="nav-link text-gray-800 hover:text-indigo-600">Portfolio</a>
                    <a href="#testimonials" class="nav-link text-gray-800 hover:text-indigo-600">Testimonials</a>
                    <a href="#contact" class="nav-link text-gray-800 hover:text-indigo-600">Contact</a>
                </div>
                <button class="md:hidden focus:outline-none" id="mobile-menu-button">
                    <svg class="w-6 h-6 text-gray-800" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                    </svg>
                </button>
            </div>
            <!-- Mobile menu -->
            <div class="md:hidden hidden mt-4" id="mobile-menu">
                <a href="#home" class="block nav-link active py-2 text-gray-800 hover:text-indigo-600">Home</a>
                <a href="#about" class="block nav-link py-2 text-gray-800 hover:text-indigo-600">About</a>
                <a href="#services" class="block nav-link py-2 text-gray-800 hover:text-indigo-600">Services</a>
                <a href="#portfolio" class="block nav-link py-2 text-gray-800 hover:text-indigo-600">Portfolio</a>
                <a href="#testimonials" class="block nav-link py-2 text-gray-800 hover:text-indigo-600">Testimonials</a>
                <a href="#contact" class="block nav-link py-2 text-gray-800 hover:text-indigo-600">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero text-white py-20">
        <div class="container mx-auto px-6 flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-10 md:mb-0">
                <h1 class="text-4xl md:text-5xl font-bold leading-tight mb-4">Boost Your Online Presence With <span class="border-b-4 border-yellow-400">Expert</span> Digital Marketing</h1>
                <p class="text-xl mb-8">I help businesses grow through targeted digital marketing strategies that deliver measurable results.</p>
                <div class="flex space-x-4">
                    <a href="#contact" class="bg-white text-indigo-600 px-8 py-3 rounded-lg font-semibold hover:bg-gray-100 transition duration-300">Get Started</a>
                    <a href="#portfolio" class="border-2 border-white text-white px-8 py-3 rounded-lg font-semibold hover:bg-white hover:text-indigo-600 transition duration-300">View Work</a>
                </div>
            </div>
            <div class="md:w-1/2 flex justify-center">
                <img src="https://placehold.co/600x400" alt="Asadullah digital marketer with laptop analyzing marketing data on dashboard" class="rounded-lg shadow-xl">
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="py-12 bg-indigo-50">
        <div class="container mx-auto px-6">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-6">
                <div class="stats-item rounded-xl p-6 text-center">
                    <h3 class="text-4xl font-bold text-indigo-600 mb-2">150+</h3>
                    <p class="text-gray-600">Happy Clients</p>
                </div>
                <div class="stats-item rounded-xl p-6 text-center">
                    <h3 class="text-4xl font-bold text-indigo-600 mb-2">240%</h3>
                    <p class="text-gray-600">Avg. ROI Increase</p>
                </div>
                <div class="stats-item rounded-xl p-6 text-center">
                    <h3 class="text-4xl font-bold text-indigo-600 mb-2">5+</h3>
                    <p class="text-gray-600">Years Experience</p>
                </div>
                <div class="stats-item rounded-xl p-6 text-center">
                    <h3 class="text-4xl font-bold text-indigo-600 mb-2">95%</h3>
                    <p class="text-gray-600">Client Retention</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <img src="https://placehold.co/500x600" alt="Professional headshot of Asadullah in business casual attire smiling confidently" class="rounded-lg shadow-xl">
                </div>
                <div class="md:w-1/2 md:pl-12">
                    <h2 class="text-3xl font-bold text-gray-800 mb-6">About <span class="text-indigo-600">Me</span></h2>
                    <p class="text-gray-600 mb-4">Hi, I'm Asadullah, a passionate digital marketing specialist with over 5 years of experience helping businesses establish and grow their online presence. My approach combines data-driven strategies with creative solutions to deliver tangible results.</p>
                    <p class="text-gray-600 mb-6">What sets me apart is my commitment to understanding your unique business needs and crafting customized marketing solutions that align with your goals. I stay ahead of industry trends to ensure your marketing strategies remain effective in today's competitive digital landscape.</p>
                    <div class="space-y-4">
                        <div class="flex items-center">
                            <div class="mr-4 text-indigo-600">
                                <i class="fas fa-bullseye text-2xl"></i>
                            </div>
                            <div>
                                <h4 class="text-lg font-semibold text-gray-800">Focused on Results</h4>
                                <p class="text-gray-600">Trackable metrics and continuous optimization</p>
                            </div>
                        </div>
                        <div class="flex items-center">
                            <div class="mr-4 text-indigo-600">
                                <i class="fas fa-lightbulb text-2xl"></i>
                            </div>
                            <div>
                                <h4 class="text-lg font-semibold text-gray-800">Innovative Strategies</h4>
                                <p class="text-gray-600">Custom solutions for your specific needs</p>
                            </div>
                        </div>
                        <div class="flex items-center">
                            <div class="mr-4 text-indigo-600">
                                <i class="fas fa-chart-line text-2xl"></i>
                            </div>
                            <div>
                                <h4 class="text-lg font-semibold text-gray-800">Proven Growth</h4>
                                <p class="text-gray-600">Consistent results across industries</p>
                            </div>
                        </div>
                    </div>
                    <a href="#contact" class="mt-6 inline-block bg-indigo-600 text-white px-8 py-3 rounded-lg font-semibold hover:bg-indigo-700 transition duration-300">Let's Connect</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 bg-gray-50">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">My <span class="text-indigo-600">Services</span></h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">Comprehensive digital marketing solutions tailored to help your business thrive online</p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="service-card bg-white p-8 rounded-xl shadow-md">
                    <div class="text-indigo-600 mb-4">
                        <i class="fas fa-search-dollar text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-3">SEO Optimization</h3>
                    <p class="text-gray-600 mb-4">Improve your search engine rankings with comprehensive on-page and off-page SEO strategies that drive targeted traffic.</p>
                    <ul class="space-y-2 text-gray-600 mb-6">
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> Keyword research</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> Technical SEO audits</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> Content optimization</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> Link building</li>
                    </ul>
                    <a href="#contact" class="text-indigo-600 font-semibold hover:underline">Learn more →</a>
                </div>
                
                <!-- Service 2 -->
                <div class="service-card bg-white p-8 rounded-xl shadow-md">
                    <div class="text-indigo-600 mb-4">
                        <i class="fas fa-ad text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-3">PPC Advertising</h3>
                    <p class="text-gray-600 mb-4">Run high-converting paid campaigns on Google, Facebook, Instagram and LinkedIn with maximum ROI from your ad spend.</p>
                    <ul class="space-y-2 text-gray-600 mb-6">
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> Campaign setup</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> Audience targeting</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> Ad creatives</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> A/B testing</li>
                    </ul>
                    <a href="#contact" class="text-indigo-600 font-semibold hover:underline">Learn more →</a>
                </div>
                
                <!-- Service 3 -->
                <div class="service-card bg-white p-8 rounded-xl shadow-md">
                    <div class="text-indigo-600 mb-4">
                        <i class="fas fa-hashtag text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-3">Social Media Marketing</h3>
                    <p class="text-gray-600 mb-4">Build brand awareness and engagement through strategic social media management across all major platforms.</p>
                    <ul class="space-y-2 text-gray-600 mb-6">
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> Content strategy</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> Community management</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> Influencer collaboration</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> Performance analytics</li>
                    </ul>
                    <a href="#contact" class="text-indigo-600 font-semibold hover:underline">Learn more →</a>
                </div>
                
                <!-- Service 4 -->
                <div class="service-card bg-white p-8 rounded-xl shadow-md">
                    <div class="text-indigo-600 mb-4">
                        <i class="fas fa-envelope-open-text text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-3">Email Marketing</h3>
                    <p class="text-gray-600 mb-4">Create high-converting email campaigns that nurture leads and boost customer retention and sales.</p>
                    <ul class="space-y-2 text-gray-600 mb-6">
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> List segmentation</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> Automated workflows</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> A/B testing</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> Performance tracking</li>
                    </ul>
                    <a href="#contact" class="text-indigo-600 font-semibold hover:underline">Learn more →</a>
                </div>
                
                <!-- Service 5 -->
                <div class="service-card bg-white p-8 rounded-xl shadow-md">
                    <div class="text-indigo-600 mb-4">
                        <i class="fas fa-pencil-alt text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-3">Content Marketing</h3>
                    <p class="text-gray-600 mb-4">Drive engagement and authority with compelling content that attracts and retains your target audience.</p>
                    <ul class="space-y-2 text-gray-600 mb-6">
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> Blog content</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> Copywriting</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> Infographics</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> Video scripts</li>
                    </ul>
                    <a href="#contact" class="text-indigo-600 font-semibold hover:underline">Learn more →</a>
                </div>
                
                <!-- Service 6 -->
                <div class="service-card bg-white p-8 rounded-xl shadow-md">
                    <div class="text-indigo-600 mb-4">
                        <i class="fas fa-chart-bar text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-3">Analytics & Reporting</h3>
                    <p class="text-gray-600 mb-4">Get actionable insights with comprehensive analytics and intuitive reports that measure your marketing performance.</p>
                    <ul class="space-y-2 text-gray-600 mb-6">
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> KPI tracking</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> Conversion analysis</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> Custom dashboards</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-2"></i> ROI measurement</li>
                    </ul>
                    <a href="#contact" class="text-indigo-600 font-semibold hover:underline">Learn more →</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">My <span class="text-indigo-600">Portfolio</span></h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">See examples of my work and the results I've achieved for clients</p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Project 1 -->
                <div class="portfolio-card bg-gray-50 rounded-xl overflow-hidden shadow-md hover:shadow-lg">
                    <div class="h-48 overflow-hidden">
                        <img src="https://placehold.co/600x400" alt="E-commerce website dashboard showing 320% revenue growth after implementing marketing strategies" class="w-full h-full object-cover">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-gray-800 mb-2">E-commerce Growth</h3>
                        <p class="text-gray-600 mb-4">Increased revenue by 320% for an online fashion retailer through comprehensive digital marketing strategy.</p>
                        <div class="flex flex-wrap gap-2">
                            <span class="bg-indigo-100 text-indigo-800 px-3 py-1 rounded-full text-sm">SEO</span>
                            <span class="bg-indigo-100 text-indigo-800 px-3 py-1 rounded-full text-sm">Facebook Ads</span>
                            <span class="bg-indigo-100 text-indigo-800 px-3 py-1 rounded-full text-sm">Email Marketing</span>
                        </div>
                    </div>
                </div>
                
                <!-- Project 2 -->
                <div class="portfolio-card bg-gray-50 rounded-xl overflow-hidden shadow-md hover:shadow-lg">
                    <div class="h-48 overflow-hidden">
                        <img src="https://placehold.co/600x400" alt="Mobile app screens showing growth in user engagement metrics after marketing campaign" class="w-full h-full object-cover">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-gray-800 mb-2">App Launch Campaign</h3>
                        <p class="text-gray-600 mb-4">Successfully launched mobile app with 50,000 downloads in first month through targeted acquisition strategy.</p>
                        <div class="flex flex-wrap gap-2">
                            <span class="bg-indigo-100 text-indigo-800 px-3 py-1 rounded-full text-sm">ASO</span>
                            <span class="bg-indigo-100 text-indigo-800 px-3 py-1 rounded-full text-sm">Influencer Marketing</span>
                            <span class="bg-indigo-100 text-indigo-800 px-3 py-1 rounded-full text-sm">PPC</span>
                        </div>
                    </div>
                </div>
                
                <!-- Project 3 -->
                <div class="portfolio-card bg-gray-50 rounded-xl overflow-hidden shadow-md hover:shadow-lg">
                    <div class="h-48 overflow-hidden">
                        <img src="https://placehold.co/600x400" alt="Social media analytics dashboard showing massive growth in followers and engagement" class="w-full h-full object-cover">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-gray-800 mb-2">Social Media Growth</h3>
                        <p class="text-gray-600 mb-4">Grew Instagram following from 500 to 50,000+ in 6 months with an engagement rate of 8.7%.</p>
                        <div class="flex flex-wrap gap-2">
                            <span class="bg-indigo-100 text-indigo-800 px-3 py-1 rounded-full text-sm">Content Strategy</span>
                            <span class="bg-indigo-100 text-indigo-800 px-3 py-1 rounded-full text-sm">Community Building</span>
                            <span class="bg-indigo-100 text-indigo-800 px-3 py-1 rounded-full text-sm">Paid Ads</span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="text-center mt-12">
                <a href="#contact" class="inline-block bg-indigo-600 text-white px-8 py-3 rounded-lg font-semibold hover:bg-indigo-700 transition duration-300">See More Work</a>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="py-20 bg-indigo-50">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Client <span class="text-indigo-600">Testimonials</span></h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">See what my clients say about working with me</p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="bg-white p-8 rounded-xl shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="text-yellow-400 mr-2">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                    </div>
                    <p class="text-gray-600 mb-6">"Asadullah transformed our online presence completely. Our website traffic increased by 400% in just 3 months, and we're now ranking on the first page for all our target keywords. His strategic approach and attention to detail are unmatched."</p>
                    <div class="flex items-center">
                        <div class="mr-4">
                            <img src="https://placehold.co/60" alt="Portrait of Sarah K, satisfied client smiling" class="w-12 h-12 rounded-full">
                        </div>
                        <div>
                            <h4 class="font-bold text-gray-800">Sarah K.</h4>
                            <p class="text-gray-600">CEO, TechStart</p>
                        </div>
                    </div>
                </div>
                
                <!-- Testimonial 2 -->
                <div class="bg-white p-8 rounded-xl shadow-md">
                    <div class="flex items-center mb-4">
# Ayanmarketer
Expert digital marketer
