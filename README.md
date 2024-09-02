<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LiveHD TV - Canais, Filmes e Séries Ilimitados</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background: url('https://st4.depositphotos.com/6196454/20212/i/1600/depositphotos_202120810-stock-photo-blurred-dofocused-background-red-audience.jpg') no-repeat center center fixed;
            background-size: cover;
            margin: 0;
            padding: 0;
        }
        .header {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(255, 255, 255, 0.8);
            padding: 10px 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
            z-index: 100;
        }
        .header h1 {
            margin: 0;
            font-size: 2.5em;
            color: #e74c3c;
            font-weight: bold;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }
        .header-buttons {
            position: fixed;
            top: 15px;
            right: 15px;
            display: flex;
            gap: 10px;
            z-index: 100;
        }
        .header-buttons button {
            background-color: #E4405F; /* Instagram color */
            color: white;
            border: none;
            border-radius: 50%;
            padding: 10px;
            box-shadow: 0 3px 6px rgba(0,0,0,0.2);
            cursor: pointer;
            font-size: 1.2em;
        }
        .header-buttons .whatsapp-button {
            background-color: #25D366; /* WhatsApp color */
        }
        .header-buttons img {
            width: 25px;
            height: 25px;
        }
        .marquee {
            display: none; /* Remover a rotação de texto */
        }
        .container {
            max-width: 80%;
            margin: 100px auto 20px auto; /* Ajuste para acomodar o header fixo */
            padding: 20px;
            background: rgba(255, 255, 255, 0.9);
            border-radius: 8px;
            box-shadow: 0 3px 6px rgba(0,0,0,0.2);
        }
        .highlight {
            font-size: 1.2em;
            color: #e74c3c;
            font-weight: bold;
            margin: 15px 0;
        }
        .content {
            display: flex;
            flex-direction: row;
            gap: 20px;
            justify-content: space-between;
        }
        .topic-container {
            display: flex;
            flex-direction: column;
            gap: 20px;
            flex: 1 1 100%;
        }
        .section {
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            padding: 20px;
            margin-bottom: 20px;
        }
        .section h2 {
            font-size: 1.6em;
            color: #555;
            margin-bottom: 15px;
        }
        .section ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 10px;
            text-align: left;
        }
        .section ul li {
            font-size: 1em;
            margin: 5px 0;
        }
        .price-container {
            margin-top: 20px;
            font-size: 1.8em; /* Aumentar o tamanho da fonte */
            color: #555;
            font-weight: bold;
        }
        .price-bubble {
            display: inline-block;
            padding: 15px 30px; /* Aumentar o padding */
            background: #e74c3c;
            color: #fff;
            border-radius: 8px;
            font-size: 2em; /* Aumentar o tamanho da fonte */
            font-weight: bold;
            box-shadow: 0 3px 6px rgba(0,0,0,0.2);
            animation: pulse 1.5s infinite;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        .devices {
            margin: 20px 0;
            font-size: 1.1em;
            color: #555;
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            justify-content: center;
        }
        .devices span {
            display: inline-block;
            font-weight: bold;
            background: #fff;
            border-radius: 8px;
            padding: 10px 20px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
        }
        footer {
            text-align: center;
            padding: 15px;
            background: rgba(0, 0, 0, 0.7);
            color: #fff;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>LiveHD TV</h1>
    </div>
    <div class="header-buttons">
        <button class="whatsapp-button">
            <a href="https://wa.me/+5519986077848" target="_blank" aria-label="WhatsApp">
                <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp Logo">
            </a>
        </button>
        <button class="instagram-button">
            <a href="https://www.instagram.com/livehd.tv" target="_blank" aria-label="Instagram">
                <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram Logo">
            </a>
        </button>
    </div>
    <div class="container">
        
        <div class="content">
            <div class="topic-container">
                <div class="section">
                    <h2>Canais</h2>
                    <ul>
                        <li>HBO Max</li>
                        <li>Disney+</li>
                        <li>Starz</li>
                        <li>Globoplay</li>
                        <li>Fox Premium</li>
                        <li>Telecine</li>
                        <li>Canal Brasil</li>
                        <li>AXN</li>
                        <li>Cinemax</li>
                        <li>Hulu</li>
                        <li>Showtime</li>
                        <li>AMC</li>
                        <li>Syfy</li>
                        <li>TNT</li>
                        <li>Discovery Channel</li>
                        <li>National Geographic</li>
                        <li>History Channel</li>
                        <li>ESPN</li>
                        <li>ESPN2</li>
                        <li>SportsNet</li>
                        <li>Paramount Network</li>
                        <li>Animal Planet</li>
                        <li>BBC America</li>
                        <li>MTV</li>
                        <li>Comedy Central</li>
                        <li>Oxygen</li>
                        <li>Bravo</li>
                    </ul>
                </div>
                <div class="section">
                    <h2>Filmes e Séries</h2>
                    <ul>
                        <li>Netflix</li>
                        <li>Amazon Prime Video</li>
                        <li>Hulu</li>
                        <li>Disney+</li>
                        <li>HBO Max</li>
                        <li>Apple TV+</li>
                        <li>Paramount+</li>
                        <li>Peacock</li>
                        <li>Paramount Network</li>
                        <li>Starz</li>
                        <li>HBO Europe</li>
                        <li>Acorn TV</li>
                        <li>Vudu</li>
                        <li>Kanopy</li>
                        <li>BritBox</li>
                        <li>Discovery+</li>
                        <li>IFC</li>
                        <li>Sundance Now</li>
                        <li>Epix</li>
                        <li>Shudder</li>
                        <li>Crunchyroll</li>
                        <li>BBC iPlayer</li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="price-container">
            <p>Tudo isso por apenas <span class="price-bubble">R$10,00</span></p>
        </div>
        <div class="devices">
            <span>SMART TV</span>
            <span>COMPUTADOR</span>
            <span>ANDROID</span>
            <span>IOS</span>
            <span>ROKU</span>
            <span>FIRE STICK</span>
        </div>
    </div>
    <footer>
        &copy; 2024 LiveHD TV. Desenvolvido por Rogers Cavalcante.
    </footer>
</body>
</html>
