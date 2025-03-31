<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DEVLYN APP</title>
    <link rel="stylesheet" href="style.css">
</head>
<body id="index">
    <header>
        <h1>DEVLYN </h1>
    </header>
    <nav>
    <a href="home.html">HOME</a>
    <a href="about.html">ABOUT</a>
    </nav>
    <p>In here you'll get to know a little about me</p>
    <footer>
        &copy;2025 MY SITE.
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body id="home">
    <header>
        <h1>Welcome</h1>
        <p>Hi! I'm Devlyn and this is my website.<br>Feel free to explore much about me.

    </header>
    <nav>
        <a href="index.html">WELCOME</a>
        <a href="about.html">ABOUT</a>
    </nav>
    <main>
     <div class="home-images">
        <img src="ace.jpg" alt="profile photo">
        <img src="me.jpg" alt="self">
        <img src="shish.jpg" alt="me">
     </div>
    </main>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body id="about">
    <nav>
    <a href="index.html">WELCOME</a>
    <a href="home.html">HOME</a>
    </nav>
    <a href="#">More About Me</a>
    <p>learn much about me.</p>
    <section id="my info">
        <h3>profile</h3>
        <ul>
            <li>NAME; JOY RUTH</li>
            <li>AGE; 19 yrs</li>
            <li>DOB; 11/09/2006</li>
            <li>CONTACT; 0115552044</li>
        </ul>
    

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}
body {
    background-image:url(cutee.jpg) ;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    color: blue;
    text-align: center;
}
body:has(header h1:contains("Home Page")),
body:has(section#my info){
    background-color: blueviolet;
    color: black;
}
header {
    padding: 20px;
    background-color: rgba(0, 0, 0,0.7);
}
nav {
    margin: 20px 0;
}
nav a {
    color: white;
    text-decoration: none;
    padding: 10px 20px;
    display: inline-block;
    background-color: #333;
    margin: 5px;
    border-radius: 5px;
}
nav a:hover {
    background: #555;
}
.home-images {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin: 20px;
}
.home-images img {
    width: 300px;
    height: auto;
    border-radius: 10px;
}
#index {
    background-image: url(cutee.jpg)no-repeat center center/cover ;
    height: 100vh;
    color:white;
    text-align:center;
}
#home {
    background-color: aqua;
    height:100vh;
    color:blue;
}
#about {
    background-color: #e6e6e6;
    height:100vh;
    color: black;
}
section {
    padding: 20px;
    background-color: white;
    margin: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0,0.1);
}
footer {
    background-color: rgba(0, 0, 0,0.7);
    color: white;
    padding: 10px;
    margin-top: 20px;text-align: center;
}
