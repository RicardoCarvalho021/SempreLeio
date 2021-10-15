# Especificação de Caso de Uso **Sempre Leio**

# CDU03: **Submeter Postagem**

## 1. Descrição

O usuário membro de uma comunidade registra um novo comentário e/ou um arquivo de mídia em um tópico, ou sem tópico, de uma comunidade.

## 2. Atores

* Membro da comunidade

## 3. Pré-condições

### 3.1 O usuário precisa estar autenticado

### 3.2 O usuário deve ser membro da comunidade

## 4. Pós-condições

### 4.1 Uma nova postagem é registrada para o tópico da comunidade

## 5. Pontos de Extensão

### 5.1 Postagem Criada

## 6. Fluxos de Evento

### 6.1 Fluxo principal

1. O usuário devidademente autenticado, ao escolher um tópico pertencente a uma comunidade à qual é membro seleciona a função “Nova Postagem”.
1. O sistema apresentará um formulário com os dados necessários para criar uma postagem (RN-06).
1. O usuário preenche o formulário.
1. O usuário confirma os dados.
1. O sistema cria a postagem.
1. O CDU finalizado e o sistema exibe a postagem criada.

### 6.2 Fluxo alternativo

3a1. O usuário opta por uma _Postagem com arquivo de midia_
3a2. O fluxo retorna ao passo 4.

## 7. Situações de erro

### 7.1 Formulário incompleto 

O usuário não informa o texto ou arquivo de mídia.

## 8. Regras de negócio

RN-06, RN-09
