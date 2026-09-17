<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Random Shopping</title>

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #f5f7fa, #e4ecf7);
            color: #222;
            min-height: 100vh;
        }

        /* Header */
        header {
            background: linear-gradient(135deg, #111827, #374151);
            color: white;
            text-align: center;
            padding: 35px 20px;
        }

        header h1 {
            font-size: 42px;
            margin-bottom: 10px;
            animation: slideDown 1s ease;
        }

        header p {
            font-size: 18px;
            color: #d1d5db;
        }

        /* Main */
        .container {
            width: 90%;
            max-width: 1000px;
            margin: 40px auto;
            text-align: center;
        }

        .container h2 {
            font-size: 30px;
            margin-bottom: 10px;
        }

        .description {
            color: #666;
            margin-bottom: 25px;
        }

        /* Categories */
        .categories {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
            margin-bottom: 35px;
        }

        .category-btn {
            padding: 12px 25px;
            border: none;
            border-radius: 25px;
            background: white;
            color: #333;
            font-size: 16px;
            cursor: pointer;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
            transition: 0.3s;
        }

        .category-btn:hover {
            transform: translateY(-4px);
            background: #111827;
            color: white;
        }

        .category-btn.active {
            background: #111827;
            color: white;
        }

        /* Shopping Card */
        .shopping-card {
            background: white;
            max-width: 450px;
            margin: auto;
            padding: 35px 25px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.15);
            transition: 0.4s;
        }

        .shopping-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 15px 35px rgba(0,0,0,0.2);
        }

        .product-icon {
            font-size: 80px;
            margin-bottom: 20px;
            animation: float 3s ease-in-out infinite;
        }

        #productName {
            font-size: 28px;
            margin-bottom: 10px;
        }

        #productCategory {
            color: #777;
            margin-bottom: 15px;
        }

        #productPrice {
            font-size: 24px;
            font-weight: bold;
            margin-bottom: 25px;
        }

        /* Buttons */
        .buttons {
            display: flex;
            justify-content: center;
            gap: 12px;
            flex-wrap: wrap;
        }

        .random-btn,
        .shop-btn {
            padding: 14px 24px;
            border: none;
            border-radius: 10px;
            font-size: 16px;
            cursor: pointer;
            transition: 0.3s;
        }

        .random-btn {
            background: #111827;
            color: white;
        }

        .shop-btn {
            background: #2563eb;
            color: white;
        }

        .random-btn:hover,
        .shop-btn:hover {
            transform: scale(1.05);
        }

        /* Message */
        #message {
            margin-top: 20px;
            font-weight: bold;
            min-height: 25px;
        }

        /* Footer */
        footer {
            margin-top: 60px;
            background: #111827;
            color: white;
            text-align: center;
            padding: 20px;
        }

        /* Animations */
        @keyframes slideDown {
            from {
                opacity: 0;
                transform: translateY(-30px);
            }

            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes float {
            0%, 100% {
                transform: translateY(0);
            }

            50% {
                transform: translateY(-10px);
            }
        }

        @keyframes cardAnimation {
            from {
                opacity: 0;
                transform: scale(0.9);
            }

            to {
                opacity: 1;
                transform: scale(1);
            }
        }

        .animate-card {
            animation: cardAnimation 0.5s ease;
        }

        /* Mobile */
        @media (max-width: 600px) {

            header h1 {
                font-size: 32px;
            }

            .container h2 {
                font-size: 25px;
            }

            .shopping-card {
                width: 95%;
            }
        }
    </style>
</head>

<body>

    <!-- Header -->
    <header>
        <h1>🛍️ Random Shopping</h1>
        <p>Discover something exciting to shop today!</p>
    </header>


    <!-- Main Content -->
    <div class="container">

        <h2>🎲 Pick Your Shopping Category</h2>

        <p class="description">
            Select a category and let Random Shopping choose an item for you.
        </p>


        <!-- Categories -->
        <div class="categories">

            <button class="category-btn active"
                    onclick="selectCategory('All', this)">
                🛍️ All
            </button>

            <button class="category-btn"
                    onclick="selectCategory('Men', this)">
                👨 Men
            </button>

            <button class="category-btn"
                    onclick="selectCategory('Women', this)">
                👩 Women
            </button>

            <button class="category-btn"
                    onclick="selectCategory('Electronics', this)">
                💻 Electronics
            </button>

        </div>


        <!-- Shopping Card -->
        <div class="shopping-card" id="card">

            <div class="product-icon" id="productIcon">
                🎁
            </div>

            <h3 id="productName">
                Ready to Shop?
            </h3>

            <p id="productCategory">
                Choose a category
            </p>

            <p id="productPrice">
                💰 ---
            </p>


            <div class="buttons">

                <button class="random-btn"
                        onclick="randomShopping()">
                    🎲 Random Item
                </button>

                <button class="shop-btn"
                        onclick="shopNow()">
                    🛒 Shop Now
                </button>

            </div>

            <p id="message"></p>

        </div>

    </div>


    <!-- Footer -->
    <footer>
        <p>© 2026 Random Shopping | Happy Shopping 🛍️</p>
    </footer>


    <script>

        let selectedCategory = "All";

        const products = {

            Men: [
                {
                    name: "Stylish T-Shirt",
                    icon: "👕",
                    price: "₹599"
                },
                {
                    name: "Running Shoes",
                    icon: "👟",
                    price: "₹1,499"
                },
                {
                    name: "Classic Watch",
                    icon: "⌚",
                    price: "₹999"
                },
                {
                    name: "Cool Sunglasses",
                    icon: "🕶️",
                    price: "₹799"
                }
            ],

            Women: [
                {
                    name: "Handbag",
                    icon: "👜",
                    price: "₹899"
                },
                {
                    name: "Fashion Dress",
                    icon: "👗",
                    price: "₹1,299"
                },
                {
                    name: "Elegant Watch",
                    icon: "⌚",
                    price: "₹1,099"
                },
                {
                    name: "Sunglasses",
                    icon: "🕶️",
                    price: "₹699"
                }
            ],

            Electronics: [
                {
                    name: "Wireless Headphones",
                    icon: "🎧",
                    price: "₹1,999"
                },
                {
                    name: "Smartphone",
                    icon: "📱",
                    price: "₹14,999"
                },
                {
                    name: "Laptop",
                    icon: "💻",
                    price: "₹49,999"
                },
                {
                    name: "Smart Watch",
                    icon: "⌚",
                    price: "₹2,499"
                }
            ]
        };


        function selectCategory(category, button) {

            selectedCategory = category;

            document.querySelectorAll(".category-btn")
                .forEach(btn => {
                    btn.classList.remove("active");
                });

            button.classList.add("active");

            document.getElementById("productName").innerText =
                "Ready to Shop?";

            document.getElementById("productCategory").innerText =
                category + " selected";

            document.getElementById("productIcon").innerText =
                "🎁";

            document.getElementById("productPrice").innerText =
                "💰 ---";

            document.getElementById("message").innerText =
                "Click Random Item to discover something!";
        }


        function randomShopping() {

            let productList = [];

            if (selectedCategory === "All") {

                productList = [
                    ...products.Men,
                    ...products.Women,
                    ...products.Electronics
                ];

            } else {

                productList = products[selectedCategory];

            }


            const randomIndex =
                Math.floor(Math.random() * productList.length);

            const product =
                productList[randomIndex];


            document.getElementById("productIcon").innerText =
                product.icon;

            document.getElementById("productName").innerText =
                product.name;

            document.getElementById("productCategory").innerText =
                selectedCategory === "All"
                ? "Random Pick"
                : selectedCategory;

            document.getElementById("productPrice").innerText =
                "💰 " + product.price;


            document.getElementById("message").innerText =
                "✨ Great choice!";


            /* Restart card animation */

            const card = document.getElementById("card");

            card.classList.remove("animate-card");

            void card.offsetWidth;

            card.classList.add("animate-card");
        }


        function shopNow() {

            const product =
                document.getElementById("productName").innerText;

            if (product === "Ready to Shop?") {

                document.getElementById("message").innerText =
                    "⚠️ Please choose a random item first.";

            } else {

                document.getElementById("message").innerText =
                    "🛒 You selected " + product + "!";

            }
        }

    </script>

</body>
</html>
