![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

# Gerenciador de Metas

Bem-vindo ao **Gerenciador de Metas**! Um sistema de terminal simples para gerenciar suas metas de forma prática. Você pode adicionar metas, listar as abertas, marcar como realizadas, e até deletar as que não precisa mais. As metas são salvas em um arquivo JSON, garantindo que seu progresso seja mantido entre execuções.

## Funcionalidades

- **Cadastrar Metas**: Adicione novas metas para acompanhar o que deseja realizar.
- **Listar Metas**: Veja todas as metas cadastradas e marque as realizadas.
- **Metas Realizadas**: Veja todas as metas já concluídas.
- **Metas Abertas**: Visualize suas metas ainda pendentes.
- **Deletar Metas**: Exclua metas que não são mais relevantes.
- **Persistência de Dados**: As metas são salvas em um arquivo `metas.json`, garantindo que seus dados sejam mantidos entre execuções.

## Pré-requisitos

- **Node.js**: Certifique-se de ter o [Node.js](https://nodejs.org/) instalado na sua máquina.
- **Inquirer.js**: Utilizamos a biblioteca `@inquirer/prompts` para os inputs no terminal.

## Instalação

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/app-de-metas.git
   
2. Acesse o diretório do projeto:
    ```bash
    cd app-de-metas
   
3. Instale as dependências:
    ```bash
    npm install

## Como Usar
1. Execute o aplicativo:

   ```bash
    node app.js

2. Escolha uma opção no menu:
   
- Cadastrar meta: Insira uma nova meta.
- Listar meta: Liste todas as metas e marque como concluídas.
- Metas realizadas: Veja as metas já completadas.
- Metas abertas: Veja suas metas pendentes.
- Deletar metas: Exclua metas indesejadas.
- Sair: Feche o aplicativo.
  
Exemplo de Uso:
   ```bash
    Bem-vindo ao App de Metas!

    Menu >
    Cadastrar meta
    Listar meta
    Metas realizadas
    Metas abertas
    Deletar metas
    Sair
