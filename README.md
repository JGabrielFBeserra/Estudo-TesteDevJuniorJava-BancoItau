# Desafio de Programação - Itaú Unibanco

## Descrição
Este projeto consiste na implementação de uma API REST que recebe transações e retorna estatísticas com base nessas transações. A API foi desenvolvida utilizando Java 21 e Spring Boot 3.4.1, seguindo as restrições técnicas definidas no desafio.

## Tecnologias Utilizadas
- Java 21
- Spring Boot 3.4.1
- Spring Web
- Spring Boot Actuator
- Lombok

## Endpoints Implementados
1. **Receber Transações** (`POST /transacao`)
2. **Limpar Transações** (`DELETE /transacao`)
3. **Calcular Estatísticas** (`GET /estatistica`)

## Extras Implementados
- **[3] Logs:** A aplicação registra eventos relevantes para monitoramento e solução de problemas.
- **[6] Tratamento de Erros:** Melhorias no tratamento de erros, garantindo respostas claras e padronizadas.
- **[8] Documentação da API:** Utilização do SpringDoc OpenAPI para geração automática da documentação da API.
- **[9] Documentação do Sistema:** Instruções de como construir e executar a aplicação.

## Extras a serem implementados
- **[1] Testes Automatizados**
- **[2] Containerização**
- **[4] Observabilidade (Healthcheck)**
- **[5] Performance**
- **[7] Configurações dinâmicas para cálculo das estatísticas**

## Como Executar o Projeto
1. Certifique-se de ter o JDK 21 instalado.
2. Clone este repositório.
3. Execute o seguinte comando para iniciar a aplicação:
   ```sh
   ./gradlew bootRun
   ```
4. Acesse a documentação da API em: `http://localhost:8080/swagger-ui.html`

## Testes
Os testes unitários podem ser executados com:
```sh
./gradlew test
```

## Contribuição
Contribuições são bem-vindas! Sinta-se livre para abrir issues e pull requests.


