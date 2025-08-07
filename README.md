<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README - Gerenciador de Tarefas</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body {
            background-color: #f8f9fa;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
        }
        .container {
            max-width: 960px;
            margin-top: 50px;
            margin-bottom: 50px;
            background-color: #ffffff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #2c3e50;
            font-weight: 600;
        }
        h1 {
            text-align: center;
            margin-bottom: 20px;
        }
        h2 {
            border-bottom: 2px solid #ecf0f1;
            padding-bottom: 10px;
            margin-top: 30px;
        }
        p, ul {
            font-size: 1rem;
            color: #34495e;
        }
        a {
            color: #3498db;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        code {
            background-color: #ecf0f1;
            padding: 2px 5px;
            border-radius: 4px;
            font-family: 'Courier New', Courier, monospace;
        }
        ul {
            padding-left: 20px;
        }
        .live-link {
            text-align: center;
            margin-top: 20px;
        }
        .live-link a {
            font-size: 1.1rem;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1><i class="fas fa-list-check me-2"></i> Gerenciador de Tarefas do Condomínio</h1>

        <div class="live-link">
            <p><strong>Acesse a aplicação online:</strong></p>
            <a href="https://seu-concominio-front.vercel.app/" target="_blank" class="btn btn-primary btn-lg">
                <i class="fas fa-external-link-alt me-2"></i> Abrir Projeto
            </a>
        </div>

        <h2>Visão Geral do Projeto</h2>
        <p>Este é um protótipo de um sistema de gerenciamento de tarefas desenvolvido para um condomínio. A aplicação foi construída utilizando apenas tecnologias de frontend, com os dados sendo armazenados temporariamente na memória do navegador. Isso demonstra a capacidade de construir uma interface de usuário rica e interativa sem a necessidade de um backend ou banco de dados persistente.</p>
        <p>O projeto segue uma abordagem de **Frontend Puro**, sendo executado diretamente no navegador do cliente.</p>

        <h2>Tecnologias Utilizadas</h2>
        <ul>
            <li><strong>HTML5:</strong> Estrutura fundamental da página.</li>
            <li><strong>CSS3:</strong> Estilização personalizada, com o uso de variáveis CSS para facilitar a manutenção do tema visual.</li>
            <li><strong>Bootstrap 5.3:</strong> Framework CSS que garante um design responsivo, elegante e funcional em todos os dispositivos (desktop, tablets e celulares).</li>
            <li><strong>JavaScript:</strong> Linguagem de programação responsável por toda a lógica da aplicação, como a manipulação dos dados, a renderização dinâmica da interface, e o gerenciamento dos eventos do usuário.</li>
            <li><strong>Font Awesome:</strong> Biblioteca de ícones utilizada para enriquecer a interface e melhorar a usabilidade.</li>
        </ul>

        <h2>Funcionalidades do Sistema</h2>
        <p>A aplicação permite que o usuário gerencie as tarefas do condomínio de forma completa:</p>
        <ul>
            <li><strong>Criação de Tarefas:</strong> Adicionar novas tarefas com nome, custo, data de início, data de conclusão e status.</li>
            <li><strong>Visualização e Edição:</strong> Exibir todas as tarefas em uma tabela e editar qualquer campo de uma tarefa existente.</li>
            <li><strong>Ações Rápidas:</strong> Concluir e excluir tarefas com um clique.</li>
            <li><strong>Gerenciamento de Comentários:</strong> Uma aba dedicada permite visualizar e adicionar comentários a cada tarefa, mantendo um histórico das discussões.</li>
            <li><strong>Design Responsivo:</strong> A interface se adapta automaticamente a diferentes tamanhos de tela, garantindo uma experiência de uso otimizada em dispositivos móveis.</li>
        </ul>

        <h2>Estrutura do Código</h2>
        <p>O código-fonte está contido em um único arquivo <code>index.html</code>. A lógica JavaScript está integrada na página, manipulando um array global de objetos (<code>let tasks = []</code>) para simular o armazenamento dos dados. As funções de manipulação de dados (adicionar, editar, excluir) e renderização da interface são chamadas por eventos do usuário, como o clique em um botão ou o envio de um formulário.</p>

    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
