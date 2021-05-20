<html lang="en">
<head>
<title>CSS Template</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

/* Style the header */
header {
  background-color: #666;
  padding: 30px;
  text-align: center;
  font-size: 35px;
  color: white;
}

/* Create two columns/boxes that floats next to each other */
nav {
  float: left;
  width: 30%;
  height: 300px; /* only for demonstration, should be removed */
  background: #ccc;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}

article {
  float: left;
  padding: 20px;
  width: 70%;
  background-color: #f1f1f1;
  height: 300px; /* only for demonstration, should be removed */
}

/* Clear floats after the columns */
section::after {
  content: "";
  display: table;
  clear: both;
}

/* Style the footer */
footer {
  background-color: #777;
  padding: 10px;
  text-align: center;
  color: white;
}

/* Responsive layout - makes the two columns/boxes stack on top of each other instead of next to each other, on small screens */
@media (max-width: 600px) {
  nav, article {
    width: 100%;
    height: auto;
  }
}
</style>
</head>
<body>

<h1>Welcome to Shkuba's PENITENTIARY</h1>


<header>
  <h5>CONTENT</h5>
</header>

<section>
  <nav>
      ENJOY !!!
      <p>&#128512;</p>
  </nav>
  
  <article>
    <h3>I am only going to use this site to explain what is in store for you </h3>
    <p>I have been writing poems ever since I discovered my talent and passion in writing and I always wanted to share my wisdom with the world but it always seemed hard to start publishing books and my goal always looked out of reach simply because of the cost but technology seems to have made this easier to reach the world</p>
  </article>
</section>

<footer>
    <p>Click the button below to go to the poem "THE SMALL CLAIM OF BONES" by SHKUBA</p>

    <button
     onclick="document.location='albanpoem.htm'">CONTINUE</button>
</footer>

</body>
</html>
