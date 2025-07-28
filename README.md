<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Joe's Academy of Sports and Science (JASS)</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Inter font from Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc; /* Light blue-gray background */
        }
        .section-title {
            position: relative;
            display: inline-block;
            padding-bottom: 0.5rem; /* Space for the underline */
        }
        .section-title::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            width: 70%; /* Shorter underline */
            height: 4px;
            background-color: #fcd34d; /* Yellow color */
            border-radius: 2px;
        }
    </style>
</head>
<body class="text-gray-800">

    <!-- Navigation Bar -->
    <nav class="bg-blue-800 p-4 shadow-lg">
        <div class="container mx-auto flex flex-col md:flex-row justify-between items-center">
            <div class="flex items-center space-x-3">
                <!-- Logo -->
                <!-- IMPORTANT: Ensure 'InShot_20220818_233516590.jpg' is in the same folder as this HTML file -->
                <img src="InShot_20220818_233516590.jpg" alt="JASS Logo" class="h-16 w-auto rounded-lg">
                <span class="text-white text-2xl font-bold tracking-wide">JASS</span>
            </div>
            <!-- Navigation Links -->
            <div class="mt-4 md:mt-0 flex flex-col md:flex-row space-y-2 md:space-y-0 md:space-x-6">
                <a href="#home" class="text-white hover:text-yellow-300 transition duration-300 ease-in-out px-3 py-2 rounded-md">Home</a>
                <a href="#about" class="text-white hover:text-yellow-300 transition duration-300 ease-in-out px-3 py-2 rounded-md">About Us</a>
                <a href="#programs" class="text-white hover:text-yellow-300 transition duration-300 ease-in-out px-3 py-2 rounded-md">Programs</a>
                <a href="#contact" class="text-white hover:text-yellow-300 transition duration-300 ease-in-out px-3 py-2 rounded-md">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="bg-gradient-to-r from-blue-700 to-blue-900 text-white py-20 md:py-32 flex items-center justify-center min-h-screen-75 relative overflow-hidden">
        <div class="container mx-auto px-6 text-center z-10">
            <h1 class="text-4xl md:text-6xl font-extrabold leading-tight mb-6 animate-fade-in-down">
                Unleash Your Potential at <span class="text-yellow-300">JASS</span>
            </h1>
            <p class="text-lg md:text-xl mb-10 max-w-3xl mx-auto animate-fade-in-up">
                Joe's Academy of Sports and Science: Where athletic excellence meets scientific innovation.
            </p>
            <a href="#programs" class="bg-yellow-400 hover:bg-yellow-500 text-blue-900 font-bold py-3 px-8 rounded-full shadow-lg transform hover:scale-105 transition duration-300 ease-in-out inline-block animate-bounce-once">
                Explore Our Programs
            </a>
        </div>
        <!-- Abstract shapes for background effect -->
        <div class="absolute inset-0 opacity-20">
            <svg class="w-full h-full" viewBox="0 0 100 100" preserveAspectRatio="none">
                <polygon points="0,0 100,0 100,20 0,60" fill="rgba(255,255,255,0.1)"></polygon>
                <polygon points="0,80 100,40 100,100 0,100" fill="rgba(255,255,255,0.1)"></polygon>
            </svg>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about" class="py-16 md:py-24 bg-white">
        <div class="container mx-auto px-6 max-w-5xl">
            <h2 class="text-4xl font-bold text-center mb-12 section-title mx-auto">About Joe's Academy</h2>
            <div class="flex flex-col md:flex-row items-center md:space-x-12">
                <div class="md:w-1/2 mb-8 md:mb-0">
                    <img src="https://placehold.co/600x400/e0f2fe/0284c7?text=Team+Training" alt="Team Training" class="rounded-xl shadow-xl transform hover:scale-105 transition duration-300">
                </div>
                <div class="md:w-1/2 text-lg leading-relaxed">
                    <p class="mb-4">
                        At JASS, we believe in nurturing holistic development. Our unique approach combines rigorous sports training with a strong foundation in scientific principles, preparing our students not just for athletic success but for intellectual growth and future innovation.
                    </p>
                    <p class="mb-4">
                        Founded by visionary educators and seasoned athletes, Joe's Academy is dedicated to providing a cutting-edge learning environment. We empower our students to push their boundaries, understand the 'why' behind their performance, and apply scientific knowledge to excel in their chosen fields.
                    </p>
                    <p>
                        Our state-of-the-art facilities and experienced faculty are committed to fostering a community of driven, curious, and resilient individuals. Join us to embark on a journey of discovery, discipline, and unparalleled achievement.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Programs Section -->
    <section id="programs" class="py-16 md:py-24 bg-blue-50">
        <div class="container mx-auto px-6 max-w-6xl">
            <h2 class="text-4xl font-bold text-center mb-12 section-title mx-auto">Our Programs</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10">
                <!-- Program Card 1 -->
                <div class="bg-white rounded-xl shadow-lg p-8 flex flex-col items-center text-center transform hover:scale-105 transition duration-300 ease-in-out border-t-4 border-yellow-400">
                    <div class="text-5xl text-blue-600 mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M9 19V6l12-3v13M9 19c0 1.105-1.79 2-4 2s-4-.895-4-2 1.79-2 4-2 4 .895 4 2zm-4 0V5l12-3v13c0 1.105-1.79 2-4 2s-4-.895-4-2z" />
                        </svg>
                    </div>
                    <h3 class="text-2xl font-semibold mb-4 text-blue-800">Elite Athletic Training</h3>
                    <p class="text-gray-600 mb-6">
                        Specialized coaching for various sports, focusing on technique, strength, endurance, and mental fortitude. Tailored programs for aspiring professional athletes.
                    </p>
                    <a href="#" class="text-blue-600 font-semibold hover:text-blue-800 flex items-center">
                        Learn More
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 ml-1" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7" />
                        </svg>
                    </a>
                </div>

                <!-- Program Card 2 -->
                <div class="bg-white rounded-xl shadow-lg p-8 flex flex-col items-center text-center transform hover:scale-105 transition duration-300 ease-in-out border-t-4 border-yellow-400">
                    <div class="text-5xl text-blue-600 mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M10 21h7a2 2 0 002-2V9.414a1 1 0 00-.293-.707l-5.414-5.414A1 1 0 0012.586 3H7a2 2 0 00-2 2v14a2 2 0 002 2z" />
                        </svg>
                    </div>
                    <h3 class="text-2xl font-semibold mb-4 text-blue-800">Sports Science & Analytics</h3>
                    <p class="text-gray-600 mb-6">
                        Dive deep into biomechanics, physiology, nutrition, and data analytics. Understand the science behind peak performance and injury prevention.
                    </p>
                    <a href="#" class="text-blue-600 font-semibold hover:text-blue-800 flex items-center">
                        Learn More
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 ml-1" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7" />
                        </svg>
                    </a>
                </div>

                <!-- Program Card 3 -->
                <div class="bg-white rounded-xl shadow-lg p-8 flex flex-col items-center text-center transform hover:scale-105 transition duration-300 ease-in-out border-t-4 border-yellow-400">
                    <div class="text-5xl text-blue-600 mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.246 18 16.5 18c-1.747 0-3.332.477-4.5 1.253" />
                        </svg>
                    </div>
                    <h3 class="text-2xl font-semibold mb-4 text-blue-800">Academic Excellence</h3>
                    <p class="text-gray-600 mb-6">
                        Integrated academic curriculum designed to complement athletic schedules, ensuring students excel in both sports and their studies.
                    </p>
                    <a href="#" class="text-blue-600 font-semibold hover:text-blue-800 flex items-center">
                        Learn More
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 ml-1" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7" />
                        </svg>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Call to Action Section -->
    <section class="bg-blue-800 text-white py-16 md:py-20 text-center">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-bold mb-6">Ready to Join JASS?</h2>
            <p class="text-lg md:text-xl mb-8 max-w-2xl mx-auto">
                Take the first step towards a future of athletic and academic success. Contact us today to learn more about admissions!
            </p>
            <a href="#contact" class="bg-yellow-400 hover:bg-yellow-500 text-blue-900 font-bold py-3 px-8 rounded-full shadow-lg transform hover:scale-105 transition duration-300 ease-in-out inline-block">
                Get in Touch
            </a>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 md:py-24 bg-white">
        <div class="container mx-auto px-6 max-w-4xl">
            <h2 class="text-4xl font-bold text-center mb-12 section-title mx-auto">Contact Us</h2>
            <div class="flex flex-col md:flex-row md:space-x-12">
                <div class="md:w-1/2 mb-8 md:mb-0">
                    <h3 class="text-2xl font-semibold mb-4 text-blue-800">Reach Out</h3>
                    <p class="mb-4 text-gray-700">
                        Have questions about our programs, admissions, or anything else? We'd love to hear from you!
                    </p>
                    <ul class="space-y-3 text-gray-700">
                        <li class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-blue-600 mr-3" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                                <path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                            </svg>
                            123 Sports & Science Blvd, Academy City, 560001
                        </li>
                        <li class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-blue-600 mr-3" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
                            </svg>
                            +91 95973 61310
                        </li>
                        <li class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-blue-600 mr-3" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                            </svg>
                            jpjack185@gmail.com
                        </li>
                    </ul>
                </div>
                <div class="md:w-1/2">
                    <h3 class="text-2xl font-semibold mb-4 text-blue-800">Send Us a Message</h3>
                    <form class="space-y-4">
                        <div>
                            <label for="name" class="block text-gray-700 text-sm font-bold mb-2">Name</label>
                            <input type="text" id="name" name="name" class="shadow-sm appearance-none border rounded-lg w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent transition duration-200" placeholder="Your Name" required>
                        </div>
                        <div>
                            <label for="email" class="block text-gray-700 text-sm font-bold mb-2">Email</label>
                            <input type="email" id="email" name="email" class="shadow-sm appearance-none border rounded-lg w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent transition duration-200" placeholder="your@example.com" required>
                        </div>
                        <div>
                            <label for="message" class="block text-gray-700 text-sm font-bold mb-2">Message</label>
                            <textarea id="message" name="message" rows="5" class="shadow-sm appearance-none border rounded-lg w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent transition duration-200" placeholder="Your message..." required></textarea>
                        </div>
                        <button type="submit" class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-6 rounded-full shadow-md transform hover:scale-105 transition duration-300 ease-in-out">
                            Send Message
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-6 text-center text-sm">
            <p>&copy; 2024 Joe's Academy of Sports and Science (JASS). All rights reserved.</p>
            <div class="flex justify-center space-x-4 mt-4">
                <a href="#" class="hover:text-yellow-300 transition duration-300">Privacy Policy</a>
                <a href="#" class="hover:text-yellow-300 transition duration-300">Terms of Service</a>
            </div>
        </div>
    </footer>

</body>
</html>
