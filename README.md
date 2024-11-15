<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Môn Thiết Kế Web</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <!-- Header -->
        <header>
            <h1>WEBSITE MÔN THIẾT KẾ WEB</h1>
            <p>Kiến thức - Kinh nghiệm - Hỏi đáp</p>
            <span>Sử dụng flexible layout.</span>
        </header>

        <!-- Navigation Menu -->
        <nav>
            <ul>
                <li><a href="#">TRANG CHỦ</a></li>
                <li><a href="#">KHOA HỌC</a></li>
                <li><a href="#">CÔNG NGHỆ</a></li>
                <li><a href="#">CUỘC SỐNG</a></li>
            </ul>
        </nav>

        <!-- Main Content -->
        <div class="content">
            <!-- Sidebar -->
            <aside class="sidebar">
                <div class="sidebar-section">
                    <h2>Giới thiệu</h2>
                    <img src="./images/gioithieu.png" alt="Sidebar Image">
                    <p>Sidebar là gì? Bạn thường nghe về sidebar nhưng có thực sự biết, hiểu và dùng nó hiệu quả.</p>
                </div>
                <h3>Nổi bật</h3>
                <div class="highlight">
                    <img src="./images/noi-bat.png" alt="Feature 1">
                    <img src="./images/noi-bat.png" alt="Feature 2">
                    <img src="./images/noi-bat.png" alt="Feature 3">
                </div>
                <div class="follow">
                    <p>Follow Me</p>
                    <a href="#"><img src="./images/facebook.svg" alt="YouTube"></a>
                    <a href="#"><img src="./images/youtube.svg" alt="Facebook"></a>
                </div>
            </aside>

            <!-- Articles -->
            <section class="articles">
                <article>
                    <h2>Attribute Selector trong CSS</h2>
                    <img src="./images/article.png" alt="" />
                    <p><i>Đăng bởi admin, 15/04/2019</i></p>
                    <p>Attribute selector là cách chọn các phần tử bạn muốn dựa vào thuộc tính của nó trong tài liệu HTML. Nó giúp code của bạn gọn gàng và mạch lạc hơn.</p>
                </article>
                <article>
                    <h2>Form - Biểu mẫu trong CSS</h2>
                    <img src="./images/article.png  " alt="" />
                    <p><i>Đăng bởi admin, 14/02/2019</i></p>
                    <p>Biểu mẫu là thành phần phổ biến trong mọi thiết kế trang web. Nó giúp bạn thu thập dữ liệu người dùng một cách hiệu quả và hợp lý.</p>
                </article>
            </section>
        </div>

        <!-- Footer -->
        <footer>
            <p>© 2024 Trường Cao đẳng Công nghiệp Huế. All rights reserved.</p>
        </footer>
    </div>
</body>
</html>
