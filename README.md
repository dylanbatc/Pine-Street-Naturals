# Pine-Street-Naturals
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pine Street Naturals</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f4f1ec; color: #2c3e50; }
    header, footer { background: #2e5632; color: white; text-align: center; padding: 1em 0; }
    nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
    main { padding: 2em; max-width: 900px; margin: auto; }
    section { margin-bottom: 2em; }
    img.logo { width: 150px; }
    form { background: #ffffff; padding: 1em; border-radius: 8px; }
    label { display: block; margin-top: 1em; }
    input, textarea { width: 100%; padding: 0.5em; margin-top: 0.5em; }
    button { background: #2e5632; color: white; border: none; padding: 0.7em 1.5em; margin-top: 1em; cursor: pointer; }
  </style>
</head>
<body>
  <header>
    <img src="/mnt/data/5eb05b2b-2e76-4013-b479-f587dbe7e09c.png" alt="Pine Street Naturals Logo" class="logo" />
    <h1>Pine Street Naturals</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#products">Products</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section id="home">
      <h2>Welcome to Pine Street Naturals</h2>
      <p>Handcrafted, all-natural soaps made with care for your skin and the environment.</p>
    </section>

    <section id="about">
      <h2>About Us</h2>
      <p>Pine Street Naturals was founded with a simple mission: to provide wholesome, eco-friendly soaps that nourish your skin and uplift your senses. Each bar is made with natural ingredients, inspired by the beauty of nature.</p>
    </section>

    <section id="products">
      <h2>Our Products</h2>
      <ul>
        <li>Lavender & Oatmeal Bar</li>
        <li>Charcoal Detox Bar</li>
        <li>Honey & Goat Milk Soap</li>
        <li>Unscented Sensitive Skin Soap</li>
      </ul>
    </section>

    <section id="contact">
      <h2>Contact Us</h2>
      <p>Have a question or a soap idea? We'd love to hear from you!</p>
      <form>
        <label for="name">Your Name</label>
        <input type="text" id="name" name="name" required />

        <label for="email">Your Email</label>
        <input type="email" id="email" name="email" required />

        <label for="message">Message</label>
        <textarea id="message" name="message" rows="4"></textarea>

        <button type="submit">Send</button>
      </form>

      <h3>Soap Idea Survey</h3>
      <form>
        <label for="scent">What scent would you love to see?</label>
        <input type="text" id="scent" name="scent" />

        <label for="ingredients">Any special ingredients you’d like?</label>
        <input type="text" id="ingredients" name="ingredients" />

        <label for="feedback">Additional thoughts</label>
        <textarea id="feedback" name="feedback" rows="3"></textarea>

        <button type="submit">Submit Idea</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Pine Street Naturals. All rights reserved.</p>
  </footer>
</body>
</html>
