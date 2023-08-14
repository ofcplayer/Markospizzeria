# Markospizzeria<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Marko's Pizza</title>
    <style>
        /* ... (Previous CSS styles) ... */

        .order-button {
            /* ... (Previous button styles) ... */
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Marko's Pizza</h1>
    </header>
    
    <section>
        <h2>Menu</h2>
        <div class="menu-item">
            <h3>Pepperoni Pizza</h3>
            <p>Delicious pepperoni pizza made with fresh ingredients.</p>
            <button class="order-button" onclick="orderPizza('Pepperoni Pizza')">Order Now</button>
        </div>
        
        <div class="menu-item">
            <h3>Margherita Pizza</h3>
            <p>Classic Margherita pizza with tomato, mozzarella, and basil.</p>
            <button class="order-button" onclick="orderPizza('Margherita Pizza')">Order Now</button>
        </div>
        
        <!-- Add more menu items and buttons here -->
    </section>
    
    <section>
        <h2>Contact Us</h2>
        <p>If you have any questions or need assistance with your order, please email us at: <a href="mailto:5markizik5@gmail.com">5markizik5@gmail.com</a></p>
        <button class="contact-button">Contact Us</button>
    </section>
    
    <footer>
        <p>&copy; 2023 Marko's Pizza. All rights reserved.</p>
    </footer>

    <script>
        function orderPizza(pizzaType) {
            // Replace this alert with your actual ordering logic
            alert('You ordered a ' + pizzaType + ' pizza!');
        }
    </script>
</body>
</html>
