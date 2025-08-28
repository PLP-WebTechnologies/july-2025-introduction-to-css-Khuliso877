<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Khuliso</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>Welcome to My Page</h1>
    <p class="subtitle">It's a blessing to be the color of Earth, do you know how flowers confuse me for home</p>
  </header>

  <main>
    <section class="card">
      <h2>About This Page</h2>
      <p>This page demonstrates the CSS Box Model, selectors, and layout styling.</p>
    </section>

    <section class="card">
      <h2>Features</h2>
      <ul>
        <li>Lets style Moose</li>
        <li>Box Model Implementation of moose</li>
        <li>Consistent Layout</li>
      </ul>
    </section>
  </main>

/* Reset default spacing */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Body styling */
body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f4;
  padding: 20px;
}

/* Header */
header {
  text-align: center;
  margin-bottom: 30px;
}

.subtitle {
  color: #555;
  font-style: italic;
}

/* Card sections */
.card {
  background-color: #fff;
  border: 1px solid #ddd;
  padding: 20px;
  margin-bottom: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

/* Footer */
footer {
  text-align: center;
  margin-top: 40px;
  font-size: 0.9em;
  color: #888;
}
</body>
</html>
