![Ilustração de servidores interligados por linhas de dados](assets/backend-cover.jpg)

# João Rodrigues

**Desenvolvedor backend Java · Spring Boot**

Estudo Engenharia de Software e compartilho projetos de APIs, ferramentas de terminal e integração com dispositivos IoT. Tenho interesse em modelagem de domínio, testes automatizados e documentação que ajude a rodar o projeto.

[LinkedIn](https://www.linkedin.com/in/jo%C3%A3o-pedro-rodrigues-alves-1592b9255/) · [Todos os repositórios](https://github.com/joaorodrigues12?tab=repositories)

## Projetos selecionados

### [ESP32 Fleet Simulator](https://github.com/joaorodrigues12/esp32-fleet-simulator-mqtt)

Simulador de dispositivos ESP32 para testar aplicações MQTT. Publica leituras sintéticas e sinais de presença para um dispositivo ou uma frota.

**Python · MQTT · Docker Compose**

[![Status dos testes automatizados do simulador na branch main](https://github.com/joaorodrigues12/esp32-fleet-simulator-mqtt/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/joaorodrigues12/esp32-fleet-simulator-mqtt/actions/workflows/ci.yml) · [Versões publicadas](https://github.com/joaorodrigues12/esp32-fleet-simulator-mqtt/releases)

<details>
<summary>Ver cenários e testes</summary>

- Sementes fixas permitem reproduzir sequências de leituras.
- Cada dispositivo virtual mantém sua própria conexão e sessão MQTT.
- A integração contínua roda em Windows e Ubuntu.

</details>

### [todo-cli](https://github.com/joaorodrigues12/todo-cli)

Gerenciador de tarefas no terminal para cadastrar, listar, concluir e filtrar tarefas, com persistência em JSON local.

**Java 25 · Maven · JUnit 5**

<details>
<summary>Ver arquitetura e testes</summary>

- O domínio usa records imutáveis e os comandos usam sealed interfaces.
- O serviço de tarefas depende de uma interface de repositório. Isso permite testar as regras sem gravar arquivos.
- O Maven executa os testes com `mvn verify`. [Histórico de integração contínua](https://github.com/joaorodrigues12/todo-cli/actions/workflows/ci.yml)

</details>

### [FinMarket](https://github.com/joaorodrigues12/Finmarket)

Projeto acadêmico de um aplicativo móvel que reúne notícias financeiras e usa IA para gerar resumos e analisar o sentimento das notícias.

**React Native · Expo · FastAPI**
