<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Spirits & Scenes</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            font-family: 'Georgia', serif;
            background-color: #1c1c1c;
            color: #f0f0f0;
        }
        header {
            background-color: #000;
            padding: 60px 20px;
            text-align: center;
            background-image: url('hero-banner.jpg'); /* Replace with your actual image */
            background-size: cover;
            background-position: center;
            color: #fff;
        }
        header h1 {
            font-size: 3em;
            margin: 0;
            text-shadow: 2px 2px 4px #000;
        }
        header p {
            font-size: 1.2em;
            margin-top: 10px;
        }
        section {
            padding: 40px 20px;
            max-width: 800px;
            margin: auto;
        }
        h2 {
            border-bottom: 1px solid #444;
            padding-bottom: 10px;
            margin-bottom: 20px;
            color: #e0b589;
        }
        .cta {
            text-align: center;
            margin-top: 30px;
        }
        .cta a {
            background-color: #e0b589;
            color: #000;
            padding: 12px 24px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }
        footer {
            background-color: #111;
            text-align: center;
            padding: 20px;
            font-size: 0.9em;
            color: #888;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin-top: 10px;
            background-color: #2c2c2c;
            border: 1px solid #555;
            color: #fff;
        }
        form {
            margin-top: 20px;
        }
        button {
            background-color: #e0b589;
            color: #000;
            padding: 10px 20px;
            border: none;
            margin-top: 10px;
            cursor: pointer;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <header>
        <h1>Spirits & Scenes</h1>
        <p>Murder, Mystery, and Mayhem — Delivered to Your Doorstep!</p>
        <div class="cta">
            #contactBook Your Mystery Night</a>
        </div>
    </header>

    <section>
        <h2>About Us</h2>
        <p>Spirits & Scenes is a mobile murder mystery experience that brings thrilling entertainment to your parties and events. Whether it's a birthday, corporate gathering, or themed celebration, we deliver immersive mystery adventures right to your venue.</p>
    </section>

    <section>
        <h2>How It Works</h2>
        <ul>
            <li>Choose a mystery theme</li>
            <li>We arrive with props, scripts, and atmosphere</li>
            <li>You and your guests solve the mystery together!</li>
        </ul>
    </section>

    <section>
        <h2>Mystery Themes</h2>
        <ul>
            <li>1920s Speakeasy</li>
            <li>Haunted Manor</li>
            <li>Hollywood Whodunit</li>
            <li>Victorian Secrets</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact / Booking</h2>
        <form>
            <label for="name">Name</label>
            <input type="text" id="name" name="name">

            <label for="email">Email</label>
            <input type="email" id="email" name="email">

            <label for="date">Event Date</label>
            <input type="date" id="date" name="date">

            <label for="message">Message</label>
            <textarea id="message" name="message" rows="4"></textarea>

            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>Contact us: spiritsandscenes@example.com | Instagram: @spiritsandscenes</p>
        <p>&copy; 2024 Spirits & Scenes</p>
    </footer>
</body>
</html>
