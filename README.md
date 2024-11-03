# league-of-legeds
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>League of Legends Hub</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to the League of Legends Hub!</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#champions">Champions</a></li>
                <li><a href="#guides">Strategy Guides</a></li>
                <li><a href="#news">News</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About the Game</h2>
        <p>League of Legends is a multiplayer online battle arena game...</p>
    </section>

    <section id="champions">
        <h2>Champion Database</h2>
        <div class="champion">
            <h3>Champion Name</h3>
            <p>Abilities, lore, and tips for playing this champion...</p>
        </div>
        <!-- Add more champions as needed -->
    </section>

    <section id="guides">
        <h2>Strategy Guides</h2>
        <p>Tips for each role, item builds, and map awareness...</p>
    </section>

    <section id="news">
        <h2>Latest News</h2>
        <p>Patch notes and upcoming events...</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Submit</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 League of Legends Hub</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}

header {
    background-color: #0033cc;
    color: white;
    padding: 20px;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    margin: 20px;
    padding: 20px;
    background-color: white;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h2 {
    color: #0033cc;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #0033cc;
    color: white;
    position: fixed;
    width: 100%;
    bottom: 0;
}

form {
    display: flex;
    flex-direction: column;
}

label {
    margin: 10px 0 5px;
}

input, textarea {
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

button {
    background-color: #0033cc;
    color: white;
    padding: 10px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

button:hover {
    background-color: #0056b3;
}
<section id="champion-profiles">
    <h2>Champion Profiles</h2>
    <div class="champion">
        <h3>Aatrox</h3>
        <img src="path/to/aatrox-image.jpg" alt="Aatrox" />
        <p><strong>Role:</strong> Fighter</p>
        <p><strong>Abilities:</strong> Aatrox wields a massive sword and has abilities that deal damage and heal him.</p>
        <p><strong>Lore:</strong> Aatrox is a fallen god who seeks to find a way to resurrect his fellow Darkin.</p>
        <p><strong>Tips:</strong> Focus on using his abilities to sustain in fights and outplay your opponents.</p>
    </div>
    <!-- Add more champion profiles as needed -->
</section>
<section id="popular-builds">
    <h2>Popular Builds</h2>
    <ul>
        <li>
            <h3>Aatrox Build</h3>
            <p><strong>Items:</strong> Goredrinker, Black Cleaver, Guardian Angel</p>
            <p><strong>Runes:</strong> Conqueror, Triumph, Legend: Tenacity, Last Stand</p>
        </li>
        <li>
            <h3>Ahri Build</h3>
            <p><strong>Items:</strong> Luden's Echo, Zhonya's Hourglass, Rylai's Crystal Scepter</p>
            <p><strong>Runes:</strong> Electrocute, Taste of Blood, Eyeball Collection, Ultimate Hunter</p>
        </li>
        <!-- Add more builds as needed -->
    </ul>
</section>
<section id="community-highlights">
    <h2>Community Highlights</h2>
    <p>Check out some amazing content from the League of Legends community!</p>
    <div class="highlight">
        <h3>Fan Art</h3>
        <img src="path/to/fan-art.jpg" alt="Fan Art" />
        <p>By Artist Name. Follow them on <a href="link/to/artist">Twitter</a>!</p>
    </div>
    <div class="highlight">
        <h3>Top Streams</h3>
        <p>Watch <a href="link/to/streamer">Streamer Name</a> live on Twitch!</p>
    </div>
    <!-- Add more highlights as needed -->
</section>
