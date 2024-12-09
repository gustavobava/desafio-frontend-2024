# Desafio: Gerenciamento de Transações Financeiras
Neste desafio, você será responsável por desenvolver a interface de um sistema de gerenciamento de transações financeiras, utilizando JavaScript e TypeScript. O objetivo é avaliar sua habilidade em criar soluções interativas, bem tipadas e que sigam boas práticas de desenvolvimento front-end.

## Orientações
1. Crie um repositório no GitHub para a resolução do desafio.
2. No README, documente:
    - Tecnologias utilizadas.
    - Como configurar e executar o projeto.
    - Descrição das funcionalidades implementadas.
3. Utilize TypeScript como linguagem principal.
4. Frameworks como React, Angular, ou Vue.js são permitidos, mas não obrigatórios.

## Objetivo
Desenvolver uma interface dinâmica que permita aos usuários interagir com seu histórico de transações financeiras.

## Funcionalidades Requeridas
1. Cadastro de Transações

- Crie um formulário que permita adicionar transações ao sistema.
- Campos obrigatórios:
  - Descrição: Texto curto sobre a transação.
  - Valor: Número positivo ou negativo (entrada/saída).
  - Data: Data da transação (formato DD/MM/AAAA).
- Valide as entradas, exibindo mensagens de erro em caso de inconsistências.
2. Histórico de Transações

- Exiba as transações cadastradas em uma tabela com as colunas:
  - Descrição
  - Valor (positivo ou negativo, com formatação monetária)
  - Data (ordenada do mais recente ao mais antigo)
- Adicione um botão para excluir uma transação.
3. Filtros e Ordenação

- Permita que o usuário:
  - Ordene as transações por data, valor ou descrição.
  - Filtre as transações por tipo (entrada/saída).
4. Resumo Financeiro

- Exiba um resumo no topo da página com:
  - Total de entradas.
  - Total de saídas.
  - Saldo atual.
5. Modo Claro/Escuro

- Adicione uma funcionalidade para alternar entre tema claro e escuro.
## Requisitos Técnicos
1. Uso de TypeScript

- Tipagem obrigatória para:
  - Dados das transações (ex.: interface Transaction).
  - Funções (tipagem de parâmetros e retornos).
  - Componentes, se estiver usando um framework.
- Use generics quando necessário.
2. Estrutura e Organização

- Separe responsabilidades no código:
  - Ex.: um arquivo para os componentes, outro para os dados, outro para lógica de ordenação e filtros.
3. Boas Práticas
- Utilize ferramentas como ESLint e/ou Prettier para manter a padronização do código.
- Priorize a acessibilidade no design.
4. Simulação de API

- Use um mock local ou biblioteca (ex.: json-server) para armazenar as transações e simular um backend.
5. Testes

- Escreva testes unitários para as funcionalidades principais, como:
  - Adicionar uma transação.
  - Filtrar/ordenar transações.
  - Cálculo do saldo e resumo financeiro.
## Avaliação
### Habilidades Avaliadas
- JavaScript/TypeScript

  - Uso consistente e eficiente de TypeScript, incluindo interfaces, tipagem de funções e classes.
  - Domínio das principais estruturas e funções do JavaScript.
- Front-End

  - Manipulação de eventos e estado.
  - Componentização e reutilização de código.
  - Consumo de APIs simuladas.
- Design e UX

  - Implementação responsiva e acessível.
  - Boas práticas visuais e de interação.
- Testes

  - Qualidade e cobertura dos testes escritos.

Esse desafio avaliará suas habilidades com JavaScript e TypeScript, além de práticas modernas de desenvolvimento front-end. Boa sorte! 🚀