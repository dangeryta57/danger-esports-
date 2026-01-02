<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DE COMMUNITY | Official Links</title>

    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- OPTIONAL: Ads baad me add karna -->
    <!--
    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"
     crossorigin="anonymous"></script>
    -->

    <style>
        body {
            margin: 0;
            padding: 0;
            background: radial-gradient(circle at center, #1a0b2e 0%, #050505 100%);
            color: white;
            font-family: 'Poppins', sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
            overflow-x: hidden;
        }

        body::before {
            content: "";
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://www.transparenttextures.com/patterns/stardust.png');
            opacity: 0.3;
            animation: moveBackground 50s linear infinite;
            z-index: -1;
        }

        @keyframes moveBackground {
            from { background-position: 0 0; }
            to { background-position: 1000px 1000px; }
        }

        .profile-section {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-top: 60px;
            margin-bottom: 30px;
            z-index: 1;
        }

        .profile-logo {
            width: 130px;
            height: 130px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #a855f7;
            box-shadow: 0 0 30px rgba(168, 85, 247, 0.6);
            animation: pulse 2s infinite ease-in-out;
        }

        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }

        .profile-name {
            margin-top: 20px;
            font-size: 26px;
            font-weight: 800;
            background: linear-gradient(to right, #fff, #a855f7);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .container {
            width: 90%;
            max-width: 550px;
            display: flex;
            flex-direction: column;
            gap: 18px;
            padding-bottom: 80px;
            z-index: 1;
        }

        .link-card {
            background: rgba(255, 255, 255, 0.03);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(168, 85, 247, 0.2);
            border-radius: 20px;
            padding: 18px 25px;
            display: flex;
            align-items: center;
            text-decoration: none;
            color: white;
            transition: all 0.3s ease;
        }

        .link-card:hover {
            transform: scale(1.05);
            background: rgba(168, 85, 247, 0.1);
            border-color: #a855f7;
        }

        .card-content {
            display: flex;
            align-items: center;
            width: 100%;
            justify-content: space-between;
        }

        .left-side {
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .icon {
            font-size: 26px;
        }

        .link-text {
            font-size: 17px;
            font-weight: 600;
        }

        .menu-dots {
            color: rgba(255,255,255,0.3);
            font-size: 14px;
        }

        .fa-youtube { color: #FF0000; }
        .fa-instagram { color: #E1306C; }
        .fa-facebook { color: #1877F2; }
        .fa-discord { color: #5865F2; }
        .fa-x-twitter { color: #FFFFFF; }
    </style>
</head>

<body>

    <div class="profile-section">
        <img src="PASTE_IMAGE_URL_HERE" alt="Logo" class="profile-logo">
        <div class="profile-name">DE COMMUNITY</div>
    </div>

    <div class="container">

        <a href="https://youtube.com/@dangerbhai257official" target="_blank" class="link-card">
            <div class="card-content">
                <div class="left-side">
                    <i class="fab fa-youtube icon"></i>
                    <span class="link-text">YouTube</span>
                </div>
                <i class="fas fa-ellipsis-v menu-dots"></i>
            </div>
        </a>

        <a href="https://www.instagram.com/yogendravishwakarma_07" target="_blank" class="link-card">
            <div class="card-content">
                <div class="left-side">
                    <i class="fab fa-instagram icon"></i>
                    <span class="link-text">Instagram</span>
                </div>
                <i class="fas fa-ellipsis-v menu-dots"></i>
            </div>
        </a>

        <a href="https://discord.com" target="_blank" class="link-card">
            <div class="card-content">
                <div class="left-side">
                    <i class="fab fa-discord icon"></i>
                    <span class="link-text">Join Discord</span>
                </div>
                <i class="fas fa-ellipsis-v menu-dots"></i>
            </div>
        </a>

        <a href="https://facebook.com" target="_blank" class="link-card">
            <div class="card-content">
                <div class="left-side">
                    <i class="fab fa-facebook icon"></i>
                    <span class="link-text">Facebook</span>
                </div>
                <i class="fas fa-ellipsis-v menu-dots"></i>
            </div>
        </a>

        <a href="https://twitter.com" target="_blank" class="link-card">
            <div class="card-content">
                <div class="left-side">
                    <i class="fa-brands fa-x-twitter icon"></i>
                    <span class="link-text">X (Twitter)</span>
                </div>
                <i class="fas fa-ellipsis-v menu-dots"></i>
            </div>
        </a>

    </div>

</body>
</html>
