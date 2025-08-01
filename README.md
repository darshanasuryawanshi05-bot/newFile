# newFile
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Pawesome Blog</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fefefe;
      color: #333;
    }

    header {
      background-color: #ffcc00;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    nav {
      background-color: #333;
      display: flex;
      justify-content: center;
    }

    nav a {
      color: white;
      padding: 14px 20px;
      display: block;
      text-decoration: none;
    }

    nav a:hover {
      background-color: #555;
    }

    .hero {
      background-image: url('https://images.unsplash.com/photo-1518717758536-85ae29035b6d'); /* Example image */
      background-size: cover;
      background-position: center;
      height: 300px;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      text-shadow: 2px 2px 6px #000;
    }

    .hero h2 {
      font-size: 3rem;
    }

    .content {
      padding: 20px;
    }

    .post {
      margin-bottom: 30px;
      border-bottom: 1px solid #ddd;
      padding-bottom: 20px;
    }

    .post h3 {
      color: #e67e22;
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 15px;
      position: relative;
      bottom: 0;
      width: 100%;
    }

    @media (max-width: 600px) {
      .hero h2 {
        font-size: 2rem;
        padding: 0 10px;
        text-align: center;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>Pawesome Blog</h1>
  <p>All about dogs, paws, and tails!</p>
</header>

<nav>
  <a href="#">Home</a>
  <a href="#">Blog</a>
  <a href="#">About</a>
  <a href="#">Contact</a>
</nav>

<div class="hero">
  <h2>Welcome to the Dog Blog!</h2>
</div>

<div class="content">
  <div class="post">
    <h3>🐾 How to Train Your Puppy</h3>
    <p>Training your puppy is essential for good behavior. Start with simple commands like sit, stay, and come. Use treats and positive reinforcement!</p>
  </div>

  <div class="post">
    <h3>🐕 Top 10 Dog Breeds for Families</h3>
    <p>Looking for a family-friendly pup? Golden Retrievers, Labradors, and Beagles are among the most loving companions.</p>
  </div>

  <div class="post">
    <h3>🍖 Homemade Dog Treat Recipes</h3>
    <p>Make your own healthy and tasty dog treats at home using peanut butter, oats, and a dash of love.</p>
  </div>
</div>

<footer>
  <p>&copy; 2025 Pawesome Blog. All rights reserved.</p>
</footer>

</body>
</html>
