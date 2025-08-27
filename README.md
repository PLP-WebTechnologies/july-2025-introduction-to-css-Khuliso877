<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Box Model Demo</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>

  <nav class="navbar">
    <h1>My Styled Page</h1>
    <button>Click Me</button>
  </nav>

  <section class="container">
    <div class="card">
      <h2>Welcome!</h2>
      <p>This is a demonstration of the CSS Box Model. Each section has margin, padding, and borders applied.</p>
    </div>

    <div class="card">
      <h2>Another Section</h2>
      <p>Notice how spacing and alignment change with different box properties.</p>
    </div>
  </section>


/* Reset default spacing */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

/* Body styling */
body {
  font-family: Arial, sans-serif;
  background-color: #f0f4f8;
  padding: 20px;
}

/* Navbar */
.navbar {
  background-color: #333;
  color: white;
  padding: 15px 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-radius: 8px;
  margin-bottom: 20px;
}

.navbar button {
  background-color: #ff9800;
  border: none;
  padding: 10px 15px;
  border-radius: 5px;
  color: white;
  cursor: pointer;
}

/* Container section */
.container {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
}

/* Card-like sections */
.card {
  background-color: #ffffff;
  border: 2px solid #ccc;
  padding: 20px;
  margin: 10px;
  width: 300px;
  border-radius: 10px;
  box-shadow: 2px 2px 8px rgba(0,0,0,0.1);
}

/* Headings and paragraphs */
h2 {
  color: #2c3e50;
  margin-bottom: 10px;
}

p {
  color: #555;
  line-height: 1.6;
}
</body>
</html>
