<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BADR STORE</title>
    <style>
        /* الأساسيات */
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f7f7f7;
            color: #333;
        }

        /* رأس الصفحة */
        header {
            background-color: #004466;
            color: white;
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 10px 20px;
        }
        header img {
            height: 60px;
        }
        nav {
            display: flex;
            gap: 20px;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #ffa500;
        }

        /* الصفحة الرئيسية */
        .home {
            text-align: center;
            padding: 50px 20px;
            background: linear-gradient(135deg, #ffa500, #004466);
            color: white;
        }
        .home h1 {
            font-size: 50px;
        }

        /* صفحة المنتجات */
        .products {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            padding: 20px;
            justify-content: center;
        }
        .product {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            width: 250px;
            text-align: center;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .product img {
            max-width: 100%;
            border-radius: 8px;
        }
        .product h3 {
            margin: 10px 0;
            font-size: 20px;
        }
        .product button {
            background-color: #ffa500;
            border: none;
            color: white;
            padding: 10px 15px;
            border-radius: 4px;
            cursor: pointer;
            transition: background 0.3s;
        }
        .product button:hover {
            background-color: #cc8400;
        }

        /* صفحة التواصل */
        .contact {
            padding: 20px;
            text-align: center;
        }
        .contact h2 {
            margin-bottom: 20px;
        }
        .contact form {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 15px;
        }
        .contact input, .contact textarea {
            width: 300px;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        .contact button {
            background-color: #004466;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 4px;
            transition: background 0.3s;
        }
        .contact button:hover {
            background-color: #002233;
        }

        /* تذييل الصفحة */
        footer {
            text-align: center;
            padding: 10px;
            background-color: #004466;
            color: white;
        }
    </style>
</head>
<body>
    <!-- رأس الصفحة -->
    <header>
        <img src="logo.png" alt="BADR STORE Logo">
        <nav>
            <a href="#home">الرئيسية</a>
            <a href="#products">المنتجات</a>
            <a href="#contact">تواصل معنا</a>
        </nav>
    </header>

    <!-- الصفحة الرئيسية -->
    <section id="home" class="home">
        <h1>مرحبًا بكم في BADR STORE</h1>
        <p>أفضل متجر للهواتف وملحقاتها بأسعار تنافسية وخدمة مميزة</p>
    </section>

    <!-- المنتجات -->
    <section id="products" class="products">
        <div class="product">
            <img src="phone1.jpg" alt="هاتف 1">
            <h3>هاتف مميز</h3>
            <p>وصف قصير عن المنتج.</p>
            <button>إضافة إلى السلة</button>
        </div>
        <div class="product">
            <img src="phone2.jpg" alt="هاتف 2">
            <h3>هاتف رائع</h3>
            <p>وصف قصير عن المنتج.</p>
            <button>إضافة إلى السلة</button>
        </div>
        <div class="product">
            <img src="phone3.jpg" alt="هاتف 3">
            <h3>هاتف متطور</h3>
            <p>وصف قصير عن المنتج.</p>
            <button>إضافة إلى السلة</button>
        </div>
    </section>

    <!-- التواصل -->
    <section id="contact" class="contact">
        <h2>تواصل معنا</h2>
        <form>
            <input type="text" placeholder="اسمك">
            <input type="email" placeholder="بريدك الإلكتروني">
            <textarea rows="4" placeholder="رسالتك"></textarea>
            <button type="submit">إرسال</button>
        </form>
    </section>

    <!-- تذييل الصفحة -->
    <footer>
        <p>© 2024 BADR STORE. جميع الحقوق محفوظة.</p>
    </footer>
</body>
</html>
