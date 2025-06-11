# Sistema de Agenda de Contatos 📖

![Status do Projeto](https://img.shields.io/badge/status-conclu%C3%ADdo-green)

## Sobre o Projeto
<p align="justify">
Este projeto é uma aplicação web completa de Agenda de Contatos desenvolvida em Django. A plataforma permite que usuários se cadastrem, façam login e gerenciem seus próprios contatos de forma segura e eficiente. Cada usuário tem acesso apenas aos contatos que criou, garantindo a privacidade dos dados.
</p>
<p align="justify">
O sistema implementa todas as operações essenciais de um CRUD (Create, Read, Update, Delete) para os contatos, além de funcionalidades de busca e um sistema de autenticação de usuários robusto.
</p>

---

## Funcionalidades

-   ✅ **Autenticação de Usuários:** Sistema completo de registro, login e logout.
-   🔒 **Segurança:** Usuários só podem ver e editar os seus próprios contatos.
-   👤 **Gerenciamento de Usuário:** Permite que o usuário atualize suas próprias informações (nome, sobrenome, email).
-   ➕ **Criar Contatos:** Adicionar novos contatos à agenda pessoal.
-   ✏️ **Editar Contatos:** Atualizar informações de contatos existentes.
-   🗑️ **Deletar Contatos:** Remover contatos da agenda.
-   🔍 **Buscar Contatos:** Funcionalidade de busca para encontrar contatos rapidamente pelo nome ou sobrenome.
-   📱 **Design Responsivo:** Interface que se adapta a diferentes tamanhos de tela (desktop, tablet e mobile).

---

## Tecnologias Utilizadas

As seguintes ferramentas e tecnologias foram usadas na construção do projeto:

-   **Backend:** Python, Django
-   **Frontend:** HTML, CSS
-   **Banco de Dados:** SQLite3 (padrão do Django para desenvolvimento)
-   **Controle de Versão:** Git e GitHub

---

## Como Executar o Projeto

Siga as instruções abaixo para rodar o projeto em sua máquina local.

```bash
# 1. Clone este repositório
$ git clone [https://github.com/gledyson007/Sistema_de_Agenda_de_Contatos.git](https://github.com/gledyson007/Sistema_de_Agenda_de_Contatos.git)

# 2. Acesse a pasta do projeto
$ cd Sistema_de_Agenda_de_Contatos

# 3. Crie um ambiente virtual (recomendado)
$ python -m venv venv

# 4. Ative o ambiente virtual
# No Windows:
$ venv\Scripts\activate
# No Linux ou macOS:
$ source venv/bin/activate

# 5. Instale as dependências do projeto
# (Certifique-se de que você tem um arquivo requirements.txt)
$ pip install -r requirements.txt

# 6. Aplique as migrações do banco de dados
$ python manage.py migrate

# 7. Inicie o servidor de desenvolvimento
$ python manage.py runserver

# 8. Abra o navegador e acesse [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
