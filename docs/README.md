# 🌱 Vozes da Amazônia

Rede social colaborativa para dar visibilidade às comunidades ribeirinhas, indígenas e tradicionais da Amazônia sobre os impactos das mudanças climáticas.  
---

## 📂 Estrutura do Projeto

```

vozes-da-amazonia/
├── frontend/
│   ├── assets/           # Arquivos estáticos (css, js, imagens, fonts)
│   ├── components/       # Componentes reutilizáveis (cards, navbar, footer)
│   ├── pages/            # Telas completas (home, login, perfil, etc.)
│   ├── map/              # Integrações e scripts do mapa
│   ├── index.html        # Página inicial
│   └── login.html        # Tela de login (exemplo)
│
├── backend/
│   ├── controllers/      # Lógica do sistema (auth, relatos, etc.)
│   ├── models/           # Regras de negócio e manipulação do banco
│   ├── routes/           # Rotas da API (arquivos PHP)
│   ├── config/           # Configuração, conexão com o banco, .env
│   ├── middleware/       # Autenticação, validação, etc.
│   ├── uploads/          # Mídias enviadas pelos usuários
│   ├── api.php           # Arquivo principal das rotas da API
│   └── .htaccess         # Regras de URL e segurança
│
├── database/
│   ├── migrations/       # Scripts SQL para criar as tabelas
│   └── vozes\_da\_amazonia.sql # Backup do banco principal
│
├── docs/
│   └── arquitetura-e-requisitos.pdf # Documentação oficial do projeto
│
│
├── README.md             # Este arquivo
└── .gitignore            # Itens ignorados no Git

````

---

## 🚀 Visão Geral

O **Vozes da Amazônia** é uma plataforma para que as comunidades amazônicas compartilhem relatos (texto, imagem, áudio ou vídeo) sobre os impactos das mudanças climáticas, levando essas histórias até a COP 30 e para o mundo.  
Funcionalidades principais:
- Cadastro e login de usuários
- Postagens multimídia
- Feed social (curtir, comentar, compartilhar)
- Relatos geolocalizados no mapa da Amazônia
- Filtros por categoria (desmatamento, rios, seca, queimadas, etc.)

---

## 🛠️ Tecnologias

- **Frontend:** HTML, Tailwind CSS, JavaScript
- **Backend:** PHP
- **Banco de Dados:** MySQL

---

## 🏗️ Organização dos diretórios

- **frontend/**: interface do usuário e scripts
- **backend/**: lógica de negócio, rotas e regras de negócio
- **database/**: scripts SQL e backups do banco
- **docs/**: documentação oficial do projeto
---

## ⚙️ Como rodar (dev)

Clone o projeto:
   ```bash
   git clone [URL do repo]
````

---

## 📢 Observações internas

* Siga o padrão de organização dos diretórios!
* Toda nova feature deve ser feita na branch `develop`.
* Dúvidas? Puxe pelo grupo ou consulte o PDF de requisitos.

---
