# Docker Compose: PostgreSQL e pgAdmin

Este repositório contém um exemplo simples de como usar o Docker Compose para configurar um ambiente de desenvolvimento local com PostgreSQL e pgAdmin.

## Pré-requisitos

Antes de começar, certifique-se de ter o Docker e o Docker Compose instalados na sua máquina. Você pode baixá-los e instalá-los a partir do [site oficial do Docker](https://www.docker.com/get-started).

## Como usar

1. Clone este repositório para o seu ambiente local:

    ```bash
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    ```

2. Navegue até o diretório clonado:

    ```bash
    cd PostgresDocker
    ```

3. Navegue até o app:

    ```bash
    cd app
    ```

4. Inicie os serviços do Docker Compose:

    ```bash
    docker-compose up --build
    ```

5. Acesse o pgAdmin no navegador:

    Abra o navegador e visite `http://localhost:8888`. Faça login com as credenciais padrão:
    - **Email:** vmartinsz@localhost.com
    - **Senha:** 17465849

6. Conecte-se ao PostgreSQL pelo pgAdmin:

    - Host: `postgres`
    - Porta: `5432`
    - Nome do usuário: `postgres`
    - Senha: `17465849`

7. Após concluir o trabalho, você pode parar os serviços do Docker Compose usando:

    ```bash
    docker-compose down
    ```

## Contribuindo

Se você encontrar qualquer problema ou tiver sugestões para melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto é distribuído sob a licença [MIT](https://opensource.org/licenses/MIT). Veja o arquivo [LICENSE](LICENSE) para obter mais detalhes.
