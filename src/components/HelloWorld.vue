<template>

<body>
    <div class="top-background">
        <div class="itens-column">
            <div class="logo-container">
                <img src="@/assets/logo.png" alt="Logo">
                <span class="brand-name">MUSCLELOCK</span>
            </div>
            <div class="promo-banner">
                <p>Novidade no mercado</p>
            </div>
            <p class="venha">Faça Parte Deste Projeto</p>

        </div>
    </div>

    <div class="nav">
        <img src="assets/logo.png" alt="">
        <div class="spacer"></div>
        <a href="#home"><i class="fas fa-home"></i> Home</a>
        <a href="#nos"><i class="fas fa-solid fa-users"></i> Nós</a>
        <a href="#contatos"><i class="fas fa-solid fa-envelope"></i> Contatos</a>
        <a href="#info"><i class="fas fa-info-circle"></i> Informações</a>
    </div>

    <div id="nos">
        <hr class="linha">
        <p class="subtitle">sobre nós</p>
    </div>

    <div class="content-1">
        <div class="container-text">
            <hr class="linha-text">
            <p class="title">Quem somos</p>
            <p class="text">A musclelock é uma iniciativa que visa tornar o <br>mundo esportivo do ArmWrestling mais<br>
                tecnológico e profissional, além de melhorar a<br> imagem do esporte para o público.</p>
        </div>
        <img class="image-content" src="@/assets/none-image.png" alt="">
    </div>

    <div class="space-between-content"></div>

    <div class="content-2">
        <div class="container-text">
            <hr class="linha-text">
            <p class="title">Sobre o Projeto </p>
            <p class="text">Uma ideia inovadora e mais profissional para o<br> esporte. Consiste em uma mesa tecnológica
                e<br> interativa programados para calcular o vetor, a força<br> e até mesmo a frequência cardíaca!</p>
        </div>
        <img src="@/assets/none-image.png" alt="">

    </div>

    <div id="contatos" class="contacts">
        <div class="column-text">
            <p>Deseja saber mais sobre a MuscleLock<br> e fazer parte desse projeto?</p>
            <p>Contate-nos pelo whatsapp<br> ou nos mande um email!
            </p>
        </div>
        <img src="@/assets/whatsapp_branco.png" alt="">
        <img src="@/assets/o-email.png" alt="">
    </div>

    <div id="info">
        <hr class="linha">
        <p class="subtitle">Informações</p>
    </div>

    <br>
    <br>
    <br>

    <div class="content-3">
        <div>
            <hr class="linha-content-3">
            <p class="title-content-3">Informações</p>
            <p class="text">Nosso produto é programado para atender as<br> principais necessidades da modalidade,
                incluindo<br> novas funções, das quais são:</p>
            <br>
            <div class="itens-content-3">

                <p class="text-content-3">Sistema programado em arduino <br> calcular a pontução exibida no placar
                    após<br> passar
                    do ponto de ativação por sensor de<br> proximidade.</p>
                <br>
                <p class="text-content-3">Bracelete vinculado à um sistema para<br> monitoramento de frequência
                    cardíaca.</p>

            </div>
        </div>
        <div>
            <hr class="linha">
            <p class="subtitle">Informações</p>
        </div>
    </div>

</body>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Garamond&display=swap');

@font-face {
    font-family: 'scanah';
    /* Name your font family */
    src: url('@/assets/Scanah.otf');
    /* Locate the .ttf file within your directory*/
}

@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');

body {
    margin: 0;
    overflow-x: hidden;
    margin-left: -1vw;
    margin-top: -4.4vw;
    margin-right: -1vw;
}

::-webkit-scrollbar {
    width: 0px;
    /* Largura da barra de rolagem */
    background: transparent;
    /* Fundo da barra de rolagem */
}

.top-background {
    background: linear-gradient(to right, #31293D, #3d40a5);
    color: white;
    flex-wrap: wrap;
    height: 80vh;
    width: 100%;
    display: flex;
    align-items: center;
}

.itens-column {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 6vw;
    margin-left: 7vw;
}

.logo-container {
    display: flex;
    align-items: center;
    margin-bottom: 10px;
    height: 10vh;
    justify-content: flex-start;
}

.logo-container img {
    height: 80px;
    /* Ajuste conforme necessário */
    margin-right: -0.5vw;
}

.brand-name {
    font-family: 'scanah', sans-serif;
    /* Use the font family */
    font-size: 2.4rem;
    /* Ajuste conforme necessário */
    margin-left: 10px;
    /* Espaço entre o logo e o nome */
}

.promo-banner {
    background-color: #6C72FF;
    /* Cor de fundo diferente */
    padding: 10px 20px;
    border-radius: 5px;
    height: 4.1vw;
    width: 37vw;
}

.promo-banner p {
    margin-top: 0.5vh;
    font-size: 2.3rem;
    /* Tamanho da fonte da frase */
    display: flex;
    justify-content: center;
    font-weight: bold;
}

.venha {
    font-size: 2.4rem;
    margin-top: 3vh;

}

.nav {
    display: flex;
    align-items: center;
    background: linear-gradient(to right, #31293D, #3d40a5);

    /* Adiciona espaçamento horizontal */
    width: 100%;
}

.nav img {
    height: 65px;
    margin-left: 2.4vh;
}

.spacer {
    flex-grow: 1;
    /* Cria o espaço vazio */
}

.nav a {
    padding: 14px 20px;
    display: flex;
    align-items: center;
    color: white;
    text-align: center;
    text-decoration: none;
    margin-right: 1vw;
    font-size: 1rem;
    /* Tamanho da fonte */
}

.nav a i {
    margin-right: 8px;
}

.nav a:hover {
    background-color: #ddd;
    color: rgb(69, 86, 243);
}

.linha {
    margin-top: 3.8vh;
    background-color: #6C72FF;
    height: 0.4vh;
    width: 6vh;
}

#about {
    margin-bottom: 5vw;
}

.subtitle {
    display: flex;
    justify-content: center;
    color: #6C72FF;
    font-size: 1.3rem;
    font-weight: bold;
}

.linha-text {
    width: 4vw;
    margin-top: 3.8vh;
    margin-left: 0vw;
    background-color: #000;
    height: 0.2vh;
}

.title {
    font-weight: bold;
    font-size: 1.9rem;
}

.content-1 {
    display: flex;
    margin: 5vw;
    justify-content: space-around;
}

.text {

    font-size: 1.5rem;
    color: #565159;
}

.content-2 {
    display: flex;
    margin: 5vw;
    justify-content: space-around;
    flex-direction: row-reverse;

}

.space-between-content {
    height: 8vh;
}

.contacts {
    background: linear-gradient(to right, #31293D, #3d40a5);
    width: 100%;
    height: 27vh;
    display: flex;
    justify-content: flex-start;
    
}

.contacts p {
    font-size: 2.5rem;
    display: flex;
    justify-content: flex-start;
    color: white;
    margin-bottom: 0vh;
}


.contacts img {
    height: 5vw;
    width: 5vw;
    margin-left: 7vw;
    margin-top: 10vh;
}

.column-text {
    display: flex;
    flex-direction: column;
    margin-left: 12.5vw;
}

.content-3 {
    display: flex;
    flex-wrap: nowrap;
    flex-direction: row;
    justify-content: space-around;
}

.linha-content-3 {
    width: 4vw;
    margin-top: 3.8vh;
    background-color: #000;
    height: 0.2vh;
}

.title-content-3 {

    font-weight: bold;
    font-size: 1.9rem;
    display: flex;
    justify-content: center;
}

.itens-content-3 {
    margin-left: 2vw;

}

.text-content-3 {
    margin-left: 20px; /* Espaço para o ponto */
    position: relative; /* Necessário para posicionar o ponto */
    font-size: 1.5rem;
    color: #565159;
}

.text-content-3:before {
    content: "•"; /* Caractere do ponto */
    position: absolute; /* Posiciona absolutamente em relação ao conteúdo */
    left: -20px; /* Posição do ponto em relação ao texto */
}

@media screen and (min-width: 1366px) and (min-height: 768px) {

    .top-background {
        background: linear-gradient(to right, #31293D, #3d40a5);
        color: white;
        padding: 20px 1vw;
        flex-wrap: wrap;
        height: 80vh;
        display: flex;
        align-items: center;
    }

    .itens-column {
        display: flex;
        flex-direction: column;
        align-items: center;
        margin-bottom: 6vw;
        margin-left: 5vw;
    }

    .logo-container {
        display: flex;
        align-items: center;
        margin-bottom: 10px;
        height: 10vh;
        justify-content: flex-start;
    }

    .logo-container img {
        height: 80px;
        /* Ajuste conforme necessário */
        margin-right: -0.5vw;
    }

    .brand-name {
        font-family: 'scanah', sans-serif;
        /* Use the font family */
        font-size: 2.4rem;
        /* Ajuste conforme necessário */
        margin-left: 10px;
        /* Espaço entre o logo e o nome */
    }

    .promo-banner {
        background-color: #6C72FF;
        /* Cor de fundo diferente */
        padding: 10px 20px;
        border-radius: 5px;
        height: 4.1vw;
        width: 37vw;
    }

    .promo-banner p {
        margin-top: 0.5vh;
        font-size: 2.3rem;
        /* Tamanho da fonte da frase */
        display: flex;
        justify-content: center;
        font-weight: bold;
    }

    .venha {
        font-size: 2.4rem;
        margin-top: 3vh;

    }

    .nav {
        display: flex;
        align-items: center;
        background: linear-gradient(to right, #31293D, #3d40a5);
        padding: 0 1vw;
        /* Adiciona espaçamento horizontal */
    }

    .nav img {
        height: 65px;
        margin-left: 2.4vh;
    }

    .spacer {
        flex-grow: 1;
        /* Cria o espaço vazio */
    }

    .nav a {
        padding: 14px 20px;
        display: flex;
        align-items: center;
        color: white;
        text-align: center;
        text-decoration: none;
        margin-right: 1vw;
        font-size: 1rem;
        /* Tamanho da fonte */
    }

    .nav a i {
        margin-right: 8px;
    }

    .nav a:hover {
        background-color: #ddd;
        color: rgb(69, 86, 243);
    }

    .linha {
        margin-top: 3.8vh;
        background-color: #6C72FF;
        height: 0.4vh;
        width: 6vh;
    }

    #about {
        margin-bottom: 5vw;
    }

    .subtitle {
        display: flex;
        justify-content: center;
        color: #6C72FF;
        font-size: 1.3rem;
        font-weight: bold;
    }

    .linha-text {
        width: 4vw;
        margin-top: 3.8vh;
        margin-left: 0vw;
        background-color: #000;
        height: 0.2vh;
    }

    .title {
        font-weight: bold;
        font-size: 1.9rem;
    }

    .content-1 {
        display: flex;
        margin: 5vw;
        justify-content: space-around;
    }

    .text {
        
        font-size: 1.5rem;
    }

    .content-2 {
        display: flex;
        margin: 5vw;
        justify-content: space-around;
        flex-direction: row-reverse;

    }

    .space-between-content {
        height: 8vh;
    }

}

@media screen and (max-width: 1040px) {
    .top-background {
        background: linear-gradient(to right, #31293D, #3d40a5);
        color: white;
        padding: 20px 1vw;
        flex-wrap: wrap;
        height: 80vh;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .promo-banner {
        background-color: #6C72FF;
        /* Cor de fundo diferente */
        padding: 10px 20px;
        border-radius: 5px;
        height: 6vw;
        width: 55vw;
    }

    .itens-column {
        display: flex;
        flex-direction: column;
        align-items: center;
        margin-bottom: 6vw;
    }

    .image-content {
        width: 45vw;
        margin: 2vw;
    }

}

@media screen and (max-width: 768px) {
    .top-background {
        background: linear-gradient(to right, #31293D, #3d40a5);
        color: white;
        padding: 10px 5vw;
        flex-wrap: wrap;
        height: auto;
        /* Ajusta a altura para conteúdo dinâmico */
        display: flex;
        align-items: center;
        flex-direction: column;
        /* Alinha os itens em coluna */
    }

    .itens-column {
        display: flex;
        flex-direction: column;
        align-items: center;
        margin-bottom: 4vw;
        margin-left: 0;
    }

    .logo-container {
        display: flex;
        align-items: center;
        margin-bottom: 10px;
        height: auto;
        justify-content: center;
    }

    .logo-container img {
        height: 50px;
        /* Ajuste conforme necessário */
        margin-right: 10px;
    }

    .brand-name {
        font-family: 'scanah', sans-serif;
        /* Use the font family */
        font-size: 1.5rem;
        /* Ajuste conforme necessário */
        margin-left: 5px;
        /* Espaço entre o logo e o nome */
    }

    .promo-banner {
        background-color: #6C72FF;
        /* Cor de fundo diferente */
        padding: 8px 15px;
        border-radius: 5px;
        height: auto;
        width: 80vw;
        /* Ajusta a largura para caber na tela */
    }

    .promo-banner p {
        margin-top: 0.5vh;
        font-size: 1.2rem;
        /* Tamanho da fonte da frase */
        display: flex;
        justify-content: center;
        font-weight: bold;
    }

    .venha {
        font-size: 1.5rem;
        margin-top: 2vh;
    }

    .nav {
        display: flex;
        align-items: center;
        background: linear-gradient(to right, #31293D, #3d40a5);
        padding: 0 5vw;
        /* Adiciona espaçamento horizontal */
        flex-direction: column;
        /* Alinha os itens em coluna */
    }

    .nav img {
        height: 50px;
        margin-left: 0;
    }

    .spacer {
        display: none;
        /* Remove o espaço vazio */
    }

    .nav a {
        padding: 10px 0;
        display: flex;
        align-items: center;
        color: white;
        text-align: center;
        text-decoration: none;
        margin-right: 0;
        font-size: 0.9rem;
        /* Tamanho da fonte */
    }

    .nav a i {
        margin-right: 5px;
    }

    .nav a:hover {
        background-color: #ddd;
        color: rgb(69, 86, 243);
    }

    .linha {
        margin-top: 2vh;
        background-color: #6C72FF;
        height: 0.4vh;
        width: 4vh;
    }

    #about {
        margin-bottom: 5vw;
    }

    .subtitle {
        display: flex;
        justify-content: center;
        color: #6C72FF;
        font-size: 1rem;
        font-weight: bold;
    }

    .linha-text {
        width: 4vw;
        margin-top: 2vh;
        margin-left: 0;
        background-color: #000;
        height: 0.2vh;
    }

    .title {
        font-weight: bold;
        font-size: 1.5rem;
    }

    .content-1 {
        display: flex;
        margin: 5vw;
        justify-content: center;
        flex-direction: column;
    }

    .text {
        
        font-size: 1.2rem;
    }

    .content-2 {
        display: flex;
        margin: 5vw;
        justify-content: center;
        flex-direction: column;
    }

    .space-between-content {
        height: 4vh;
    }
}
</style>
