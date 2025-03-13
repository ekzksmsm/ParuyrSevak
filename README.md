# ParuyrSevak
<!DOCTYPE html>
<html lang="hy">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Paruyr Sevak</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Փարույր Սևակ</h1>
            <nav>
                <ul>
                    <li><a href="#bio">Կենսագրություն</a></li>
                    <li><a href="#works">Ստեղծագործություններ</a></li>
                    <li><a href="#photos">Լուսանկարներ</a></li>
                </ul>
            </nav>
        </div>
    </header>
    
    <section id="bio" class="section">
        <div class="container">
            <h2>Կենսագրություն</h2>
            <p>Փարույր Սևակը (1924-1971) 20-րդ դարի մեծագույն հայ բանաստեղծներից էր...</p>
        </div>
    </section>

    <section id="works" class="section">
        <div class="container">
            <h2>Ստեղծագործություններ</h2>
            <ul>
                <li>Անլռելի զանգակատուն (1959)</li>
                <li>Մարդը ափի մեջ (1963)</li>
                <li>Եղիցի լույս (1969)</li>
            </ul>
        </div>
    </section>

    <section id="photos" class="section">
        <div class="container">
            <h2>Լուսանկարներ</h2>
            <img src="photo1.jpg" alt="Փարույր Սևակ">
            <img src="photo2.jpg" alt="Փարույր Սևակ">
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 Paruyr Sevak</p>
        </div>
    </footer>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: white;
    color: #333;
}

header {
    background-color: #FFD700; /* Ոսկեգույն */
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 36px;
    color: white;
}

nav ul {
    list-style: none;
    padding: 10px;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: white;
    font-size: 18px;
}

.section {
    padding: 40px 20px;
    text-align: center;
}

.section h2 {
    font-size: 28px;
    color: #FFD700;
}

footer {
    background-color: #FFD700;
    text-align: center;
    padding: 20px 0;
}

footer p {
    color: white;
}