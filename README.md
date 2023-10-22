# FIAP Airflow

## Introdução

Este projeto foi criado para demonstrar e executar tarefas de ETL usando o Apache Airflow no contexto do ambiente Astronomer. Ele contém várias DAGs que exemplificam diferentes funcionalidades e integrações.

## Configuração e Dependências

Antes de iniciar o projeto, certifique-se de ter instalado:

- Docker
- Astronomer CLI

Além disso, instale as dependências Python listadas em `requirements.txt`.

## Estrutura do Projeto

- `dags/`: Contém as Directed Acyclic Graphs (DAGs) do Airflow.
- `Dockerfile`: Define a imagem Docker usada pelo Astronomer.
- `requirements.txt`: Lista as dependências Python necessárias.

## Executando o Projeto Localmente

1. Inicie o Apache Airflow em sua máquina local executando `astro dev start`.
2. Verifique se todos os 4 contêineres Docker foram criados executando `docker ps`.
3. Acesse a UI do Airflow em [http://localhost:8080/](http://localhost:8080/). Use "admin" como nome de usuário e senha.

## Deploy no Astronomer

Se você tiver uma conta Astronomer, enviar código para um Deployment no Astronomer é simples. Para instruções de deploy, consulte a [documentação do Astronomer](https://docs.astronomer.io/cloud/deploy-code/).

## Contribuindo

Se você deseja contribuir para este projeto, siga as práticas padrão de desenvolvimento do Git:

1. Faça um fork do repositório.
2. Crie uma nova branch para suas alterações.
3. Envie suas alterações via pull request para revisão.
