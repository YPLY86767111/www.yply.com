[index.html](https://github.com/user-attachments/files/26198009/index.html)
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>青岛市一品良印图文快印有限公司 - 专业门头设计 | 黑彩同价五分钱</title>
    <meta name="description" content="青岛一品良印专注专业门头设计、发光字、灯箱制作，黑彩同价仅0.05元，9.9元全国包邮，3公里免费送货，当天加急出稿！">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#1A4B8C', // 深海蓝
                        secondary: '#FF7A2E', // 活力橙
                        light: '#F5F7FA', // 浅灰
                    },
                    fontFamily: {
                        sans: ['思源黑体', 'Helvetica', 'Arial', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    <style type="text/tailwindcss">
        @layer utilities {
            .text-shadow {
                text-shadow: 0 2px 4px rgba(0,0,0,0.1);
            }
            .btn-hover {
                transition: all 0.3s ease;
            }
            .btn-hover:hover {
                transform: translateY(-3px);
                box-shadow: 0 10px 20px rgba(0,0,0,0.1);
            }
        }
    </style>
</head>
<body class="font-sans text-gray-800 bg-light">
    <!-- 导航栏 -->
    <nav class="sticky top-0 bg-white shadow-md z-50">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <a href=" " class="text-2xl font-bold text-primary flex items-center">
                <i class="fa fa-print mr-2 text-secondary"></i>
                <span>一品良印</span>
            </a >
            <div class="hidden md:flex space-x-6 text-sm font-medium">
                <a href="#home" class="hover:text-secondary transition">首页</a >
                <a href="#mantou" class="hover:text-secondary transition">门头设计</a >
                <a href="#print" class="hover:text-secondary transition">印刷服务</a >
                <a href="#express" class="hover:text-secondary transition">加急服务</a >
                <a href="#cases" class="hover:text-secondary transition">案例展示</a >
                <a href="#contact" class="hover:text-secondary transition">联系我们</a >
            </div>
            <a href="#contact" class="bg-secondary text-white px-4 py-2 rounded-md text-sm font-medium btn-hover hidden md:block">
                立即咨询
            </a >
            <button class="md:hidden text-primary">
                <i class="fa fa-bars text-xl"></i>
            </button>
        </div>
    </nav>

    <!-- 首屏 Hero 区域 -->
    <section id="home" class="relative bg-gradient-to-r from-primary to-primary/90 text-white py-20 md:py-32">
        <div class="absolute inset-0 bg-[url('图片URL-门头背景图')] bg-cover bg-center opacity-20"></div>
        <div class="container mx-auto px-4 relative flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-10 md:mb-0">
                <h1 class="text-[clamp(2rem,5vw,3.5rem)] font-bold leading-tight text-shadow mb-4">
                    专业门头设计<br>高性价比印刷
                </h1>
                <p class="text-xl md:text-2xl mb-6 text-gray-100">
                    <span class="font-bold text-secondary">黑彩同价五分钱</span> | <span class="font-bold text-secondary">9.9元全国包邮</span>
                </p >
                <p class="mb-8 text-gray-200">3公里免费送货 · 当天加急出稿 · 上门测量安装</p >
                <div class="flex flex-wrap gap-4">
                    <a href="#mantou" class="bg-secondary hover:bg-secondary/90 text-white px-6 py-3 rounded-md font-semibold btn-hover">
                        <i class="fa fa-paint-brush mr-2"></i>门头设计
                    </a >
                    <a href="#contact" class="bg-white text-primary px-6 py-3 rounded-md font-semibold btn-hover">
                        <i class="fa fa-phone mr-2"></i>免费报价
                    </a >
                </div>
            </div>
            <div class="md:w-1/2 flex justify-center">
                < img src="图片URL-门头产品图" alt="专业门头设计" class="rounded-lg shadow-xl w-full max-w-md transform -rotate-3 hover:rotate-0 transition-all duration-300">
            </div>
        </div>
    </section>

    <!-- 核心优势 -->
    <section class="py-12 bg-white">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="bg-light p-6 rounded-lg text-center hover:shadow-lg transition">
                    <div class="w-16 h-16 bg-secondary/10 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fa fa-tag text-2xl text-secondary"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">黑彩同价五分钱</h3>
                    <p class="text-gray-600">黑白/彩色打印复印统一低价，无隐形消费，省钱更省心</p >
                </div>
                <div class="bg-light p-6 rounded-lg text-center hover:shadow-lg transition">
                    <div class="w-16 h-16 bg-secondary/10 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fa fa-truck text-2xl text-secondary"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">9.9元全国包邮</h3>
                    <p class="text-gray-600">满额即享全国配送，无论多远都能发货，在家等收货</p >
                </div>
                <div class="bg-light p-6 rounded-lg text-center hover:shadow-lg transition">
                    <div class="w-16 h-16 bg-secondary/10 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fa fa-paint-brush text-2xl text-secondary"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">专业门头设计</h3>
                    <p class="text-gray-600">10年经验团队，定制化设计，包安装/配送，效果有保障</p >
                </div>
            </div>
        </div>
    </section>

    <!-- 门头设计板块 -->
    <section id="mantou" class="py-16 bg-light">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold text-primary mb-2">专业门头设计</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">青岛本地定制 · 一站式服务 · 所见即所得 · 3天快速完工</p >
            </div>

            <div class="grid grid-cols-2 md:grid-cols-4 gap-4 mb-10">
                <div class="bg-white p-4 rounded-lg text-center hover:shadow-md transition">
                    <i class="fa fa-cutlery text-2xl text-primary mb-2"></i>
                    <p class="font-medium">餐饮门头</p >
                </div>
                <div class="bg-white p-4 rounded-lg text-center hover:shadow-md transition">
                    <i class="fa fa-shopping-bag text-2xl text-primary mb-2"></i>
                    <p class="font-medium">商业门店</p >
                </div>
                <div class="bg-white p-4 rounded-lg text-center hover:shadow-md transition">
                    <i class="fa fa-building text-2xl text-primary mb-2"></i>
                    <p class="font-medium">写字楼</p >
                </div>
                <div class="bg-white p-4 rounded-lg text-center hover:shadow-md transition">
                    <i class="fa fa-lightbulb-o text-2xl text-primary mb-2"></i>
                    <p class="font-medium">发光字/灯箱</p >
                </div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
                < img src="图片URL-案例1" alt="门头案例1" class="rounded-lg shadow-md w-full h-48 object-cover hover:scale-105 transition">
                < img src="图片URL-案例2" alt="门头案例2" class="rounded-lg shadow-md w-full h-48 object-cover hover:scale-105 transition">
                < img src="图片URL-案例3" alt="门头案例3" class="rounded-lg shadow-md w-full h-48 object-cover hover:scale-105 transition">
                < img src="图片URL-案例4" alt="门头案例4" class="rounded-lg shadow-md w-full h-48 object-cover hover:scale-105 transition">
            </div>

            <div class="mt-10 text-center">
                <a href="#contact" class="inline-block bg-primary text-white px-8 py-3 rounded-md font-semibold btn-hover">
                    <i class="fa fa-map-marker mr-2"></i>免费上门测量
                </a >
            </div>
        </div>
    </section>

    <!-- 印刷服务板块 -->
    <section id="print" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold text-primary mb-2">全品类印刷</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">黑彩同价五分钱 | 9.9元全国包邮 | 3公里免费送货</p >
            </div>

            <div class="grid grid-cols-2 md:grid-cols-4 gap-6 mb-10">
                <div class="bg-light p-6 rounded-lg text-center hover:shadow-lg transition">
                    <i class="fa fa-copy text-2xl text-secondary mb-3"></i>
                    <h4 class="font-semibold">打印复印</h4>
                    <p class="text-sm text-gray-500 mt-1">标书/图纸/文档</p >
                </div>
                <div class="bg-light p-6 rounded-lg text-center hover:shadow-lg transition">
                    <i class="fa fa-book text-2xl text-secondary mb-3"></i>
                    <h4 class="font-semibold">商务印刷</h4>
                    <p class="text-sm text-gray-500 mt-1">名片/画册/展架</p >
                </div>
                <div class="bg-light p-6 rounded-lg text-center hover:shadow-lg transition">
                    <i class="fa fa-gift text-2xl text-secondary mb-3"></i>
                    <h4 class="font-semibold">包装印刷</h4>
                    <p class="text-sm text-gray-500 mt-1">包装盒/不干胶</p >
                </div>
                <div class="bg-light p-6 rounded-lg text-center hover:shadow-lg transition">
                    <i class="fa fa-paint-brush text-2xl text-secondary mb-3"></i>
                    <h4 class="font-semibold">定制物料</h4>
                    <p class="text-sm text-gray-500 mt-1">文化墙/展板</p >
                </div>
            </div>

            <div class="bg-primary/5 p-8 rounded-lg text-center">
                <h3 class="text-2xl font-bold text-primary mb-4">黑彩同价仅需 <span class="text-secondary text-3xl">0.05元</span>/页</h3>
                <p class="mb-6 text-gray-600">9.9元全国包邮，青岛本地3公里免费送货，当天出稿</p >
                <a href="#contact" class="bg-secondary text-white px-6 py-3 rounded-md font-semibold btn-hover inline-block">
                    <i class="fa fa-file-o mr-2"></i>上传文件报价
                </a >
            </div>
        </div>
    </section>

    <!-- 加急服务 -->
    <section id="express" class="py-16 bg-primary text-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold mb-2">加急不涨价</h2>
                <p class="text-gray-200 max-w-2xl mx-auto">当天出 · 当天送 · 极速交付</p >
            </div>

            <div class="grid grid-cols-2 md:grid-cols-4 gap-6 text-center">
                <div class="p-6">
                    <div class="text-4xl font-bold text-secondary mb-2">2小时</div>
                    <p class="text-lg">标书加急</p >
                </div>
                <div class="p-6">
                    <div class="text-4xl font-bold text-secondary mb-2">1小时</div>
                    <p class="text-lg">海报加急</p >
                </div>
                <div class="p-6">
                    <div class="text-4xl font-bold text-secondary mb-2">当天</div>
                    <p class="text-lg">名片取件</p >
                </div>
                <div class="p-6">
                    <div class="text-4xl font-bold text-secondary mb-2">3天</div>
                    <p class="text-lg">门头安装</p >
                </div>
            </div>

            <div class="mt-10 text-center">
                <p class="text-xl mb-4">青岛本地加急订单，优先制作，免费配送</p >
                <a href="#contact" class="inline-block bg-secondary text-white px-8 py-3 rounded-md font-semibold btn-hover">
                    <i class="fa fa-bolt mr-2"></i>联系急单客服
                </a >
            </div>
        </div>
    </section>

    <!-- 案例展示 -->
    <section id="cases" class="py-16 bg-light">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold text-primary mb-2">真实案例</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">上千家青岛本地商户的选择</p >
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                < img src="图片URL-案例5" alt="客户案例5" class="rounded-lg shadow-md w-full h-64 object-cover hover:scale-105 transition">
                < img src="图片URL-案例6" alt="客户案例6" class="rounded-lg shadow-md w-full h-64 object-cover hover:scale-105 transition">
                < img src="图片URL-案例7" alt="客户案例7" class="rounded-lg shadow-md w-full h-64 object-cover hover:scale-105 transition">
            </div>
        </div>
    </section>

    <!-- 联系我们 -->
    <section id="contact" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-<div class="grid grid-cols-1 md:grid-cols-2 gap-12">
    <!-- 左侧：联系方式 -->
    <div>
        <h3 class="text-2xl font-bold text-primary mb-4">联系我们</h3>
        <div class="space-y-4">
            <div class="flex items-center">
                <i class="fa fa-map-marker w-6 text-secondary"></i>
                <span>山东省青岛市黄岛区富春江路1509号</span>
            </div>
            <div class="flex items-center">
                <i class="fa fa-phone w-6 text-secondary"></i>
                <span>0532-88888888</span>
            </div>
            <div class="flex items-center">
                <i class="fa fa-wechat w-6 text-secondary"></i>
                <span>yipinliangyin</span>
            </div>
            <div class="flex items-center">
                <i class="fa fa-clock-o w-6 text-secondary"></i>
                <span>周一至周日 8:30-20:00</span>
            </div>
        </div>
    </div>

    <!-- 右侧：简单的咨询表单 -->
    <div>
        <h3 class="text-2xl font-bold text-primary mb-4">在线留言</h3>
        <form action="你的表单处理地址" method="POST">
            <div class="mb-4">
                <input type="text" placeholder="您的姓名" class="w-full border border-gray-300 rounded-md px-4 py-2 focus:outline-none focus:ring-2 focus:ring-primary">
            </张经理>
            <div class="mb-4">
                <input type="tel" placeholder="联系电话" class="w-full border border-gray-300 rounded-md px-4 py-2 focus:outline-none focus:ring-2 focus:ring-primary">
            </13305321678>
            <div class="mb-4">
                <textarea rows="3" placeholder="需求描述" class="w-full border border-gray-300 rounded-md px-4 py-2 focus:outline-none focus:ring-2 focus:ring-primary"></textarea>
            </div>
            <button type="submit" class="bg-secondary text-white px-6 py-2 rounded-md font-semibold btn-hover">提交咨询</button>
        </form>
    </div>
</div>
            </div>
        </div>
    </section>
    <!-- 页脚可自行添加 -->
    <footer class="bg-primary text-white text-center py-6">
        <p>© 2025 青岛市一品良印图文快印有限公司 版权所有</p>
    </footer>
</body>
</html>
