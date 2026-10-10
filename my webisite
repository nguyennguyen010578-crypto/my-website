<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang Web Cá Nhân</title>
    <style>
        :root { --bg: #0f172a; --card: #1e293b; --text: #f8fafc; --primary: #38bdf8; }
        body { margin: 0; font-family: 'Segoe UI', Arial, sans-serif; background: var(--bg); color: var(--text); line-height: 1.6; }
        header { background: #1e293b; padding: 20px; text-align: center; border-bottom: 2px solid var(--primary); }
        h1 { color: var(--primary); margin: 0 0 10px 0; }
        .container { max-width: 900px; margin: 40px auto; padding: 0 20px; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin-top: 20px; }
        
        /* Hiệu ứng khi bấm vào thẻ card */
        .card-link {
            text-decoration: none;
            color: inherit;
            display: block;
            transition: transform 0.2s, box-shadow 0.2s;
        }
        .card-link:hover {
            transform: translateY(-5px);
        }
        .card { 
            background: var(--card); 
            padding: 20px; 
            border-radius: 8px; 
            border: 1px solid #334155; 
            height: 100%;
            box-sizing: border-box;
        }
        .card-link:hover .card {
            border-color: var(--primary);
            box-shadow: 0 10px 20px rgba(56, 189, 248, 0.15);
        }
        .card h3 { color: var(--primary); margin-top: 0; }

        form { display: flex; flex-direction: column; gap: 10px; max-width: 500px; margin: 20px auto 0; }
        input, textarea { padding: 12px; border-radius: 6px; border: 1px solid #334155; background: #0f172a; color: white; }
        button { background: var(--primary); color: #0f172a; border: none; padding: 12px; font-weight: bold; border-radius: 6px; cursor: pointer; }
        button:hover { background: #0284c7; color: white; }
        footer { text-align: center; padding: 20px; color: #64748b; margin-top: 40px; }
    </style>
</head>
<body>
    <header>
        <h1>WELCOME TO MY WEBSITE</h1>
        <p>Trang web cá nhân được tạo bằng HTML, CSS và JavaScript</p>
    </header>

    <div class="container">
        <h2>Dịch Vụ & Giới Thiệu</h2>
        <div class="grid">
            <!-- Thẻ Thiết Kế Web -->
            <a href="https://github.com" target="_blank" class="card-link">
                <div class="card">
                    <h3>Thiết Kế Web 🔗</h3>
                    <p>Tạo giao diện trang web hiện đại, nhanh chóng. (Bấm vào để sang trang chủ GitHub)</p>
                </div>
            </a>

            <!-- Thẻ Lập Trình JavaScript -->
            <a href="https://www.w3schools.com/js/tryit.asp?filename=tryjs_intro_inner_html" target="_blank" class="card-link">
                <div class="card">
                    <h3>Lập Trình JavaScript 🔗</h3>
                    <p>Xử lý tính năng và sự kiện mượt mà. (Bấm vào để thử nghiệm mã JavaScript)</p>
                </div>
            </a>
            
            <!-- Thẻ Tối Ưu SEO -->
            <a href="https://developers.google.com/search" target="_blank" class="card-link">
                <div class="card">
                    <h3>Tối Ưu SEO 🔗</h3>
                    <p>Giúp trang web hiển thị chuẩn xác và thu hút người dùng. (Bấm vào để xem tài liệu SEO)</p>
                </div>
            </a>
        </div>

        <h2 style="text-align: center; margin-top: 50px;">Gửi Tin Nhắn</h2>
        <form id="contactForm">
            <input type="text" id="name" placeholder="Họ và tên của bạn" required>
            <input type="email" placeholder="Địa chỉ Email" required>
            <textarea rows="4" placeholder="Nội dung tin nhắn..." required></textarea>
            <button type="submit">Gửi Tin Nhắn</button>
        </form>
        <p id="status" style="text-align: center; color: #4ade80; font-weight: bold; margin-top: 15px;"></p>
    </div>

    <footer>
        <p>© 2026 Website Cá Nhân</p>
    </footer>

    <script>
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            const name = document.getElementById('name').value;
            document.getElementById('status').innerText = 'Cảm ơn ' + name + '! Tin nhắn đã được gửi thành công.';
            this.reset();
        });
    </script>
</body>
</html>
