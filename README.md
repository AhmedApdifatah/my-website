<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Family Members</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f3f4f6;
      color: #333;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #4caf50;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
    h1 {
      margin: 0;
    }
    .grid-container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .child-card {
      background-color: white;
      border: 1px solid #ccc;
      border-radius: 8px;
      padding: 10px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }
    .child-card img {
      max-width: 100%;
      border-radius: 50%;
      height: 150px;
      object-fit: cover;
      margin-bottom: 10px;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 10px 0;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Our Family Members</h1>
    <p>Meet all 17 of us, with love and joy!</p>
  </header>
  <section>
    <div class="grid-container">
      <!-- Repeat this child-card for each family member -->
      <div class="child-card">
        <img src="child1.jpg" alt="Child 1">
        <h3>Child 1</h3>
        <p>A brief description about Child 1. Talented and kind-hearted.</p>
      </div>
      <div class="child-card">
        <img src="child2.jpg" alt="Child 2">
        <h3>Child 2</h3>
        <p>A brief description about Child 2. Always full of energy and fun!</p>
      </div>
      <div class="child-card">
        <img src="pictures/photos" alt="Child 3">
        <h3>Child 3</h3>
        <p>A brief description about Child 3. The creative artist of the family.</p>
      </div>
      <!-- Add more child-cards for the remaining children -->
    </div>
  </section>
  <footer>
    <p>&copy; 2025 Ahmed's Family. All rights reserved.</p>
  </footer>
</body>
</html>
