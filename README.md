<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tiffin Service</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Andhra Pradesh Tiffin Service</h1>
            <nav>
                <ul>
                    <li><a href="#veg-tiffins">Veg Tiffins</a></li>
                    <li><a href="#non-veg-tiffins">Non-Veg Tiffins</a></li>
                    <li><a href="#contact">Contact Us</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- User Authentication Section -->
    <section id="login">
        <h2>Login</h2>
        <form action="/login" method="POST">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>
            <button type="submit">Login</button>
        </form>
        <p>Don't have an account? <a href="#register">Register here</a></p>
    </section>

    <!-- Registration Section -->
    <section id="register">
        <h2>Register</h2>
        <form action="/register" method="POST">
            <label for="new-username">Username:</label>
            <input type="text" id="new-username" name="username" required>
            <label for="new-password">Password:</label>
            <input type="password" id="new-password" name="password" required>
            <button type="submit">Register</button>
        </form>
    </section>

    <main>
        <section id="veg-tiffins">
            <div class="container">
                <h2>Veg Tiffins</h2>
                <div class="menu-item">
                    <h3>Idli</h3>
                    <p>Soft steamed rice cakes served with chutney and sambar.</p>
                    <button>Order Now</button>
                </div>
                <div class="menu-item">
                    <h3>Pesarattu</h3>
                    <p>Green gram dosa served with ginger chutney.</p>
                    <button>Order Now</button>
                </div>
                <div class="menu-item">
                    <h3>Upma</h3>
                    <p>Savory semolina porridge with vegetables and spices.</p>
                    <button>Order Now</button>
                </div>
            </div>
        </section>
        <section id="non-veg-tiffins">
            <div class="container">
                <h2>Non-Veg Tiffins</h2>
                <div class="menu-item">
                    <h3>Chicken Dosa</h3>
                    <p>Crispy dosa filled with spicy chicken masala.</p>
                    <button>Order Now</button>
                </div>
                <div class="menu-item">
                    <h3>Egg Biryani</h3>
                    <p>Flavorful biryani rice with boiled eggs and spices.</p>
                    <button>Order Now</button>
                </div>
                <div class="menu-item">
                    <h3>Fish Pulusu</h3>
                    <p>Traditional Andhra fish curry with tamarind and spices.</p>
                    <button>Order Now</button>
                </div>
                <div class="menu-item">
                    <h3>Garelu with Nattu Kodi</h3>
                    <p>Delicious lentil fritters served with spicy country chicken curry.</p>
                    <button>Order Now</button>
                </div>
                <div class="menu-item">
                    <h3>Dosa with Non-Veg Pulusu</h3>
                    <p>Classic dosa served with a side of spicy non-veg gravy.</p>
                    <button>Order Now</button>
                </div>
            </div>
        </section>
    </main>

    <!-- Reviews Section -->
    <section id="reviews">
        <div class="container">
            <h2>Customer Reviews</h2>
            <div class="review">
                <h3>John Doe</h3>
                <p>The Pesarattu was delicious and delivered on time!</p>
                <p>Rating: ★★★★☆</p>
            </div>
            <div class="review">
                <h3>Jane Smith</h3>
                <p>Loved the Idli! Will order again.</p>
                <p>Rating: ★★★★★</p>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer id="contact">
        <div class="container">
            <p>Contact us at: <a href="mailto:info@tiffinservice.com">info@tiffinservice.com</a></p>
            <p>&copy; 2024 Andhra Pradesh Tiffin Service</p>
        </div>
    </footer>
</body>
</html>
