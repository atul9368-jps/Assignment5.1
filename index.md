1. The HTML File (index.html)
Make sure your HTML file links the external stylesheet in the <head> section.

HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Styled Website</title>
    <!-- Step 2: Link the external stylesheet -->
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <!-- Step 5: Navigation menu -->
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- Step 4: Headings and paragraphs -->
        <h1>Welcome to My Website</h1>
        <p>This is a paragraph explaining the content of my page. Adding CSS makes everything look clean and readable!</p>
        <p>Feel free to check out <a href="https://example.com" target="_blank">this sample link</a> for more details.</p>
    </main>
</body>
</html>
2. The CSS File (style.css)
Create a file named style.css in the same folder as your HTML file and add the following rules:

CSS
/* Step 3: Set body background, text color, and font */
body {
    background-color: #f4f6f9;
    color: #333333;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    padding: 20px;
    line-height: 1.6;
}

/* Step 4: Style headings */
h1 {
    color: #2c3e50;
    font-size: 2.5rem;
    margin-bottom: 20px;
}

/* Step 4: Style paragraphs */
p {
    font-size: 1.1rem;
    margin-bottom: 15px;
}

/* Step 4: Style general links */
a {
    color: #3498db;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
    color: #2980b9;
}

/* Step 5: Make navigation links readable and attractive */
nav ul {
    list-style-type: none;
    padding: 0;
    margin: 0 0 30px 0;
    background-color: #2c3e50;
    display: flex;
    border-radius: 5px;
    overflow: hidden;
}

nav li {
    margin: 0;
}

nav a {
    display: block;
    color: white;
    padding: 14px 20px;
    text-align: center;
    text-decoration: none;
    transition: background-color 0.3s ease;
}

nav a:hover {
    background-color: #1abc9c;
    color: white;
    text-decoration: none;
}