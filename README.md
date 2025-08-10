<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio - Projetos em Análise de Dados</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }
        header {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 25px;
        }
        header h1 {
            margin: 0;
            font-size: 2em;
        }
        .container {
            flex: 1;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 20px;
            padding: 30px;
            max-width: 1200px;
            margin: auto;
        }
        .card {
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            padding: 20px;
            transition: transform 0.2s ease-in-out;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        .card h2 {
            font-size: 1.3em;
            margin-bottom: 10px;
            color: #2c3e50;
        }
        .card p {
            font-size: 0.95em;
            color: #555;
            line-height: 1.5;
        }
        .links {
            margin-top: 15px;
        }
        .links a {
            display: inline-block;
            margin: 5px 5px 0 0;
            padding: 8px 12px;
            background-color: #3498db;
            color: white;
            text-decoration: none;
            border-radius: 4px;
            font-size: 0.9em;
        }
        .links a:hover {
            background-color: #217dbb;
        }
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 15px;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Portfólio - Projetos em Análise de Dados</h1>
    </header>

    <section class="container">
        
        <!-- Projeto 1 -->
        <div class="card">
            <h2>Análise de Engajamento em Redes Sociais</h2>
            <p>
                Neste projeto, analisei um conjunto de dados simulado de redes sociais com informações como postagens, sentimento, curtidas, retweets, hashtags e país de origem.
                Utilizei o Google Sheets para limpeza e tratamento dos dados e o Looker Studio para criar um painel interativo.
            </p>
            <div class="links">
                <a href="https://docs.google.com/spreadsheets/d/1Hl_HDrnCr_5qbA-PlBuUvvHR0f1Om28DcHqOSJoK4zc/edit?usp=sharing" target="_blank">Planilha</a>
                <a href="https://lookerstudio.google.com/reporting/22e88c0c-e40a-4b46-9b05-ff2a40f275f7" target="_blank">Dashboard</a>
            </div>
        </div>

        <!-- Projeto 2 -->
        <div class="card">
            <h2>Dashboard de Análise de Salários na Área de Dados</h2>
            <p>
                Projeto feito em uma imersão de dados com Python promovida pela Alura. 
                Foi criado um dashboard no VSCode usando Python e hospedado no Streamlit.
            </p>
            <div class="links">
                <a href="https://imersao-dados-alura-2025-lia-souza.streamlit.app/" target="_blank">Acessar Dashboard</a>
            </div>
        </div>

    </section>

    <footer>
        <p>© 2025 Lia Souza — Projeto criado para fins de portfólio.</p>
    </footer>
</body>
</html>
