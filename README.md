# Projeto Netflix Clone

Este projeto é um clone básico da plataforma Netflix, desenvolvido como exercício de aprendizado utilizando Django, HTML, CSS e JavaScript. O objetivo principal foi replicar algumas funcionalidades principais do Netflix, adaptando para um contexto simplificado de treino.

## Funcionalidades Principais

- *Autenticação de Usuário:*
  - Criação de contas de usuário.
  - Login e logout.
  - Interface diferenciada para usuários logados e não logados.

- *Gerenciamento de Perfil:*
  - Edição de perfil do usuário.
  - Mudança de senha.
  - Controle de sessão e status de login.

- *Visualização de Filmes e Séries:*
  - Reprodução de episódios através de links embed do YouTube.
  - Contabilização de visualizações por filme.
  - Adição automática de filmes assistidos à lista "Continuar Assistindo".

- *Atualizações de Conteúdo:*
  - Renovação automática dos filmes em destaque com base em novos lançamentos.
  - Listagem de filmes "Em Alta" baseada nas visualizações.
  - Listagem dos ultimos filmes que a conta visualizou e adição no campo "assistido".

- *Interface de Administração:*
  - Painel de administração do Django para gerenciamento completo do site.
  - Controle sobre usuários, filmes, visualizações, usuários e configurações gerais.

## Tecnologias Utilizadas

- *Python* - Linguagem de programação principal.
- *Django* - Framework web para backend.
- *HTML, CSS* - Para estruturação e estilização da interface.
- *JavaScript* - Implementação mínima para funcionalidades adicionais.
- *Bootstrap* - Para facilitar o desenvolvimento do frontend.

## Requisito

- *Python* - 3.x instalado.

## Como Instalar e Rodar a Aplicação

1. *Clonar o Repositório:*

   ```bash
   git clone https://github.com/seuusuario/netflix-clone.git
   cd netflix-clone

2. *Ativar o ambiente virtual(Venv)*
    ```
   - .\venv\Scripts\Activate
     *2.1 Detalhe importante!!*
     - Caso ele peça para baixar as dependências do projeto é só executar o comando a seguir no bash
     - *pip install -r requirements.txt*

3. *Rodar a aplicação para a curtição*
    ```
    -python manage.py runserver

4. *Acessar o Admin e/ou as funcionalidades do site*

Para acessar a interface de administração do Django, você pode usar as seguintes credenciais, mas caso queira pode criar a sua própia:

5. PARA SE LOGAR COMO UM ADMIN
    ```
    Usuário: Apresentacao_github 
    Senha: Git_hub_10
O painel de administração estará disponível em http://127.0.0.1:8000/admin/.

6. PARA SE LOGAR COMO USUÁRIO COMUM DO SITE
    ```
    Usuário: user_comum_site
    Senha: pessoa_comum_10
Após iniciar o servidor a pessoa comum já pode se divertir a vontade no 