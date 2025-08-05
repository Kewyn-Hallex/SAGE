# 🎓 SAGE - Plataforma Acadêmica

Sistema web inspirado no SIGAA para facilitar a gestão acadêmica entre professores e alunos de forma moderna, prática e interativa.

---

## 📂 Estrutura do Projeto

```

SAGE/
├── frontend/
│ ├── assets/           # Imagens, ícones e fontes
│ ├── css/           # Estilos personalizados
│ ├── js/           # Scripts do frontend
│ ├── components/           # Componentes HTML reutilizáveis (sidebar, header, etc.)
│ ├── pages/           # Páginas HTML (login, dashboard, disciplinas, etc.)
│ └── index.html           # Página inicial ou tela de login
│
├── backend/
│ ├── controllers/           # Lógica das rotas (disciplinas, usuários, notas)
│ ├── models/           # Modelos de dados
│ ├── routes/           # Definição das rotas da API
│ ├── middleware/           # Autenticação, validações, etc.
│ ├── config/           # Conexão com banco e variáveis de ambiente
│ ├── utils/           # Funções auxiliares
│ ├── app.js           # App principal do Express
│ └── server.js           # Inicialização do servidor
│
├── public/           # Arquivos servidos pelo Node.js (HTML, CSS, JS)
│
├── database/
│ ├── schema.sql           # Estrutura do banco de dados
│ └── seed.js           # Inserção de dados iniciais
│
├── docs/
│ └── roteiro.md           # Documentação e roteiro do sistema
│
├── .env           # Variáveis de ambiente
├── .gitignore           # Arquivos/pastas ignoradas no Git
├── package.json           # Dependências do projeto Node.js
└── README.md           # Este arquivo
````


---

## 🎯 Objetivo do Projeto

Desenvolver uma plataforma acadêmica web que centralize a gestão de disciplinas, notas, materiais, frequência e avisos, otimizando a comunicação entre professores e alunos.

---

## 👤 Público-Alvo

- **Professores:** gerenciamento de disciplinas, lançamento de notas, frequência e publicação de materiais.
- **Alunos:** acompanhamento de desempenho, acesso a conteúdos e envio de atividades.

---

## 📌 Funcionalidades

### Para Professores:
- Cadastro e edição de disciplinas
- Lançamento de notas e frequência
- Upload de materiais (PDF, slides, vídeos, etc.)
- Criação de atividades com prazos
- Publicação de avisos
- Respostas a dúvidas dos alunos

### Para Alunos:
- Visualização de disciplinas
- Acesso a materiais e avisos
- Envio de trabalhos
- Consulta de notas e frequência
- Área de comentários/dúvidas
- Notificações sobre prazos e novidades

---

## 💻 Tecnologias Utilizadas

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express
- **Banco de Dados:** (Você pode especificar MongoDB, MySQL, PostgreSQL, etc.)

---

## 🖥️ Design e Experiência

- Layout responsivo (mobile e desktop)
- Sidebar fixa para navegação
- Tipografia moderna e limpa
- Cards interativos com hover
- Painel com métricas acadêmicas
- Rodapé institucional simples

---

## ⚙️ Como rodar o projeto (dev)

1. Clone o repositório:
   ```bash
   git clone [URL-do-repositório]
