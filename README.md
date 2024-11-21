<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Buy and Sell App</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }
        h1 {
            text-align: center;
        }
        .container {
            max-width: 600px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .item {
            border: 1px solid #ddd;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
        }
        .button {
            background-color: #28a745;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
            border-radius: 5px;
        }
        .button:hover {
            background-color: #218838;
        }
        .alert {
            color: red;
            display: none;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Buy and Sell App</h1>
    
    <div id="items">
        <div class="item">
            <h3>Product 1</h3>
            <p>Price: $10</p>
            <button class="button" onclick="buyItem('Product 1', 10)">Buy</button>
        </div>
        <div class="item">
            <h3>Product 2</h3>
            <p>Price: $20</p>
            <button class="button" onclick="buyItem('Product 2', 20)">Buy</button>
        </div>
    </div>

    <div class="alert" id="alert"></div>
</div>

<script>
    function buyItem(product, price) {
        const alertBox = document.getElementById('alert');
        alertBox.style.display = 'block';
        alertBox.innerText = `You have bought ${product} for $${price}.`;
        
        // You can add more logic here, like updating a database or inventory.
    }
</script>

</body>
</html> 👋 Hi, I’m @miki527-crypyo
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
miki527-crypyo/miki527-crypyo is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->