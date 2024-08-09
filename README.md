# petshop-finder
## Instruções para executar o sistema

### Backend
1. Navegue para a pasta `backend`:
    ```bash
    cd backend
    ```
2. Instale as dependências:
    ```bash
    npm install
    ```
3. Inicie o servidor backend:
    ```bash
    node index.js
    ```
   
### Frontend
1. Navegue para a pasta `frontend`:
    ```bash
    cd frontend
    ```
2. Instale as dependências:
    ```bash
    npm install
    ```
3. Inicie o servidor frontend:
    ```bash
    npm start
    ```

## Lista de premissas assumidas

- Os preços variam entre dias de semana e finais de semana para alguns petshops.
- A distância é fixa e fornecida no código.
- A comparação entre petshops é feita com base no menor custo total, e em caso de empate, a distância é o critério decisivo.

## Decisões de projeto

- Utilizei Node.js com Express para o backend devido à sua simplicidade e integração fácil com o frontend React.
- Axios foi usado para fazer as requisições HTTP do frontend para o backend.

## O que mais você achar importante compartilhar sobre o projeto

- Este projeto é um exemplo simples e direto de como criar uma aplicação full-stack utilizando Node.js e React.
- O código está estruturado para ser de fácil compreensão e extensão. Por exemplo, novos petshops podem ser adicionados ao array `petshops` no backend com suas respectivas regras de precificação.
