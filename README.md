    <style>
        *{
            scroll-behavior: smooth;
        }
        .nav{
            display: flex;
            height: 50px;
            background-color: black;
            gap: 15px;
            width: 100%;
            position: fixed;
            top: 0px;
            justify-content: center;
            align-items: center;
            z-index: 1;
        }
        .a1{
            margin-top: 40px;
        }
        .area{
            width: 100%;
            min-height: 40vh;
            display: flex;
            flex-direction: column;
            gap: 10px;
            justify-content: space-around;
        }
        .autor{
            margin: 10px;
            transition: 0.5s;
            border-radius: 100%; 
            max-width: 150px;
        }
        .autor:hover{
            scale: 1.1;
            transition: 0.5s;
        }
        .layout{
            min-width: 100%;
        }
        .btn{
            width: 100%;
            padding: 15px;
            font-size: 1.2rem;
            background-color: #708090;
            color: #fff;
            font-weight: bold;
            border: none;
            transition: 0.5s;
            cursor: pointer;
        }
        .btn:hover{
            background-color: #5d8aa8;
            transition: 0.5s;
        }
    </style>

    <div class="nav"> 
    
    <a href="#sobre">Sobre mim </a>
    <a href="#skilss"> Habilidades </a>
    <a href="#formacao">Formações Acadêmicas</a>
    <a href="#projetos">Projetos </a>
    <a href="#contato">Contato </a>
    
    </div>

    <div class="area a1">

    # Bem-vindos!👋

    <!-- ![olaMundo](./assets/olaMundo.gif) -->
    <img style="width: 100%; height: 250px" src="./assets/olaMundo.gif">

    - 😊 Eu sou Victor Almeida. Um entusiasta em tecnologia.
    - 👀 Estou procurando uma oportunidade de praticar e aprimorar meus conhecimentos.
    - 🌱 Aprendendo algo novo a cada dia.
    - 💞️ Paixão por programação.

    </div>

    <div class="area">

    <h2 id="sobre">Sobre Mim</h2>

    - [x] Trabalho em Equipe

    - [x] Relacionamento interpessoal

    - [x] Facilidade em Resolução e de problemas e mediação de conflitos.

    - [x] Buscando uma oportunidade para utilizar e aprimorar as habilidades adquiridas ao longo das formações.

    - [x] Pronto para enfrentar novos desafios.

    <a href="https://alurabooks-navy-chi.vercel.app/" >
        <button class="btn"> ACESSAR PORTIFÓLIO </button> 
    </a>


    </div>

    <div class="area">

    <h2 id="skills">Skills</h2>

    - HTML5.
    - CSS3.
    - JavaScript.
    - PHP.
    - SQL.
    - PYTHON.
    - JAVA.
    - REACT JS (cursando).
    - NODE JS (cursando).

    </div>

    <div class="area">

    <h2 id="formacao">Formação</h2>

    - Análise e Desenvolvimento de Sistemas - Uninter - Concluído.
    - Criação de APIs - Udemy - Cursando.
    - Especialização em Front-end - ORACLE ALURA - Cursando.
    - Noções de Java - Udemy - Concluído.
    - PHP - Curso em Vídeo - Concluído.
    - Python - Curso em Vídeo - Concluído.
    - Algoritmos e Lógica de Programação - Curso em Vídeo - Concluído.
    - Noções de POO - Curso em Vídeo - Concluído.

    </div>

    <div class="area">

    <h1 id="projetos">Projetos</h1>

    # Espaço Amanda Fernandes
    Um projeto voltado ao negócio de Designer de sobrancelhas.

    ### Funcionalidades
    - [x] Calendário dinâmico criado com JavaScript;
    - [x] Integração com Instagram e Whatsapp
    - [x] Interface para realização de agendamento online

    ### Layout
    <img src="./assets/layout.png" class="layout">

    <a href="https://projeto-eaf.vercel.app/" >
        <button class="btn">VER DEMONSTRAÇÃO</button> 
    </a>


    ### Tecnologias Utilizadas
    1. HTML5
    2. CSS3
    3. JAVASCRIPT

    ### Próximos Passos
    - [ ] Integração com Banco de Dados

    - [ ] Utilização de React e Node JS

    - [ ] Criação e Consumo de API

    ## Autores

    <a href="https://www.linkedin.com/in/v1774r/">
        <img src="./assets/me.jpg" class="autor">
    </a>
    <br>



    <!-- FIM PROJETO -->

    # Projeto Alura Fokus
    Neste projeto, o objetivo foi adicionar toda a dinâmica ao site para que houvesse interação com o usuário.
    Esse projeto se baseia na técina Pomodoro.
    A Técnica é um método de gerenciamento de tempo que consiste na utilização de um cronômetro para dividir o trabalho em períodos de 25 minutos, separados por breves intervalos.

    ### Funcionalidades
    - [x] Temporizadores para foco e pausas curta e loga.
    - [x] Reprodução de trilha sonora neutra para acompanhar atividade ou pausa.
    - [x] Emissão de alerta ao fim da contagem.
    - [x] Sinais sonoros para indicar o acionamento dos controles.

    ### Layout
    <img src="./assets/layoutFokus.png" class="layout">

    <a href="https://projeto-fokus-rosy.vercel.app/" >
        <button class="btn">VER DEMONSTRAÇÃO</button> 
    </a>

    ### Tecnologias Utilizadas
    1. HTML5
    2. CSS3
    3. JAVASCRIPT

    ## Autores

    <a href="https://www.linkedin.com/in/v1774r/">
        <img src="./assets/me.jpg" class="autor">
    </a>
    <a href="https://www.alura.com.br/">
        <img src="./assets/aluraLogo.webp" class="autor">
    </a>


    <!-- FIM PROJETO -->

    # Projeto Alura Books
    Neste projeto foi realizado o consumo de uma API fornecida pela Alura.
    Através do consumo desta API foi desenvolvida a sessão de exibição de cada livro bem como os seus respectivos filtros. 
    Também é possível reordenar os elementos exibidos.

    ### Funcionalidades
    - [x] Filtro por categoria.
    - [x] Filtro por Disponibilidade.
    - [x] Filtro e reordenação por preço.


    ### Layout
    <img src="./assets/layoutAluraBooks.png" class="layout">

    <a href="https://alurabooks-navy-chi.vercel.app/" >
        <button class="btn">VER DEMONSTRAÇÃO</button> 
    </a>


    ### Tecnologias Utilizadas
    1. HTML5
    2. CSS3
    3. JAVASCRIPT

    ## Autores

    <a href="https://www.linkedin.com/in/v1774r/">
        <img src="./assets/me.jpg" class="autor">
    </a>
    <a href="https://www.alura.com.br/">
        <img src="./assets/aluraLogo.webp" class="autor">
    </a>

    </div>

    <div class="area">

    <h1 id="contato"> Contato </h1>

    ### Meu perfil no Linkedin: <a href="https://www.linkedin.com/in/v1774r/"> Victor Almeida </a>

    </div>
