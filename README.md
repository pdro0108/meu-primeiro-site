-----CSS------

header{
    width: 100%;
    height: 28px 8%;
}

#navbar{
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

#nav_logo{
    font-size: 24px;
    color:#e9a209
}

#nav_list {
    display:flex;
    list-style: none;
    gap:20px;
}

.nav_item a {
    text-decoration: none;
    color:#1d1d1dda;
    font-weight: 600;
}

----CSS----

---HTML----

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Primeiro Site</title>
    <link rel="stylesheet" href="src/styles/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css">
    <link rel="stylesheet" href="src/styles/header.css">
 

<body>
      <header>
        <nav id="navbar">
            <i class="fa-solid fa-burger" id="nav_logo">FOOD</i>
                <ul id="nav_list">
                    <li id="nav-item">
                        <a href="#home">Início</a>
                    </li>
                    <li id="nav-item">
                        <a href="#menu">Cardápio</a>
                    </li>
                    <li id="nav-item">
                        <a href="#testmonials">Avaliações</a>
                    </li>
                </ul>

                <button class="btn-default">
                    Peça aqui
                </button>
                <button id="mobile-btn">
                    <i class="fa-solid fa-bars"></i>
                </button>
        </nav>
        <div id="mobile_menu">
            <ul id="mobile_nav_list">
                    <li id="nav-item">
                        <a href="#home">Início</a>
                    </li>
                    <li id="nav-item">
                        <a href="#menu">Cardápio</a>
                    </li>
                    <li id="nav-item">
                        <a href="#testimonials">Avaliações</a>
                    </li>
                </ul>

                <button class="btn-default">
                    Peça aqui
                </button>

        </div>
   </header>

</body>
</html>

---HTML----
