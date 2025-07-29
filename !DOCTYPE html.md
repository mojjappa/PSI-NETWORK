<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>PSI NETWORK | Connect with Physics, Science \& Innovation Minds</title>

    <script src="https://cdn.tailwindcss.com"></script>

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <style>

        .gradient-bg {

            background: linear-gradient(135deg, #6e8efb, #a777e3);

        }

        .post-card:hover {

            transform: translateY(-5px);

            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);

        }

        .category-chip {

            transition: all 0.3s ease;

        }

        .category-chip:hover {

            transform: scale(1.05);

        }

        .like-animation {

            animation: like 0.6s ease;

        }

        @keyframes like {

            0% { transform: scale(1); }

            50% { transform: scale(1.3); }

            100% { transform: scale(1); }

        }

    </style>

</head>

<body class="bg-gray-50 min-h-screen">

    <!-- Navigation -->

    <nav class="gradient-bg text-white shadow-lg">

        <div class="container mx-auto px-4 py-3 flex justify-between items-center">

            <div class="flex items-center space-x-2">

                <i class="fas fa-atom text-2xl">

                <h1 class="text-xl font-bold">PSI NETWORK</h1>

            </div>

            <div class="hidden md:flex space-x-6">

                <a href="#" class="hover:text-gray-200 font-medium">Home</a>

                <a href="#" class="hover:text-gray-200 font-medium">Explore</a>

                <a href="#" class="hover:text-gray-200 font-medium">Topics</a>

                <a href="#" class="hover:text-gray-200 font-medium">Events</a>

            </div>

            <div class="flex items-center space-x-4">

                <div class="relative">

                    <input type="text" placeholder="Search..." class="px-4 py-2 rounded-full text-gray-800 focus:outline-none focus:ring-2 focus:ring-purple-300 w-32 md:w-64">

                    <i class="fas fa-search absolute right-3 top-2.5 text-gray-500">

                </div>

                <div class="w-8 h-8 rounded-full bg-white flex items-center justify-center text-purple-600 font-bold cursor-pointer">U</div>

            </div>

            <button class="md:hidden">

                <i class="fas fa-bars text-xl">

            </button>

        </div>

    </nav>



    <!-- Main Content -->

    <div class="container mx-auto px-4 py-6 flex flex-col md:flex-row gap-6">

        <!-- Left Sidebar -->

        <div class="w-full md:w-1/4 lg:w-1/5 space-y-4">

            <!-- User Profile Card -->

            <div class="bg-white rounded-lg shadow p-4">

                <div class="flex flex-col items-center">

                    <div class="w-20 h-20 rounded-full bg-purple-100 flex items-center justify-center text-purple-600 text-2xl font-bold mb-3">U</div>

                    <h3 class="font-bold text-lg">User Name</h3>

                    <p class="text-gray-500 text-sm">@username</p>

                    <div class="flex justify-between w-full mt-3 text-sm">

                        <div class="text-center">

                            <div class="font-bold">142</div>

                            <div class="text-gray-500">Posts</div>

                        </div>

                        <div class="text-center">

                            <div class="font-bold">1.2K</div>

                            <div class="text-gray-500">Followers</div>

                        </div>

                        <div class="text-center">

                            <div class="font-bold">356</div>

                            <div class="text-gray-500">Following</div>

                        </div>

                    </div>

                </div>

            </div>



            <!-- Categories -->

            <div class="bg-white rounded-lg shadow p-4">

                <h3 class="font-bold text-lg mb-3">Categories</h3>

                <div class="space-y-2">

                    <div class="category-chip bg-purple-100 text-purple-800 px-3 py-1 rounded-full text-sm font-medium cursor-pointer flex items-center justify-between">

                        <span>Physics</span>

                        <span class="bg-white rounded-full w-5 h-5 flex items-center justify-center text-xs">42</span>

                    </div>

                    <div class="category-chip bg-blue-100 text-blue-800 px-3 py-1 rounded-full text-sm font-medium cursor-pointer flex items-center justify-between">

                        <span>Mathematics</span>

                        <span class="bg-white rounded-full w-5 h-5 flex items-center justify-center text-xs">36</span>

                    </div>

                    <div class="category-chip bg-green-100 text-green-800 px-3 py-1 rounded-full text-sm font-medium cursor-pointer flex items-center justify-between">

                        <span>Technology</span>

                        <span class="bg-white rounded-full w-5 h-5 flex items-center justify-center text-xs">78</span>

                    </div>

                    <div class="category-chip bg-yellow-100 text-yellow-800 px-3 py-1 rounded-full text-sm font-medium cursor-pointer flex items-center justify-between">

                        <span>Entrepreneurship</span>

                        <span class="bg-white rounded-full w-5 h-5 flex items-center justify-center text-xs">24</span>

                    </div>

                    <div class="category-chip bg-red-100 text-red-800 px-3 py-1 rounded-full text-sm font-medium cursor-pointer flex items-center justify-between">

                        <span>Research</span>

                        <span class="bg-white rounded-full w-5 h-5 flex items-center justify-center text-xs">15</span>

                    </div>

                </div>

            </div>



            <!-- Trending Topics -->

            <div class="bg-white rounded-lg shadow p-4">

                <h3 class="font-bold text-lg mb-3">Trending Topics</h3>

                <div class="space-y-3">

                    <div class="flex items-start space-x-2">

                        <div class="bg-gray-100 rounded-full w-8 h-8 flex items-center justify-center text-sm font-bold">1</div>

                        <div>

                            <h4 class="font-medium text-sm">Quantum Computing</h4>

                            <p class="text-gray-500 text-xs">1.2K posts</p>

                        </div>

                    </div>

                    <div class="flex items-start space-x-2">

                        <div class="bg-gray-100 rounded-full w-8 h-8 flex items-center justify-center text-sm font-bold">2</div>

                        <div>

                            <h4 class="font-medium text-sm">AI Ethics</h4>

                            <p class="text-gray-500 text-xs">980 posts</p>

                        </div>

                    </div>

                    <div class="flex items-start space-x-2">

                        <div class="bg-gray-100 rounded-full w-8 h-8 flex items-center justify-center text-sm font-bold">3</div>

                        <div>

                            <h4 class="font-medium text-sm">String Theory</h4>

                            <p class="text-gray-500 text-xs">756 posts</p>

                        </div>

                    </div>

                    <div class="flex items-start space-x-2">

                        <div class="bg-gray-100 rounded-full w-8 h-8 flex items-center justify-center text-sm font-bold">4</div>

                        <div>

                            <h4 class="font-medium text-sm">Startup Funding</h4>

                            <p class="text-gray-500 text-xs">632 posts</p>

                        </div>

                    </div>

                </div>

            </div>

        </div>



        <!-- Main Feed -->

        <div class="w-full md:w-2/4 lg:w-3/5 space-y-6">

            <!-- Create Post -->

            <div class="bg-white rounded-lg shadow p-4">

                <div class="flex space-x-3">

                    <div class="w-10 h-10 rounded-full bg-purple-100 flex items-center justify-center text-purple-600 font-bold">U</div>

                    <input type="text" placeholder="Share your thoughts on science, tech or business..." class="flex-1 bg-gray-100 rounded-full px-4 py-2 focus:outline-none focus:ring-2 focus:ring-purple-300 cursor-pointer" onclick="document.getElementById('post-modal').classList.remove('hidden')">

                </div>

                <div class="flex justify-between mt-3 px-2">

                    <button class="flex items-center text-gray-500 hover:text-purple-600 text-sm">

                        <i class="fas fa-image mr-1"> Photo

                    </button>

                    <button class="flex items-center text-gray-500 hover:text-purple-600 text-sm">

                        <i class="fas fa-link mr-1"> Link

                    </button>

                    <button class="flex items-center text-gray-500 hover:text-purple-600 text-sm">

                        <i class="fas fa-poll mr-1"> Poll

                    </button>

                    <button class="flex items-center text-gray-500 hover:text-purple-600 text-sm">

                        <i class="fas fa-code mr-1"> Code

                    </button>

                </div>

            </div>



            <!-- Post Filters -->

            <div class="bg-white rounded-lg shadow p-3">

                <div class="flex space-x-4 overflow-x-auto pb-2">

                    <button class="bg-purple-600 text-white px-4 py-1 rounded-full text-sm font-medium whitespace-nowrap">Latest</button>

                    <button class="bg-gray-100 hover:bg-gray-200 px-4 py-1 rounded-full text-sm font-medium whitespace-nowrap">Popular</button>

                    <button class="bg-gray-100 hover:bg-gray-200 px-4 py-1 rounded-full text-sm font-medium whitespace-nowrap">Physics</button>

                    <button class="bg-gray-100 hover:bg-gray-200 px-4 py-1 rounded-full text-sm font-medium whitespace-nowrap">Math</button>

                    <button class="bg-gray-100 hover:bg-gray-200 px-4 py-1 rounded-full text-sm font-medium whitespace-nowrap">Tech</button>

                    <button class="bg-gray-100 hover:bg-gray-200 px-4 py-1 rounded-full text-sm font-medium whitespace-nowrap">Business</button>

                </div>

            </div>



            <!-- Sample Post 1 -->

            <div class="post-card bg-white rounded-lg shadow p-4 transition duration-300">

                <div class="flex justify-between items-start">

                    <div class="flex space-x-3">

                        <div class="w-10 h-10 rounded-full bg-blue-100 flex items-center justify-center text-blue-600 font-bold">M</div>

                        <div>

                            <h3 class="font-bold">Marie Curie</h3>

                            <p class="text-gray-500 text-sm">Physics Researcher · 2h ago</p>

                        </div>

                    </div>

                    <button class="text-gray-400 hover:text-gray-600">

                        <i class="fas fa-ellipsis-h">

                    </button>

                </div>

                <div class="mt-3">

                    <p class="text-gray-800">Just published our latest research on radioactive elements! The implications for medical applications are particularly exciting. What do you think about the future of radiation therapy?</p>

                    <div class="mt-2 flex flex-wrap gap-2">

                        <span class="bg-blue-100 text-blue-800 px-2 py-1 rounded-full text-xs font-medium">#Physics</span>

                        <span class="bg-purple-100 text-purple-800 px-2 py-1 rounded-full text-xs font-medium">#Research</span>

                        <span class="bg-green-100 text-green-800 px-2 py-1 rounded-full text-xs font-medium">#Medicine</span>

                    </div>

                </div>

                <div class="mt-4 flex justify-between border-t border-b border-gray-100 py-2">

                    <button class="like-btn flex items-center text-gray-500 hover:text-red-500" onclick="toggleLike(this)">

                        <i class="far fa-heart mr-1"> <span>142</span>

                    </button>

                    <button class="flex items-center text-gray-500 hover:text-blue-500" onclick="toggleComments('comments1')">

                        <i class="far fa-comment mr-1"> 36

                    </button>

                    <button class="flex items-center text-gray-500 hover:text-green-500">

                        <i class="fas fa-share mr-1"> Share

                    </button>

                    <button class="flex items-center text-gray-500 hover:text-purple-500">

                        <i class="far fa-bookmark">

                    </button>

                </div>

 

                <!-- Comments Section (Initially Hidden) -->

                <div id="comments1" class="hidden mt-3 space-y-3">

                    <div class="flex space-x-3">

                        <div class="w-8 h-8 rounded-full bg-gray-100 flex items-center justify-center text-sm font-bold">A</div>

                        <div class="flex-1 bg-gray-50 rounded-lg p-2">

                            <div class="font-medium text-sm">Albert Einstein</div>

                            <p class="text-gray-700 text-sm">Fascinating work, Marie! The potential applications in targeted cancer treatments could be revolutionary.</p>

                            <div class="flex text-xs text-gray-500 mt-1 space-x-3">

                                <span>1h ago</span>

                                <button class="hover:text-gray-700">Like</button>

                                <button class="hover:text-gray-700">Reply</button>

                            </div>

                        </div>

                    </div>

                    <div class="flex space-x-3 pl-11">

                        <div class="w-8 h-8 rounded-full bg-gray-100 flex items-center justify-center text-sm font-bold">N</div>

                        <div class="flex-1 bg-gray-50 rounded-lg p-2">

                            <div class="font-medium text-sm">Niels Bohr</div>

                            <p class="text-gray-700 text-sm">Have you considered the quantum mechanical implications of your findings?</p>

                            <div class="flex text-xs text-gray-500 mt-1 space-x-3">

                                <span>45m ago</span>

                                <button class="hover:text-gray-700">Like</button>

                                <button class="hover:text-gray-700">Reply</button>

                            </div>

                        </div>

                    </div>

                    <div class="flex space-x-3 mt-2">

                        <div class="w-8 h-8 rounded-full bg-gray-100 flex items-center justify-center text-sm font-bold">Y</div>

                        <div class="flex-1">

                            <input type="text" placeholder="Write a comment..." class="w-full bg-gray-50 rounded-full px-3 py-1 text-sm focus:outline-none focus:ring-1 focus:ring-purple-300">

                        </div>

                    </div>

                </div>

            </div>



            <!-- Sample Post 2 -->

            <div class="post-card bg-white rounded-lg shadow p-4 transition duration-300">

                <div class="flex justify-between items-start">

                    <div class="flex space-x-3">

                        <div class="w-10 h-10 rounded-full bg-green-100 flex items-center justify-center text-green-600 font-bold">E</div>

                        <div>

                            <h3 class="font-bold">Elon Musk</h3>

                            <p class="text-gray-500 text-sm">Tech Entrepreneur · 5h ago</p>

                        </div>

                    </div>

                    <button class="text-gray-400 hover:text-gray-600">

                        <i class="fas fa-ellipsis-h">

                    </button>

                </div>

                <div class="mt-3">

                    <p class="text-gray-800">The future of AI is both exciting and concerning. We need to ensure proper regulation while not stifling innovation. What's your take on balancing these two aspects?</p>

                    <div class="mt-3 bg-gray-50 rounded-lg p-3">

                        <div class="flex items-center text-sm text-gray-600 mb-1">

                            <i class="fas fa-link mr-2">

                            <span>ai-ethics.org/regulation-framework</span>

                        </div>

                        <h4 class="font-medium">AI Regulation Framework for the 21st Century</h4>

                        <p class="text-gray-600 text-sm mt-1">A comprehensive look at potential regulatory approaches for artificial intelligence systems...</p>

                    </div>

                    <div class="mt-2 flex flex-wrap gap-2">

                        <span class="bg-green-100 text-green-800 px-2 py-1 rounded-full text-xs font-medium">#Technology</span>

                        <span class="bg-yellow-100 text-yellow-800 px-2 py-1 rounded-full text-xs font-medium">#AI</span>

                        <span class="bg-blue-100 text-blue-800 px-2 py-1 rounded-full text-xs font-medium">#Entrepreneurship</span>

                    </div>

                </div>

                <div class="mt-4 flex justify-between border-t border-b border-gray-100 py-2">

                    <button class="like-btn flex items-center text-gray-500 hover:text-red-500" onclick="toggleLike(this)">

                        <i class="far fa-heart mr-1"> <span>892</span>

                    </button>

                    <button class="flex items-center text-gray-500 hover:text-blue-500" onclick="toggleComments('comments2')">

                        <i class="far fa-comment mr-1"> 147

                    </button>

                    <button class="flex items-center text-gray-500 hover:text-green-500">

                        <i class="fas fa-share mr-1"> Share

                    </button>

                    <button class="flex items-center text-gray-500 hover:text-purple-500">

                        <i class="far fa-bookmark">

                    </button>

                </div>

 

                <!-- Comments Section (Initially Hidden) -->

                <div id="comments2" class="hidden mt-3 space-y-3">

                    <div class="flex space-x-3">

                        <div class="w-8 h-8 rounded-full bg-gray-100 flex items-center justify-center text-sm font-bold">B</div>

                        <div class="flex-1 bg-gray-50 rounded-lg p-2">

                            <div class="font-medium text-sm">Bill Gates</div>

                            <p class="text-gray-700 text-sm">I agree we need thoughtful regulation. The Gates Foundation is working on policy recommendations in this space.</p>

                            <div class="flex text-xs text-gray-500 mt-1 space-x-3">

                                <span>3h ago</span>

                                <button class="hover:text-gray-700">Like</button>

                                <button class="hover:text-gray-700">Reply</button>

                            </div>

                        </div>

                    </div>

                    <div class="flex space-x-3">

                        <div class="w-8 h-8 rounded-full bg-gray-100 flex items-center justify-center text-sm font-bold">S</div>

                        <div class="flex-1">

                            <input type="text" placeholder="Write a comment..." class="w-full bg-gray-50 rounded-full px-3 py-1 text-sm focus:outline-none focus:ring-1 focus:ring-purple-300">

                        </div>

                    </div>

                </div>

            </div>



            <!-- Sample Post 3 -->

            <div class="post-card bg-white rounded-lg shadow p-4 transition duration-300">

                <div class="flex justify-between items-start">

                    <div class="flex space-x-3">

                        <div class="w-10 h-10 rounded-full bg-yellow-100 flex items-center justify-center text-yellow-600 font-bold">T</div>

                        <div>

                            <h3 class="font-bold">Terence Tao</h3>

                            <p class="text-gray-500 text-sm">Mathematician · 1d ago</p>

                        </div>

                    </div>

                    <button class="text-gray-400 hover:text-gray-600">

                        <i class="fas fa-ellipsis-h">

                    </button>

                </div>

                <div class="mt-3">

                    <p class="text-gray-800">Sharing my latest paper on prime number distribution patterns. This could have implications for cryptography algorithms. Feedback welcome!</p>

                    <div class="mt-3 bg-gray-50 rounded-lg p-3 border border-gray-200">

                        <div class="flex items-center justify-between">

                            <div class="flex items-center">

                                <i class="fas fa-file-pdf text-red-500 mr-2">

                                <div>

                                    <h4 class="font-medium">Prime Patterns in Modular Spaces</h4>

                                    <p class="text-gray-600 text-sm">PDF · 2.4MB</p>

                                </div>

                            </div>

                            <button class="text-blue-500 hover:text-blue-700 text-sm font-medium">

                                <i class="fas fa-download mr-1"> Download

                            </button>

                        </div>

                    </div>

                    <div class="mt-2 flex flex-wrap gap-2">

                        <span class="bg-blue-100 text-blue-800 px-2 py-1 rounded-full text-xs font-medium">#Mathematics</span>

                        <span class="bg-purple-100 text-purple-800 px-2 py-1 rounded-full text-xs font-medium">#Research</span>

                        <span class="bg-green-100 text-green-800 px-2 py-1 rounded-full text-xs font-medium">#Cryptography</span>

                    </div>

                </div>

                <div class="mt-4 flex justify-between border-t border-b border-gray-100 py-2">

                    <button class="like-btn flex items-center text-gray-500 hover:text-red-500" onclick="toggleLike(this)">

                        <i class="far fa-heart mr-1"> <span>356</span>

                    </button>

                    <button class="flex items-center text-gray-500 hover:text-blue-500" onclick="toggleComments('comments3')">

                        <i class="far fa-comment mr-1"> 42

                    </button>

                    <button class="flex items-center text-gray-500 hover:text-green-500">

                        <i class="fas fa-share mr-1"> Share

                    </button>

                    <button class="flex items-center text-gray-500 hover:text-purple-500">

                        <i class="far fa-bookmark">

                    </button>

                </div>

 

                <!-- Comments Section (Initially Hidden) -->

                <div id="comments3" class="hidden mt-3 space-y-3">

                    <div class="flex space-x-3">

                        <div class="w-8 h-8 rounded-full bg-gray-100 flex items-center justify-center text-sm font-bold">A</div>

                        <div class="flex-1 bg-gray-50 rounded-lg p-2">

                            <div class="font-medium text-sm">Andrew Wiles</div>

                            <p class="text-gray-700 text-sm">Brilliant work as always, Terence. The connections to elliptic curves are particularly interesting.</p>

                            <div class="flex text-xs text-gray-500 mt-1 space-x-3">

                                <span>18h ago</span>

                                <button class="hover:text-gray-700">Like</button>

                                <button class="hover:text-gray-700">Reply</button>

                            </div>

                        </div>

                    </div>

                    <div class="flex space-x-3">

                        <div class="w-8 h-8 rounded-full bg-gray-100 flex items-center justify-center text-sm font-bold">C</div>

                        <div class="flex-1">

                            <input type="text" placeholder="Write a comment..." class="w-full bg-gray-50 rounded-full px-3 py-1 text-sm focus:outline-none focus:ring-1 focus:ring-purple-300">

                        </div>

                    </div>

                </div>

            </div>

        </div>



        <!-- Right Sidebar -->

        <div class="w-full md:w-1/4 lg:w-1/5 space-y-4">

            <!-- Upcoming Events -->

            <div class="bg-white rounded-lg shadow p-4">

                <h3 class="font-bold text-lg mb-3">Upcoming Events</h3>

                <div class="space-y-3">

                    <div class="flex space-x-3">

                        <div class="bg-purple-100 text-purple-800 rounded-lg w-12 h-12 flex flex-col items-center justify-center">

                            <div class="font-bold text-sm">JUN</div>

                            <div class="font-bold">15</div>

                        </div>

                        <div>

                            <h4 class="font-medium text-sm">Quantum Computing Summit</h4>

                            <p class="text-gray-500 text-xs">Virtual · 10:00 AM</p>

                            <button class="text-purple-600 text-xs font-medium mt-1">Register</button>

                        </div>

                    </div>

                    <div class="flex space-x-3">

                        <div class="bg-blue-100 text-blue-800 rounded-lg w-12 h-12 flex flex-col items-center justify-center">

                            <div class="font-bold text-sm">JUN</div>

                            <div class="font-bold">22</div>

                        </div>

                        <div>

                            <h4 class="font-medium text-sm">Math Olympiad Workshop</h4>

                            <p class="text-gray-500 text-xs">New York · 2:00 PM</p>

                            <button class="text-blue-600 text-xs font-medium mt-1">Register</button>

                        </div>

                    </div>

                    <div class="flex space-x-3">

                        <div class="bg-green-100 text-green-800 rounded-lg w-12 h-12 flex flex-col items-center justify-center">

                            <div class="font-bold text-sm">JUL</div>

                            <div class="font-bold">05</div>

                        </div>

                        <div>

                            <h4 class="font-medium text-sm">Tech Startup Pitch Night</h4>

                            <p class="text-gray-500 text-xs">San Francisco · 6:30 PM</p>

                            <button class="text-green-600 text-xs font-medium mt-1">Register</button>

                        </div>

                    </div>

                </div>

                <button class="w-full mt-3 text-purple-600 font-medium text-sm text-center">View All Events</button>

            </div>



            <!-- Recommended Connections -->

            <div class="bg-white rounded-lg shadow p-4">

                <h3 class="font-bold text-lg mb-3">Recommended Connections</h3>

                <div class="space-y-3">

                    <div class="flex items-center justify-between">

                        <div class="flex items-center space-x-2">

                            <div class="w-8 h-8 rounded-full bg-red-100 flex items-center justify-center text-red-600 font-bold text-sm">R</div>

                            <div>

                                <h4 class="font-medium text-sm">Richard Feynman</h4>

                                <p class="text-gray-500 text-xs">Theoretical Physicist</p>

                            </div>

                        </div>

                        <button class="text-purple-600 text-xs font-medium">Connect</button>

                    </div>

                    <div class="flex items-center justify-between">

                        <div class="flex items-center space-x-2">

                            <div class="w-8 h-8 rounded-full bg-indigo-100 flex items-center justify-center text-indigo-600 font-bold text-sm">G</div>

                            <div>

                                <h4 class="font-medium text-sm">Grace Hopper</h4>

                                <p class="text-gray-500 text-xs">Computer Scientist</p>

                            </div>

                        </div>

                        <button class="text-purple-600 text-xs font-medium">Connect</button>

                    </div>

                    <div class="flex items-center justify-between">

                        <div class="flex items-center space-x-2">

                            <div class="w-8 h-8 rounded-full bg-yellow-100 flex items-center justify-center text-yellow-600 font-bold text-sm">S</div>

                            <div>

                                <h4 class="font-medium text-sm">Steve Jobs</h4>

                                <p class="text-gray-500 text-xs">Tech Entrepreneur</p>

                            </div>

                        </div>

                        <button class="text-purple-600 text-xs font-medium">Connect</button>

                    </div>

                </div>

                <button class="w-full mt-3 text-purple-600 font-medium text-sm text-center">See All</button>

            </div>



            <!-- Trending Papers -->

            <div class="bg-white rounded-lg shadow p-4">

                <h3 class="font-bold text-lg mb-3">Trending Papers</h3>

                <div class="space-y-3">

                    <div class="flex space-x-2">

                        <i class="fas fa-file-alt text-gray-400 mt-1">

                        <div>

                            <h4 class="font-medium text-sm">"Neural Networks for Quantum State Approximation"</h4>

                            <p class="text-gray-500 text-xs">Nature Physics · 1.2K reads</p>

                        </div>

                    </div>

                    <div class="flex space-x-2">

                        <i class="fas fa-file-alt text-gray-400 mt-1">

                        <div>

                            <h4 class="font-medium text-sm">"A New Approach to P=NP"</h4>

                            <p class="text-gray-500 text-xs">Journal of ACM · 856 reads</p>

                        </div>

                    </div>

                    <div class="flex space-x-2">

                        <i class="fas fa-file-alt text-gray-400 mt-1">

                        <div>

                            <h4 class="font-medium text-sm">"Sustainable Tech Business Models"</h4>

                            <p class="text-gray-500 text-xs">Harvard Review · 723 reads</p>

                        </div>

                    </div>

                </div>

                <button class="w-full mt-3 text-purple-600 font-medium text-sm text-center">Browse Papers</button>

            </div>

        </div>

    </div>



    <!-- Create Post Modal -->

    <div id="post-modal" class="hidden fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50">

        <div class="bg-white rounded-lg w-full max-w-md mx-4">

            <div class="flex justify-between items-center border-b border-gray-200 p-4">

                <h3 class="font-bold text-lg">Create Post</h3>

                <button onclick="document.getElementById('post-modal').classList.add('hidden')" class="text-gray-500 hover:text-gray-700">

                    <i class="fas fa-times">

                </button>

            </div>

            <div class="p-4">

                <div class="flex space-x-3 mb-4">

                    <div class="w-10 h-10 rounded-full bg-purple-100 flex items-center justify-center text-purple-600 font-bold">U</div>

                    <div>

                        <h4 class="font-medium">User Name</h4>

                        <div class="flex space-x-2 mt-1">

                            <select class="bg-gray-100 border-0 rounded-full text-sm focus:ring-1 focus:ring-purple-300">

                                <option>Public</option>

                                <option>Connections</option>

                                <option>Private</option>

                            </select>

                        </div>

                    </div>

                </div>

                <textarea class="w-full border-0 focus:ring-0 resize-none text-gray-800 placeholder-gray-400" rows="5" placeholder="What's on your mind about science, tech or business?"></textarea>

                <div class="flex items-center justify-between border border-gray-200 rounded-lg p-2 mt-2">

                    <span class="text-sm text-gray-500 ml-2">Add to your post</span>

                    <div class="flex space-x-2">

                        <button class="w-8 h-8 rounded-full bg-gray-100 flex items-center justify-center text-blue-500">

                            <i class="fas fa-image">

                        </button>

                        <button class="w-8 h-8 rounded-full bg-gray-100 flex items-center justify-center text-green-500">

                            <i class="fas fa-link">

                        </button>

                        <button class="w-8 h-8 rounded-full bg-gray-100 flex items-center justify-center text-yellow-500">

                            <i class="fas fa-poll">

                        </button>

                        <button class="w-8 h-8 rounded-full bg-gray-100 flex items-center justify-center text-purple-500">

                            <i class="fas fa-code">

                        </button>

                    </div>

                </div>

            </div>

            <div class="border-t border-gray-200 p-4">

                <button class="w-full bg-purple-600 hover:bg-purple-700 text-white font-medium py-2 px-4 rounded-lg">

                    Post

                </button>

            </div>

        </div>

    </div>



    <script>

        // Toggle like button

        function toggleLike(button) {

            const icon = button.querySelector('i');

            const countSpan = button.querySelector('span');

            let count = parseInt(countSpan.textContent);

 

            if (icon.classList.contains('far')) {

                icon.classList.remove('far');

                icon.classList.add('fas', 'like-animation');

                countSpan.textContent = count + 1;

            } else {

                icon.classList.remove('fas');

                icon.classList.add('far');

                countSpan.textContent = count - 1;

            }

        }



        // Toggle comments section

        function toggleComments(commentId) {

            const commentsSection = document.getElementById(commentId);

            commentsSection.classList.toggle('hidden');

        }



        // Simulate clicking on a category chip

        document.querySelectorAll('.category-chip').forEach(chip => {

            chip.addEventListener('click', function() {

                // In a real app, this would filter the posts

                alert(`Filtering by ${this.querySelector('span').textContent}`);

            });

        });

    </script>

</body>

# </html>.[.html](.html)

