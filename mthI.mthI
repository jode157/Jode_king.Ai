<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صفحتي الشخصية | [جوادالسيد]</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #2c3e50;
            --secondary: #3498db;
            --accent: #e74c3c;
            --light: #ecf0f1;
            --dark: #1a252f;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family:  Segoe UI , Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #1a2a6c, #b21f1f, #1a2a6c);
            color: var(--light);
            line-height: 1.6;
        }
        
        /* التصميم المتجاوب */
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        /* الشريط العلوي */
        header {
            background: rgba(26, 37, 47, 0.9);
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.3);
        }
        
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-size: 1.8rem;
            font-weight: 700;
            color: var(--light);
        }
        
        .logo span {
            color: var(--secondary);
        }
        
        .nav-links {
            display: flex;
            list-style: none;
        }
        
        .nav-links li {
            margin-left: 2rem;
        }
        
        .nav-links a {
            color: var(--light);
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
            font-size: 1.1rem;
        }
        
        .nav-links a:hover {
            color: var(--secondary);
        }
        
        /* الأقسام الرئيسية */
        section {
            padding: 100px 0;
        }
        
        .hero {
            height: 100vh;
            display: flex;
            align-items: center;
            background: rgba(0, 0, 0, 0.5);
        }
        
        .hero-content {
            max-width: 800px;
        }
        
        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 1rem;
            line-height: 1.2;
        }
        
        .hero p {
            font-size: 1.5rem;
            margin-bottom: 2rem;
            opacity: 0.9;
        }
        
        .btn {
            display: inline-block;
            background: var(--secondary);
            color: white;
            padding: 12px 30px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s;
            border: 2px solid var(--secondary);
        }
        
        .btn:hover {
            background: transparent;
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }
        
        .btn-outline {
            background: transparent;
            margin-left: 15px;
        }
        
        .btn-outline:hover {
            background: var(--secondary);
        }
        
        /* قسم عني */
        .about-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 50px;
            align-items: center;
        }
        
        .about-img {
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
        }
        
        .about-img img {
            width: 100%;
            height: auto;
            display: block;
            transition: transform 0.5s;
        }
        
        .about-img img:hover {
            transform: scale(1.05);
        }
        
        .section-title {
            font-size: 2.5rem;
            margin-bottom: 2rem;
            position: relative;
            display: inline-block;
        }
        
        .section-title::after {
            content:   ;
            position: absolute;
            bottom: -10px;
            left: 0;
            width: 70%;
            height: 4px;
            background: var(--secondary);
        }
        
        /* قسم المهارات */
        .skills {
            background: rgba(26, 37, 47, 0.7);
        }
        
        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 30px;
        }
        
        .skill-card {
            background: rgba(255, 255, 255, 0.1);
            padding: 30px;
            border-radius: 10px;
            text-align: center;
            transition: transform 0.3s;
            backdrop-filter: blur(10px);
        }
        
        .skill-card:hover {
            transform: translateY(-10px);
        }
        
        .skill-card i {
            font-size: 3rem;
            color: var(--secondary);
            margin-bottom: 20px;
        }
        
        /* التواصل */
        .contact-form {
            max-width: 700px;
            margin: 0 auto;
        }
        
        .form-group {
            margin-bottom: 25px;
        }
        
        .form-control {
            width: 100%;
            padding: 15px;
            background: rgba(255, 255, 255, 0.1);
            border: none;
            border-radius: 5px;
            color: white;
            font-size: 1rem;
        }
        
        textarea.form-control {
            min-height: 150px;
            resize: vertical;
        }
        
        /* الفوتر */
        footer {
            background: var(--dark);
            padding: 40px 0;
            text-align: center;
        }
        
        .social-links {
            margin-bottom: 20px;
        }
        
        .social-links a {
            display: inline-block;
            width: 50px;
            height: 50px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            margin: 0 10px;
            line-height: 50px;
            color: white;
            font-size: 1.2rem;
            transition: all 0.3s;
        }
        
        .social-links a:hover {
            background: var(--secondary);
            transform: translateY(-5px);
        }
        
        /* التكيف مع الجوال */
        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }
            
            .hero h1 {
                font-size: 2.5rem;
            }
            
            .about-content {
                grid-template-columns: 1fr;
            }
            
            .btn {
                display: block;
                margin-bottom: 15px;
                text-align: center;
            }
        }
    </style>
 <link type="text/css" rel="stylesheet" href="css/style.css"/>
</head>
<body>
    <!-- شريط التنقل -->
    <header>
        <div class="container">
            <nav>
                <div class="logo">اسم<span>ك</span></div>
                <ul class="nav-links">
                    <li><a href="#home">الرئيسية</a></li>
                    <li><a href="#about">عني</a></li>
                    <li><a href="#skills">مهاراتي</a></li>
                    <li><a href="#projects">أعمالي</a></li>
                    <li><a href="#contact">تواصل معي</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- قسم البطل -->
    <section id="home" class="hero">
        <div class="container">
            <div class="hero-content">
                <h1>مرحبًا، أنا <span style="color: #3498db;">[جوادالسيد]</span></h1>
                <p>مطور ويب محترف | مصمم تجارب مستخدم | خبير حلول رقمية</p>
                <div>
                    <a href="#projects" class="btn">أعمالي السابقة</a>
                    <a href="#contact" class="btn btn-outline">وظفني</a>
                </div>
            </div>
        </div>
    </section>

    <!-- قسم عني -->
    <section id="about">
        <div class="container">
            <h2 class="section-title">عني</h2>
            <div class="about-content">
                <div>
                    <h3 style="font-size: 1.8rem; margin-bottom: 20px;">من أنا؟</h3>
                    <p>
                        أنا مطور ويب متخصص مع أكثر من 5 سنوات من الخبرة في إنشاء حلول رقمية مبتكرة. 
                        شغفي يكمن في تحويل الأفكار إلى واقع ملموس من خلال أكواد أنيقة وتصاميم جذابة.
                    </p>
                    <p style="margin-top: 15px;">
                        أعمل حاليًا كمستقل مع عملاء من جميع أنحاء العالم، مساعدًا إياهم في بناء وجودهم الرقمي 
                        وتحقيق أهداف أعمالهم من خلال تطبيقات ويب متقدمة.
                    </p>
                </div>
                <div class="about-img">
                    <!-- استبدل رابط الصورة -->
                    <img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=80" alt="صورتي الشخصية">
                </div>
            </div>
        </div>
    </section>

    <!-- قسم المهارات -->
    <section id="skills" class="skills">
        <div class="container">
            <h2 class="section-title">مهاراتي</h2>
            <div class="skills-container">
                <div class="skill-card">
                    <i class="fab fa-html5"></i>
                    <h3>تطوير الواجهات</h3>
                    <p>HTML5, CSS3, JavaScript, React, Vue.js</p>
                </div>
                
                <div class="skill-card">
                    <i class="fas fa-server"></i>
                    <h3>تطوير الخلفية</h3>
                    <p>Node.js, Python, PHP, قواعد البيانات</p>
                </div>
                
                <div class="skill-card">
                    <i class="fas fa-mobile-alt"></i>
                    <h3>التصميم المتجاوب</h3>
                    <p>تجربة مستخدم رائعة على جميع الأجهزة</p>
                </div>
                
                <div class="skill-card">
                    <i class="fas fa-paint-brush"></i>
                    <h3>التصميم الجرافيكي</h3>
                    <p>Figma, Adobe XD, Photoshop, Illustrator</p>
                </div>
            </div>
        </div>
    </section>

    <!-- قسم المشاريع -->
    <section id="projects">
        <div class="container">
            <h2 class="section-title">أعمالي السابقة</h2>
            <p style="text-align: center; max-width: 800px; margin: 0 auto 50px;">
                هنا بعض مشاريعي الأخيرة التي تظهر مهاراتي وخبراتي في مختلف المجالات
            </p>
            <!-- سيتم إضافة المشاريع هنا عبر JavaScript -->
            <div id="projects-container" style="display: grid; grid-template-columns: repeat(auto-fill, minmax(300px, 1fr)); gap: 30px;"></div>
        </div>
    </section>

    <!-- قسم التواصل -->
    <section id="contact" style="background: rgba(26, 37, 47, 0.7);">
        <div class="container">
            <h2 class="section-title">تواصل معي</h2>
            <div class="contact-form">
                <form id="contactForm">
                    <div class="form-group">
                        <input type="text" class="form-control" placeholder="اسمك الكامل" required>
                    </div>
                    <div class="form-group">
                        <input type="email" class="form-control" placeholder="بريدك الإلكتروني" required>
                    </div>
                    <div class="form-group">
                        <input type="text" class="form-control" placeholder="الموضوع">
                    </div>
                    <div class="form-group">
                        <textarea class="form-control" placeholder="رسالتك" required></textarea>
                    </div>
                    <button type="submit" class="btn" style="width: 100%; padding: 15px;">إرسال الرسالة</button>
                </form>
            </div>
        </div>
    </section>

    <!-- الفوتر -->
    <footer>
        <div class="container">
            <div class="social-links">
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-linkedin-in"></i></a>
                <a href="#"><i class="fab fa-github"></i></a>
                <a href="#"><i class="fab fa-behance"></i></a>
            </div>
            <p>© 2023 [اسمك]. جميع الحقوق محفوظة.</p>
        </div>
    </footer>

    <script>
        // مشاريع عينة
        const projects = [
            {
                title: "متجر إلكتروني",
                description: "منصة تسوق كاملة مع نظام دفع آمن",
                category: "تطوير ويب"
            },
            {
                title: "تطبيق تعليمي",
                description: "منصة تعليمية تفاعلية للدورات التدريبية",
                category: "تطبيق جوال"
            },
            {
                title: "موقع شركة",
                description: "بوابة إلكترونية حديثة لشركة تقنية",
                category: "تصميم وتطوير"
            }
        ];

        // توليد المشاريع ديناميكياً
        const projectsContainer = document.getElementById( projects-container );
        
        projects.forEach(project => {
            const projectElement = document.createElement( div );
            projectElement.className =  skill-card ;
            projectElement.innerHTML = `
                <h3>${project.title}</h3>
                <p>${project.description}</p>
                <span class="category">${project.category}</span>
            `;
            projectsContainer.appendChild(projectElement);
        });

        // إرسال النموذج
        document.getElementById( contactForm ).addEventListener( submit , function(e) {
            e.preventDefault();
            alert( تم إرسال رسالتك بنجاح! سأتواصل معك قريبًا. );
            this.reset();
        });

        // تأثير التمرير السلس
        document.querySelectorAll( a[href^="#"] ).forEach(anchor => {
            anchor.addEventListener( click , function(e) {
                e.preventDefault();
                document.querySelector(this.getAttribute( href )).scrollIntoView({
                    behavior:  smooth 
                });
            });
        });
    </script>
<script type="text/javascript" src="js/script.js"></script>
<!-- این فایل توسط ادیتور آنلاین وبسایت آموزشی فری لرن ایجاد شده است -->
<!-- https://Free-Learn.Ir/ -->
</body>
</html>
