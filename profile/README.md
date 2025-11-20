# FIAP Pós Tech - Software Architecture - Tech Challenge
Repositório central para o projeto "Tech Challenge" do curso de Pós-Graduação em Arquitetura de Software da FIAP.

## Sobre o Projeto
O objetivo deste projeto é aplicar conceitos avançados de arquitetura de software desenvolvendo um sistema de gerenciamento de pedidos para uma lanchonete fictícia. O sistema abrange desde o autoatendimento do cliente até o gerenciamento da cozinha.

O fluxo principal permite que o cliente se identifique (ou não), monte um pedido, confirme, realize o pagamento via integração externa e acompanhe o status de preparação até a entrega.

## Fases

Tanto o projeto quanto o curso estão estruturados em fases distintas, cada uma focada em conceitos específicos de arquitetura de software. A evolução desses conceitos demandou, em certos momentos, a reescrita de código, refatorações e o desmembramento de repositórios.

<details>
  <summary>Detalhes de cada fase</summary>

### Fase 1
  
- Aplicação Monolítica com Spring Boot.
- Banco de dados PostgreSQL.
- Arquitetura Hexagonal (Ports and Adapters).
- Definição inicial do DDD (Domain-Driven Design).
- Containerização com Docker.

### Fase 2

- Orquestração de containers com Kubernetes.
- Refatoração utilizando Clean Architecture.

### Fase 3

- Migração e refatoração para deploy na AWS.
- Implementação de Serverless (Lambda) para autenticação.
- Infraestrutura como Código (IaC) com Terraform.
- Pipelines de CI/CD com Github Actions.

### Fase 4

- O backend foi refatorado e dividido em 4 micro serviços.
- Adoção de bancos NoSQL (DynamoDB) em serviços que exigem alta escalabilidade de leitura/escrita, mantendo PostgreSQL onde a integridade relacional é crítica.
- Implementação de análise estática de código (SonarCloud) e cobertura de testes unitários (JUnit e JaCoCo).

![Fase 4 AWS diagram](../images/FASE_4.svg)

### Fase 5

</details>

## Integrantes do Grupo
- [Aldo Santos de Oliveira de Santana](https://github.com/AldoOps)
- [Alexandre Freire Ropero Junior](https://github.com/Alejunior32)
- [Iago Cavalcante Geraldo](https://github.com/ashenOneDev)
- [Pedro César Moura França](https://github.com/Pedro-cmf)
- [Reverson Batista Mendes](https://github.com/ReversonMendes)
