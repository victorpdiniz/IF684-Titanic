# Predição de Sobrevivência no Titanic com Árvores de Decisão

Este projeto foi desenvolvido como parte da disciplina IF684 - Sistemas Inteligentes do curso de Engenharia da Computação do CIn-UFPE. O objetivo do projeto é construir um modelo preditivo que utilize a base de dados do Titanic para prever a sobrevivência dos passageiros no famoso naufrágio de 1912. 

Utilizando técnicas de Machine Learning, Multilayer Perceptron, Decision Trees e ____, exploramos diversas características dos passageiros, como idade, gênero, classe social, entre outras, para determinar a probabilidade de sobrevivência. 

Este repositório contém o código-fonte de cada um dos modelos, os dados utilizados, a análise exploratória e os resultados obtidos.

**Importante:** Os conteúdos e estrutura do projeto estão contidos no relatório do google colaboratory.

# Guidelines de Contribuição

## Mensagens de Commit

Utilizamos uma convenção que fornece um conjunto de regras para formular uma estrutura de mensagem de commit consistente da seguinte forma:

```
<type>[optional scope]: <description>

[optional body]
```

O tipo do commit pode ser:

- `feat` – uma nova funcionalidade é introduzida com as mudanças.
- `fix` – ocorreu uma correção de bug.
- `refactor` – código refatorado que não corrige um bug nem adiciona uma funcionalidade.
- `docs` – atualizações na documentação, como o README ou outros arquivos markdown.
- `style` – mudanças que não afetam o significado do código, provavelmente relacionadas à formatação do código, como espaços em branco, pontos e vírgulas ausentes, e assim por diante.

A linha de assunto do tipo de commit deve ser toda em letras minúsculas com um limite de 75 caracteres. Além disso, o corpo opcional do commit deve ser usado para fornecer mais detalhes que não cabem nas limitações de caracteres da descrição da linha de assunto.

## Criação de Branches

Uma branch do git deve começar com uma categoria. Escolha uma destas: `feature`, `bugfix`, ou `test`.

- `feature` é para adicionar, refatorar ou remover uma funcionalidade.
- `bugfix` é para corrigir um bug.
- `test` é para experimentação.

Após a categoria, deve haver um "/" seguido por uma descrição que resume o propósito desta branch específica. Esta descrição deve ser curta e em `kebab-case`. Para resumir, siga este padrão ao criar branches:

```
git branch <category/description-in-kebab-case>
```

Exemplos:

- Você precisa adicionar, refatorar ou remover uma funcionalidade: `git branch feature/create-new-button-component`
- Você precisa corrigir um bug: `git branch bugfix/button-overlap-form-on-mobile`
- Você precisa experimentar algo: `git branch test/refactor-components-with-atomic-design`
