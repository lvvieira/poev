# POEV - Portal de Oportunidades de Estágio e Vagas

**Website**: [poev.com.br](https://poev.com.br)  
**Status**: Em desenvolvimento 🚀

## 📚 Sobre o Projeto

**POEV** é um portal de oportunidades de estágio e empregos que conecta alunos e empresas em busca de talentos. O objetivo é criar uma plataforma que facilite o processo de recrutamento para empresas e amplie as chances dos estudantes e profissionais em início de carreira.

Este projeto é desenvolvido utilizando o framework **Django**, com o banco de dados **PostgreSQL** e está hospedado em um **VPS** com integração SSL para segurança. No futuro, ele será expandido para incluir funcionalidades como filtro por localidade, categorias de vagas e notificações em tempo real.

---

## 🚀 Tecnologias Utilizadas

- **Django** - Backend robusto e escalável em Python
- **PostgreSQL** - Banco de dados relacional para armazenamento eficiente
- **HTML5 & CSS3** - Estrutura e estilo da interface
- **JavaScript (Vanilla)** - Interatividade básica e funcionalidades front-end
- **Nginx** - Servidor web para gerenciar requisições
- **Certbot com SSL** - Segurança HTTPS para o site
- **Git & GitHub** - Controle de versão e colaboração

---

## 📂 Estrutura do Projeto

```plaintext
poev/
├── users/                # Módulo para gestão de usuários (login, registro)
├── jobs/                 # Módulo para criação e gestão de vagas de emprego
├── static/               # Arquivos estáticos (CSS, JS, imagens)
├── templates/            # Templates HTML para as páginas do site
├── poev/                 # Configurações principais do projeto Django
└── README.md             # Documentação do projeto
