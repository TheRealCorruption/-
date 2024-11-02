<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ROBUX SHOP</title>
    <style>
        body {
            background-color: #1e1e1e;
            color: #ffffff;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        h1 {
            margin-top: 20px;
            font-size: 2rem;
        }
        .separator {
            border: 1px solid #666;
            margin: 30px 0;
        }
        .shop-section {
            margin: 20px 0;
        }
        .button {
            background-color: #00b300;
            color: white;
            border: none;
            border-radius: 50%;
            padding: 15px;
            font-size: 1rem;
            cursor: pointer;
            margin: 10px;
            display: inline-block;
            width: 100px;
            height: 100px;
        }
        .square-button {
            border-radius: 10px;
        }
    </style>
</head>
<body>

    <h1>ROBUX SHOP</h1>
    <hr class="separator">

    <div class="shop-section" id="robux-shop">
        <!-- Dynamic ROBUX buttons will be inserted here by JavaScript -->
        [ button text ]
    </div>

    <hr class="separator">

    <h1>Other</h1>
    <div class="shop-section">
        <button class="button square-button">Gift Card</button>
    </div>

    <script>
        // Placeholder JavaScript to fetch and add ROBUX buttons dynamically.
        // In a real setup, you'd use Roblox API (if accessible) to fetch the gamepasses.
        
        // Example of adding a static button
        const robuxShop = document.getElementById('robux-shop');

        // Dummy buttons for ROBUX
        const gamepasses = [
            '25',
            '50',
            '75',
            '100',
            '125',
            '150',
            '175',
        ];

        gamepasses.forEach(gamepass => {
            const button = document.createElement('button');
            button.className = 'button';
            button.textContent = [ ${gamepass} ];
            robuxShop.appendChild(button);
        });

        // If we had access to an API:
        // fetch("https://roblox-api-for-gamepass.com").then(...).then(data => {
        //     data.forEach(gamepass => {
        //         // dynamically create buttons based on data
        //     });
        // });
    </script>
</body>
</html>
