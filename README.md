# Back-end do Projeto de Site.

Bem-vindo ao repositório do back-end do projeto de site. Este repositório contém o código fonte e as configurações necessárias para desenvolver e implantar o back-end do site utilizando tecnologias como AWS Lambda, API Gateway, PostgreSQL e Python.

## Visão Geral

Este back-end é responsável por gerenciar a lógica de negócios, a comunicação com o banco de dados e a exposição de endpoints através de uma API para o front-end do site da APAE.

## Tecnologias Utilizadas

- AWS Lambda: Plataforma de computação serverless que nos permite executar código sem a necessidade de provisionar ou gerenciar servidores.
- API Gateway: Serviço que permite criar, publicar, manter, monitorar e proteger APIs.
- PostgreSQL: Banco de dados relacional usado para armazenar informações relevantes para o site da APAE.
- Python: Linguagem de programação utilizada para escrever a lógica do back-end.

## Estrutura do Projeto

- `src/`: Diretório que contém o código fonte do back-end.
  - `handlers/`: Contém os manipuladores de eventos para as funções AWS Lambda.
  - `models/`: Contém os modelos de dados que representam as entidades do sistema.
  - `services/`: Contém os serviços que encapsulam a lógica de negócios.
- `serverless.yml`: Arquivo de configuração do Serverless Framework, usado para definir as funções AWS Lambda, os endpoints da API e outras configurações relacionadas à implantação.
- `requirements.txt`: Lista de dependências do Python necessárias para o projeto.

## Configuração e Implantação

1. Certifique-se de ter o Serverless Framework instalado: `npm install -g serverless`
2. Configure suas credenciais da AWS: `serverless config credentials --provider aws --key <SUA_CHAVE> --secret <SEU_SECRET>`
3. Instale as dependências Python: `pip install -r requirements.txt`
4. Edite o arquivo `serverless.yml` para ajustar as configurações conforme necessário, como nome da função, eventos da API, etc.
5. Execute o comando `serverless deploy` para implantar o back-end na AWS.

## Contato

Se você tiver alguma dúvida ou precisar de assistência, entre em contato com a equipe de desenvolvimento da APAE através do email: felipecarillo@outlook.com.
