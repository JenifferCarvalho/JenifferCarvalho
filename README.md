<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Portfólio</title>

<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background: #0f172a;
        color: white;
        display: flex;
        justify-content: center;
    }

    .container {
        width: 100%;
        max-width: 420px;
        padding: 30px 20px;
        text-align: center;
    }

    /* HEADER */
    .header {
        margin-top: 20px;
    }

    .wave {
        font-size: 28px;
        animation: wave 1.5s infinite;
        display: inline-block;
    }

    @keyframes wave {
        0% { transform: rotate(0deg); }
        25% { transform: rotate(20deg); }
        50% { transform: rotate(0deg); }
        75% { transform: rotate(20deg); }
        100% { transform: rotate(0deg); }
    }

    h1 {
        margin: 10px 0 5px;
        font-size: 22px;
    }

    h2 {
        margin: 0;
        font-size: 14px;
        font-weight: normal;
        color: #94a3b8;
    }

    /* TECNOLOGIAS */
    .tech {
        margin-top: 40px;
        background: #1e293b;
        padding: 20px;
        border-radius: 15px;
    }

    .tech h3 {
        margin-bottom: 15px;
    }

    .icons {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        gap: 12px;
    }

    .box {
        background: #0f172a;
        padding: 10px;
        border-radius: 10px;
        font-size: 14px;
        border: 1px solid #334155;
    }

    /* SOBRE */
    .about {
        margin-top: 30px;
        font-size: 14px;
        color: #cbd5e1;
        line-height: 1.5;
    }

    /* BOTÃO */
    .btn {
        margin-top: 25px;
        display: inline-block;
        padding: 10px 15px;
        background: #38bdf8;
        color: black;
        border-radius: 10px;
        text-decoration: none;
        font-weight: bold;
    }
</style>

</head>

<body>

<div class="container">

    <!-- HEADER -->
    <div class="header">
        <div class="wave">👋</div>
        <h1>Olá, seja bem-vindo</h1>
        <h2>Desenvolvedora Full Stack | Suporte TI</h2>
    </div>

    <!-- TECNOLOGIAS -->
    <div class="tech">
        <h3>Tecnologias</h3>
        <div class="icons">
            <div class="box">JavaScript</div>
            <div class="box">React</div>
            <div class="box">Node.js</div>
            <div class="box">MySQL</div>
            <div class="box">Git</div>
            <div class="box">GitHub</div>
        </div>
    </div>

    <!-- SOBRE -->
    <div class="about">
        Profissional com experiência em suporte técnico, administração e desenvolvimento web,
        focada em resolver problemas e criar soluções eficientes.
    </div>

    <!-- BOTÃO -->
    <a class="btn" href="#">Ver projetos</a>

</div>

</body>
</html>
