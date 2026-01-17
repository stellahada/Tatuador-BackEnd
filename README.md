# 🩸 Web site portfólio para um profissional autonomo - BackEnd

![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![MySQL](https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)

> Solução de back-end desenvolvida para fornecer uma experiência intuitiva e visualmente atrativa para clientes de um estúdio de tatuagem.

Este projeto gerencia os dados para o site do tatuador, permitindo que clientes conheçam trabalhos, entrem em contato e agendem sessões, além de fornecer ferramentas administrativas para o profissional.

![Dribbble](https://github.com/user-attachments/assets/20b2cac2-a2b0-4a64-b9ec-30bc7d2f6816)

---

## 🚀 Funcionalidades

- **Exibição de Portfólio:** API para alimentação da galeria com os trabalhos do tatuador.
- **Formulário de Contato:** Integração para permitir que clientes enviem emails diretamente pelo site.
- **Sessão "Sobre":** Gerenciamento das informações sobre o artista e seu estilo de trabalho.
- **Agendamento Online:** Ferramenta completa para verificar disponibilidade e marcar sessões.
- **Gerenciamento de Estoque:** Controle administrativo dos materiais e estoque do estúdio.
- **Autenticação Segura:** Login e Registro de usuários com criptografia (Bcrypt) e Tokens JWT.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi estruturado para garantir organização e integridade dos dados relacionais.

- **Back-end:** Node.js + Express
- **Banco de Dados:** MySQL
- **Autenticação:** JSON Web Token (JWT)
- **Integração:** Axios 
- **Util:** Dotenv, Nodemon

---

## 📂 Estrutura do Projeto

```bash
/src
  ├── config/       # Configuração do Banco de Dados (MySQL)
  ├── controllers/  # Lógica das requisições (Agendamento, Estoque, Portfólio)
  ├── routes/       # Definição das rotas da API
  ├── services/     # Regras de negócio
  └── app.js        # Configuração principal do Express
```

## ⚙️ Pré-requisitos e Instalação
Antes de começar, você vai precisar ter instalado em sua máquina o Node.js e um servidor MySQL rodando.

1. Clone o repositório
```Bash
git clone [https://github.com/SEU_USUARIO/NOME_DO_REPO.git](https://github.com/SEU_USUARIO/NOME_DO_REPO.git)
cd NOME_DO_REPO
```

2. Instale as dependências

```Bash
npm install
```
3. Configure as Variáveis de Ambiente Crie um arquivo ```.env``` na raiz do projeto e preencha com as credenciais do seu banco de dados:

```Bash
PORT=3000
DB_HOST=localhost
DB_USER=seu_usuario_mysql
DB_PASS=sua_senha_mysql
DB_NAME=nome_do_banco
```
## ⚡ Como Executar
Modo de Desenvolvimento Para rodar o servidor:

```Bash
npm run dev
# ou
node app.js
```
O servidor iniciará em: ```http://localhost:3000```

## Contribuidores 🧑‍💻👩‍💻🧑‍💻
Desenvolvido por:

| [<img src="https://avatars.githubusercontent.com/u/95144250?s=400&u=149cf20f52f4c096721d16967b22655f18e5c7f5&v=4" width=115><br><sub>Samuel Victor</sub>](https://github.com/Samuel-045) | [<img src="https://avatars.githubusercontent.com/u/138524660?v=4" width=115><br><sub>Erick Bernat</sub>](https://github.com/ErickBernat) | [<img src="https://avatars.githubusercontent.com/u/91349698?v=4" width=115><br><sub>Stella Hada</sub>](https://github.com/stellahada) | 
| :---: | :---: | :---: |
