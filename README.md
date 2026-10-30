# Online-food-order-website-
A responsive  online food ordering  website developer 
<!DOCTYPE html>
<html>
<head>
    <title>Online Food Ordering</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Online Food Ordering</h1>
    <p>Order Your Favourite Food</p>
</header>

<section>
    <h2>Food Menu</h2>

    <input type="text" id="search"
           placeholder="Search Food">

    <select id="category">
        <option value="All">All Categories</option>
        <option value="Meals">Meals</option>
        <option value="Pizza">Pizza</option>
        <option value="Drinks">Drinks</option>
    </select>

    <div id="menu"></div>
</section>

<section>
    <h2>Shopping Cart</h2>

    <div id="cart"></div>

    <h3 id="total">Total: ₹0</h3>

    <form id="checkout">
        <input name="customer"
               placeholder="Customer Name" required>

        <input name="phone"
               placeholder="Phone Number"
               type="tel" required>

        <textarea name="address"
                  placeholder="Delivery Address"
                  required></textarea>

        <button type="submit">Place Order</button>
    </form>

    <p id="message"></p>
</section>

<script src="script.js"></script>

</body>
</html>
