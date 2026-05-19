# maisCine
A maisCine é uma API criada para organizar informações sobre filmes e séries. 
Com ela é possivel listar os conteúdos, adicionar as informações e remover algo no sistema.

---
# Como executar o projeto
## Clonar o repositório
```bash
git clone https://github.com/seuusuario/cineapi.git
```
## Entrar na pasta do projeto 
```bash
cd maiscineapi
```
## Instalar as dependências
```bash
npm install
```
## Rodar o projeto
```bash
npm run dev
```
## Acessar no navegador
```bash
http://localhost:3000
```
---

# Endpoints / Rotas

## Filmes

| Método | Rota | Função |
|--------|------|---------|
| GET | /movies | Mostrar todos os filmes |
| GET | /movies/:id | Buscar filme pelo ID |
| POST | /movies | Adicionar filme |
| PUT | /movies/:id | Atualizar filme |
| DELETE | /movies/:id | Deletar filme |

---

## Séries

| Método | Rota | Função |
|--------|------|---------|
| GET | /series | Mostrar todas as séries |
| GET | /series/:id | Buscar série pelo ID |
| POST | /series | Adicionar série |
| PUT | /series/:id | Atualizar série |
| DELETE | /series/:id | Deletar série |

---
# Tecnologias usadas
- Node.js
- TypeScript
- Express
- EJS

---
# Estrutura de pastas

```bash
maiscineapi/
│
├── src/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middlewares/
│   ├── views/
│   └── app.ts
│
├── package.json
├── tsconfig.json
└── README.md
```

---
# Autor 
- Antonio Lucas
- Turma: Segunda série
- Instituição: Senac
