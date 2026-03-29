# Projeto Conceitual de Banco de Dados - Oficina Mecânica

Este projeto apresenta o modelo conceitual de um sistema de controle e gerenciamento de ordens de serviço em uma oficina mecânica.

## Escopo

- Clientes levam veículos para consertos ou revisões.
- Cada veículo gera uma Ordem de Serviço (OS).
- Uma equipe de mecânicos é designada para cada OS.
- Serviços e peças são vinculados à OS, compondo o valor total.
- Mecânicos possuem código, nome, endereço e especialidade.
- Cada OS possui número, data de emissão, valor, status e data de conclusão.

## Entidades Principais
- Cliente
- Veículo
- Ordem de Serviço
- Equipe
- Mecânico
- Serviço
- Peça

## Relacionamentos
- Cliente possui Veículo.
- Veículo gera OS.
- OS é atribuída a uma Equipe.
- Equipe é composta por Mecânicos.
- OS inclui Serviços e Peças.
- Cliente autoriza OS.

O modelo foi desenvolvido utilizando a ferramenta [Draw.io](https://app.diagrams.net/) e está disponível neste repositório.
