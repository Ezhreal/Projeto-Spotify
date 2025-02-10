## README para Projeto Fullstack "Sporty" (4 Aulas)

Este README detalha o projeto "Sporty", um aplicativo web fullstack para entusiastas do esporte encontrarem e participarem de diversas atividades esportivas em sua região. O projeto será desenvolvido ao longo de 4 aulas, com foco em construção via código.

### Visão Geral do Projeto

O "Sporty" será construído utilizando tecnologias modernas de desenvolvimento web, abrangendo tanto o frontend quanto o backend. Cada aula focará em aspectos específicos da aplicação, permitindo a construção incremental do projeto.

### Tecnologias Utilizadas

  * **Frontend:** React, HTML, CSS, JavaScript
  * **Backend:** Node.js, Express, MongoDB
  * **Outras:** Git (controle de versão)

### Funcionalidades

  * **Cadastro e Login de Usuários:** Autenticação segura de usuários.
  * **Criação e Gerenciamento de Atividades:** Organização de eventos esportivos.
  * **Busca e Filtro de Atividades:** Encontre atividades por diversos critérios.
  * **Participação em Atividades:** Confirme sua presença em eventos.

### Instruções para Executar o Projeto

1.  **Clone o Repositório:**

    ```bash
    git clone [https://github.com/seu-usuario/sporty.git](https://github.com/seu-usuario/sporty.git)
    ```

2.  **Instale as Dependências:**

    ```bash
    cd sporty
    npm install
    ```

3.  **Configure o Banco de Dados:**

      * Crie um banco de dados MongoDB.
      * Configure as informações de conexão no arquivo `.env`.

4.  **Execute o Backend:**

    ```bash
    npm start
    ```

5.  **Execute o Frontend:**

    ```bash
    cd client
    npm start
    ```

### Estrutura do Projeto

  * **Backend:**
      * `routes`: Arquivos de rotas para as APIs.
      * `models`: Schemas de dados para o MongoDB.
      * `config`: Arquivos de configuração (banco de dados, etc.).
      * `index.js`: Arquivo principal do servidor.
  * **Frontend:**
      * `src`: Código fonte da aplicação React.
      * `components`: Componentes reutilizáveis da interface.
      * `App.js`: Componente principal da aplicação.
      * `index.js`: Arquivo principal do frontend.

### Conteúdo das Aulas

  * **Aula 1: Interface do Aplicativo**
      * Criação da interface do aplicativo usando HTML, CSS, Javascript e React.
  * **Aula 2: Backend do Projeto**
      * Desenvolvimento do backend com Express e Node, conectando com o banco de dados MongoDB.
  * **Aula 3: Player de Áudio Completo**
      * Conexão do frontend e backend, criação do player de áudio completo.
  * **Aula 4: Deploy e Portfólio**
      * Deploy da aplicação e disponibilização em um site para o portfólio.

### Recursos Adicionais

  * **Documentação React:** [https://react.dev/](https://react.dev/)
  * **Documentação Node.js:** [https://nodejs.org/en](https://nodejs.org/en)
  * **Documentação MongoDB:** [https://www.mongodb.com/](https://www.mongodb.com/)

Este README será atualizado ao longo do desenvolvimento do projeto, com mais detalhes sobre cada aula e funcionalidades implementadas.
