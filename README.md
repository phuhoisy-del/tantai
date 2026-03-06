<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Social Profile | Kết Nối Với Mình</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Inter', 'Segoe UI', Roboto, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            color: white;
            padding: 20px;
        }

        .container {
            width: 100%;
            max-width: 400px;
            text-align: center;
            animation: fadeIn 0.8s ease-in-out;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .profile-img {
            width: 110px;
            height: 110px;
            border-radius: 50%;
            border: 4px solid rgba(255, 255, 255, 0.3);
            margin-bottom: 20px;
            object-fit: cover;
            box-shadow: 0 10px 20px rgba(0,0,0,0.2);
        }

        h1 {
            font-size: 1.8rem;
            margin-bottom: 8px;
            letter-spacing: -0.5px;
        }

        .bio {
            font-size: 0.95rem;
            opacity: 0.9;
            margin-bottom: 35px;
            line-height: 1.5;
        }

        .links {
            display: flex;
            flex-direction: column;
            gap: 16px;
        }

        .link-card {
            background: rgba(255, 255, 255, 0.15);
            padding: 16px;
            border-radius: 15px;
            text-decoration: none;
            color: white;
            font-weight: 600;
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 12px;
            position: relative;
            overflow: hidden;
        }

        .link-card:hover {
            background: rgba(255, 255, 255, 0.25);
            transform: translateY(-4px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.15);
        }

        /* Border accents for brand colors */
        .facebook-btn { border-left: 6px solid #1877F2; }
        .tiktok-btn { border-left: 6px solid #000000; }
        .insta-btn { border-left: 6px solid #E1306C; }
        .youtube-btn { border-left: 6px solid #FF0000; }

        .footer {
            margin-top: 50px;
            font-size: 0.8rem;
            opacity: 0.7;
            font-weight: 300;
        }
    </style>
</head>
<body>

    <div class="container">
        <img src="https://via.placeholder.com/150" alt="Avatar" class="profile-img">
        
        <h1>DONG CONG TAN TAI</h1>
        <p class="bio">Sáng tạo nội dung & Chia sẻ đam mê ✨<br>Kết nối với mình qua các nền tảng bên dưới nhé!</p>

        <div class="links">
            <a href="https://www.tiktok.com/@dmmyothi?_r=1&_t=ZS-94SmLjvwAy4" target="_blank" rel="noopener noreferrer" class="link-card facebook-btn">
                <i class="fab fa-facebook"></i> tiktok của mình
            </a>

            <a href="https://www.tiktok.com/@dmmyothi?_r=1&_t=ZS-94SlWztxbKn" target="_blank" rel="noopener noreferrer" class="link-card tiktok-btn">
                <i class="fab fa-tiktok"></i> TikTok Profile
            </a>

            <a href="https://instagram.com/yourusername" target="_blank" rel="noopener noreferrer" class="link-card insta-btn">
                <i class="fab fa-instagram"></i> Instagram
            </a>

            <a href="https://youtube.com/@yourchannel" target="_blank" rel="noopener noreferrer" class="link-card youtube-btn">
                <i class="fab fa-youtube"></i> YouTube Channel
            </a>
        </div>

        <div class="footer">
            © 2026 Crafted with ❤️ by Gemini
        </div>
    </div>

</body>
</html>
