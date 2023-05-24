# TRABALHO DE PI:  Domos 
Trabalho desenvolvido durante a disciplina de Banco de Dados do Integrado

# Sumário

### 1. COMPONENTES<br>
Integrantes do grupo<br>
Camila Fraga Egydio: camilafragaegydio@gail.com <br>
Davi Nunes Ribeiro: davinunesribeiro@gmail.com<br>
Isabelly Balestrassi Nunes de Andrades: isabellyandrades.ifes@gmail.com <br>
Yasmin Santana Rodrigues: mamin8172@gmail.com <br>
...

### 2.MINIMUNDO<br>
Descrever o mini-mundo! (Não deve ser maior do que 30 linhas, se necessário resumir para justar)
Entrevista com o usuário e identificação dos requisitos.(quando for o caso de sistemas com cliente real)
Descrição textual das regras de negócio definidas como um subconjunto do mundo real cujos elementos são propriedades que desejamos incluir, processar, armazenar, gerenciar, atualizar, e que descrevem a proposta/solução a ser desenvolvida.
<br>

> O sistema proposto para a "Devcom Projetos conterá as informacões aqui detalhadas. Dos Projetos serão armazenados o número, nome e cidade. Dos Departamentos serão armazenados o número e nome. O cliente destacou que cada projeto pode ter vários departamentos auxiliando no seu desenvolvimento, e cada departamento pode estar envolvido em vários projetos. Os dados relativos aos empregados que serão armazenados são: rg, nome, cpf, salário, data inicial do salario e supervisor de cada empregado. É importante destacar que cada empregado pode ser supervisionado por outro empregado, e obrigatoriamente deve estar alocado a um único departamento, mas pode gerenciar vários departamentos ou não gerenciar nenhum. Um empregado também pode participar de vários projetos, caso seja necessário, mas não precisa obrigatoriamente estar alocado em algum projeto. Com relação aos dependentes serão armazenadas as informações de nome do dependente, data de nascimento, sexo e grau de parentesco. Cada empregado pode ter vários dependentes, mas um dependente esta associado apenas a um único empregado. Com relação ao histórico de salário devemos armazenar as informações de valor do salário, data de início do salário no período e data final do salário no período. É importante lembrar que cada funcionario pode ter diversos eventos de histórico de salário associados a ele visto que este dado pode ser alterado várias vezes..
 
 
### 3.PMC<br>
![image](https://github.com/projintegrador2023/template_projeto_integrador/assets/127967558/a2f1e82f-aa81-480b-83f9-1cd19aad4e0e)


#### 3.1. EAP - Estrutura Analítica do Projeto
![image](https://github.com/projintegrador2023/template_projeto_integrador/assets/127967558/2ee1a25d-8e9e-4df3-8acb-d137197c6165)  
![image](https://github.com/projintegrador2023/template_projeto_integrador/assets/127967558/d4905657-4df4-4760-8c28-855ef66b6305)
![image](https://github.com/projintegrador2023/template_projeto_integrador/assets/127967558/b6b416b2-e06e-404d-902f-398715228a17)
![image](https://github.com/projintegrador2023/template_projeto_integrador/assets/127967558/98dfccd2-90c6-475f-b54b-79037fa0bebd)
![image](https://github.com/projintegrador2023/template_projeto_integrador/assets/127967558/cbe79752-fc08-4875-a49b-ab96e3964465)


#### 3.2. Requisitos funcionais e não funcionais
**Requisitos funcionais**
![image](https://github.com/projintegrador2023/template_projeto_integrador/assets/127967558/ae985059-0a2e-4226-bcae-24d67c937f9e)
![image](https://github.com/projintegrador2023/template_projeto_integrador/assets/127967558/24ed9047-1aee-4fdc-b8ad-fbe7a1773f15)
**Requisitos não funcionais**
![image](https://github.com/projintegrador2023/template_projeto_integrador/assets/127967558/44700410-2a40-4e5d-bf85-772a2bf2ea06)


#### 3.3 Validação da Ideia.
**Formulário:** https://docs.google.com/forms/d/1UVo8cfiToc55kceu3vzgRaVAiUsT3d8eUm1UVY6vaIY/edit <br>
**Relatório:** https://www.canva.com/design/DAFjLUgTWOE/O7eW_Np8ccUgRKZSzz4PeQ/edit?analyticsCorrelationId=5fb6e34d-741c-49a8-8a73-0285c9f5ed47

### 4.Personas e Histórias de usuário<br>
![image](https://github.com/projintegrador2023/template_projeto_integrador/assets/127967558/737d11de-5d19-40c4-aa08-d2adae77fd93)
![image](https://github.com/projintegrador2023/template_projeto_integrador/assets/127967558/d5a92f93-a5f4-4ce6-b612-12b5e0890a52)
![image](https://github.com/projintegrador2023/template_projeto_integrador/assets/127967558/391b6894-2bd1-43ea-997d-1b03e8299667)
![image](https://github.com/projintegrador2023/template_projeto_integrador/assets/127967558/1478a877-7c05-4c70-91c3-8c04105ca16b)
![image](https://github.com/projintegrador2023/template_projeto_integrador/assets/127967558/c6e225d6-7536-44e5-b81a-624869c3f5a5)
<br>
![image](https://github.com/projintegrador2023/template_projeto_integrador/assets/127967558/3f2780df-f5a3-4a83-a033-d2f1646c70ef)
![image](https://github.com/projintegrador2023/template_projeto_integrador/assets/127967558/59a81090-775c-4a85-8356-cff40b6ab2b7)



### 5. PROTÓTIPOS DO SISTEMA<br>

#### 5.1 PROTÓTIPO DO SISTEMA MOBILE
https://quant-ux.com/#/apps/644920c703e7a20038a8b23b/design/s10484_99706.html

#### 5.2 PROTÓTIPO DO SISTEMA WEB
https://quant-ux.com/#/apps/6434194257bd5377df476056/design/s10000_67130.html

#### 5.3 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM OS SISTEMA WEB/MOBILE PROPOSTOS? 
> A Empresa DevCom precisa inicialmente dos seguintes relatórios:
* Relatório que informe quais são os gerentes de cada departamento incluindo as seguintes informações: número do departamento,  nome do departamento, e nome do gerente.
* Relatório de empregados por projeto incluindo as seguintes informações: número do projeto, nome do projeto, rg do empregado, nome do empregado e quantidade de horas de trabalho do empregado alocadas ao projeto.
* Relatório de empregados com dependentes incluindo as seguintes informações: rg do empregado, nome do empregado, nome do dependente, tipo de relação, data de nascimento do dependente e sexo do dependente.
* Relatório com a quantidade de empregados por cada departamento incluindo as seguintes informações: nome do departamento, supervisor e quantidade de empregados alocados no departamento.
* Relatório de supervisores e supervisionados incluindo as seguintes informações: nome do supervisor e nome do supervisionado.
 
 #### 6.MODELO CONCEITUAL<br>
    Em alteração
    
#### 7 Descrição dos dados 
    Em alteração

### 8	RASTREABILIDADE DOS ARTEFATOS<br>
        a) Historia de usuários vs protótipo (Histórias de Usuário e em qual tela do protótipo aquela HU está sendo realizada).
        b) Protótipo vs Modelo conceitual (Histórias de Usuário e em quais tabelas aquele dado está sendo registrado).
        (modelos devem obrigatoriamente estar em conformidade de rastreabilidade)

### 9	MODELO LÓGICO<br>
        Em alteração

### 10	MODELO FÍSICO<br>
        Em alteração
        
       
### 11	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
        Em alteração
        
#### 12 PRINCIPAIS CONSULTAS DO SISTEMA 
 Inserir as principais consultas (relativas aos 5 principais relatórios) definidas previamente no iten 3.1 deste template.
 <br>
  a) Você deve apresentar as consultas em formato SQL para cad um dos relatórios.
 <br>
  b) Além da consulta deve ser apresentada uma imagem com o resultado obtido para cada consulta.<br>

 ### 13 Gráficos, relatórios, integração com Linguagem de programação e outras solicitações.<br>
     OBS: Observe as instruções relacionadas a cada uma das atividades abaixo.<br>
 #### 13.1	Integração com Linguagem de programação; <br>
 #### 13.2	Desenvolvimento de gráficos/relatórios pertinentes, juntamente com demais <br>
 #### solicitações feitas pelo professor. <br>
 
 ### 14 Slides e Apresentação em vídeo. <br>
     OBS: Observe as instruções relacionadas a cada uma das atividades abaixo.<br>
 #### 14.1 Slides; <br>
 #### 14.2 Apresentação em vídeo <br>

    
##### About Formatting
    https://help.github.com/articles/about-writing-and-formatting-on-github/
    
##### Basic Formatting in Git
    
    https://help.github.com/articles/basic-writing-and-formatting-syntax/#referencing-issues-and-pull-requests
   
    
##### Working with advanced formatting
    https://help.github.com/articles/working-with-advanced-formatting/

#### Mastering Markdown
    https://guides.github.com/features/mastering-markdown/

### OBSERVAÇÕES IMPORTANTES

#### Todos os arquivos que fazem parte do projeto (Imagens, pdfs, arquivos fonte, etc..), devem estar presentes no GIT. Os arquivos do projeto vigente não devem ser armazenados em quaisquer outras plataformas.
1. Caso existam arquivos com conteúdos sigilosos, comunicar o professor que definirá em conjunto com o grupo a melhor forma de armazenamento do arquivo.

#### Todos os grupos deverão fazer Fork deste repositório e dar permissões administrativas ao usuário deste GIT, para acompanhamento do trabalho.

#### Os usuários criados no GIT devem possuir o nome de identificação do aluno (não serão aceitos nomes como Eu123, meuprojeto, pro456, etc). Em caso de dúvida comunicar o professor.


Link para BrModelo:<br>
http://sis4.com/brModelo/brModelo/download.html
<br>


Link para curso de GIT<br>
![https://www.youtube.com/curso_git](https://www.youtube.com/playlist?list=PLo7sFyCeiGUdIyEmHdfbuD2eR4XPDqnN2?raw=true "Title")
