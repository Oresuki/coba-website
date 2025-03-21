<!DOCTYPE html>
<html>
<head>
    <title>Halaman HTML dengan Video Latar Belakang</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            overflow: hidden;
        }
        video {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            z-index: -1;
        }
        .content {
            position: relative;
            text-align: center;
            color: white;
            font-family: Arial, sans-serif;
            z-index: 1;
            padding-top: 20%;
        }
        .button {
            background-color: #25D366;
            color: white;
            padding: 15px 30px;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
            text-decoration: none;
        }
        .button:hover {
            background-color: #20b857;
        }

https://github.com/user-attachments/assets/6fc0df7d-4e17-4999-b338-a4e5e7c7fc00


    </style>
</head>
<body>
    <video autoplay muted loop>
        <source src="sunset.mp4" type="video/mp4">
        Browser Anda tidak mendukung elemen video.
    </video>
    <div class="content">
        <h1>Selamat Datang!</h1>
        <p>Klik tombol di bawah untuk menghubungi saya di WhatsApp.</p>
        <a href="https://wa.me/6281400788258" class="button">Hubungi WhatsApp</a>
    </div>
</body>
</html>

