# TRABALHO 01:  Gestor de Tarefas e Projetos
Trabalho desenvolvido durante a disciplina de BD1

# Sumário

### 1. COMPONENTES<br>
Integrantes do grupo<br>
João Pedro Garcia Pereira:garcia.jops@gmail.com<br>
Paulo Ricardo:pauloricardo1705@gmail.com<br>
Rodrigo Couto:rodcoutocontas@gmail.com<br>




### 2.INTRODUÇÃO E MOTIVAÇÃO<br>


> Dados divulgados no começo de julho pela OIT (Organização Internacional do Trabalho) revelam que entre 20% e 30% dos trabalhadores da América Latina e Caribe fizeram home office durante a pandemia. Antes, eram menos de 3%. Por esse motivo que idealizamos o Gestor de Tarefas e processos, para ajudar esses trabalhadores que não estavam acostumados a esse tipo de trabalho a se organizarem melhor não só com as demandas dos seus respectivos trabalhos, mas também com as domesticas.
 

### 3.MINI-MUNDO<br>

>Com o decorrer da pandemia, tornou-se mais comum o home office e com isso surge uma dificuldade em supervisionar quais tarefas estão sendo executadas e obter dados sobre elas como tempo utilizado para realiza-la e o tempo limite para entrega. Além disso as pessoas estão passando mais tempo em casa, logo, estando mais tempo presente em casa há um uso maior da residência e portanto mais tarefas a serem realizadas para se manter em ordem.
O sistema deve ser simples e de fácil entendimento para ser utilizado tanto por pequenas empresas quanto por ambientes familiares, etc.
O sistema precisa armazenar informações das tarefas e dos integrantes.
Os integrantes devem ser cadastrados por nome e possuir uma classificação dada pelo criador do projeto que irá divergir dos demais, para que exista tarefas exclusivas para determinado cargo. Todas as tarefas terão seu nome, data de entrega, e uma classificação (caso o criador deseja que esta tarefa seja realizada por um determinado integrante).
As tarefas são realizadas por um ou mais integrantes e devem armazenar o nome da tarefa realizada além da data e quem foram os realizadores.

### 4.PROTOTIPAÇÃO, PERGUNTAS A SEREM RESPONDIDAS E TABELA DE DADOS<br>
#### 4.1 RASCUNHOS BÁSICOS DA INTERFACE (MOCKUPS)<br>
 
![Alt text](https://github.com/RodrigoCoouto/Template_Trab_BD1_2020/blob/master/gest%C3%A3odeprojetos.png "Title")
![Arquivo PDF do Protótipo Balsamiq feito para Gestor de Tarefas e Projetos](https://github.com/RodrigoCoouto/Template_Trab_BD1_2020/blob/master/arquivos/gest%C3%A3odeprojetos.pdf "Gestor de Tarefas e Projetos")
#### 4.2 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM O SISTEMA PROPOSTO?
    
> O Sistema de gestão de tarefas precisa inicialmente dos seguintes relatórios:
* Relatório que mostra os temas mais comuns presentes em projetos.
* Relatório que mostra a quantidade de horas/dias gastos para cumprir uma tarefa ou projeto. 
* Relatório que mostra o desempenho dos cargos na realização de tarefas.
* Relatório que mostra a porcentagem concluída do projeto.
* Relatório que informa quantas tarefas foram criadans e não foram entregues, assim como as que foram entregues.
 
 
#### 4.3 TABELA DE DADOS DO SISTEMA:
    
![LINK](https://github.com/RodrigoCoouto/Template_Trab_BD1_2020/blob/master/Banco%20de%20Dados1_Tabela.xlsx)

    
    
### 5.MODELO CONCEITUAL<br>
    
        
![LINK](https://github.com/RodrigoCoouto/Template_Trab_BD1_2020/blob/master/ModeloConceitualBD.PNG)
  
        
    
#### 5.1 Validação do Modelo Conceitual
    [Grupo01]: [Nomes dos que participaram na avaliação]
    [Grupo02]: [Nomes dos que participaram na avaliação]

#### 5.2 Descrição dos dados 
    Pessoa: Tabela que armazena as informações relativas aos usuários do sistema.
    Tarefa: Tabela que armazena as informações relativas as tarefas dos projetos.
    Prioridade: Tabela que armazena as informações relativas a prioridade das tarefas e projetos do sistema.
    Estado: Tabela que armazena as informações aos estado tanto da tarefa, tanto do projeto no sistema.
    Projeto: Tabela que armazena as informações relacionadas ao projeto.
    Cargo: Tabela que armazena as informações dos cargos de cada usuário do sistema.
    
 
    Email: campo responsável pelo armazenamento do e-mail dos usuários.
    ID: campo para o armazenamento do identificador unico de cada usuário.
    Nome: campo responsavel por armazenar o nome do usuário.
    Data_Nascimento: campo que armazena a data de nascimento dos usuários.
    Senha: campo para o armazenamento das senhas dos usuários.
    Nome(projeto): responsável por armazenar o nome do projeto criado pelo usuário.
    Codigo(projeto: campo responsável para ser um identificador unico de cada projeto.
    Data_entrega: campo responsável pelo armazenamento da data de entrega de cada projeto.
    Codigo(tarefa): campo responsável para ser um identificador unico de cada projeto.
    Nome(tarefa): responsável por armazenar o nome do projeto criado pelo usuário.
    Data_limite: campo responsável pelo armazenamento da data limite de cada tarefa.
    Descrição: campo responsável por armazenar a descrição da tarefa a ser realizada.
    Todo: campo responsável por armazenar a tarefa ou projeto a ser realizada.
    Doing:  campo responsável por armazenar a tarefa ou projeto em andamento.
    Done: campo responsável por armazenar a tarefa ou o projeto já realizado.
    Adm: campo responsável por armazenar os administradores de cada projeto.
    Cargo: campo responsável por armazenar o cargo de cada usuário do projeto.
    Nivel: campo responsável por armazenar o nivel de dificuldade da tarefa.

### 6	MODELO LÓGICO<br>
![LINK](https://github.com/RodrigoCoouto/Template_Trab_BD1_2020/blob/master/modelo%20logico.png)

### 7	MODELO FÍSICO<br>
![LINK](https://github.com/RodrigoCoouto/Template_Trab_BD1_2020/blob/master/modelo%20fisico.txt)

        
       
### 8	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
![LINK](https://github.com/RodrigoCoouto/Template_Trab_BD1_2020/blob/master/INSERT.txt)


### 9	TABELAS E PRINCIPAIS CONSULTAS<br>
#### 9.1	CONSULTAS DAS TABELAS COM TODOS OS DADOS INSERIDOS (Todas) <br>
![COLAB](https://github.com/RodrigoCoouto/Template_Trab_BD1_2020/blob/master/Gestor_de_Tarefas_e_Projeto_BD.ipynb)
># Marco de Entrega 01: Do item 1 até o item 9.1<br>

#### 9.2	CONSULTAS DAS TABELAS COM FILTROS WHERE (Mínimo 4)<br>
#### 9.3	CONSULTAS QUE USAM OPERADORES LÓGICOS, ARITMÉTICOS E TABELAS OU CAMPOS RENOMEADOS (Mínimo 11)
#### 9.4	CONSULTAS QUE USAM OPERADORES LIKE E DATAS (Mínimo 12) <br>
#### 9.5	INSTRUÇÕES APLICANDO ATUALIZAÇÃO E EXCLUSÃO DE DADOS (Mínimo 6)<br>
#### 9.6	CONSULTAS COM INNER JOIN E ORDER BY (Mínimo 6)<br>
#### 9.7	CONSULTAS COM GROUP BY E FUNÇÕES DE AGRUPAMENTO (Mínimo 6)<br>
#### 9.8	CONSULTAS COM LEFT, RIGHT E FULL JOIN (Mínimo 4)<br>
#### 9.9	CONSULTAS COM SELF JOIN E VIEW (Mínimo 6)<br>
#### 9.10	SUBCONSULTAS (Mínimo 4)<br>

De 9.2 até 9.10 está no ![COLAB](https://github.com/RodrigoCoouto/Template_Trab_BD1_2020/blob/master/Gestor_de_Tarefas_e_Projeto_BD.ipynb)

># Marco de Entrega 02: Do item 9.2 até o ítem 9.10<br>

### 10 RELATÓRIOS E GRÁFICOS

#### a) análises e resultados provenientes do banco de dados desenvolvido (usar modelo disponível)
#### b) link com exemplo de relatórios será disponiblizado pelo professor no AVA
#### OBS: Esta é uma atividade de grande relevância no contexto do trabalho. Mantenha o foco nos 5 principais relatórios/resultados visando obter o melhor resultado possível.

    

### 11	AJUSTES DA DOCUMENTAÇÃO, CRIAÇÃO DOS SLIDES E VÍDEO PARA APRESENTAÇAO FINAL <br>

#### a) Modelo (pecha kucha)<br>
#### b) Tempo de apresentação 6:40 

># Marco de Entrega 03: Itens 10 e 11<br>
<br>
<br>
<br> 



### 12 FORMATACAO NO GIT:<br> 
https://help.github.com/articles/basic-writing-and-formatting-syntax/
<comentario no git>
    
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
1. <strong>Caso existam arquivos com conteúdos sigilosos<strong>, comunicar o professor que definirá em conjunto com o grupo a melhor forma de armazenamento do arquivo.

#### Todos os grupos deverão fazer Fork deste repositório e dar permissões administrativas ao usuário do git "profmoisesomena", para acompanhamento do trabalho.

#### Os usuários criados no GIT devem possuir o nome de identificação do aluno (não serão aceitos nomes como Eu123, meuprojeto, pro456, etc). Em caso de dúvida comunicar o professor.


Link para BrModelo:<br>
http://www.sis4.com/brModelo/download.html
<br>


Link para curso de GIT<br>
![https://www.youtube.com/curso_git](https://www.youtube.com/playlist?list=PLo7sFyCeiGUdIyEmHdfbuD2eR4XPDqnN2?raw=true "Title")


