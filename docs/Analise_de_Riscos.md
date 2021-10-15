# **SempreLeio**
# **Gerenciamento de Processo**

**Histórico da Revisão**

| Data | Versão | Descrição | Autor 
| :--- | :---:| :------- | :----- |
| 19/04/2021 | 1.0 | Sistema desenvolvido e apresentado no WTADS de 2020.2 e em seguida, apresentado a banca | Ricardo Carvalho, André Luiz e Vicente Limeira |
| 20/06/2021 | 1.1 | Primeira análise | Vicente Limeira | 
| 23/06/2021 | 1.2 | Revisão | Vicente Limeira |
| 15/10/2021 | 1.2.1 | Revisão | Ricardo Carvalho e André Luiz |


## 1. Resumo

Este documento tem como objetivo identificar e monitorar qualquer coisa conhecida, desconhecida ou incerta, exposta ao projeto, que possa impedir ou mitigar o sucesso do planejamento. Os riscos aqui identificados são qualificados pelo impacto que podem causar no projeto, caso ocorram, proporcionando ao gerente do projeto empreender ações específicas de atenuação ou contingência.

## 2. Lista de Riscos

| Risco | Impacto |
| :----- | :------: |
| Gerente de Projeto | Muito Alto |
| Prazos e tempos de execução | Baixo |
| Adoção de novos métodos | Médio |
| Volatilidade da equipe | Alto |
| Equipe desfalcada | Alto |


### 2.1 Gerente de Projeto

A ausência de uma gestão acertada do gerente do projeto pode causar transtornos ao desenvolvimento da solução, provocando uma falta de alinhamento da visão da solução entre a equipe, gerando atrasos e implementações falhas ou incompatíveis com a solução.  

#### 2.1.1 Classificação ou Gravidade do Risco

**Alto impacto no projeto.**

#### 2.1.2 Estratégia de Diminuição

Realização de reuniões fixas semanais, gravadas e com registro de deliberações(ata de reunião), e planejamento de atividades individuais.
A equipe deve definir alguém responsável pela gestão da solução e da equipe, verificando constantemente o engajamento do gerente do projeto de modo a detectar antecipadamente um eventual risco de saída na gestão e a equiepe deve relatar falhas na gestão do gerente de projeto caso ocorra.

#### 2.1.3 Plano de Contingência

* Caso não tenha um gerente de projeto, ou o responsável pela gestão se ausente, a equipe do projeto deve eleger entre eles, de forma concensual, um novo gerente responsável para o projeto.
* A equiepe e o gerente de projeto devem gerar um relatório de cada interação para fins de verificação do próprio desenpenho. 

### 2.2 Prazos e tempos de execução

Prazos e tempos de execução de tarefas mal estimados provocam atrasos nas iterações e consequentemente na entrega do produto final, bem como podem causar aumento de custos na construção do software e provocar descontentamento para os stakeholders.

#### 2.2.1 Classificação ou Gravidade do Risco

**Baixo impacto no projeto.**

#### 2.2.2 Indicadores

Prazo para entrega final originalmente planejado: 2 meses. 

#### 2.2.3 Estratégia de Diminuição

Os prazos para entregas parciais e final deverão estar continuamente sendo revisados a cada fim de iteração.

#### 2.2.4 Plano de Contingência

* Reavaliação seguida de negociação junto ao cliente de uma eventual diminuição no escopo do projeto.
* Consultar os stakeholders sobre os conflito da solução e com os feedback guiar as próximas iterações.

### 2.3 Adoção de novos métodos

Tentativas de adoção de novos métodos de desenvolvimento ou tecnologia durante o projeto poderá ocasionar atrasos nas iterações e consequentemente na entrega do produto final, bem como podem causar aumento de custos na construção do software. Dependências de produtos de terceiros podem causar impasses nos momentos futuros de atualização tecnológica do software quando algum fornecedor não evoluiu ou mesmo descontinuou o produto agregado ao projeto.

#### 2.3.1 Classificação ou Gravidade do Risco

**Médio impacto no projeto.**

#### 2.3.2 Indicadores

Lista de produtos utilizados no projeto.

| Produto | Versão | Licença |
| :---- | :---: | :-----: |
| Python | 3.7.3 | Open Source |
| JavaScript | ECMAScript 2018 | Netscape |
| Framework Django | 3.1.6 | BSD |
| Framework React | 17.0.2 | MIT |
| Astah UML | 8.3.0 | Academic |
| PostgreSQL | 13.2 | BSD |


#### 2.3.3 Estratégia de Diminuição

Utilizar o menor número de produtos agregados, debatendo internamente sobre sua evolução histórica e a credibilidade de cada fornecedor.

#### 2.3.4 Plano de Contingência

* Substituir tecnologia ou produto empregados no projeto de modo a garantir a continuidade dos trabalhos.

### 2.4 Volatilidade da equipe

A troca de membros da equipe ou a perda de profissionais importantes pode ocasionar atrasos nas iterações e consequentemente na entrega do produto final.

#### 2.4.1 Classificação ou Gravidade do Risco

**Alto impacto no projeto.**

#### 2.4.2 Indicadores

Falta de experiência na resolução de uma demanda pede por uma equipe altamente volátil para resolver, ou pesquisar sobre, a demanda exposta.

#### 2.4.3 Estratégia de Diminuição

Proporcionar que o grupo compartilhe informações sobre os trabalhos individuais desenvolvidos. Normatizar sobre boas práticas na documentação do projeto e do código gerado de modo a registrar comentários descritivos das funcionalidades codificadas.
Empreender treinamentos internos onde cada membro do grupo possa disseminar seus conhecimentos e experiências em suas competências.

#### 2.4.4 Plano de Contingência

* O gerente do projeto deve manter profissionais contatados com as mesmas competências da equipe para eventual substituição de algum elemento.

Lista de profissionais e suas competências necessárias ao projeto.

| Profissional | Competências |
| :---- | :--------- |
| André | OpenUP(aprendendo), MySQL, Python, Django, PHP, Web Design(HTML, CSS), JavaScript(aprendendo), React.js(aprendendo), Node.js(aprendendo) | 
| Vicente Limeira | OpenUP, PostgreSQL, Python, Django, UML, C# .NET for MVC |
| Ricardo Rafael | OpenUP(aprendendo), Java, MySQL, Python, Django, Web Design(HTML, CSS), JavaScript(aprendendo), React.js(aprendendo), Node.js(aprendendo) |