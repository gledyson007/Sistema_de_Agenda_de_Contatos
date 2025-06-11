# Sistema de Agenda de Contatos

<p align="center">
  <img src="https://raw.githubusercontent.com/gledyson007/Sistema_de_Agenda_de_Contatos/main/assets/tela-inicial.png" alt="Tela Inicial" width="420"/>
  <img src="https://raw.githubusercontent.com/gledyson007/Sistema_de_Agenda_de_Contatos/main/assets/contact.png" alt="Formulário de Contato" width="420"/>
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/gledyson007/Sistema_de_Agenda_de_Contatos/main/assets/login.png" alt="Tela de Login" width="420"/>
  <img src="https://raw.githubusercontent.com/gledyson007/Sistema_de_Agenda_de_Contatos/main/assets/sing-up.png" alt="Tela de Registro" width="420"/>
</p>

Sistema de gerenciamento de contatos pessoais desenvolvido com Django, com funcionalidades completas para cadastro, autenticação de usuários e manipulação de contatos.

## Tecnologias Utilizadas

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)

## Funcionalidades

-   **CRUD Completo de Contatos** - Cadastro, leitura, atualização e remoção de contatos do sistema.
-   **Autenticação de Usuários** - Sistema de login e registro seguro, onde cada usuário só pode ver seus próprios contatos.
-   **Gerenciamento de Perfil** - Usuários podem visualizar e atualizar suas próprias informações.
-   **Busca de Contatos** - Pesquisa eficiente para encontrar contatos no acervo pessoal.
-   **Upload de Imagens** - Capacidade de associar uma imagem de perfil a cada contato.
-   **Sistema Visual e Responsivo** - Interface limpa e adaptável para uso em desktop e dispositivos móveis.

## Pré-requisitos

-   Python 3.8+
-   Git

## Como Executar o Projeto

1.  **Clonar o repositório**:
    ```bash
    git clone [https://github.com/gledyson007/Sistema_de_Agenda_de_Contatos.git](https://github.com/gledyson007/Sistema_de_Agenda_de_Contatos.git)
    cd Sistema_de_Agenda_de_Contatos
    ```

2.  **Criar e ativar o ambiente virtual**:
    ```bash
    python -m venv venv
    # No Windows:
    venv\Scripts\activate
    # No Linux/macOS:
    source venv/bin/activate
    ```

3.  **Instalar as dependências**:
    ```bash
    pip install -r requirements.txt
    ```

4.  **Aplicar as migrações do banco de dados**:
    ```bash
    python manage.py migrate
    ```

5.  **Criar um superusuário (opcional, para testes)**:
    ```bash
    python manage.py createsuperuser
    ```

6.  **Iniciar a aplicação**:
    ```bash
    python manage.py runserver
    ```

7.  **Acesse a aplicação no seu navegador**:
    ```
    [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
    ```

---

#### Desenvolvido por Gledyson © 2025
