<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kids Coding School</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f0f0f0; }
        header { background-color: #4CAF50; color: white; padding: 10px 0; text-align: center; }
        nav { text-align: center; margin: 20px 0; }
        nav a { text-decoration: none; color: #4CAF50; padding: 10px 20px; border: 2px solid #4CAF50; border-radius: 5px; }
        nav a:hover { background-color: #4CAF50; color: white; }
        .container { width: 80%; margin: auto; overflow: hidden; }
        footer { text-align: center; padding: 1px; background-color: #4CAF50; color: white; position: fixed; bottom: 0; width: 100%; }
        .hero { text-align: center; padding: 50px; background-color: #ffffff; margin-bottom: 20px; }
        .hero h1 { margin: 0; font-size: 2.5em; }
        .hero p { font-size: 1.2em; }
        .form-container { max-width: 600px; margin: 20px auto; padding: 20px; background: white; border-radius: 8px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); }
        .form-container h2 { text-align: center; margin-bottom: 20px; }
        .form-container label { display: block; margin: 10px 0 5px; }
        .form-container input { width: 100%; padding: 10px; margin-bottom: 20px; border: 1px solid #ddd; border-radius: 5px; }
        .form-container button { background-color: #FF0000; color: white; padding: 15px; border: none; border-radius: 5px; cursor: pointer; width: 100%; }
        .form-container button:hover { background-color: #FF0000; }
    </style>
</head>
<body>
    <header>
        <h1>Esubu Media Technologies </h1>
    </header>
    <nav>
        <a href="index.html">Home</a>
    </nav>
    <div class="container">
        <section class="hero">
            <h1>Welcome to Kids Coding School!</h1>
            <p>Empowering the next generation with coding skills.</p>
        </section>
        <div class="form-container">
            <h2>Sign Up</h2>
            <form action="#" method="post">
                <label for="name">Name</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email</label>
                <input type="email" id="email" name="email" required>

                <label for="age">Age</label>
                <input type="number" id="age" name="age" required>

                <label for="interests">Interests</label>
                <input type="text" id="interests" name="interests">

                <button type="submit">Sign Up</button>
            </form>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Esubu Media Tech. All rights reserved.</p>
    </footer>
</body>
</html>
