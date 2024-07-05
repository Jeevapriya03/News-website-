# News-website-

HTML CODE 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>News Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
<header>
<h1>News Today</h1>
<nav>
<ul>
      <li><a href="#home">Home</a></li>
       <li><a href="#world">World</a></li>
       <li><a href="#politics">Politics</a></li>
       <li><a href="#business">Business</a></li>
        <li><a href="#technology">Technology</a></li>
        <li><a href="#sports">Sports</a></li>
        <li><a href="#entertainment">Entertainment</a></li>
 </ul>
</nav>
</header>
  <main>
   <article>
            <h2>Headline News Article</h2>
            <p>Here is some content for the main news article. It includes the latest updates and information on the topic.</p>
  </article>

  <section>
       <h2>More News</h2>
        <article>
        <h3>Subheadline 1</h3>
        <p>Details about another news article. This section can include multiple news items.</p>
        </article>
        <article>
        <h3>Subheadline 2</h3>
        <p>Details about another news article. This section can include multiple news items.</p>
        </article>
        </section>
    </main>

    <footer>
     <p>&copy; 2024 News Today. All rights reserved.</p>
    </footer>
</body>
</html>



CSS CODE 


body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 1rem;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

main {
    padding: 2rem;
}

article {
    margin-bottom: 2rem;
}

h2, h3 {
    color: #333;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
