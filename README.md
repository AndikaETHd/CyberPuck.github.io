# CyberPuck.github.io

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Explore the digital cyberpunk world with our NFT collection. Experience futuristic art, exclusive benefits, and join the cyberpunk revolution!">
    <link href="https://fonts.googleapis.com/css2?family=Orbitron&family=Roboto+Mono&display=swap" rel="stylesheet">
    <link rel="icon" href="cyberpunk_favicon_48x48.png" type="image/png">
    <title>Digital Cyberpunk World</title>
    <style>
        /* Global Styles */
        body {
            margin: 0;
            font-family: 'Orbitron', sans-serif;
            background: linear-gradient(45deg, rgba(0, 255, 255, 0.2), rgba(255, 0, 255, 0.2)), url('https://via.placeholder.com/1920x1080') no-repeat center center fixed;
            background-size: cover;
            color: #fff;
            overflow-x: hidden;
        }

        /* Header Styles */
        header {
            text-align: center;
            padding: 60px 20px;
            background: rgba(0, 0, 0, 0.7);
            border-bottom: 3px solid #00ffff;
        }

        header h1 {
            font-size: 4rem;
            color: #00ffff;
            text-shadow: 0 0 10px rgba(0, 255, 255, 0.8), 0 0 20px rgba(0, 255, 255, 0.6);
            margin-bottom: 20px;
        }

        header p {
            font-size: 1.5rem;
            color: #fff;
            text-shadow: 0 0 5px rgba(255, 255, 255, 0.7);
            margin-bottom: 30px;
        }

        /* Buttons */
        .buttons a {
            text-decoration: none;
            padding: 15px 25px;
            background: linear-gradient(90deg, #00ffff, #ff00ff);
            border-radius: 5px;
            font-size: 1.2rem;
            font-weight: bold;
            color: #fff;
            box-shadow: 0 0 10px rgba(0, 255, 255, 0.8), 0 0 10px rgba(255, 0, 255, 0.8);
            transition: transform 0.2s ease-in-out, background 0.3s ease;
        }

        .buttons a:hover {
            transform: scale(1.1);
            background: linear-gradient(90deg, #ff00ff, #00ffff);
        }

        /* Collection Section */
        section {
            padding: 60px 20px;
            background: rgba(0, 0, 0, 0.7);
            margin: 20px 0;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 255, 255, 0.5);
        }

        section h2 {
            font-size: 3rem;
            margin-bottom: 20px;
            text-shadow: 0 0 5px rgba(255, 255, 255, 0.7);
            color: #00ffff;
        }

        .collection-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            padding: 20px;
        }

        .nft-item {
            background: #222;
            border: 2px solid rgba(0, 255, 255, 0.3);
            border-radius: 10px;
            text-align: center;
            color: #fff;
            padding: 20px;
            transition: transform 0.3s ease;
        }

        .nft-item:hover {
            transform: translateY(-10px);
            box-shadow: 0 0 20px rgba(0, 255, 255, 0.8);
        }

        .nft-item img {
            width: 100%;
            border-radius: 5px;
            transition: transform 0.3s ease;
        }

        .nft-item:hover img {
            transform: scale(1.05);
        }

        .nft-item h3 {
            margin: 15px 0;
            font-size: 1.6rem;
            color: #00ffff;
        }

        .nft-item p {
            font-size: 1rem;
            color: #ccc;
        }

        .nft-item a {
            color: #ff00ff;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        .nft-item a:hover {
            color: #00ffff;
        }

        /* Narrative Section */
        #narrative {
            background: rgba(0, 0, 0, 0.7);
            padding: 40px 20px;
            margin: 40px 0;
            border-radius: 10px;
            color: #fff;
            font-size: 1.2rem;
            text-align: justify;
            box-shadow: 0 0 15px rgba(0, 255, 255, 0.5);
        }

        #narrative h2 {
            font-size: 3rem;
            color: #00ffff;
            margin-bottom: 20px;
            text-align: center;
            text-shadow: 0 0 10px rgba(0, 255, 255, 0.8);
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px;
            background: #111;
            color: rgba(255, 255, 255, 0.6);
        }

        footer a {
            color: #00ffff;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        /* Animation for parallax background */
        .parallax {
            background: url('https://via.placeholder.com/1920x1080') no-repeat center center fixed;
            background-size: cover;
            height: 500px;
            position: relative;
            animation: parallaxEffect 30s infinite linear;
        }

        @keyframes parallaxEffect {
            0% { background-position: 0 0; }
            100% { background-position: 0 100%; }
        }

    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Explore the Digital Cyberpunk World</h1>
        <p>Enter a futuristic world blending technology and dystopian aesthetics. Our NFT collection is a fusion of stunning digital art, inspired by the cyberpunk world and the metaverse.</p>
        <div class="buttons">
            <a href="#collection">Explore the Collection</a>
            <a href="#adventure">Start the Adventure</a>
            <a href="https://opensea.io/Cyberpuck" target="_blank">View on OpenSea</a>
        </div>
    </header>

    <!-- Collection Section -->
    <section id="collection">
        <h2>Collection Highlights</h2>
        <div class="collection-grid">
            <div class="nft-item">
                <img src="pixel_art_resized_1080x1080.png" alt="Pixel Neon Vanguard">
                <h3>Pixel Neon Vanguard</h3>
                <p>A cyberpunk warrior exuding futuristic vibes, captured in vibrant neon pixel art.</p>
                <a href="https://opensea.io/assets/base/0xf026efaf8e3b602b3692ebcb06c2adb482fd6209/1/" target="_blank">View on OpenSea</a>
            </div>
            <div class="nft-item">
                <img src="cyberpunk_art_woman_1080x1080.jpg" alt="Guardian of the Future">
                <h3>Guardian of the Future</h3>
                <p>In a synthwave landscape, a guardian stands tall in a neon-lit city, ready to defend the future.</p>
                <a href="https://opensea.io/assets/base/0xf026efaf8e3b602b3692ebcb06c2adb482fd6209/3/" target="_blank">View on OpenSea</a>
            </div>
        </div>
    </section>

    <!-- Narrative Section -->
    <section id="narrative">
        <h2>The Story Behind the Cyberpuck World</h2>
        <p>In this cyberpunk world, advanced technology and neon-filled megacities are just the surface. The real battle is taking place deep within the human body itself. Technology has been embedded into the biological system, creating a new frontier for both humans and artificial intelligence.</p>
        <p>The underground movement, led by the "Dopamine Rebels," fights against rogue AIs seeking to dominate human minds. These rebels are the last hope to reclaim freedom of thought, battling within the digital and biological realms where the human body and machine merge into one.</p>
        <p>Who will emerge victorious in this high-stakes battle of man versus machine? Will it be the rebels fighting for freedom, or the digital entities seeking to control humanity's thoughts?</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Digital Cyberpunk World. All rights reserved.</p>
        <p>
            <a href="#">Join us on Discord</a> | 
            <a href="https://twitter.com/Cyberpuck00
            " target="_blank">Follow on Twitter</a>
        </p>
    </footer>
    

</body>
</html>
