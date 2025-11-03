# EcoCleanSystem 
Sistema de Gerenciamento para Empresa Especializada em Limpezas de Vidro Projeto de Trabalho de Conclusão de Curso (TCC) — Técnico em Informática para Internet Integrado ao Ensino Médio.

## 1. Introdução  
O **EcoCleanSystem** é um sistema completo de gerenciamento desenvolvido como **Trabalho de Conclusão de Curso (TCC)**, voltado para a empresa EcoClean que presta **serviços de limpeza de vidros**.  
O sistema foi criado para automatizar e centralizar tarefas essenciais, como atendimento ao cliente, agendamento de serviços e controle de estoque.  


## 2. Tecnologias Utilizadas  

### **Backend**
- Node.js  
- Express  
- MySQL  
- JWT (Json Web Token)  
- Arquitetura RESTful  

### **Frontend**
- HTML  
- CSS  
- JavaScript  


## 3. Estrutura do Projeto  

EcoClean/
│
├─ config/ ← Configurações do servidor e variáveis de ambiente
├─ public/ ← Arquivos públicos (CSS, JS, imagens)
├─ src/ ← Código-fonte do backend
│ ├─ controllers/ ← Controladores das rotas
│ ├─ routes/ ← Definição das rotas REST
│ ├─ models/ ← Modelos de dados (MySQL)
│ └─ services/ ← Lógica de negócio
├─ frontend/
│ └─ views/ ← Páginas HTML do sistema
├─ database.sql ← Script SQL de criação do banco de dados
├─ package.json
├─ app.js ← Ponto de entrada do servidor Node.js
└─ README.md

## 4. Como executar o projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/pamelaespindula/EcoClean.git

2. **Instale as dependências:**
   npm install
   
3. **Configure o banco de dados MySQL:**
Crie um banco de dados chamado ecoclean.

Execute o script database.sql para criar as tabelas necessárias.

4. **Atualize as credenciais de acesso ao banco:**

No arquivo config/db.js, insira seu usuário, senha e host do MySQL.

5. **Inicie o servidor:**
   ```bash
   npm run dev

6. **Acesse a aplicação no navegador:**
   http://localhost:3000  
