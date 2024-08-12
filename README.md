# Projeto CRUD com Angular 9 #

Este é um projeto Angular que implementa um CRUD básico com um backend simples usando `json-server`.

## Estrutura do Projeto

- **frontend/**: Contém o código fonte do projeto Angular.
  - **src/**: Inclui os arquivos principais do aplicativo Angular, como `app`, `assets`, `environments`, `index.html`, `main.ts`, `polyfills.ts`, `styles.css`.
  - **angular.json**: Configuração principal do Angular CLI.
  - **tsconfig.json**: Configurações do TypeScript.
  - **tsconfig.app.json**: Configurações específicas para a aplicação Angular.
  - **package.json**: Lista de dependências e scripts do projeto frontend.

- **backend/**: Contém o servidor JSON para simular uma API.
  - **db.json**: Arquivo que armazena os dados da API simulada.
  - **package.json**: Lista de dependências e scripts do projeto backend.

## Instalação

### Frontend

1. Navegue até o diretório `frontend`:
    ```bash
    cd frontend
    ```

2. Instale as dependências:
    ```bash
    npm install
    ```

3. Execute o servidor de desenvolvimento:
    ```bash
    npm start
    ```

4. A aplicação estará disponível em `http://localhost:4200/`.

### Backend

1. Navegue até o diretório `backend`:
    ```bash
    cd backend
    ```

2. Instale as dependências:
    ```bash
    npm install
    ```

3. Execute o servidor JSON:
    ```bash
    npm start
    ```

4. O servidor estará disponível em `http://localhost:3001/`.

## Dependências

### Frontend

As principais dependências do frontend incluem:
- `@angular/core`: Framework principal para a construção de aplicações Angular.
- `@angular/material`: Conjunto de componentes UI da Google baseado no Material Design.
- `rxjs`: Biblioteca para programação reativa usando observables.

### Backend

As principais dependências do backend incluem:
- `json-server`: Simula uma API RESTful com base em um arquivo JSON.

## Uso

Após iniciar tanto o frontend quanto o backend, você pode interagir com a aplicação Angular para realizar operações CRUD, que serão manipuladas pelo servidor `json-server`.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Autor

Desenvolvido por Marcelo Novello.


