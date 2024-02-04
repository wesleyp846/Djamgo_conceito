# Djamgo - Conceitos para iniciantes

> Linguagens em `Python`, com o Framework `Django`.

&nbsp;
## Introdução `Projeto Terminado`
Bem-vindo à documentação do `tutorial` para `iniciantes` no framework `Django`. 

Uma ferramenta `completa` para codificação de aplicações `python` feitas para o embiente `web`.

Desenvolvida por [Wesley Pereira](https://github.com/wesleyp846).

&nbsp;

Este tutorial foi criado no contexto de servir de `consulta` com foco em `programadores iniciantes`. 

&nbsp;
&nbsp;
## Versão Atual: 1.0
&nbsp;
Na versão v1.0, o tutorial foi finalizado e entregue.

&nbsp;
&nbsp;
> ### Pré-requisitos
&nbsp;
`Python` 3.9+

Acesso a `WEB`.

&nbsp;
&nbsp;
> ### Tecnologias Utilizadas

[Python](https://docs.python.org/3/tutorial/index.html): Usado como linguagem de programação.


[Django](https://docs.djangoproject.com/en/5.0/): Usado na construção da aplicação, um facilitador como naturalmente é um framework.

&nbsp;
&nbsp;
> ### Funcionalidades

1. Averiguar se o framework foi completamente `instalado`.
   
&nbsp;
&nbsp;
> ###  Implementação
Para implementação basta `seguir` o tutorial.

&nbsp;
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

> ### Uso
* Em terminal
  
        python manage.py runserver

* Depois em navegador
  
        http://127.0.0.1:8000


&nbsp;
&nbsp;
> ### Créditos

Documentação e melhorias por [Wesley Pereira](https://github.com/wesleyp846).

&nbsp;
&nbsp;
> ### Licença
MIT

---


Esperamos que esta documentação ajude você a compreender a aplicação. 

Fique à vontade para contribuir e adicionar melhorias ao código. 

Para mais informações, visite o LinkedIn de [Wesley Pereira](https://www.linkedin.com/in/wesleyp846/).

Primeiro commit na data de 23/01/2025

# Algumas telas gráficas


![Se esta vendo essa imagem, deu tudo certo](<Captura de tela 2023-12-24 121034.png>)
Se você viu essa tela, deu tudo certo! Bons estudos
