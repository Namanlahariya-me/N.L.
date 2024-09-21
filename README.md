<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wikipedia Page Example</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
        }
        header {
            background-color: #3366cc;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #f1f1f1;
            padding: 10px;
        }
        nav a {
            margin: 0 10px;
            text-decoration: none;
            color: #3366cc;
        }
        .content {
            display: flex;
            padding: 20px;
        }
        .main-content {
            flex: 3;
            padding-right: 20px;
        }
        .infobox {
            flex: 1;
            background-color: #e9ecef;
            padding: 10px;
            border: 1px solid #ccc;
        }
        footer {
            background-color: #f1f1f1;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        h2, h3 {
            color: #3366cc;
        }
    </style>
</head>
<body>
    <header>
        <h1>Wikipedia</h1>
        <p>The Free Encyclopedia</p>
    </header>
    <nav>
        <a href="#">Main Page</a>
        <a href="#">Contents</a>
        <a href="#">Current Events</a>
        <a href="#">Random Article</a>
        <a href="#">About Wikipedia</a>
        <a href="#">Contact Us</a>
    </nav>
    <div class="content">
        <div class="main-content">
            <h2>Article Title</h2>
            <p>This is an example of a detailed Wikipedia-like page created using HTML and CSS. You can add more sections and content as needed.</p>
            <h3>Introduction</h3>
            <p>Introduction details...</p>
            <h3>History</h3>
            <p>History details...</p>
            <h3>Features</h3>
            <p>Features details...</p>
            <h3>References</h3>
            <ul>
                <li>Reference 1</li>
                <li>Reference 2</li>
                <li>Reference 3</li>
            </ul>
            <h3>External Links</h3>
            <ul>
                <li><a href="#">External Link 1</a></li>
                <li><a href="#">External Link 2</a></li>
                <li><a href="#">External Link 3</a></li>
            </ul>
        </div>
        <div class="infobox">
            <h3>Infobox</h3>
            <p>Infobox details...</p>
        </div>
    </div>
    <footer>
        <p>Wikipedia is a registered trademark of the Wikimedia Foundation, Inc., a non-profit organization.</p>
    </footer>
</body>
</html>
