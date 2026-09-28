# 📝 Lista de Amigos (PT-BR)

## 📒 Sobre o projeto
Este projeto consiste em uma aplicação web para gerenciamento de contatos e controle de acesso, desenvolvida como projeto final da disciplina de **Programação Web II** pela aluna **Gabriela (Gabi)**, sob orientação da **Profª Alice**.

O sistema foi projetado para demonstrar na prática a integração entre **Front-end** (HTML5/CSS3) e **Back-end** (PHP/MySQLi), contemplando desde a restrição de acesso por login e sessões até as 4 operações fundamentais de dados (**CRUD**).

## 🔒 Sistema de Login e Autenticação
**Controle de Acesso:** Autenticação de usuários cadastrados no banco de dados.
**Sessões PHP (session_start):** Manutenção de login ativo entre as páginas e bloqueio de acessos não autorizados.
**Logoff Seguro:** Encerramento completo da sessão via session_destroy().

## ✨ Como funciona?
A aplicação utiliza o método **POST** para envio seguro dos dados de formulários e processa as seguintes operações na tabela de amigos:

1. **Create (Cadastrar):** Inserção de novos contatos (Nome, E-mail, Telefone e Data de Nascimento) via `INSERT INTO`.
2. **Read (Listar):** Exibição dinâmica da tabela de amigos cadastrados via `SELECT`.
3. **Update (Editar):** Atualização das informações de contatos existentes utilizando `UPDATE ... WHERE id = X`.
4. **Delete (Excluir):** Remoção de registros com confirmação e uso de `DELETE FROM ... WHERE id = X`.

## 🛠 Linguagens de programação
<div style="display: inline_block"><br>
    <img align="center" alt="HTML" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" >
    <img align="center" alt="PHP" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/php/php-original.svg" >
    <img align="center" alt="CSS" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" >
    <img align="center" alt="MySQL" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original-wordmark.svg" >
    <img align="center" alt="Markdown" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/markdown/markdown-original.svg" />
</div>

## 📊 Commits
![GitHub commit activity](https://img.shields.io/github/commit-activity/t/aline-coro/forms-registration)
![GitHub last commit](https://img.shields.io/github/last-commit/aline-coro/apresentacao-programacao)