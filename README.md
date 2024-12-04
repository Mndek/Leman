<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Pertamaku</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Selamat Datang di Websiteku</h1>
    </header>
    <main>
        <p>Ini adalah contoh website sederhana.</p>
    </main>
    <footer>
        <p>&copy; 2024 Nama Anda</p>
    </footer>
</body>
</html>body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}
header {
    background-color: #4CAF50;
    color: white;
    padding: 1em;
    text-align: center;
}
main {
    padding: 2em;
}
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1em;
    position: absolute;
    bottom: 0;
    width: 100%;
}document.querySelector('main').addEventListener('click', () => {
    alert('Hello, world!');
});
