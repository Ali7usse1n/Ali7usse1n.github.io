<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>كافتيريا الربيع - Al-Rabi' Cafeteria</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap');
        body {
            font-family: 'Cairo', sans-serif;
            background-color: #fdfaf5;
            color: #2c2c2c;
            scroll-behavior: smooth;
        }
        .hero-bg {
            background-image: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?auto=format&fit=crop&q=80&w=2070');
            background-size: cover;
            background-position: center;
        }
        .menu-item-card {
            background: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .menu-item-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
        }
        .price-tag {
            background: #c2410c;
            color: white;
            padding: 4px 12px;
            border-radius: 20px;
            font-weight: bold;
            font-size: 0.9rem;
        }
        .section-title {
            position: relative;
            display: inline-block;
            margin-bottom: 2rem;
        }
        .section-title::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 0;
            right: 0;
            height: 3px;
            background: #c2410c;
            border-radius: 2px;
        }
    </style>
</head>
<body class="bg-stone-50">

    <!-- Navigation -->
    <nav class="fixed w-full z-50 bg-white/90 backdrop-blur-md border-b border-stone-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <div class="flex items-center">
                    <span class="text-2xl font-bold text-orange-800">كافتيريا الربيع</span>
                </div>
                <div class="hidden md:flex items-center space-x-8 space-x-reverse">
                    <a href="#home" class="text-stone-700 hover:text-orange-800 font-medium transition-colors">الرئيسية</a>
                    <a href="#menu" class="text-stone-700 hover:text-orange-800 font-medium transition-colors">المنيو</a>
                    <a href="#about" class="text-stone-700 hover:text-orange-800 font-medium transition-colors">من نحن</a>
                    <a href="#contact" class="text-stone-700 hover:text-orange-800 font-medium transition-colors">اتصل بنا</a>
                </div>
                <div class="md:hidden">
                    <button class="text-stone-700 p-2"><i class="fas fa-bars text-xl"></i></button>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-bg h-screen flex items-center justify-center text-center text-white relative">
        <div class="container mx-auto px-4">
            <h1 class="text-5xl md:text-8xl font-bold mb-6 drop-shadow-2xl">كافتيريا الربيع</h1>
            <p class="text-xl md:text-3xl mb-10 opacity-90 max-w-2xl mx-auto font-light">استمتع بأفضل المشروبات والمأكولات في جو رائع ومريح</p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center">
                <a href="#menu" class="bg-orange-600 hover:bg-orange-700 text-white px-10 py-4 rounded-full text-lg font-bold transition-all transform hover:scale-105 shadow-lg">استعرض المنيو</a>
            </div>
        </div>
    </section>

    <!-- Menu Section -->
    <section id="menu" class="py-24">
        <div class="container mx-auto px-4">
            <div class="text-center mb-20">
                <h2 class="text-4xl md:text-5xl font-bold text-stone-800 section-title">قائمة المذاق الرفيع</h2>
                <p class="text-stone-500 mt-4 text-lg">نقدم لكم تشكيلة مختارة بعناية لتناسب جميع الأذواق</p>
            </div>

            <!-- Hookah Section -->
            <div class="mb-20">
                <h3 class="text-3xl font-bold text-orange-900 mb-10 border-r-4 border-orange-600 pr-4">قسم الأرجيلة</h3>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                    <!-- Shisha Item 1 -->
                    <div class="menu-item-card">
                        <img src="https://images.unsplash.com/photo-1527661591475-527312dd65f5?auto=format&fit=crop&q=80&w=600" alt="نعناع" class="w-full h-48 object-cover">
                        <div class="p-4">
                            <h4 class="text-xl font-bold text-stone-800 mb-2">أرجيلة نعناع</h4>
                            <div class="flex justify-between items-center">
                                <span class="price-tag">3,000 د.ع</span>
                            </div>
                        </div>
                    </div>
                    <!-- Shisha Item 2 -->
                    <div class="menu-item-card">
                        <img src="https://images.unsplash.com/photo-1527661591475-527312dd65f5?auto=format&fit=crop&q=80&w=600" alt="تفاحتين" class="w-full h-48 object-cover">
                        <div class="p-4">
                            <h4 class="text-xl font-bold text-stone-800 mb-2">أرجيلة تفاحتين</h4>
                            <div class="flex justify-between items-center">
                                <span class="price-tag">3,000 د.ع</span>
                            </div>
                        </div>
                    </div>
                    <!-- Shisha Item 3 -->
                    <div class="menu-item-card">
                        <img src="https://images.unsplash.com/photo-1527661591475-527312dd65f5?auto=format&fit=crop&q=80&w=600" alt="عنب" class="w-full h-48 object-cover">
                        <div class="p-4">
                            <h4 class="text-xl font-bold text-stone-800 mb-2">أرجيلة عنب</h4>
                            <div class="flex justify-between items-center">
                                <span class="price-tag">3,000 د.ع</span>
                            </div>
                        </div>
                    </div>
                    <!-- Shisha Item 4 -->
                    <div class="menu-item-card">
                        <img src="https://images.unsplash.com/photo-1527661591475-527312dd65f5?auto=format&fit=crop&q=80&w=600" alt="طبيعي اناناس" class="w-full h-48 object-cover">
                        <div class="p-4">
                            <h4 class="text-xl font-bold text-stone-800 mb-2">أرجيلة طبيعي اناناس</h4>
                            <div class="flex justify-between items-center">
                                <span class="price-tag">15,000 د.ع</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Juices Section -->
            <div class="mb-20">
                <h3 class="text-3xl font-bold text-orange-900 mb-10 border-r-4 border-orange-600 pr-4">عصائر طبيعية</h3>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                    <!-- Juice Item 1 -->
                    <div class="menu-item-card">
                        <img src="https://images.unsplash.com/photo-1600271886332-699bb2798b9b?auto=format&fit=crop&q=80&w=600" alt="برتقال" class="w-full h-48 object-cover">
                        <div class="p-4">
                            <h4 class="text-xl font-bold text-stone-800 mb-2">برتقال طبيعي</h4>
                            <div class="flex justify-between items-center">
                                <span class="price-tag">2,000 د.ع</span>
                            </div>
                        </div>
                    </div>
                    <!-- Juice Item 2 -->
                    <div class="menu-item-card">
                        <img src="https://images.unsplash.com/photo-1523677012304-d0251105151b?auto=format&fit=crop&q=80&w=600" alt="ليمون" class="w-full h-48 object-cover">
                        <div class="p-4">
                            <h4 class="text-xl font-bold text-stone-800 mb-2">ليمون فريش</h4>
                            <div class="flex justify-between items-center">
                                <span class="price-tag">2,000 د.ع</span>
                            </div>
                        </div>
                    </div>
                    <!-- Juice Item 3 -->
                    <div class="menu-item-card">
                        <img src="https://images.unsplash.com/photo-1551024709-8f23befc6f87?auto=format&fit=crop&q=80&w=600" alt="كوكتيل" class="w-full h-48 object-cover">
                        <div class="p-4">
                            <h4 class="text-xl font-bold text-stone-800 mb-2">كوكتيل فواكه</h4>
                            <div class="flex justify-between items-center">
                                <span class="price-tag">1,000 د.ع</span>
                            </div>
                        </div>
                    </div>
                    <!-- Juice Item 4 -->
                    <div class="menu-item-card">
                        <img src="https://images.unsplash.com/photo-1563227812-0ea4c22e6cc8?auto=format&fit=crop&q=80&w=600" alt="بطيخ" class="w-full h-48 object-cover">
                        <div class="p-4">
                            <h4 class="text-xl font-bold text-stone-800 mb-2">عصير بطيخ</h4>
                            <div class="flex justify-between items-center">
                                <span class="price-tag">1,000 د.ع</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Food Section -->
            <div class="mb-20">
                <h3 class="text-3xl font-bold text-orange-900 mb-10 border-r-4 border-orange-600 pr-4">مأكولات وحلويات</h3>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                    <!-- Food Item 1 -->
                    <div class="menu-item-card">
                        <img src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd?auto=format&fit=crop&q=80&w=600" alt="همبركر" class="w-full h-48 object-cover">
                        <div class="p-4">
                            <h4 class="text-xl font-bold text-stone-800 mb-2">همبركر لحم</h4>
                            <div class="flex justify-between items-center">
                                <span class="price-tag">1,500 د.ع</span>
                            </div>
                        </div>
                    </div>
                    <!-- Food Item 2 -->
                    <div class="menu-item-card">
                        <img src="https://images.unsplash.com/photo-1528207776546-365bb710ee93?auto=format&fit=crop&q=80&w=600" alt="بانكيك" class="w-full h-48 object-cover">
                        <div class="p-4">
                            <h4 class="text-xl font-bold text-stone-800 mb-2">بانكيك نوتيلا</h4>
                            <div class="flex justify-between items-center">
                                <span class="price-tag">5,000 د.ع</span>
                            </div>
                        </div>
                    </div>
                    <!-- Food Item 3 -->
                    <div class="menu-item-card">
                        <img src="https://images.unsplash.com/photo-1519676867240-f03562e64548?auto=format&fit=crop&q=80&w=600" alt="كريب" class="w-full h-48 object-cover">
                        <div class="p-4">
                            <h4 class="text-xl font-bold text-stone-800 mb-2">كريب فواكه</h4>
                            <div class="flex justify-between items-center">
                                <span class="price-tag">4,000 د.ع</span>
                            </div>
                        </div>
                    </div>
                    <!-- Food Item 4 -->
                    <div class="menu-item-card">
                        <img src="https://images.unsplash.com/photo-1534778101976-62847782c213?auto=format&fit=crop&q=80&w=600" alt="كابتشينو" class="w-full h-48 object-cover">
                        <div class="p-4">
                            <h4 class="text-xl font-bold text-stone-800 mb-2">كابتشينو</h4>
                            <div class="flex justify-between items-center">
                                <span class="price-tag">1,000 د.ع</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </section>

    <!-- Footer -->
    <footer id="contact" class="bg-stone-900 text-white py-12">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold mb-4">كافتيريا الربيع</h2>
            <p class="mb-6 text-stone-400">أفضل تجربة تذوق في المنطقة. تفضل بزيارتنا!</p>
            <div class="flex justify-center space-x-6 space-x-reverse text-2xl mb-8">
                <a href="#" class="hover:text-orange-500 transition-colors"><i class="fab fa-facebook"></i></a>
                <a href="#" class="hover:text-orange-500 transition-colors"><i class="fab fa-instagram"></i></a>
                <a href="#" class="hover:text-orange-500 transition-colors"><i class="fab fa-whatsapp"></i></a>
            </div>
            <p class="text-stone-500">© 2026 كافتيريا الربيع. جميع الحقوق محفوظة.</p>
        </div>
    </footer>

</body>
</html>