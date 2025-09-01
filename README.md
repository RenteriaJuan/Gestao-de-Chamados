# INTERFIX 🤖
 
### Quem somos?
A InterFix é uma empresa dedicada a transformar o suporte técnico empresarial por meio do uso de inteligência artificial. Nosso objetivo é conectar soluções inteligentes com as necessidades de nossos clientes, oferecendo assistência eficiente, personalizada e em tempo real.

![InterFix](https://github.com/user-attachments/assets/8aa8a096-88fa-4be4-952c-946d63ceed66)

## Desafio <a id="desafio"></a> 🏅

O desafio consiste em criar uma aplicação web, desktop e mobile de suporte tecnico e gestão de chamados com integração de IA. O aplicativo possuira três níveis de acesso e deve ser capaz de analisar e atribuir a prioridade do chamado, também atribuirá o chamado ao técnico que tiver a carga horária mais baixa. Além da criação e gestão de chamadas, o sistema deverá gerar e gerenciar relatórios (com filtro de tempo), disponibilizando também uma função para gerenciar os níveis de acesso (função à qual somente o administrador poderá acessar).

## Solução 🏅
InterFix ST. Permitirá aos usuários criar ou gerenciar chamadas dependendo do seu nível de acesso, que é dividido em 3 (Administrador, Técnico e Funcionário). As chamadas têm níveis de prioridade que são distribuídos em Baixo, Médio, Alto e Crítico. Critérios como a prioridade das chamadas serão decididos pela IA durante a atribuição da prioridade, que depois perguntará ao usuário se concorda com o nível de prioridade da chamada. Uma vez que uma chamada é atribuída a um técnico e resolvida, o sistema criará um relatório que será guardado por 2 anos junto com a chamada.

# *Backlog do Produto* 📋

|*Quem?*        | *O que?*                                                              |*Para*                                                                                | *Prioridade* | *Status*      |
|---------------|-----------------------------------------------------------------------|--------------------------------------------------------------------------------------|--------------|---------------| 
|Funcionario    | Quero criar chamados de suporte com descrição e categoria detalhadas. | Relatar problemas técnicos de forma organizada.                                      |P1            |Em andamento ⏳|
|Funcionario    | Quero ver o status de meus chamados anteriores                        | Fazer um acompanhamento sem entrar em contato com a area de TI.                      |P2            |Em andamento ⏳|
|Sistema        | Como um sistema de IA, devo analisar a descrição do chamado.          | Atribuição de prioridade (baixa/média/alta) com base em palavras-chave históricas.   |P1            |Em andamento ⏳| 
|Sistema        | Como um sistema de IA, devo atribuir chamados ao técnico              | Que o técnico designado resolva o chamado.                                           |P1            |Em andamento ⏳| 
|Técnico        | Quero Exbir chamados atribuídos                                       | Saber quais chamados estão pendentes para serem resolvidos.                          |P1            |Em andamento ⏳|
|Técnico        | Quero gerenciar meus chamados asginados                               | Ser mais organizado em meu trabalho diário.                                          |P2            |Em andamento ⏳|
|Técnico        | Quero marcar meu chamado como resolvido                               | Saber quando o problema foi resolvido.                                               |P2            |Em andamento ⏳|
|Técnico        | Quero ver meus chamados já resolvidos                                 | ter um acompanhamento dos problemas resolvidos.                                      |P2            |Em andamento ⏳| 
|Administrador  | Desejo poder gerenciar os níveis de acesso                            | que os usuários possam ter sua função atribuída a eles.                              |P1            |Em andamento ⏳|
|Administrador  | Desejo poder gerenciar os chamados                                    | Conhecer quais problemas existem na empresa e que prioridade está sendo dada a eles. |P1            |Em andamento ⏳|

---

## DoR - Definition of Ready <a id="dor"></a> 🏃

* User Stories com **Critérios de Aceitação**
* Subtarefas divididas **a partir das US**
* Design no **Figma**
* Modelagem do **Banco de Dados**


## DoD - Definition of Done 🏆

* Manual da Aplicação



## Cronograma de Sprints <a id="sprint"></a> 📅

| Sprint          |    Período    | Documentação                            |
| --------------- | :-----------: | ----------------------------------------|
| 🔖 **SPRINT 1** | 18/08 - 25/08 | [Sprint1](https://github.com/RenteriaJuan/Gestao-de-Chamados/blob/main/Scrum/Relatorios%20Sprints/Sprint1.md) |
| 🔖 **SPRINT 2** |  - | |



## Tecnologias Utilizadas 💻

Categoría | Tecnologías
--------- | -------------
FrontEnd | HTML, CSS e Figma (Modelagem da interface) 
BackEnd |  C#
Base De Dados | BrModel e SQL Server (Windows Server)
IA | BlackBox AI
Metodología | Scrum + Git FLow 

## Integrantes 👥

Função       | Nome                | Github                                                       |
------------ | --------------------| -------------------------------------------------------------|
Project Owner| Christian Fernandes | [Acessar Github](https://github.com/ChristianFernandesLemos) |
Scrum Master | Juan Vargas         | [Acessar Github](https://github.com/RenteriaJuan)            |
Dev Team     | Théo Pinto          | [Acessar Github](https://github.com/Thorphinm)               |
Dev Team     | Ana Beatriz         | [Acessar Github](https://github.com/Anasouza2802)            |
Dev Team     |Gustavo Gramacho     | [Acessar Github](https://github.com/gramachoo)               |
Dev Team     | Lukas Keiji         | [Acessar Github](https://github.com/Lucaskeiji)              |
