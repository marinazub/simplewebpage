body {
    margin: 0;
    font-family: Arial, sans-serif;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav a {
    text-decoration: none;
    color: #fff;
}

.hero {
    background-image: url('hero-image.jpg');
    background-size: cover;
    background-position: center;
    color: #fff;
    text-align: center;
    padding: 100px 0;
}

.hero h2 {
    font-size: 36px;
}

.hero p {
    font-size: 18px;
    margin: 20px 0;
}

.btn {
    display: inline-block;
    background-color: #333;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

.btn:hover {
    background-color: #555;
}
