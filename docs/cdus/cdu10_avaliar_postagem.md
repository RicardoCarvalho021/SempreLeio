### Criado por Vicente Limeira em 12/4/2021

# Especificação de Caso de Uso **Sempre Leio**

# CDU10: **Avaliar postagem** 

## 1. Descrição

O usuário autenticado seleciona o tópico da comunidade para exibir as últimas postagens daquele tópico. No detalhe da postagem de sua escolha irá avaliá-la como interessante, relevante ou destaque.

## 2. Atores

* Usuário membro

## 3. Pré-condições 

* Usuário membro da comunidade não deve ser o signatário da Postagem

## 4. Pós-condições

* O sistema registra a avaliação da postagem e recalcula o conceito da postagem

## 5. Pontos de Extensão

Não identificados.

## 6. Fluxos de Evento

### 6.1 Fluxo principal

_Estende o Caso de Uso “Exibir Postagens”_

1. O sistema exibe os detalhes das postagens do tópico escolhido e junto a cada postagem o conceito e as opções de avaliação: interessante, relevante ou destaque.
1. O ator seleciona uma das três opções de avaliação da postagem.
1. O sistema reexibe os detalhes das postagens com a atualização do conceito da postagem.
1. O CDU finalizado o sistema informa que o usuário foi acolhido pela comunidade

## 7. Situações de erro

* Não identificadas.

## 8. Regras de negócio

* RN 03
* RN 06
