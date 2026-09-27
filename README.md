# Sistema de Gestão para Padaria Santo Pão

Projeto desenvolvido para a disciplina de **Práticas Extensionistas IV**.

## Sobre o projeto

O Sistema de Gestão para Padaria Santo Pão é uma solução web desenvolvida
para auxiliar na organização e gerenciamento das atividades de uma padaria.

O projeto dá continuidade ao sistema desenvolvido nas etapas anteriores
das Práticas Extensionistas, avançando nesta etapa para a definição da
arquitetura da aplicação, infraestrutura de implantação e processo DevOps.

## Tecnologias

- HTML
- CSS
- JavaScript
- PHP
- Apache
- MariaDB
- Git
- GitHub
- GitHub Actions

## Arquitetura

A arquitetura proposta utiliza uma infraestrutura self-hosted baseada
em Linux, separando a aplicação web e o banco de dados.

O servidor de aplicação utiliza Apache e PHP para execução do sistema,
enquanto o servidor de banco de dados utiliza MariaDB.

## Diagramas

Os diagramas desenvolvidos nesta etapa estão disponíveis na pasta
`diagramas/`.

Foram elaborados:

- Diagrama UML de Pacotes
- Diagrama de Arquitetura de Implantação
- Diagrama de Arquitetura DevOps

## Documentação

A documentação completa da Entrega 1 está disponível na pasta
`documentacao/`.

## Infraestrutura proposta

A solução utiliza uma infraestrutura self-hosted baseada em Linux.

A publicação da aplicação poderá ser realizada utilizando GitHub Actions
para integração e entrega contínua, com deploy no servidor através de
SSH e rsync.

## Estrutura do repositório

```text
.
├── diagramas/
│   ├── diagrama-pacotes.png
│   ├── diagrama-implantacao.png
│   └── diagrama-devops.png
├── documentacao/
│   └── pratica-extensionista-iv.pdf
├── sistema/
└── README.md
