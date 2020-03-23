h1 align="center">
	<img alt="GoStack" src=".github/GoStackLogo.png" width="200px" />
</h1>

<h3 align="center">
  GoBarber
</h3>

<p align="center">
  <a href="#-Instalação-e-execução">Instalação e execução</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-contribuir">Como contribuir</a>&nbsp;&nbsp;&nbsp;
</p>

## 📥 Instalação e execução

Faça um clone desse repositório.

### Backend

1. A partir da raiz do projeto, entre na pasta do backend rodando `cd backend`;
2. Rode `yarn --force` para instalar as dependências;
3. Crie um banco de dados no `postgres` com o nome de `gobarber`;
4. Rode `cp .env.example .env` e preencha o arquivo `.env` com **SUAS** variáveis ambiente;
5. Rode `yarn sequelize db:migrate` para executar as migrations;
6. Rode `yarn dev` para iniciar o servidor.