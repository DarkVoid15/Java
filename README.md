```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Advanced HTML5 Example</title>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
    }
    header {
        background-color: #333;
        color: #fff;
        padding: 20px;
        text-align: center;
    }
    nav {
        background-color: #444;
        color: #fff;
        padding: 10px;
        text-align: center;
    }
    section {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 20px;
        padding: 20px;
    }
    article {
        border: 1px solid #ccc;
        padding: 20px;
    }
    footer {
        background-color: #333;
        color: #fff;
        padding: 20px;
        text-align: center;
    }
</style>
</head>
<body>

<header>
    <h1>Advanced HTML5 Example</h1>
</header>

<nav>
    <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact</a></li>
    </ul>
</nav>

<section>
    <article>
        <h2>Article 1</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla lacinia vestibulum nunc, nec fermentum risus.</p>
    </article>
    <article>
        <h2>Article 2</h2>
        <p>Proin quis nunc quis massa dictum fermentum. Suspendisse potenti. Proin consectetur nunc nec lectus tincidunt, sit amet fermentum justo blandit.</p>
    </article>
    <article>
        <h2>Article 3</h2>
        <p>Fusce porta dignissim purus, non sodales velit tristique et. Sed eu tortor sit amet lacus semper suscipit.</p>
    </article>
</section>

<footer>
    <p>&copy; 2024 Advanced HTML5 Example. All rights reserved.</p>
</footer>

</body>
</html>
```

This code includes a structured layout using semantic elements like `<header>`, `<nav>`, `<section>`, `<article>`, and `<footer>`, along with CSS Grid for a responsive grid layout.
