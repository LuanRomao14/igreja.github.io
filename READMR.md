# IGREJA GITHUB

## PROJETO CRIADO <!DOCTYPE html>
<html>
<body>
</body>
</html>
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Assembleia de Deus</title>
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to right, hsl(210, 94%, 14%), #19065d);
            color: hsl(0, 0%, 0%);
        }

        header {
            background: linear-gradient(to right, hwb(241 2% 76%), #0f0436);
            color: hwb(0 95% 5%);
            text-align: center;
            padding: 20px 0;
        }

        header img {
            max-width: 100px;
        }

        nav {
            background:linear-gradient(to right, hsl(256, 83%, 21%), hsl(243, 90%, 20%));
            text-align: center;
            padding: 10px 0;
        }

        nav ul {
            list-style: none;
            padding:10px 0;
            margin: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: rgb(226, 197, 68);
            text-decoration: none;
            font-weight: bold;
        }

        nav ul li a:hover {
            color: #f1c40f;
        }

        .hero {
            background: url('img/igreja.png.jpg') no-repeat center center/cover;
            height: 490px;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: rgb(247, 247, 247);
            text-shadow: 3px 2px 8px rgba(0, 0, 0, 0.7);
        }

        .hero h1 {
            font-size: 65px;
        }

        section {
            padding: 40px 20px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
        }

        h2 {
            color: hsl(253, 85%, 18%);
            text-align: center;
            margin-bottom: 20px;
        }

        .about,
        .ministries,
        .schedule,
        .events,
        .gallery {
          background:linear-gradient(to right, hwb(240 89% 10%), hsl(0, 0%, 100%));
            margin-bottom: 20px;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .gallery img {
            max-width: 100%;
            height: auto;
            margin-bottom: 10px;
            border-radius: 8px;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        footer {
            background-color: #34495e;
            color: #ecf0f1;
            text-align: center;
            padding: 20px 0;
        }

        footer a {
            color: #f1c40f;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <img src="img/mi.png" 
        width="500px"alt="Logo da Igreja" style="float: left; margin-right: 10px;">
        <img src="img/mi.png" alt="Logo da Igreja" style="float: right; margin-left: 10px;">
        <h1>Assembleia de Deus Mibe de São Lourenço MG </h1>
        </h1><li><strong></strong>Rua Heitor Modesto-335 Bairro Estação<h1></h1>
    </header>

    <nav>
        <ul>
            <li><a href="#about">Sobre Nós</a></li>
            <li><a href="#gallery">Galeria</a></li>
            <li><a href="#ministries">Filiais</a></li>
            <li><a href="#schedule">Horários</a></li>
            <li><a href="#events">Eventos</a></li>
        </ul>
    </nav>

    <div class="hero">
        <h1>Bem-vindo à Assembleia de Deus Mibe<h1>

        </h1>
    </div>

    <section id="about" class="container about">
        <h2><li><strong></strong>SOBRE NÓS</h2>
        <p>Somos uma igreja  dedicada em pregar o evangelho de Cristo. Nossa missão é transformar e salvar vidas por meio da palavra de Deus.</p>
    </section>
    <section id="gallery" class="container gallery">
        <img src="img/dentro.jpg"
        width="500px">
        <img src="img/fora.jpg">
        <img src="img/igreja.png.jpg">
        <img src="img/log.jpg"
        width="220px">
    </section>

    <section id="ministries" class="container ministries">
        <h2>Filiais</h2>
        <p><li><strong></strong>Conheça nossas igrejas e horários de cultos:</p>
        <ul>
            <li><strong>CASAS POPULARES:</strong> Cultos às Quartas, Sextas e Domingos, às 19:30.</li>
            <li><strong>PALMELA:</strong> Cultos aos Sábados, às 19:30.</li>
        </ul>
    </section>

    <section id="schedule" class="container schedule">
        <h2><li><strong></strong>Horários dos Cultos</h2>
        <ul>
            <li><strong>Domingo:</strong> Escola Bíblica às 09:00 e Culto às 19:00.</li>
            <li><strong>Terça-feira:</strong> Culto às 19:30.</li>
            <li><strong>Quinta-feira:</strong> Culto às 19:30.</li>
        </ul>
    </section>

    <section id="events" class="container events">
        <h2>Eventos</h2>
        <p><li><strong></strong>Fique atento aos nossos próximos eventos:</p>
        <ul>
            <li><strong>Congresso dos Jovens - 12 a 14 de Setembro.</li>
            <li><strong>Congresso de Missões - 18 a 19 de Novembro.</li>
            <li><strong>Aniversario da igreja - 19 a 21 de Julho .</li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2025 Assembleia de Deus. Todos os direitos reservados. | <a href="#contact">Contato:mibesaolourenco@gmail.com</a></p>
    </footer>
</body>
</html>
