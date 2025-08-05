<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ALLMOST entertainment</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .gradient-text {
            background: linear-gradient(90deg, #6366f1 0%, #8b5cf6 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        .ticket-card:hover {
            transform: translateY(-8px);
            transition: all 0.3s ease;
        }
        .gallery-img:hover {
            transform: scale(1.05);
            transition: all 0.3s ease;
        }
        /* Make logo 3x larger and invert to white */
        .logo {
            height: 12rem; /* 3x larger: ~192px */
            filter: invert(1); /* Makes logo white */
            object-fit: contain;
        }
    </style>
</head>
<body class="bg-gradient-to-br from-slate-900 via-purple-900 to-slate-900 min-h-screen">
    <!-- Navigation -->
    <nav class="bg-black/20 backdrop-blur-md border-b border-white/10 sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center py-4">
                <div class="flex items-center space-x-3">
                    <!-- Your Logo - 3x Larger & Inverted -->
                    <img src="https://lh3.googleusercontent.com/d/1TTFr0C1GOm_joUsjUXLcckJ4-IuChe0L" alt="ALLMOST entertainment Logo" class="logo">
                </div>
                <div class="hidden md:flex space-x-8">
                    <a href="#events" class="text-gray-300 hover:text-white transition duration-200">Events</a>
                    <a href="#gallery" class="text-gray-300 hover:text-white transition duration-200">Gallery</a>
                    <a href="#about" class="text-gray-300 hover:text-white transition duration-200">About</a>
                    <a href="#contact" class="text-gray-300 hover:text-white transition duration-200">Contact</a>
                </div>
                <button class="bg-gradient-to-r from-purple-500 to-pink-500 text-white px-6 py-2 rounded-full hover:shadow-lg hover:shadow-purple-500/25 transition duration-200 font-medium">
                    Sign In
                </button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <div class="relative overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20">
            <div class="text-center">
                <h1 class="text-5xl md:text-7xl font-bold text-white mb-6">
                    Experience <span class="gradient-text">Unforgettable</span> Events
                </h1>
                <p class="text-xl text-gray-300 mb-10 max-w-3xl mx-auto">
                    Discover amazing concerts, festivals, and cultural events. Secure your tickets today and create memories that last a lifetime.
                </p>
                <div class="flex flex-col sm:flex-row gap-4 justify-center">
                    <a href="#events" class="bg-gradient-to-r from-purple-500 to-pink-500 text-white px-8 py-4 rounded-full text-lg font-semibold hover:shadow-xl hover:shadow-purple-500/25 transition-all duration-300 transform hover:-translate-y-1">
                        Buy Tickets Now
                    </a>
                    <a href="#events" class="border border-white/30 text-white px-8 py-4 rounded-full text-lg font-semibold hover:bg-white/10 transition-all duration-300">
                        View Events
                    </a>
                </div>
            </div>
            
            <!-- Floating elements -->
            <div class="absolute top-20 left-10 w-20 h-20 bg-purple-500/20 rounded-full blur-3xl"></div>
            <div class="absolute bottom-20 right-10 w-32 h-32 bg-pink-500/20 rounded-full blur-3xl"></div>
            <div class="absolute top-1/2 left-5 w-16 h-16 bg-blue-500/20 rounded-full blur-2xl"></div>
        </div>
    </div>

    <!-- Events Section -->
    <section id="events" class="py-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-white mb-4">Upcoming Events</h2>
                <p class="text-xl text-gray-400">Choose your next unforgettable experience</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Event 1 -->
                <div class="ticket-card bg-white/10 backdrop-blur-md border border-white/20 rounded-2xl overflow-hidden hover:bg-white/20 transition-all duration-300">
                    <div class="h-48 bg-gradient-to-r from-blue-500 to-purple-600 relative">
                        <div class="absolute top-4 right-4 bg-black/50 text-white px-3 py-1 rounded-full text-sm font-medium">
                            Concert
                        </div>
                        <div class="absolute bottom-4 left-4">
                            <p class="text-white text-sm opacity-90">August 15, 2025</p>
                            <p class="text-white font-semibold">7:00 PM</p>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-white mb-2">Summer Music Festival</h3>
                        <p class="text-gray-300 mb-4">Downtown Amphitheater • 15,000 capacity</p>
                        <div class="flex justify-between items-center mb-4">
                            <span class="text-2xl font-bold text-white">$49</span>
                            <span class="text-sm text-gray-400">starting at</span>
                        </div>
                        <button class="w-full bg-gradient-to-r from-purple-500 to-pink-500 text-white py-3 rounded-xl hover:shadow-lg hover:shadow-purple-500/25 transition-all duration-200 font-medium">
                            Get Tickets
                        </button>
                    </div>
                </div>

                <!-- Event 2 -->
                <div class="ticket-card bg-white/10 backdrop-blur-md border border-white/20 rounded-2xl overflow-hidden hover:bg-white/20 transition-all duration-300">
                    <div class="h-48 bg-gradient-to-r from-green-500 to-teal-600 relative">
                        <div class="absolute top-4 right-4 bg-black/50 text-white px-3 py-1 rounded-full text-sm font-medium">
                            Festival
                        </div>
                        <div class="absolute bottom-4 left-4">
                            <p class="text-white text-sm opacity-90">September 5-7, 2025</p>
                            <p class="text-white font-semibold">All Weekend</p>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-white mb-2">Art & Culture Festival</h3>
                        <p class="text-gray-300 mb-4">Riverside Park • Multiple stages</p>
                        <div class="flex justify-between items-center mb-4">
                            <span class="text-2xl font-bold text-white">$75</span>
                            <span class="text-sm text-gray-400">3-day pass</span>
                        </div>
                        <button class="w-full bg-gradient-to-r from-purple-500 to-pink-500 text-white py-3 rounded-xl hover:shadow-lg hover:shadow-purple-500/25 transition-all duration-200 font-medium">
                            Get Tickets
                        </button>
                    </div>
                </div>

                <!-- Event 3 -->
                <div class="ticket-card bg-white/10 backdrop-blur-md border border-white/20 rounded-2xl overflow-hidden hover:bg-white/20 transition-all duration-300">
                    <div class="h-48 bg-gradient-to-r from-orange-500 to-red-600 relative">
                        <div class="absolute top-4 right-4 bg-black/50 text-white px-3 py-1 rounded-full text-sm font-medium">
                            Comedy
                        </div>
                        <div class="absolute bottom-4 left-4">
                            <p class="text-white text-sm opacity-90">October 12, 2025</p>
                            <p class="text-white font-semibold">8:30 PM</p>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-white mb-2">Comedy Night Live</h3>
                        <p class="text-gray-300 mb-4">Grand Theater • Limited seating</p>
                        <div class="flex justify-between items-center mb-4">
                            <span class="text-2xl font-bold text-white">$35</span>
                            <span class="text-sm text-gray-400">per ticket</span>
                        </div>
                        <button class="w-full bg-gradient-to-r from-purple-500 to-pink-500 text-white py-3 rounded-xl hover:shadow-lg hover:shadow-purple-500/25 transition-all duration-200 font-medium">
                            Get Tickets
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="py-20 bg-black/20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-white mb-4">Event Gallery</h2>
                <p class="text-xl text-gray-400">Relive the magic of past events</p>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4">
                <!-- Gallery Images -->
                <div class="gallery-img aspect-square bg-gradient-to-br from-purple-600 to-blue-600 rounded-xl overflow-hidden hover:shadow-2xl transition-all duration-300 cursor-pointer group">
                    <img src="https://placehold.co/300x300/6366f1/ffffff?text=Concert+Night" alt="Concert" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-300">
                </div>
                <div class="gallery-img aspect-square bg-gradient-to-br from-pink-600 to-purple-600 rounded-xl overflow-hidden hover:shadow-2xl transition-all duration-300 cursor-pointer group">
                    <img src="https://placehold.co/300x300/8b5cf6/ffffff?text=Music+Festival" alt="Festival" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-300">
                </div>
                <div class="gallery-img aspect-square bg-gradient-to-br from-blue-600 to-cyan-600 rounded-xl overflow-hidden hover:shadow-2xl transition-all duration-300 cursor-pointer group">
                    <img src="https://placehold.co/300x300/06b6d4/ffffff?text=Art+Exhibit" alt="Art" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-300">
                </div>
                <div class="gallery-img aspect-square bg-gradient-to-br from-green-600 to-emerald-600 rounded-xl overflow-hidden hover:shadow-2xl transition-all duration-300 cursor-pointer group">
                    <img src="https://placehold.co/300x300/10b981/ffffff?text=Outdoor+Event" alt="Outdoor" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-300">
                </div>
                <div class="gallery-img aspect-square bg-gradient-to-br from-orange-600 to-red-600 rounded-xl overflow-hidden hover:shadow-2xl transition-all duration-300 cursor-pointer group">
                    <img src="https://placehold.co/300x300/f97316/ffffff?text=Comedy+Show" alt="Comedy" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-300">
                </div>
                <div class="gallery-img aspect-square bg-gradient-to-br from-indigo-600 to-purple-600 rounded-xl overflow-hidden hover:shadow-2xl transition-all duration-300 cursor-pointer group">
                    <img src="https://placehold.co/300x300/4f46e5/ffffff?text=Theater+Performance" alt="Theater" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-300">
                </div>
                <div class="gallery-img aspect-square bg-gradient-to-br from-teal-600 to-cyan-600 rounded-xl overflow-hidden hover:shadow-2xl transition-all duration-300 cursor-pointer group">
                    <img src="https://placehold.co/300x300/14b8a6/ffffff?text=Cultural+Festival" alt="Cultural" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-300">
                </div>
                <div class="gallery-img aspect-square bg-gradient-to-br from-rose-600 to-pink-600 rounded-xl overflow-hidden hover:shadow-2xl transition-all duration-300 cursor-pointer group">
                    <img src="https://placehold.co/300x300/ec4899/ffffff?text=VIP+Experience" alt="VIP" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-300">
                </div>
            </div>

            <div class="text-center mt-12">
                <button class="border border-white/30 text-white px-8 py-3 rounded-full hover:bg-white/10 transition-all duration-300 font-medium">
                    View More Photos
                </button>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="py-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-white mb-4">Why Choose ALLMOST entertainment?</h2>
                <p class="text-xl text-gray-400">The most trusted platform for event tickets</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Feature 1 -->
                <div class="text-center">
                    <div class="w-16 h-16 bg-gradient-to-r from-purple-500 to-pink-500 rounded-2xl flex items-center justify-center mx-auto mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 10h18M7 15h1m4 0h1m-7 4h12a3 3 0 003-3V8a3 3 0 00-3-3H6a3 3 0 00-3 3v8a3 3 0 003 3z" />
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-2">Secure Payments</h3>
                    <p class="text-gray-400">Your transactions are protected with bank-level encryption</p>
                </div>

                <!-- Feature 2 -->
                <div class="text-center">
                    <div class="w-16 h-16 bg-gradient-to-r from-blue-500 to-cyan-500 rounded-2xl flex items-center justify-center mx-auto mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-2">Instant Delivery</h3>
                    <p class="text-gray-400">Receive your e-tickets immediately after purchase</p>
                </div>

                <!-- Feature 3 -->
                <div class="text-center">
                    <div class="w-16 h-16 bg-gradient-to-r from-green-500 to-emerald-500 rounded-2xl flex items-center justify-center mx-auto mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.165-2.052-.48-3.016z" />
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-2">100% Authentic</h3>
                    <p class="text-gray-400">Guaranteed genuine tickets with no hidden fees</p>
                </div>

                <!-- Feature 4 -->
                <div class="text-center">
                    <div class="w-16 h-16 bg-gradient-to-r from-orange-500 to-red-500 rounded-2xl flex items-center justify-center mx-auto mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-4.5 4.5zm0 10.163c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-2">Best Price Guarantee</h3>
                    <p class="text-gray-400">We'll match any lower price you find elsewhere</p>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="py-20">
        <div class="max-w-4xl mx-auto text-center px-4 sm:px-6 lg:px-8">
            <div class="bg-gradient-to-r from-purple-600/20 to-pink-600/20 backdrop-blur-md border border-white/20 rounded-3xl p-12">
                <h2 class="text-4xl font-bold text-white mb-6">Ready to Experience Amazing Events?</h2>
                <p class="text-xl text-gray-300 mb-8">Join thousands of happy customers who've created unforgettable memories with ALLMOST entertainment.</p>
                <div class="flex flex-col sm:flex-row gap-4 justify-center">
                    <a href="#events" class="bg-gradient-to-r from-purple-500 to-pink-500 text-white px-8 py-4 rounded-full text-lg font-semibold hover:shadow-xl hover:shadow-purple-500/25 transition-all duration-300">
                        Get Your Tickets Now
                    </a>
                    <a href="#events" class="border border-white/30 text-white px-8 py-4 rounded-full text-lg font-semibold hover:bg-white/10 transition-all duration-300">
                        Browse Events
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-black/40 border-t border-white/10 py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div class="col-span-1 md:col-span-2">
                    <div class="flex items-center mb-4">
                        <!-- Your Logo - 3x Larger & Inverted -->
                        <img src="https://lh3.googleusercontent.com/d/1TTFr0C1GOm_joUsjUXLcckJ4-IuChe0L" alt="ALLMOST entertainment Logo" class="logo">
                    </div>
                    <p class="text-gray-400 mb-4">
                        The premier destination for event tickets and experiences. We connect you with the best concerts, festivals, and cultural events.
                    </p>
                    <div class="flex space-x-4">
                        <a href="#" class="text-gray-400 hover:text-white transition duration-200">
                            <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24"><path d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z"/></svg>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white transition duration-200">
                            <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.163c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/></svg>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white transition duration-200">
                            <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24"><path d="M9 8h-3v4h3v12h5v-12h3.642l.358-4h-4v-1.667c0-.955.192-1.333 1.115-1.333h2.885v-5h-3.808c-3.596 0-5.192 1.583-5.192 4.615v3.385z"/></svg>
                        </a>
                    </div>
                </div>
                
                <div>
                    <h3 class="text-white font-semibold mb-4">Events</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white transition duration-200">Concerts</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition duration-200">Festivals</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition duration-200">Theater</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition duration-200">Comedy</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition duration-200">Sports</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-white font-semibold mb-4">Support</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white transition duration-200">Help Center</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition duration-200">Contact Us</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition duration-200">Refund Policy</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition duration-200">Terms of Service</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition duration-200">Privacy Policy</a></li>
                    </ul>
                </div>
            </div>
            
            <div class="border-t border-white/10 mt-8 pt-8 text-center">
                <p class="text-gray-400">© 2025 ALLMOST entertainment. All rights reserved.</p>
            </div>
        </div>
    </footer>
</body>
</html>
