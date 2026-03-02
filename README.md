📌 API de Cadastro de Usuários

API simples para cadastro, listagem, atualização e remoção de usuários, desenvolvida com Node.js, Express, Prisma e MongoDB, com suporte a CORS.

---

🚀 Tecnologias utilizadas

Node.js

Express

Prisma

MongoDB

Cors

---

📂 Instalação e execução
1. Clonar o repositório
git clone https://github.com/seu-usuario/seu-repo.git
cd api-cadastro-de-usuarios

2. Instalar dependências
npm install

3. Configurar variáveis de ambiente

Crie um arquivo .env na raiz do projeto com a variável abaixo (ajuste com seus dados do MongoDB):

DATABASE_URL="mongodb+srv://<usuario>:<senha>@<cluster>/<database>?retryWrites=true&w=majority&appName=Users"

4. Rodar migrações do Prisma
npx prisma generate

5. Iniciar a aplicação
npm run dev


A API ficará disponível em:

http://localhost:3000

---

🔑 Endpoints disponíveis
➤ Listar usuários
GET /usuarios


Resposta:

[
  {
    "id": "66c0f19d8e8e...",
    "name": "Lucas",
    "email": "lucas@email.com",
    "age": 23
  }
]

---

➤ Criar usuário
POST /usuarios


Body:

{
  "name": "Lucas",
  "email": "lucas@email.com",
  "age": 23
}


Resposta:

{
  "id": "66c0f19d8e8e...",
  "name": "Lucas",
  "email": "lucas@email.com",
  "age": 23
}

---

➤ Atualizar usuário
PUT /usuarios/:id


Body:

{
  "name": "Lucas Mendes",
  "email": "lucas@email.com",
  "age": 24
}


Resposta:

{
  "id": "66c0f19d8e8e...",
  "name": "Lucas Mendes",
  "email": "lucas@email.com",
  "age": 24
}

---

➤ Deletar usuário
DELETE /usuarios/:id


Resposta:

{
  "message": "Usuário deletado com sucesso !"
}

---

📂 Estrutura de pastas (simplificada)

api-cadastro-de-usuarios/

│── prisma/

│   └── schema.prisma

│── generated/

│   └── prisma/

│── server.js

│── package.json

│── .env

---

⚡ Observações

O CORS está habilitado para qualquer origem.

Os dados são salvos em MongoDB via Prisma.

Campos obrigatórios: name, email, age.

---

✍️ Autor: Lucas Fernandes

---
