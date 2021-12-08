# Metodologia

A metodologia pormenoriza as ferramentas aplicadas pelo grupo na organização e na distribuição da implantação das tarefas do projeto, assim como nas plataformas e artefatos utilizados para a manutenção e conservação dos códigos.


## Relação de Ambiente de Trabalho

Os artefatos do projeto são acompanhados e evoluídos com a ajuda de diferentes plataformas, cada qual com sua função específica, e a relação dos ambientes com suas respectivas finalidades é apresentada no quadro abaixo.

Quadro 7 - Ambientes de Trabalho
| AMBIENTE | PLATAFORMA | LINK DE ACESSO |
|----------|------------|----------------|
| Repositório de Código Fonte | GitHub | https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2021-2-e1-proj-web-t7-ads_2021_02_e1_grupo_05_audicao_amiga |
| Documentos do Projeto | Google Drive | https://drive.google.com/drive/folders/1nC1o-M0hkkj3bCmoYNUu5mf4AagLoLDZ?usp=sharing |
| Projeto de Interface e  Wireframes | Adobe XD | https://xd.adobe.com/view/e7aaa406-952d-4a56-a7d1-b5021fa0c83c-b2f9/?fullscreen |
| Gerenciamento do Projeto | Trello | https://trello.com/b/h196UeQh |

Fonte: Elaborado pelos autores


## Gestão de Código Fonte

De acordo com Vietro (2015), é importante observar o uso de técnicas e metodologias para o desenvolvimento de sistemas, buscando melhorar as práticas atuais. Diante disso torna-se essencial o gerenciamento do software, e isso envolve administrar as várias etapas do processo, como, por exemplo: requisitos do sistema, arquitetura do software, padrões de codificação, gerência de configuração, deploy, entre outros. 

Pensando nesse contexto, o grupo optou por utilizar um processo fundamentado no GitFlow para a gestão do código fonte do software que será desenvolvido. 

O GitFlow é um framework criado em 2010 e considerado um ótimo modelo de branching, além de ser usado para trabalhar em conjunto com o sistema de controle de versão Git (VIETRO, 2015). Assim sendo, as manutenções do código serão efetuadas definindo-se os papéis de cada branch em separado, como eles devem interagir entre si, e com a identificação de Branch Master, Branch Develop, Feature Branch, Release Branch, Maintenance Branch (Hotfix).

Figura 1 - GitFlow WorkFlow<br>
Modelo de Fluxo de Controle do Código FOnte no Repositório Git<br>
![image](https://user-images.githubusercontent.com/89549220/144713574-e45c7e18-de74-4055-9d0f-da8e1ef7c2e8.png)<br>
Fonte: Vietro (2015)

Esse modelo de workflow utiliza dois branches principais para guardar o histórico do projeto, ao invés de trabalhar com apenas um Branch Master. O Branch Master guarda o histórico oficial das entregas, já o Branch Develop serve como integração entre todos os branches de funcionalidades (Feature Branches). Cada funcionalidade deve ter seu próprio branch, e ele deve ser criado a partir do Branch Develop. Quando uma funcionalidade for concluída, ela é mesclada (merged) novamente com o seu branch pai. Quando o Branch Develop estiver com funcionalidades suficientes para uma entrega, criaremos um branch de entrega (Release Branch). Com isso, damos início ao próximo ciclo de entrega, ou seja, nenhuma nova funcionalidade pode ser incluída a partir desse momento. Quando estivermos prontos para realizar a entrega, o Release Branch é mesclada com os branches Master e Develop. O Maintenance Branches (Hotfix) são usados para corrigir rapidamente algum problema em produção. Este é o único branch que deve ser criado a partir do Master. Assim que a correção for finalizada, o branch é fechado e mesclado com o Master e Develop, mantendo assim as linhas completamente atualizadas (VIETRO, 2015).


## Gerenciamento de Projeto

O grupo decidiu por utilizar a metodologia Ágil, sendo escolhido o Scrum como base para definição do processo de desenvolvimento do projeto.

Sua organização está apresentada conforme abaixo:

* __Scrum Master__
- Carlos Eduardo Amorim Silva

* __Product Owner__
- Fabiana Bicalho Palhano Rocha Cossenzo

* __Equipe de Desenvolvimento__
- Arthur Alves Rocha de Souza
- Bruna Ester Rolim Rocha
- Carlos Eduardo Amorim Silva
- Fabiana Bicalho Palhano Rocha Cossenzo
- Sabrina Gonçalves de Andrade

* __Equipe de Design__
- Arthur Alves Rocha de Souza
- Bruna Ester Rolim Rocha
- Carlos Eduardo Amorim Silva
- Fabiana Bicalho Palhano Rocha Cossenzo
- Sabrina Gonçalves de Andrade

Na organização e na distribuição das tarefas do projeto, o grupo utiliza o aplicativo de gerenciamento de projetos denominado Trello, onde o mesmo está estruturado com as seguintes listas: 

* __Recursos__: lista com todas as tarefas que são recorrentes, com o objetivo de agilizar a criação de novos cartões, bastando movê-lo para o local necessário.
* __Backlog__: local onde é adicionado as tarefas a serem trabalhadas pela equipe, assim como as tarefas que forem identificadas no andamento do projeto. 
* __To Do__: representa o Sprint Backlog atual que está sendo trabalhado.
* __Doing__: tarefas que foram iniciadas são adicionadas nessa lista.
* __Test (CQ - Checagem de Qualidade)__: lista das tarefas que foram concluídas. Nesse estágio cabe-se ainda uma revisão para verificar a qualidade.
* __Done__: nesta lista são adicionadas as tarefas que passaram pela Checagem de Qualidade e estão prontas para serem enviadas e/ou entregues.
* __Locked__: lista onde será relacionado e especificado o que está impedindo a conclusão da tarefa, juntamente com um comentário sobre o que está travando a tarefa.

O quadro gerenciado pelo grupo no aplicativo Trello está disponível através da URL especificada no Quadro 7 e é apresentado, em seu estado atual, congênere figura abaixo. A caracterização da estrutura montada se fundamentou no artigo escrito por Littlefield (2016), assim como nos conceitos de Scrum de Schwaber e Sutherland (2020).

Figura 2 - Tela do Trello para Gerenciamento do Projeto <br>
![image](https://user-images.githubusercontent.com/89549220/144713882-1df53bdb-4ebf-4313-8f4d-507fe8fe9224.png) <br>
![image](https://user-images.githubusercontent.com/89549220/144713627-0738f683-c65e-4a3e-bcb5-cdfeff3fa957.png) <br>
Fonte: Trello - Elaborado pelos autores


A tarefas estão etiquetadas em função da natureza da atividade e seguem o esquema de cores/categorias conforme abaixo:

* Documentação
* Desenvolvimento 
* Infraestrutura
* Testes
* Gerência de Projetos
* Revisão de Código

Figura 3 - Natureza das Atividades <br>
![image](https://user-images.githubusercontent.com/89549220/144713821-e990cdfc-77be-4e80-9181-34a15e8abb6f.png)<br>
Fonte - Elaborado pelos autores

