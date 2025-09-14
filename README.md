<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Developer Freelancer - GitHub Profile</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'github-dark': '#0d1117',
                        'github-border': '#30363d',
                        'github-text': '#e6edf3',
                        'github-accent': '#58a6ff',
                        'github-green': '#238636'
                    },
                    fontFamily: {
                        'mono': ['JetBrains Mono', 'Consolas', 'Monaco', 'monospace']
                    }
                }
            }
        }
    </script>
    <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        .typing-animation {
            border-right: 2px solid #58a6ff;
            animation: typing 3s steps(40, end), blink-caret 0.75s step-end infinite;
        }
        
        @keyframes typing {
            from { width: 0 }
            to { width: 100% }
        }
        
        @keyframes blink-caret {
            from, to { border-color: transparent }
            50% { border-color: #58a6ff }
        }
        
        .code-block {
            background: linear-gradient(135deg, #161b22 0%, #0d1117 100%);
            border: 1px solid #30363d;
        }
        
        .skill-badge {
            transition: all 0.3s ease;
        }
        
        .skill-badge:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(88, 166, 255, 0.3);
        }
        
        .commit-graph {
            display: grid;
            grid-template-columns: repeat(53, 1fr);
            gap: 2px;
        }
        
        .commit-day {
            width: 10px;
            height: 10px;
            border-radius: 2px;
            background: #161b22;
        }
        
        .commit-level-1 { background: #0e4429; }
        .commit-level-2 { background: #006d32; }
        .commit-level-3 { background: #26a641; }
        .commit-level-4 { background: #39d353; }
    </style>
</head>
<body class="bg-github-dark text-github-text font-mono">
    <!-- Header -->
    <header class="border-b border-github-border bg-github-dark/95 backdrop-blur-sm sticky top-0 z-50">
        <div class="container mx-auto px-4 py-4">
            <div class="flex items-center justify-between">
                <div class="flex items-center space-x-4">
                    <div class="w-10 h-10 bg-github-accent rounded-full flex items-center justify-center">
                        <svg class="w-6 h-6 text-white" fill="currentColor" viewBox="0 0 20 20">
                            <path fill-rule="evenodd" d="M10 9a3 3 0 100-6 3 3 0 000 6zm-7 9a7 7 0 1114 0H3z" clip-rule="evenodd"/>
                        </svg>
                    </div>
                    <div>
                        <h1 class="text-xl font-semibold">WebDev-Freelancer</h1>
                        <p class="text-sm text-gray-400">Professional Web Developer</p>
                    </div>
                </div>
                <div class="flex items-center space-x-4">
                    <span class="text-sm text-gray-400">📍 Vietnam</span>
                    <span class="text-sm text-gray-400">💼 Available for hire</span>
                </div>
            </div>
        </div>
    </header>

    <!-- Main Content -->
    <main class="container mx-auto px-4 py-8">
        <!-- Profile Section -->
        <section class="mb-12">
            <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
                <!-- Left Column - Profile Info -->
                <div class="lg:col-span-1">
                    <div class="code-block rounded-lg p-6 mb-6">
                        <div class="w-32 h-32 bg-gradient-to-br from-github-accent to-github-green rounded-full mx-auto mb-4 flex items-center justify-center">
                            <svg class="w-16 h-16 text-white" fill="currentColor" viewBox="0 0 20 20">
                                <path d="M13 6a3 3 0 11-6 0 3 3 0 016 0zM18 8a2 2 0 11-4 0 2 2 0 014 0zM14 15a4 4 0 00-8 0v3h8v-3z"/>
                            </svg>
                        </div>
                        <h2 class="text-2xl font-bold text-center mb-2">Web Developer</h2>
                        <p class="text-github-accent text-center mb-4">Freelancer</p>
                        
                        <!-- Stats -->
                        <div class="grid grid-cols-3 gap-4 text-center mb-6">
                            <div>
                                <div class="text-2xl font-bold text-github-accent">50+</div>
                                <div class="text-xs text-gray-400">Projects</div>
                            </div>
                            <div>
                                <div class="text-2xl font-bold text-github-accent">5+</div>
                                <div class="text-xs text-gray-400">Years</div>
                            </div>
                            <div>
                                <div class="text-2xl font-bold text-github-accent">100%</div>
                                <div class="text-xs text-gray-400">Satisfied</div>
                            </div>
                        </div>

                        <!-- Contact Info -->
                        <div class="space-y-3 text-sm">
                            <div class="flex items-center">
                                <svg class="w-4 h-4 mr-3 text-github-accent" fill="currentColor" viewBox="0 0 20 20">
                                    <path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"/>
                                    <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"/>
                                </svg>
                                <span>webdev@example.com</span>
                            </div>
                            <div class="flex items-center">
                                <svg class="w-4 h-4 mr-3 text-github-accent" fill="currentColor" viewBox="0 0 20 20">
                                    <path fill-rule="evenodd" d="M12.586 4.586a2 2 0 112.828 2.828l-3 3a2 2 0 01-2.828 0 1 1 0 00-1.414 1.414 4 4 0 005.656 0l3-3a4 4 0 00-5.656-5.656l-1.5 1.5a1 1 0 101.414 1.414l1.5-1.5zm-5 5a2 2 0 012.828 0 1 1 0 101.414-1.414 4 4 0 00-5.656 0l-3 3a4 4 0 105.656 5.656l1.5-1.5a1 1 0 10-1.414-1.414l-1.5 1.5a2 2 0 11-2.828-2.828l3-3z" clip-rule="evenodd"/>
                                </svg>
                                <span>portfolio-website.com</span>
                            </div>
                            <div class="flex items-center">
                                <svg class="w-4 h-4 mr-3 text-github-accent" fill="currentColor" viewBox="0 0 20 20">
                                    <path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"/>
                                </svg>
                                <span>+84 123 456 789</span>
                            </div>
                        </div>
                    </div>

                    <!-- Skills -->
                    <div class="code-block rounded-lg p-6">
                        <h3 class="text-lg font-semibold mb-4 flex items-center">
                            <svg class="w-5 h-5 mr-2 text-github-accent" fill="currentColor" viewBox="0 0 20 20">
                                <path d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
                            </svg>
                            Technical Skills
                        </h3>
                        <div class="space-y-3">
                            <div class="flex flex-wrap gap-2">
                                <span class="skill-badge bg-orange-600 text-white px-3 py-1 rounded-full text-xs">HTML5</span>
                                <span class="skill-badge bg-blue-600 text-white px-3 py-1 rounded-full text-xs">CSS3</span>
                                <span class="skill-badge bg-yellow-500 text-black px-3 py-1 rounded-full text-xs">JavaScript</span>
                                <span class="skill-badge bg-purple-600 text-white px-3 py-1 rounded-full text-xs">PHP</span>
                                <span class="skill-badge bg-blue-500 text-white px-3 py-1 rounded-full text-xs">WordPress</span>
                                <span class="skill-badge bg-green-600 text-white px-3 py-1 rounded-full text-xs">MySQL</span>
                                <span class="skill-badge bg-red-600 text-white px-3 py-1 rounded-full text-xs">Git</span>
                                <span class="skill-badge bg-gray-600 text-white px-3 py-1 rounded-full text-xs">Responsive</span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Right Column - Main Content -->
                <div class="lg:col-span-2">
                    <!-- Tagline -->
                    <div class="code-block rounded-lg p-8 mb-8 text-center">
                        <h2 class="text-3xl font-bold mb-4 text-github-accent typing-animation overflow-hidden whitespace-nowrap">
                            "Biến ý tưởng thành website chuẩn SEO & tối ưu trải nghiệm."
                        </h2>
                    </div>

                    <!-- About Me -->
                    <div class="code-block rounded-lg p-6 mb-8">
                        <h3 class="text-xl font-semibold mb-4 flex items-center">
                            <svg class="w-5 h-5 mr-2 text-github-accent" fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z" clip-rule="evenodd"/>
                            </svg>
                            README.md
                        </h3>
                        <div class="prose prose-invert max-w-none">
                            <p class="mb-4">
                                Xin chào! Tôi là Web Developer Freelancer với <strong class="text-github-accent">5+ năm kinh nghiệm</strong> chuyên thiết kế và lập trình website từ code tay (HTML/CSS/JavaScript/PHP) và WordPress.
                            </p>
                            
                            <h4 class="text-github-accent font-semibold mb-3">🚀 Chuyên môn của tôi:</h4>
                            <ul class="list-disc list-inside space-y-2 mb-4">
                                <li>Thiết kế giao diện hiện đại, chuẩn UX/UI</li>
                                <li>Tối ưu tốc độ tải trang và responsive mọi thiết bị</li>
                                <li>Phát triển website doanh nghiệp, landing page, blog, cửa hàng online</li>
                                <li>Sửa chữa code và bảo trì website</li>
                            </ul>

                            <h4 class="text-github-accent font-semibold mb-3">✅ Cam kết với khách hàng:</h4>
                            <ul class="list-disc list-inside space-y-2 mb-4">
                                <li>Giao đúng deadline đã thỏa thuận</li>
                                <li>Hỗ trợ tận tình sau bàn giao</li>
                                <li>Bảo mật cao, mã nguồn sạch</li>
                                <li>Tư vấn miễn phí trước khi triển khai</li>
                            </ul>

                            <p class="mb-4">
                                Mỗi dự án đều được tôi chăm chút tỉ mỉ để mang lại trải nghiệm tốt nhất cho người dùng và hiệu quả kinh doanh cho khách hàng.
                            </p>

                            <div class="bg-github-accent/10 border border-github-accent/30 rounded-lg p-4 mt-6">
                                <p class="text-github-accent font-semibold text-center">
                                    🤝 Sẵn sàng hợp tác? Liên hệ ngay để được tư vấn chi tiết!
                                </p>
                            </div>
                        </div>
                    </div>

                    <!-- Services -->
                    <div class="code-block rounded-lg p-6 mb-8">
                        <h3 class="text-xl font-semibold mb-4 flex items-center">
                            <svg class="w-5 h-5 mr-2 text-github-accent" fill="currentColor" viewBox="0 0 20 20">
                                <path d="M9 2a1 1 0 000 2h2a1 1 0 100-2H9z"/>
                                <path fill-rule="evenodd" d="M4 5a2 2 0 012-2v1a1 1 0 102 0V3a2 2 0 012 2v6a2 2 0 01-2 2H6a2 2 0 01-2-2V5zm2.5 7a1.5 1.5 0 100-3 1.5 1.5 0 000 3zm2.45 4a2.5 2.5 0 10-4.9 0h4.9zM12 9a1 1 0 100 2h3a1 1 0 100-2h-3zm-1 4a1 1 0 011-1h2a1 1 0 110 2h-2a1 1 0 01-1-1z" clip-rule="evenodd"/>
                            </svg>
                            Services Offered
                        </h3>
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                            <div class="border border-github-border rounded-lg p-4 hover:border-github-accent transition-colors">
                                <h4 class="font-semibold text-github-accent mb-2">🏢 Website Doanh Nghiệp</h4>
                                <p class="text-sm text-gray-400">Thiết kế website chuyên nghiệp, tăng uy tín thương hiệu</p>
                            </div>
                            <div class="border border-github-border rounded-lg p-4 hover:border-github-accent transition-colors">
                                <h4 class="font-semibold text-github-accent mb-2">🎯 Landing Page</h4>
                                <p class="text-sm text-gray-400">Trang đích tối ưu chuyển đổi, tăng tỷ lệ bán hàng</p>
                            </div>
                            <div class="border border-github-border rounded-lg p-4 hover:border-github-accent transition-colors">
                                <h4 class="font-semibold text-github-accent mb-2">🛒 Cửa Hàng Online</h4>
                                <p class="text-sm text-gray-400">E-commerce hoàn chỉnh với giỏ hàng và thanh toán</p>
                            </div>
                            <div class="border border-github-border rounded-lg p-4 hover:border-github-accent transition-colors">
                                <h4 class="font-semibold text-github-accent mb-2">🔧 Bảo Trì & Sửa Code</h4>
                                <p class="text-sm text-gray-400">Hỗ trợ kỹ thuật, cập nhật và tối ưu website</p>
                            </div>
                        </div>
                    </div>

                    <!-- GitHub Activity -->
                    <div class="code-block rounded-lg p-6">
                        <h3 class="text-xl font-semibold mb-4 flex items-center">
                            <svg class="w-5 h-5 mr-2 text-github-accent" fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd" d="M6 2a1 1 0 00-1 1v1H4a2 2 0 00-2 2v10a2 2 0 002 2h12a2 2 0 002-2V6a2 2 0 00-2-2h-1V3a1 1 0 10-2 0v1H7V3a1 1 0 00-1-1zm0 5a1 1 0 000 2h8a1 1 0 100-2H6z" clip-rule="evenodd"/>
                            </svg>
                            GitHub Activity
                        </h3>
                        <div class="mb-4">
                            <div class="flex items-center justify-between mb-2">
                                <span class="text-sm text-gray-400">Contributions in the last year</span>
                                <span class="text-sm text-github-accent">1,247 contributions</span>
                            </div>
                            <div class="commit-graph mb-4" id="commit-graph">
                                <!-- Generated by JavaScript -->
                            </div>
                            <div class="flex items-center justify-between text-xs text-gray-400">
                                <span>Less</span>
                                <div class="flex space-x-1">
                                    <div class="commit-day"></div>
                                    <div class="commit-day commit-level-1"></div>
                                    <div class="commit-day commit-level-2"></div>
                                    <div class="commit-day commit-level-3"></div>
                                    <div class="commit-day commit-level-4"></div>
                                </div>
                                <span>More</span>
                            </div>
                        </div>

                        <!-- Recent Repositories -->
                        <div class="space-y-3">
                            <h4 class="font-semibold text-github-accent">📁 Recent Projects</h4>
                            <div class="space-y-2">
                                <div class="flex items-center justify-between p-3 border border-github-border rounded hover:border-github-accent transition-colors">
                                    <div>
                                        <h5 class="font-medium">ecommerce-website</h5>
                                        <p class="text-xs text-gray-400">Modern e-commerce site with PHP & MySQL</p>
                                    </div>
                                    <div class="flex items-center space-x-2 text-xs text-gray-400">
                                        <span class="w-3 h-3 bg-orange-500 rounded-full"></span>
                                        <span>HTML</span>
                                    </div>
                                </div>
                                <div class="flex items-center justify-between p-3 border border-github-border rounded hover:border-github-accent transition-colors">
                                    <div>
                                        <h5 class="font-medium">responsive-portfolio</h5>
                                        <p class="text-xs text-gray-400">Responsive portfolio template</p>
                                    </div>
                                    <div class="flex items-center space-x-2 text-xs text-gray-400">
                                        <span class="w-3 h-3 bg-blue-500 rounded-full"></span>
                                        <span>CSS</span>
                                    </div>
                                </div>
                                <div class="flex items-center justify-between p-3 border border-github-border rounded hover:border-github-accent transition-colors">
                                    <div>
                                        <h5 class="font-medium">wordpress-theme</h5>
                                        <p class="text-xs text-gray-400">Custom WordPress theme for business</p>
                                    </div>
                                    <div class="flex items-center space-x-2 text-xs text-gray-400">
                                        <span class="w-3 h-3 bg-purple-500 rounded-full"></span>
                                        <span>PHP</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="border-t border-github-border py-8">
        <div class="container mx-auto px-4 text-center">
            <div class="flex flex-col md:flex-row items-center justify-between">
                <div class="mb-4 md:mb-0">
                    <p class="text-gray-400">&copy; 2024 Web Developer Freelancer. All rights reserved.</p>
                </div>
                <div class="flex space-x-6">
                    <a href="#" class="text-gray-400 hover:text-github-accent transition-colors">
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20">
                            <path fill-rule="evenodd" d="M10 0C4.477 0 0 4.484 0 10.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0110 4.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.203 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.942.359.31.678.921.678 1.856 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0020 10.017C20 4.484 15.522 0 10 0z" clip-rule="evenodd"/>
                        </svg>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-github-accent transition-colors">
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20">
                            <path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"/>
                            <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"/>
                        </svg>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-github-accent transition-colors">
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20">
                            <path fill-rule="evenodd" d="M12.586 4.586a2 2 0 112.828 2.828l-3 3a2 2 0 01-2.828 0 1 1 0 00-1.414 1.414 4 4 0 005.656 0l3-3a4 4 0 00-5.656-5.656l-1.5 1.5a1 1 0 101.414 1.414l1.5-1.5zm-5 5a2 2 0 012.828 0 1 1 0 101.414-1.414 4 4 0 00-5.656 0l-3 3a4 4 0 105.656 5.656l1.5-1.5a1 1 0 10-1.414-1.414l-1.5 1.5a2 2 0 11-2.828-2.828l3-3z" clip-rule="evenodd"/>
                        </svg>
                    </a>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Generate commit graph
        function generateCommitGraph() {
            const graph = document.getElementById('commit-graph');
            const totalDays = 371; // ~53 weeks
            
            for (let i = 0; i < totalDays; i++) {
                const day = document.createElement('div');
                day.className = 'commit-day';
                
                // Random commit activity
                const activity = Math.random();
                if (activity > 0.8) day.classList.add('commit-level-4');
                else if (activity > 0.6) day.classList.add('commit-level-3');
                else if (activity > 0.4) day.classList.add('commit-level-2');
                else if (activity > 0.2) day.classList.add('commit-level-1');
                
                graph.appendChild(day);
            }
        }

        // Initialize on load
        document.addEventListener('DOMContentLoaded', function() {
            generateCommitGraph();
            
            // Add click handlers for contact buttons
            document.querySelectorAll('a[href="#"]').forEach(link => {
                link.addEventListener('click', function(e) {
                    e.preventDefault();
                    alert('Liên hệ: webdev@example.com hoặc +84 123 456 789');
                });
            });
        });

        // Typing animation restart
        setInterval(() => {
            const typingElement = document.querySelector('.typing-animation');
            typingElement.style.animation = 'none';
            setTimeout(() => {
                typingElement.style.animation = 'typing 3s steps(40, end), blink-caret 0.75s step-end infinite';
            }, 100);
        }, 10000);
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'97ef9b81745e6c00',t:'MTc1Nzg1MDAwNS4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
