# Formulário Básico em HTML com Loop While em JavaScript

Este é um repositório que contém um formulário básico em HTML e JavaScript, criado com o objetivo de treinar o uso do loop While em JavaScript.

## Funcionalidades

O formulário possui as seguintes funcionalidades:

- Campos de entrada para numero máximo do vetor e o numero a ser buscado.
- Um botão para submeter o formulário.
  - ao submeter o formulário, uma função javascript será chamada que irá fazer os seguintes passos:
    - Preencher um vetor sequencialmente do número 1 até o valor máximo colocado no input via loop For no javascript.
    - Dividir esse vetor ao meio e comparar se o número buscado está entre os números menores ou maiores.
    - Ao decidir, repetirá o processo.
    - Caso encontrado, será lançado um alerta na tela afirmando que o número foi encontrado, caso contrário, será alertado negativamente.

## Como Funciona

1. Abra o arquivo `index.html` em seu navegador.
2. Preencha os campos de entrada para numero máximo do vetor e o numero a ser buscado no formulário.
3. Clique no botão "Executar função" para submeter o formulário.
4. O script JavaScript alertará se o o numero buscado foi encontrado ou não e em qual posição.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

- `src/`: Pasta contendo toda a estrutura do projeto.
- `index.html`: Página contendo o formulário.

## Como Contribuir

Se você deseja contribuir com este projeto, siga estas etapas:

1. Faça um fork deste repositório.
2. Crie uma branch com a sua feature: `git checkout -b minha-feature`.
3. Faça commit das suas alterações: `git commit -m 'Adicione uma nova feature'`.
4. Faça push para a sua branch: `git push origin minha-feature`.
5. Envie um pull request.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
