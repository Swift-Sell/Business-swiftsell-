/* Estilos gerais */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f4f8;
    color: #333;
    scroll-behavior: smooth;
}

/* Cabeçalho */
header {
    background-color: #1E3A8A;
    color: white;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 50px;
    position: fixed;
    width: 100%;
    top: 0;
    left: 0;
    z-index: 1000;
}

.logo {
    display: flex;
    align-items: center;
    font-size: 24px;
    font-weight: bold;
}

.logo img {
    height: 50px;
    margin-right: 10px;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
    margin: 0;
    padding: 0;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
    transition: 0.3s;
}

nav ul li a:hover {
    color: #F97316;
}

/* Seções */
.section, .services, .transactions {
    text-align: center;
    padding: 80px 20px;
    background-color: white;
    margin-top: 20px;
    border-radius: 5px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}

img {
    width: 80%;
    max-width: 600px;
    margin: 20px 0;
}

/* Contato */
.contact {
    background-color: #1E3A8A;
    color: white;
    padding: 50px 20px;
    text-align: center;
}

.contact a {
    color: #ffcc66;
    text-decoration: none;
}

.contact a:hover {
    text-decoration: underline;
}

/* Rodapé */
footer {
    background-color: #1E3A8A;
    color: white;
    text-align: center;
    padding: 10px 0;
}
