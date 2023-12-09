<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Buscador de CEP em React</title>
</head>

<body>

    <h1>Buscador de CEP em React</h1>

    <p>Este é um projeto simples de um buscador de CEP em React, que utiliza a API ViaCEP para obter informações sobre endereços.</p>

    <h2>Pré-requisitos</h2>

    <p>Certifique-se de ter o Node.js e o npm instalados em sua máquina.</p>

    <ul>
        <li><a href="https://nodejs.org/" target="_blank" rel="noopener noreferrer">Node.js</a></li>
        <li><a href="https://www.npmjs.com/" target="_blank" rel="noopener noreferrer">npm</a></li>
    </ul>

    <h2>Instalação</h2>

    <ol>
        <li>Clone o repositório:</li>

        <pre><code>git clone https://github.com/seu-usuario/buscador-de-cep-react.git</code></pre>

        <li>Navegue até o diretório do projeto:</li>

        <pre><code>cd buscador-de-cep-react</code></pre>

        <li>Instale as dependências:</li>

        <pre><code>npm install</code></pre>
    </ol>

    <h2>Configuração</h2>

    <p>Abra o arquivo <code>src/api/api.js</code> e substitua a constante <code>VIA_CEP_BASE_URL</code> pelo endpoint da API ViaCEP, caso haja alguma alteração.</p>

    <pre><code>// src/api/api.js

const VIA_CEP_BASE_URL = 'https://viacep.com.br/ws';</code></pre>

    <h2>Uso</h2>

    <ol>
        <li>Inicie o aplicativo:</li>

        <pre><code>npm start</code></pre>

        <li>Abra o navegador e acesse <a href="http://localhost:3000" target="_blank" rel="noopener noreferrer">http://localhost:3000</a>.</li>
        <li>Insira o CEP desejado no campo de busca e clique no botão "Buscar".</li>
    </ol>

    <h2>Tecnologias utilizadas</h2>

    <ul>
        <li>React</li>
        <li>Axios</li>
        <li>React Icons</li>
    </ul>

    <h2>Contribuição</h2>

    <p>Sinta-se à vontade para contribuir com melhorias, correções de bugs ou novos recursos. Abra uma issue ou envie um pull request.</p>

    <h2>Licença</h2>

    <p>Este projeto está licenciado sob a licença MIT - consulte o arquivo <a href="LICENSE" target="_blank" rel="noopener noreferrer">LICENSE</a> para obter detalhes.</p>

</body>

</html>
