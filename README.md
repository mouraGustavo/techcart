# TechCart 🚀

**TechCart** é uma solução simples e eficiente de marketplace.

## Funcionalidades Principais 🔧

1. **Cadastro de Produto**: Permite a criação de produtos.
2. **Carrinho de Compras**: Editar, excluir e adicionar produtos ao carrinho.
3. **Processo de Checkout**: Os usuários podem finalizar a compra e escolher métodos de pagamento.
4. **Sistema de Recomendação**: Oferece sugestões de produtos com base em compras anteriores.
5. **Feedback dos Usuários:**: Permite que usuários avaliem produtos comprados.

## Tecnologias Utilizadas 🛠️

- **Node.js**: Backend da aplicação.
- **Express.js**: Framework web para criação de rotas e gerenciamento de requisições.

## Estrutura de Pastas 📂

```bash
techcart/
│
├── src/              # Código-fonte principal da aplicação.
│   ├── components/   # Componentes de interface do usuário (UI).
│   ├── services/     # Lógica e funções auxiliares para comunicação com APIs e manipulação de dados.
│   ├── tests/        # Testes automatizados para as funcionalidades do sistema.
│
├── docs/             # Documentação do projeto, como diagramas, guias e especificações.
├── scripts/          # Scripts auxiliares, como automação de tarefas ou instalação de dependências.
├── .gitignore        # Lista de arquivos e diretórios ignorados pelo Git.
├── README.md         # Arquivo de introdução e informações sobre o projeto.
└── package.json      # Configurações do projeto Node.js, incluindo dependências e scripts npm.
```

## Pré-requisitos 📝
- **Node.js** (v14.x ou superior)

## Instalação ⚙️
- **Siga os passos abaixo para rodar o projeto localmente:**

1. **Clone este repositório:**

````bash
git clone https://github.com/mouraGustavo/techcart.git
````
2. **Entre no diretório do projeto:**
````bash
cd techcart
````
3. **Instale as dependências:**
````bash
npm install
````
4. **Rode a aplicação em modo desenvolvimento:**

````bash
npm run dev
````
5. **Acesse no seu navegador**

## Comandos Básicos do Git
1. **Criar nova branch:**

````bash
git checkout -b feature/nome-da-funcionalidade
````
2. **Adicionar alterações:**

````bash
git add .
````
3. **Registrar as alterações:**

````bash
git commit -m "Descrição da alteração"
````
4. **Enviar a branch para o repositório remoto.:**
````bash
git push origin feature/nome-da-funcionalidade
````

## Práticas Recomendadas:
- Realizar commits frequentes com mensagens claras.
- Manter a branch principal sempre estável.
- Revisar o código antes de realizar merges.