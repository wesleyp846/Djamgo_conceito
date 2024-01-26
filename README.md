# Projeto em pausa

# Djamgo - conceito
Projeto inicial para estudos da estrutura do Framework Django

---

## Versão v0.1

&nbsp;

> ### Pré-requisitos

Python 3.9+
 
&nbsp;
  
> ### Bibliotecas
 
[Django](https://docs.djangoproject.com/en/5.0/)

&nbsp;

> ### Pré-code
> > virtual environment
#### Feito via terminal, instalação de um ambiente virtual
    python -m venv env
    .\env\Scripts\activate

> > Instalando as bibliotécas

    python -m pip install --upgrade pip
    pip install django 

&nbsp;
> ### Code
> > #### Criação do projeto
 
    django-admin startproject <nome_do_projeto>
Nessa etapa foi criada a pasta do projeto e o arquivo que gerencia todo o porjeto `manege.py`, atravéz desse arquivo que o projeto ira rodar pela primeira vez para fins de teste.

>> #### Entra na pasta do projeto.

    cd /nome_do_projeto

###### Oque há aqui

* __init__.py__ (Inicialmente indiga que isso é um projeto) para o Django
* asgi.py (Configurações do servidor ASGI para deploy)
* settings.py (Configurações do projeto, com, senhas do mdb, templates, etc.)
* urls.py (Onde definiremos quais são os caminhos da aplicação (`os links`)) 
* wsgi.py (Configurações do servidor WSGI para deploy)
&nbsp;

>> #### Executa o projeto

    python manage.py runserver

>> #### Criação dos App's

    python manage.py startapp <nome_do_app>
* obs>> navege até ``./nome_do_projeto/settings.py``
em `INSTALLED_APPS` e adicione o `nome_do_app`

>> #### Entra na pasta do app.

    cd /nome_do_projeto/nome_do_app

###### Oque há aqui
* migrations (Todas as alterações que serão feitas no DB)
* __init__.py__ (Inicialmente indiga que isso é um projeto) para o Django
* admin.py (Página do administrador)
* apps.py (Página do aplicativo)
* models.py (Tabela de dados do db)
* tests.py (Reservado para testes)
* views.py (O que será renderizado na tela do app)


&nbsp;
&nbsp;

> ### Funcionalidades:

* Cadastrar novos usuários com nome, idade, contato, sexo, email e endereço
* Listar todos os usuários cadastrados em uma tabela
* Editar dados de um usuario
* Excluir um usuario
* Salvar os dados em um banco SQLite

&nbsp;
&nbsp;

> ### Uso
* Em terminal
  
        python manage.py runserver

* Depois em navegador
  
        http://127.0.0.1:8000

&nbsp;

> ### Implementação

 [Django](https://docs.djangoproject.com/en/5.0/) em uso a depender do tipo de projeto para web.

&nbsp;
&nbsp;

> Créditos


Código inicial baseado no canal [Hashtag Programação](https://www.youtube.com/watch?v=4u0aI-90KnU).


Documentação e melhorias adicionadas por [Wesley Pereira](https://github.com/wesleyp846)



&nbsp;
> Licença
MIT


Espero que a documentação ajude a entender a aplicação! Por favor sinta-se a vontade para melhorá-la.


# Algumas telas gráficas


![Se esta vendo essa imagem, deu tudo certo](<Captura de tela 2023-12-24 121034.png>)
Se você viu essa tela, deu tudo certo! Bons estudos
