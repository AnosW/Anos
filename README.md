<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basit Web Sitesi</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1em;
        }

        nav {
            background-color: #333;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 10px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            padding: 10px 15px;
            display: inline-block;
        }

        nav ul li a:hover {
            background-color: #575757;
        }

        main {
            padding: 20px;
        }

        section {
            margin-bottom: 20px;
            padding: 20px;
            background: white;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Web Siteme Hoşgeldiniz</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Anasayfa</a></li>
            <li><a href="#about">Hakkında</a></li>
            <li><a href="#contact">İletişim</a></li>
        </ul>
    </nav>
    <main>
        <section id="home">
            <h2>Anasayfa</h2>
            <p>Burada anasayfanızın içeriği bulunacak.</p>
        </section>
        <section id="about">
            <h2>Hakkında</h2>
            <p>Bu bölümde hakkında bilgileri paylaşabilirsiniz.</p>
        </section>
        <section id="contact">
            <h2>İletişim</h2>
            <p>Bize ulaşmak için iletişim formunu kullanabilirsiniz.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Web Siteniz</p>
    </footer>
</body>
</html>
