# Projeto NLW Journey - Rocketseat

Projeto desenvolvido durante a NLW Journey da [Rocketseat](https://www.rocketseat.com.br) em Java utilizando Spring Boot e MySQL.

## Descrição do Projeto

Este projeto consiste em uma aplicação para gerenciamento de viagens. Os usuários podem cadastrar viagens, convidar participantes e gerenciar atividades e links importantes relacionados à viagem.

### Requisitos Funcionais

1. **Cadastro de Viagem**
    - O usuário cadastra uma viagem informando:
        - Local de destino
        - Data de início
        - Data de término
        - E-mails dos convidados
        - Nome completo do criador
        - Endereço de e-mail do criador

2. **Confirmação de Viagem**
    - O criador da viagem recebe um e-mail para confirmar a nova viagem através de um link.
    - Ao clicar no link, a viagem é confirmada.
    - Os convidados recebem e-mails de confirmação de presença.
    - O criador é redirecionado para a página da viagem.

3. **Confirmação de Presença dos Convidados**
    - Os convidados, ao clicarem no link de confirmação de presença, são redirecionados para a aplicação.
    - Na aplicação, os convidados devem inserir seu nome (o e-mail já estará preenchido).
    - Após inserirem seu nome, estarão confirmados na viagem.

4. **Gerenciamento de Links Importantes**
    - Na página do evento, os participantes da viagem podem adicionar links importantes, como:
        - Reserva do AirBnB
        - Locais para serem visitados
        - Outros links relevantes

5. **Gerenciamento de Atividades**
    - Na página do evento, o criador e os convidados podem adicionar atividades que irão ocorrer durante a viagem, informando:
        - Título
        - Data
        - Horário

6. **Convite de Novos Participantes**
    - Novos participantes podem ser convidados dentro da página do evento através do e-mail.
    - Eles devem passar pelo fluxo de confirmação como qualquer outro convidado.

## Tecnologias Utilizadas

- Java
- Spring Boot
- MySQL

## Como Executar o Projeto

### Pré-requisitos

- [JDK 11+](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- [Maven](https://maven.apache.org/)
- [MySQL](https://www.mysql.com/)

### Passos para Execução

1. Clone o repositório:
    ```bash
    git clone https://github.com/a5ur4/Plann.er.git
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd seu-repositorio
    ```
3. Configure o banco de dados MySQL:
    - Crie um banco de dados com o nome `nlw_journey`.
    - Configure o arquivo `application.properties` com suas credenciais do MySQL.

4. Compile e execute a aplicação:
    ```bash
    mvn spring-boot:run
    ```

5. Acesse a aplicação em:
    ```
    http://localhost:8080
    ```

## Contribuição

Para contribuir com este projeto, siga os passos abaixo:

1. Faça um fork do projeto.
2. Crie uma branch para a sua feature:
    ```bash
    git checkout -b minha-feature
    ```
3. Commit suas alterações:
    ```bash
    git commit -m 'Minha nova feature'
    ```
4. Envie para a branch principal:
    ```bash
    git push origin minha-feature
    ```
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---