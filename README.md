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
    B) As principais entidades desse sistema em desenvolvimento são USUÁRIO, CONDOMÍNIO e POSTAGEM
    C) Os principais fluxos de informação desse sistema são USUÁRIO, POSTAGEM e CONDOMÍNIO

#### 7 Descrição dos dados 
    NIVEL_PERMISSAO: tabela que armazena as informações do nível de permissão (síndico, morador e administrador) 
    - código_nivel_permissao: Chave primária que identifica o nível de permissão.
    - tipo: Uma string de até 15 caracteres que descreve o tipo de permissão.

    TIPO_LOGRADOURO: tabela que armazena as informações do tipo de logradouro
    - codigo_tipo_logradouro: Chave primária que identifica o tipo de logradouro.
    - nome: Uma string de até 60 caracteres que representa o nome do tipo de logradouro.

    PAIS: tabela que armazena as informações do país
    - codigo_pais: Chave primária que identifica o país.
    - nome: Uma string de até 41 caracteres que representa o nome do país.

    ESTADO:  tabela que armazena as informações do estado
    - codigo_estado: Chave primária que identifica o estado.
    - FK_PAIS_codigo_pais: Chave estrangeira que faz referência ao código do país ao qual o estado pertence.
    - uf: Uma string de até 2 caracteres que representa a sigla do estado.

    CIDADE:  tabela que armazena as informações da cidade 
    - codigo_cidade: Chave primária que identifica a cidade.
    - FK_ESTADO_codigo_estado: Chave estrangeira que faz referência ao código do estado ao qual a cidade pertence.
    - nome: Uma string de até 58 caracteres que representa o nome da cidade.

    BAIRRO:  tabela que armazena as informações do bairro
    - codigo_bairro: Chave primária que identifica o bairro.
    - FK_CIDADE_codigo_cidade: Chave estrangeira que faz referência ao código da cidade à qual o bairro pertence.
    - nome: Uma string de até 60 caracteres que representa o nome do bairro.

    ENDERECO:  tabela que armazena as informações do país
    - codigo_endereco: Chave primária que identifica o endereço.
    - numero: Um número inteiro que representa o número do endereço.
    - FK_TIPO_LOGRADOURO_codigo_tipo_logradouro: Chave estrangeira que faz referência ao código do tipo de logradouro do endereço.
    - desc_logradouro: Uma string de até 200 caracteres que descreve o logradouro do endereço.
    - FK_BAIRRO_codigo_bairro: Chave estrangeira que faz referência ao código do bairro do endereço.
    - cep: Uma string de até 9 caracteres que representa o CEP do endereço.

    TIPO_MORADIA:  tabela que armazena as informações do tipo de moradia (casa, ap etc)
    - codigo_tipo_moradia: Chave primária que identifica o tipo de moradia.
    - nome: Uma string de até 24 caracteres que representa o nome do tipo de moradia.

    FAIXA_QTD_MORADORES:  tabela que armazena as informações do faixa de quantidade de moradores (50-100, 100-500 etc)
    - codigo_faixa: Chave primária que identifica a faixa de quantidade de moradores.
    - faixa_qtd: Uma string de até 10 caracteres que descreve a faixa de quantidade de moradores.

    TIPO_DIVISAO:  tabela que armazena as informações do tipo de divisão (bloco, setor etc)
    - codigo_tipo_divisao: Chave primária que identifica o tipo de divisão.
    - nome: Uma string de até 80 caracteres que representa o nome do tipo de divisão.

    DIVISAO:  tabela que armazena as informações da divisão (A B C, rosa girassol etc)
    - codigo_divisao: Chave primária que identifica a divisão.
    - FK_TIPO_DIVISAO_codigo_tipo_divisao: Chave estrangeira que faz referência ao código do tipo de divisão da divisão.
    - desc_divisao: Uma string de até 100 caracteres que descreve a divisão.

    NUM_MORADIA:  tabela que armazena as informações do número da moradia (101, 25 etc)
    - codigo: Chave primária que identifica o número de moradia.
    - numero_moradia: Uma string de até 4 caracteres que representa o número de moradia.

    MORADIA:  tabela que armazena as informações da moradia
    - codigo: Chave primária que identifica a moradia.
    - fk_DIVISAO_codigo_divisao: Chave estrangeira que faz referência ao código da divisão da moradia.
    - fk_NUM_MORADIA_codigo: Chave estrangeira que faz referência ao código do número de moradia da moradia.

    CONDOMINIO:  tabela que armazena as informações do condomínio 
    - cnpj: Uma string de até 14 caracteres que representa o CNPJ do condomínio.
    - nome: Uma string de até 100 caracteres que representa o nome do condomínio.
    - qtd_divisoes: Um número inteiro que representa a quantidade de divisões no condomínio.
    - codigo_condominio: Chave primária que identifica o condomínio.
    - regimento: Uma string de até 4000 caracteres que representa o regimento do condomínio.
    - FK_TIPO_MORADIA_codigo_tipo_moradia: Chave estrangeira que faz referência ao código do tipo de moradia do condomínio.
    - FK_ENDERECO_codigo_endereco: Chave estrangeira que faz referência ao código do endereço do condomínio.
    - FK_FAIXA_QTD_MORADORES_codigo_faixa: Chave estrangeira que faz referência ao código da faixa de quantidade de moradores do condomínio.

    USUARIO:  tabela que armazena as informações do usuário
    - cpf: Chave primária que identifica o usuário.
    - nome: Uma string de até 100 caracteres que representa o nome do usuário.
    - email: Uma string de até 256 caracteres que representa o e-mail do usuário.
    - senha: Uma string de até 80 caracteres que representa a senha do usuário.
    - imagem: Uma string de até 500 caracteres que representa a imagem do usuário.
    - FK_CONDOMINIO_codigo_condominio: Chave estrangeira que faz referência ao código do condomínio ao qual o usuário pertence.
    - FK_NIVEL_PERMISSAO_codigo_nivel_permissao: Chave estrangeira que faz referência ao código do nível de permissão do usuário.
    - FK_MORADIA_codigo: Chave estrangeira que faz referência ao código da moradia do usuário.

    TIPOS_ESPACOS_PUBLICOS:  tabela que armazena as informações dos tipos de espaço público
    - codigo_tipos_espacos_publicos: Chave primária que identifica o tipo de espaço público.
    - nome: Uma string de até 50 caracteres que representa o nome do tipo de espaço público.

    ESPACOS_PUBLICOS:  tabela que armazena as informações dos espaços publicos
    - codigo_espacos_publicos: Chave primária que identifica o espaço público.
    - nome: Uma string de até 100 caracteres que representa o nome do espaço público.
    - FK_TIPOS_ESPACOS_PUBLICOS_codigo_tipos_espacos_publicos: Chave estrangeira que faz referência ao código do tipo de espaço público.

    RESERVA:  tabela que armazena as informações da reserva
    - fk_USUARIO_cpf: Chave estrangeira que faz referência ao CPF do usuário que fez a reserva.
    - fk_ESPACOS_PUBLICOS_codigo_espacos_publicos: Chave estrangeira que faz referência ao código do espaço público reservado.
    - data: Uma data que representa a data da reserva.
    - hora_entrada: Uma hora que representa a hora de entrada da reserva.
    - hora_saida: Uma hora que representa a hora de saída da reserva.
    - codigo_reserva: Chave primária que identifica a reserva.

    DIVISAO_CONDOMINIO:  tabela de relaçao que armazena as informações da divisão com o condomínio
    - fk_DIVISAO_codigo_divisao: Chave estrangeira que faz referência ao código da divisão relacionada ao condomínio.
    - fk_CONDOMINIO_codigo_condominio: Chave estrangeira que faz referência ao código do condomínio relacionado à divisão.

    CONDOMINIO_ESPACOS_PUBLICOS: tabela de relaçao que armazena as informações dos espaços públicos com o condomínio

    - fk_CONDOMINIO_codigo_condominio: Chave estrangeira que faz referência ao código do condomínio relacionado ao espaço público.
    - fk_ESPACOS_PUBLICOS_codigo_espacos_publicos: Chave estrangeira que faz referência ao código do espaço público relacionado ao condomínio.

    TAG:  tabela que armazena as informações das tags do anúncio (alimentação, serviços etc)
    - codigo: Chave primária que identifica a tag.
    - tag: Uma string de até 80 caracteres que representa a tag.

    IMPORTANCIA:  tabela que armazena as informações da importância de cada aviso (importante, urgente e crítico)
    - codigo: Chave primária que identifica a importância.
    - importancia: Uma string de até 80 caracteres que representa a importância.

    POSTAGEM:  tabela que armazena as informações da postagem
    - codigo_postagem: Chave primária que identifica a postagem.
    - data_hora_postagem: Uma data e hora que representa a data e hora de postagem.
    - descricao: Uma string de até 4000 caracteres que representa a descrição da postagem.
    - titulo: Uma string de até 100 caracteres que representa o título da postagem.
    - FK_USUARIO_cpf: Chave estrangeira que faz referência ao CPF do usuário que fez a postagem.

    ANUNCIO:  tabela que armazena as informações do anúncio
    - FK_POSTAGEM_codigo_postagem: Chave estrangeira que faz referência ao código da postagem relacionada ao anúncio.
    - FK_TAG_codigo: Chave estrangeira que faz referência ao código da tag relacionada ao anúncio.

    AVISO:  tabela que armazena as informações do aviso
    - FK_POSTAGEM_codigo_postagem: Chave estrangeira que faz referência ao código da postagem relacionada ao aviso.
    - FK_IMPORTANCIA_codigo: Chave estrangeira que faz referência ao código da importância relacionada ao aviso.

    IMAGEM:  tabela que armazena as informações da imagem
    - imagem_PK: Chave primária que identifica a imagem.
    - imagem: Uma string de até 500 caracteres que representa a imagem.
    - FK_POSTAGEM_codigo_postagem: Chave estrangeira que faz referência ao código da postagem relacionada à imagem.

    FAVORITA:  tabela de relaçao que armazena as informações das postagens favoritas
    - fk_USUARIO_cpf: Chave estrangeira que faz referência ao CPF do usuário que favoritou a postagem.
    - fk_POSTAGEM_codigo_postagem: Chave estrangeira que faz referência ao código da postagem favoritada pelo usuário.


### 8	RASTREABILIDADE DOS ARTEFATOS<br>
        a) Historia de usuários vs protótipo (Histórias de Usuário e em qual tela do protótipo aquela HU está sendo realizada).
        b) Protótipo vs Modelo conceitual (Histórias de Usuário e em quais tabelas aquele dado está sendo registrado).
        (modelos devem obrigatoriamente estar em conformidade de rastreabilidade)

### 9	MODELO LÓGICO<br>
        Em alteração

### 10	MODELO FÍSICO<br>
        CREATE TABLE NIVEL_PERMISSAO (
        codigo_nivel_permissao SERIAL PRIMARY KEY,
        tipo VARCHAR(15)
    );

    CREATE TABLE TIPO_LOGRADOURO (
        codigo_tipo_logradouro SERIAL PRIMARY KEY,
        nome VARCHAR(60)
    );

    CREATE TABLE PAIS (
        codigo_pais SERIAL PRIMARY KEY,
        nome VARCHAR(41)
    );

    CREATE TABLE ESTADO (
        codigo_estado SERIAL PRIMARY KEY,
        FK_PAIS_codigo_pais integer,
        uf VARCHAR(2),
        FOREIGN KEY (FK_PAIS_codigo_pais) REFERENCES PAIS (codigo_pais)
    );

    CREATE TABLE CIDADE (
        codigo_cidade SERIAL PRIMARY KEY,
    FK_ESTADO_codigo_estado integer,
        nome VARCHAR(58),
        FOREIGN KEY (FK_ESTADO_codigo_estado) REFERENCES ESTADO (codigo_estado)
    );

    CREATE TABLE BAIRRO (
        codigo_bairro SERIAL PRIMARY KEY,
    FK_CIDADE_codigo_cidade integer,
        nome VARCHAR(60),
        FOREIGN KEY (FK_CIDADE_codigo_cidade) REFERENCES CIDADE (codigo_cidade)
    );

    CREATE TABLE ENDERECO (
        codigo_endereco SERIAL PRIMARY KEY,
        numero integer,
    FK_TIPO_LOGRADOURO_codigo_tipo_logradouro integer,
        desc_logradouro VARCHAR(200),
    FK_BAIRRO_codigo_bairro integer,
        cep VARCHAR(9),
        FOREIGN KEY (FK_TIPO_LOGRADOURO_codigo_tipo_logradouro) REFERENCES TIPO_LOGRADOURO (codigo_tipo_logradouro),
        FOREIGN KEY (FK_BAIRRO_codigo_bairro) REFERENCES BAIRRO (codigo_bairro)
    );

    CREATE TABLE TIPO_MORADIA (
        codigo_tipo_moradia SERIAL PRIMARY KEY,
        nome VARCHAR(24)
    );

    CREATE TABLE FAIXA_QTD_MORADORES (
        codigo_faixa SERIAL PRIMARY KEY,
        faixa_qtd VARCHAR(10)
    );

    CREATE TABLE TIPO_DIVISAO (
        codigo_tipo_divisao SERIAL PRIMARY KEY,
        nome VARCHAR(80)
    );

    CREATE TABLE DIVISAO (
        codigo_divisao SERIAL PRIMARY KEY,
    FK_TIPO_DIVISAO_codigo_tipo_divisao integer,
        desc_divisao VARCHAR(100),
        FOREIGN KEY (FK_TIPO_DIVISAO_codigo_tipo_divisao) REFERENCES TIPO_DIVISAO (codigo_tipo_divisao) 
    );


    CREATE TABLE NUM_MORADIA (
        codigo SERIAL PRIMARY KEY,
        numero_moradia VARCHAR(4)
    );


    CREATE TABLE MORADIA (
        codigo SERIAL PRIMARY KEY,
    fk_DIVISAO_codigo_divisao integer,
    fk_NUM_MORADIA_codigo integer,
        FOREIGN KEY (fk_DIVISAO_codigo_divisao) REFERENCES DIVISAO (codigo_divisao),
        FOREIGN KEY (fk_NUM_MORADIA_codigo) REFERENCES NUM_MORADIA (codigo)
    );


    CREATE TABLE CONDOMINIO (
        cnpj VARCHAR(14),
        nome VARCHAR(100),
        qtd_divisoes INT,
        codigo_condominio VARCHAR(9) PRIMARY KEY,
        regimento VARCHAR(4000),
    FK_TIPO_MORADIA_codigo_tipo_moradia integer,
    FK_ENDERECO_codigo_endereco integer,
    FK_FAIXA_QTD_MORADORES_codigo_faixa integer,
        FOREIGN KEY (FK_TIPO_MORADIA_codigo_tipo_moradia) REFERENCES TIPO_MORADIA (codigo_tipo_moradia),
        FOREIGN KEY (FK_ENDERECO_codigo_endereco) REFERENCES ENDERECO (codigo_endereco),
        FOREIGN KEY (FK_FAIXA_QTD_MORADORES_codigo_faixa) REFERENCES FAIXA_QTD_MORADORES (codigo_faixa)
    );

    CREATE TABLE USUARIO (
        cpf VARCHAR(14) PRIMARY KEY,
        nome VARCHAR(100),
        email VARCHAR(256),
        senha VARCHAR(80),
        imagem VARCHAR(500),
    FK_CONDOMINIO_codigo_condominio VARCHAR(9),
    FK_NIVEL_PERMISSAO_codigo_nivel_permissao integer,
    FK_MORADIA_codigo integer,
        FOREIGN KEY (FK_CONDOMINIO_codigo_condominio) REFERENCES CONDOMINIO (codigo_condominio),
        FOREIGN KEY (FK_NIVEL_PERMISSAO_codigo_nivel_permissao) REFERENCES NIVEL_PERMISSAO (codigo_nivel_permissao),
        FOREIGN KEY (FK_MORADIA_codigo) REFERENCES MORADIA (codigo)
    );

    CREATE TABLE TIPOS_ESPACOS_PUBLICOS (
        codigo_tipos_espacos_publicos SERIAL PRIMARY KEY,
        nome VARCHAR(50)
    );

    CREATE TABLE ESPACOS_PUBLICOS (
        codigo_espacos_publicos SERIAL PRIMARY KEY,
        nome VARCHAR(100),
    FK_TIPOS_ESPACOS_PUBLICOS_codigo_tipos_espacos_publicos integer,
        FOREIGN KEY (FK_TIPOS_ESPACOS_PUBLICOS_codigo_tipos_espacos_publicos) REFERENCES TIPOS_ESPACOS_PUBLICOS (codigo_tipos_espacos_publicos)
    );


    CREATE TABLE RESERVA (
    fk_USUARIO_cpf VARCHAR(14),
    fk_ESPACOS_PUBLICOS_codigo_espacos_publicos integer,
        data DATE,
        hora_entrada TIME,
        hora_saida TIME,
        codigo_reserva SERIAL PRIMARY KEY,
    FOREIGN KEY (fk_USUARIO_cpf) REFERENCES USUARIO(cpf),
        FOREIGN KEY (fk_ESPACOS_PUBLICOS_codigo_espacos_publicos) REFERENCES ESPACOS_PUBLICOS(codigo_espacos_publicos)
    );


    CREATE TABLE DIVISAO_CONDOMINIO (
    fk_DIVISAO_codigo_divisao integer,
    fk_CONDOMINIO_codigo_condominio VARCHAR(9),
        FOREIGN KEY(fk_DIVISAO_codigo_divisao) REFERENCES DIVISAO(codigo_divisao),
        FOREIGN KEY (fk_CONDOMINIO_codigo_condominio) REFERENCES CONDOMINIO(codigo_condominio)
    );

    CREATE TABLE CONDOMINIO_ESPACOS_PUBLICOS (
    fk_CONDOMINIO_codigo_condominio VARCHAR(9),
    fk_ESPACOS_PUBLICOS_codigo_espacos_publicos integer,
        FOREIGN KEY (fk_CONDOMINIO_codigo_condominio) REFERENCES CONDOMINIO(codigo_condominio),
        FOREIGN KEY (fk_ESPACOS_PUBLICOS_codigo_espacos_publicos) REFERENCES ESPACOS_PUBLICOS(codigo_espacos_publicos)
    );

    CREATE TABLE TAG (
        codigo SERIAL PRIMARY KEY,
        tag VARCHAR(80)
    );

    CREATE TABLE IMPORTANCIA (
        codigo SERIAL PRIMARY KEY,
        importancia VARCHAR(80)
    );


    CREATE TABLE POSTAGEM (
        codigo_postagem SERIAL PRIMARY KEY,
        data_hora_postagem TIMESTAMP,
        descricao VARCHAR(4000),
        titulo VARCHAR(100),
    FK_USUARIO_cpf VARCHAR(14),
        FOREIGN KEY (FK_USUARIO_cpf) REFERENCES USUARIO(cpf)
    );

    CREATE TABLE ANUNCIO (
    FK_POSTAGEM_codigo_postagem integer,
    FK_TAG_codigo integer,
        FOREIGN KEY (FK_POSTAGEM_codigo_postagem) REFERENCES POSTAGEM(codigo_postagem),
        FOREIGN KEY (FK_TAG_codigo) REFERENCES TAG(codigo)
    );


    CREATE TABLE AVISO (
    FK_POSTAGEM_codigo_postagem integer,
    FK_IMPORTANCIA_codigo integer,
        FOREIGN KEY (FK_POSTAGEM_codigo_postagem) REFERENCES POSTAGEM(codigo_postagem),
        FOREIGN KEY (FK_IMPORTANCIA_codigo) REFERENCES IMPORTANCIA(codigo)
    );

    CREATE TABLE IMAGEM (
        imagem_PK SERIAL NOT NULL PRIMARY KEY,
        imagem VARCHAR(500),
    FK_POSTAGEM_codigo_postagem integer,
        FOREIGN KEY (FK_POSTAGEM_codigo_postagem) REFERENCES POSTAGEM(codigo_postagem)
    );


    CREATE TABLE FAVORITA (
    fk_USUARIO_cpf VARCHAR(14),
    fk_POSTAGEM_codigo_postagem integer,
        FOREIGN KEY (fk_USUARIO_cpf) REFERENCES USUARIO(cpf),
        FOREIGN KEY (fk_POSTAGEM_codigo_postagem) REFERENCES POSTAGEM(codigo_postagem)
    );
       
### 11	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
    -- Insert data into the NIVEL_PERMISSAO table
    INSERT INTO NIVEL_PERMISSAO (codigo_nivel_permissao, tipo)
    VALUES (1, 'Síndico'),
    (2, 'Administrador'),
    (3, 'Morador');

    -- Insert data into the TIPO_LOGRADOURO table
    INSERT INTO TIPO_LOGRADOURO (codigo_tipo_logradouro, nome)
    VALUES (1, 'Rua'),
    (2, 'Avenida'),
    (3, 'Travessa'),
    (4, 'Praça'),
    (5, 'Alameda');

    -- Insert data into the PAIS table
    INSERT INTO PAIS (codigo_pais, nome)
    VALUES (1, 'Brasil');

    -- Insert data into the ESTADO table
    INSERT INTO ESTADO (codigo_estado, uf, FK_PAIS_codigo_pais)
    VALUES (1, 'SP', 1),
           (2, 'PB', 1),
           (3, 'RJ', 1);

    -- Insert data into the CIDADE table
    INSERT INTO CIDADE (codigo_cidade, nome, FK_ESTADO_codigo_estado)
    VALUES (1, 'São Paulo', 1),
           (2, 'São Bernardo do Campo', 1),
           (3, 'João Pessoa', 2),
           (4, 'Rio de Janeiro', 3),
           (5, 'Campinas', 1);

    -- Insert data into the BAIRRO table
    INSERT INTO BAIRRO (codigo_bairro, nome, FK_CIDADE_codigo_cidade)
    VALUES (1, 'Centro', 1),
           (2, 'Jardim Vista', 2),
           (3, 'Manaíra', 3),
           (4, 'Centro', 4),
           (5, 'Parque das Flores', 5);

    -- Insert data into the ENDERECO table
    INSERT INTO ENDERECO (codigo_endereco, numero, desc_logradouro, cep, FK_TIPO_LOGRADOURO_codigo_tipo_logradouro, FK_BAIRRO_codigo_bairro)
    VALUES (1, 125, 'Rua das Flores', '12020010', 1, 1),
    (2, 2034, 'Avenida do Sol', '08090520', 2, 2),
    (3, 456, 'Travessa das Palmeiras', '58045110', 3, 3),
    (4, 987, 'Praça do Sol', '01010001', 4, 4),
    (5, 360, 'Alameda das Margaridas', '13083200', 5, 5);
    INSERT INTO TIPO_MORADIA (codigo_tipo_moradia, nome) VALUES
    (1, 'Casa'),
    (2, 'Apartamento'),
    (3, 'Casa e Apartamento');

    -- Insert data into the FAIXA_QTD_MORADORES table
    INSERT INTO FAIXA_QTD_MORADORES (codigo_faixa, faixa_qtd)
    VALUES
        (1, '1-100'),
        (2, '100-500'),
        (3, '500-1000'),
        (4, '1000+');

    -- Insert data into the TIPO_DIVISAO table
    INSERT INTO TIPO_DIVISAO (codigo_tipo_divisao, nome)
    VALUES
        (1, 'Letras'),
        (2, 'Números'),
        (3, 'Cores');

    INSERT INTO DIVISAO (desc_divisao, FK_TIPO_DIVISAO_codigo_tipo_divisao)
    VALUES
        ('A', 1),
        ('B', 1),
        ('C', 1),
        ('D', 1),
        ('E', 1),
        ('F', 1),
        ('G', 1),
        ('H', 1),
        ('I', 1),
        ('J', 1),
        ('1', 2),
        ('2', 2),
        ('3', 2),
        ('4', 2),
        ('5', 2),
        ('6', 2),
        ('7', 2),
        ('8', 2),
        ('9', 2),
        ('10', 2),
        ('Azul', 3),
        ('Vermelho', 3),
        ('Roxo', 3);

    -- Inserting data into NUM_MORADIA table
    INSERT INTO NUM_MORADIA (numero_moradia)
    VALUES
        ('101'),
        ('202'),
        ('303'),
        ('404'),
        ('505');

    -- Inserting data into MORADIA table
    INSERT INTO MORADIA (fk_DIVISAO_codigo_divisao, fk_NUM_MORADIA_codigo)
    VALUES
        (1, 1),
        (1, 5),
        (2, 1),
        (3, 1),
        (5, 3);

    INSERT INTO CONDOMINIO (cnpj, nome, qtd_divisoes, codigo_condominio, regimento, FK_TIPO_MORADIA_codigo_tipo_moradia, FK_ENDERECO_codigo_endereco, FK_FAIXA_QTD_MORADORES_codigo_faixa) VALUES
    ('97850315790467', 'Residencial das Flores', 5, '532097', 'https://exemplo.com/regimento_interno_residencial_das_flores.pdf', 1, 1, 2),
    ('67128439571218', 'Villaggio di Napoli', 10, '892356', 'https://exemplo.com/regimento_interno_villagio_di_napoli.pdf', 3, 2, 4),
    ('81029468093542', 'Condomínio dos Girassóis', 3, '415869', 'https://exemplo.com/regimento_interno_condominio_dos_girassois.pdf', 2, 3, 2),
    ('23687451230759', 'Jardim dos Lírios', 6, '724138', 'https://exemplo.com/regimento_interno_jardim_dos_lirios.pdf', 1, 4, 3),
    ('76412903576492', 'Condomínio das Acácias', 7, '301572', 'https://exemplo.com/regimento_interno_condominio_das_acacias.pdf', 3, 5, 3);

    -- Insert data into the USUARIO table
    INSERT INTO USUARIO (cpf, nome, email, senha, imagem, FK_NIVEL_PERMISSAO_codigo_nivel_permissao, FK_CONDOMINIO_codigo_condominio, FK_MORADIA_codigo)
    VALUES ('49628092010', 'Pedro Henrique da Silva', 'pedro.silva90@gmail.com', 'J#mD8n@KsT', null, 3, '532097', 1),
    ('31589904263', 'Ana Carolina Oliveira Santos', 'anacarolsantos_25@hotmail.com', '7cH$zN9mRf', null, 3, '532097', 2),
     ('72815390627', 'Gustavo Pereira Souza', 'gustavosouza@gmail.com', 'qP5^gB@2hE', null, 3, '532097', 3),
    ('42155708213', 'Fernanda Almeida Lima', 'fernandaalmeida.lima@yahoo.com', 'fY3!kT#6sL', null, 1, '532097', 4),
    ('86361974530', 'Guilherme Ferreira Costa', 'guilhermecosta87@outlook.com', '9vM@pG6rXy', null, 2, '532097', 5);

    -- Inserting data into TIPOS_ESPACOS_PUBLICOS table
    INSERT INTO TIPOS_ESPACOS_PUBLICOS (nome)
    VALUES
        ('Salão de Festas'),
        ('Churrasqueira'),
        ('Quadra'),
        ('Sauna'),
        ('Sala de Jogos'),
        ('Espaço Gourmet'),
        ('Espaço Kids');

    -- Insert data into the ESPACOS_PUBLICOS table
    INSERT INTO ESPACOS_PUBLICOS (codigo_espacos_publicos, nome, FK_TIPOS_ESPACOS_PUBLICOS_codigo_tipos_espacos_publicos)
    VALUES (1, 'A', 1),
    (2, 'B', 1),
    (3, 'C', 1),
    (4, 'A', 2),
    (5, 'B', 2),
    (6, 'C', 2),
    (7, 'D', 2),
    (8, 'E', 2),
    (9, 'F', 2),
    (10, 'futebol', 3),
    (11, 'volei', 3),
    (12, 'tenis', 3),
    (13, '1', 4),
    (14, '1', 5),
    (15, '2', 5),
    (16, '1', 6),
    (17, '1', 7);

    -- Inserting data into RESERVA table
    INSERT INTO RESERVA (fk_USUARIO_cpf, fk_ESPACOS_PUBLICOS_codigo_espacos_publicos, data, hora_entrada, hora_saida)
    VALUES
        ('72815390627', 4, '2023-07-24', '14:30', '16:00'),
        ('42155708213', 10, '2023-10-06', '14:00', '20:00'),
        ('31589904263', 1, '2023-11-14', '12:00', '18:00'),
        ('49628092010', 2, '2023-12-03', '15:00', '22:00'),
        ('42155708213', 1, '2024-01-01', '00:00', '02:00'),
        ('42155708213', 1, '2023-12-31', '22:00', '23:59');

    -- Inserting data into DIVISAO_CONDOMINIO table
    INSERT INTO DIVISAO_CONDOMINIO (fk_DIVISAO_codigo_divisao, fk_CONDOMINIO_codigo_condominio)
    VALUES
        (1, '532097'),
        (2, '532097'),
        (3, '532097'),
        (4, '532097'),
        (5, '532097'),
        (11, '892356'),
        (12, '892356'),
        (13, '892356'),
        (14, '892356'),
        (15, '892356'),
        (16, '892356'),
        (17, '892356'),
        (18, '892356'),
        (19, '892356'),
        (20, '892356'),
        (21, '415869'),
        (22, '415869'),
        (23, '415869'),
        (11, '724138'),
        (12, '724138'),
        (13, '724138'),
        (14, '724138'),
        (15, '724138'),
        (16, '724138'),
        (1, '301572'),
        (2, '301572'),
        (3, '301572'),
        (4, '301572'),
        (5, '301572'),
        (6, '301572'),
        (7, '301572');

    -- Inserting data into CONDOMINIO_ESPACOS_PUBLICOS table
    INSERT INTO CONDOMINIO_ESPACOS_PUBLICOS (fk_CONDOMINIO_codigo_condominio, fk_ESPACOS_PUBLICOS_codigo_espacos_publicos)
    VALUES
        ('532097', 1),
        ('532097', 2),
        ('532097', 10),
        ('532097', 4),
        ('532097', 14),
        ('892356', 1),
        ('892356', 11),
        ('892356', 1),
        ('892356', 4),
        ('415869', 4),
        ('415869', 1),
        ('724138', 1),
        ('724138', 4),
        ('724138', 5),
        ('724138', 10),
        ('301572', 1),
        ('301572', 2),
        ('301572', 4),
        ('301572', 13),
        ('301572', 14),
        ('301572', 17);

    INSERT INTO TAG (tag) VALUES ('Alimentação'), ('Confecção'), ('Eletrônicos'), ('Cosméticos'), ('Decoração'), ('Petshop'), ('Serviços');

    INSERT INTO IMPORTANCIA (importancia) VALUES
    ('Importante'),
    ('Urgente'),
    ('Crítico');

    INSERT INTO POSTAGEM (data_hora_postagem, descricao, titulo, FK_USUARIO_cpf)
    VALUES
        ('2023-05-09 10:15:00', 'Conjunto de panelas antiaderente, conjunto com 5 peças', 'Conjunto de Panelas', '31589904263'),
        ('2023-05-09 13:45:00', 'Camiseta masculina, tamanho P, cor azul marinho', 'Camiseta Masculina', '49628092010'),
        ('2023-05-09 16:30:00', 'Smartphone Samsung Galaxy S21, 128GB, cor preta', 'Smartphone Samsung Galaxy S21', '31589904263'),
        ('2023-05-09 18:45:00', 'Kit de maquiagem com 10 itens, incluindo batom, sombra e pincéis', 'Kit de Maquiagem', '42155708213'),
        ('2023-05-09 20:00:00', 'Luminária de mesa em madeira e metal, com cúpula em tecido', 'Luminária de Mesa', '49628092010'),
        ('2023-05-09 21:30:00', 'Ração para cachorro, marca Pedigree, sabor frango e legumes, 1kg', 'Ração para Cachorro', '42155708213'),
        ('2023-05-10 09:00:00', 'Limpeza de ar-condicionado, serviço de limpeza em domicílio', 'Limpeza de Ar-Condicionado', '86361974530'),
        ('2023-05-09 10:15:00', 'Aviso sobre vazamento na piscina do condomínio', 'Vazamento na Piscina', '42155708213'),
        ('2023-05-09 13:45:00', 'Aviso sobre reunião de condomínio para discussão de novas medidas', 'Reunião de Condomínio', '42155708213'),
        ('2023-05-09 16:30:00', 'Aviso sobre manutenção do elevador', 'Manutenção do Elevador', '86361974530'),
        ('2023-05-09 18:45:00', 'Aviso sobre obras no estacionamento', 'Obras no Estacionamento', '42155708213'),
        ('2023-05-09 20:00:00', 'Aviso sobre troca do sistema de segurança do condomínio', 'Troca do Sistema de Segurança', '86361974530');

    INSERT INTO ANUNCIO (FK_POSTAGEM_codigo_postagem, FK_TAG_codigo)
    VALUES
        (8, 2),
        (9, 2),
        (10, 1),
        (11, 1),
        (12, 3);

    INSERT INTO AVISO (FK_POSTAGEM_codigo_postagem, FK_IMPORTANCIA_codigo)
    VALUES
        (8, 2),
        (9, 2),
        (10, 1),
        (11, 1),
        (12, 3);

    INSERT INTO IMAGEM (imagem, FK_POSTAGEM_codigo_postagem)
    VALUES
        ('https://exemplo.com/panelas.jpg', 1),
        ('https://exemplo.com/camiseta.jpg', 2),
        ('https://exemplo.com/smartphone.jpg', 3),
        ('https://exemplo.com/maquiagem.jpg', 4),
        ('https://exemplo.com/luminaria.jpg', 5),
        ('https://exemplo.com/racao.jpg', 6),
        ('https://exemplo.com/limpeza.jpg', 7),
        ('https://exemplo.com/piscina.jpg', 8),
        ('https://exemplo.com/reuniao.jpg', 9),
        ('https://exemplo.com/elevador.jpg', 10),
        ('https://exemplo.com/estacionamento.jpg', 11),
        ('https://exemplo.com/seguranca.jpg', 12);

    INSERT INTO FAVORITA (fk_USUARIO_cpf, fk_POSTAGEM_codigo_postagem)
    VALUES
        ('49628092010', 1),
        ('31589904263', 1),
        ('49628092010', 2),
        ('72815390627', 2),
        ('31589904263', 3),
        ('31589904263', 4),
        ('42155708213', 4),
        ('86361974530', 4),
        ('49628092010', 5),
        ('42155708213', 6),
        ('49628092010', 7),
        ('72815390627', 7),
        ('49628092010', 3),
        ('31589904263', 3),
        ('72815390627', 3),
        ('49628092010', 3),
        ('49628092010', 1),
        ('31589904263', 5),
        ('86361974530', 5),
        ('86361974530', 1),
        ('72815390627', 5),
        ('49628092010', 2),
        ('31589904263', 2),
        ('72815390627', 2),
        ('86361974530', 2);

        
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
