# Especificação de Caso de Uso **Sempre Leio**

# CDU03: **Criar Comunidade**

## 1. Descrição

O usuário autenticado acionará opcão de "criar comunidade" quando irá preencher um formulário com informações requisitadas sobre a comunidade que pretende criar, podendo anexar uma imagem como perfil da comunidade, em seguida, irá salvar as informações.

## 2. Atores

* Usuário autenticado

## 3. Pré-condições

### 3.1 Usuário autenticado

Usuário precisa ter passado pelo processo de login.

### 3.2 Inexistência de comunidade

No SempreLeio, não deve existir duas comunidade com o mesmo nome.

## 4. Pós-condições

### 4.1 Comunidade criada

A Comunidade será registrada tornando o usuário autenticado o seu proprietário.

## 5. Pontos de Extensão

Anexar uma imagem alusiva.

### 5.1 Acessar Comunidade

O usuário será redirecionado para a página da comunidade recém criada.

## 6. Fluxos de Evento

### 6.1 Fluxo principal

_Estende o Caso de Uso “Pesquisar comunidades”_
 
1. O usuário devidademente autenticado, ao constatar que não existe uma comunidade de seu interesse, seleciona a função “Criar comunidade”.
1. O sistema apresentará um formulário com os dados necessários para criar uma comunidade (RN-05).
1. O usuário preenche o formulário.
1. O usuário confirma os dados.
1. O sistema cria a comunidade e o usuário torna-se o proprietário daquela comunidade.
1. O CDU finalizado e é exibida a tela da comunidade recém-criada.

### 6.2 Fluxo alternativo

3a1. O usuário opta por uma _Comunidade com imagem alusiva_ (RN-08).
3a2. O fluxo retorna ao passo 4.

## 7. Situações de erro

Outra Comunidade existe com o mesmo nome.

### 7.1 Consequências

1. O caso de uso retorna ao passo 3 do fluxo principal.
 
## 8. Regras de negócio

RN-05, RN-08