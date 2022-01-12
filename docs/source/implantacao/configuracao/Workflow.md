# Workflow

## Disposições Gerais 
 

Workflow é o método usado para organizar o fluxo de trabalho. Consiste na disposição e realização de tarefas em uma sequência lógica. Em outras palavras, é o passo a passo mais eficiente e prático para a execução de um trabalho. 


O SUPER.br permite a construção de Workflows personalizados que permitem, de maneira automatizada, segura e rastreável, suportar os processo de trabalho da Administração. 


O Worflow SUPER.br é composto basicamente de dois artefatos: Tarefas e Atividades. 
 

Uma tarefa nada mais é do que a indicação de uma ação a ser executada pelo usuário no sistema. A tarefa aparece no sistema como uma sentença simples, composta por um verbo no infinitivo, que descreve a ação a ser executada, e pelo objeto sobre o qual se deve executar a ação. 
 

Já as atividades, por sua vez, se referem às ações já realizadas em cumprimento àquela tarefa. São registradas normalmente da seguinte maneira: o objeto que sofre a ação, seguido do verbo no particípio. 
 

O SUPER.br permite, ainda, executar mais de uma atividade para cada tarefa. No exemplo acima, poderiam ser registradas, hipoteticamente, as atividades “Pesquisa de atos pregressos realizada”, “Consulta ao jurídico realizada”, entre outras, até que julgue que a tarefa recebida possa ser dada por cumprida. 


Essa forma de organizar o trabalho possibilita a utilização de fluxos pré-definidos, ou seja, de sequências de tarefas e atividades estabelecidas previamente e associadas a um determinado tema, o que permitirá que o usuário se concentre na atividade de análise técnica e não precise se preocupar com qual documento deve ser inserido em um processo de determinado tipo ou para onde deve enviar determinado processo depois de realizar seu trabalho. 


É uma boa prática ter cadastrado previamente os tipos de documentos, templates, espécies de processos, espécies de atividades e espécies de tarefas relacionadas ao Workflow a ser cadastrado.


 

## Tela Workflow no SUPER.br


<img src="../../_static/images/Workflow - Tela principal.png"/>
<p style=""text-align: center;""> Figura 1 - Tela de Workflow </p>


1) Novo. Utilizado para criar um Workflow; 




2) Colunas. Por esta opção será possível gerenciar as colunas que serão disponibilizadas em tela; 

 
3) Recarregar. Opção permite a atualização dos registros apresentados em tela;  


4) Filtro. Opção possibilita filtrar um intervalo de dados com base em critérios definidos; 


5) Visualizar Espécie de Processo – Opção permite que o usuário consulte as espécies de processos vinculas ao Workflow. Além disso, por esta opção, é possível vincular o Workflow a uma ou mais espécies de processos;


6) Visualizar Transições – Esta opção possibilita a visualização do workflow desenhado por meio do cadastro das transições. Neste desenho, os Círculos representam as Tarefas e os Quadrados representam as Atividades;


<img src="../../_static/images/Workflow - Exemplo fluxo.png"/>
<p style=""text-align: center;""> Figura 2 - Exemplo de Workflow </p>


7) Transições – Opção de acesso ao cadastro das transições/fase do workflow;


8) Editar o cadastro de um Workflow – Opção permite editar um Workflow anteriormente cadastrado;


9) Remover – Opção possibilita a exclusão de um workflow anteriormente cadastrado;


10) Opção permite configurar a quantidade de registros a serem mostrados em tela;


11) Tarja indica a quantidade de páginas relacionadas a consulta em tela. A navegação entre as páginas poderá ser feita por meio do uso das setas disponíveis.

 

### 1. Como Cadastrar um Workflow 

Para o Cadastro do Workflow, é necessário que já tenha sido cadastrado as [Classificações](configuraçao/Classificacoes.md), [Espécies de Atividades](configuraçao/Especies_de_Atividades.md), [Espécies de Processos](configuraçao/Especies_de_Processos.md) e [Espécies de Tarefas](configuraçao/Especies_de_Tarefas.md) 
(Para maiores detalhamentos, clique nos respectivos links disponibilizados).



1.1 Para criação de um Workflow no SUPER.br, o usuário deverá acessar o Menu “Workflow”, existente na visão Administrador, e clicar no botão “Novo” <img src="../../_static/images/Botão de Inclusão (+).png"alt="Botão de Inclusão (+)"style="zoom: 50%;"/> , localizado na parte superior esquerda da tela. 



1.2 Em seguida, deverá preencher os campos disponíveis no formulário de cadastro, conforme orientações abaixo.  

```{note}
Nota: Todos os campos marcados com * são de preenchimento obrigatório. 
```

<img src="../../_static/images/Assuntos - Tela com a Lista de Campos.png"/>
<p style=""text-align: center;""> Figura 3 - Tela de Cadastro do Workflow</p>



**Nome:** campo obrigatório para registro nome do Workflow em questão; 

**Descrição:** campo obrigatório utilizado para inclusão de uma breve descrição do workflow em questão. 


**Espécie de tarefa inicial:** campo obrigatório destinado à seleção da espécie de tarefa que irá iniciar o Workflow em questão.  

 
1.3 Após o cadastro do Workflow o usuário deverá cadastrar as transições do Workflow, por meio da opção “Transições”, e associar o workflow a uma espécie de processo, por meio da opção “Visualizar Espécie de Processo”. 


### 2. Visualizar Espécie de Processo 

 
<img src="../../_static/images/Workflow - Visualizar Espécie de processo.png"/>

<p style=""text-align: center;""> Figura 3 - Tela de Espécie de Processo </p> 

Ao acessar a opção visualizar espécie de processo, poderá:  

- consultar as espécies de processos vinculadas ao Workflow; 

- excluir uma vinculação entre o Workflow e espécie de processo por meio do botão “remover” ; e 

- vincular uma espécie de processo ao workflow. 

 

### 3. Transições 


```{note}
Nota: As transições são a descrição da ordem lógica do Workflow desenhado pela área. Nesta tela o usuário deverá cadastrar tantas transições quantas forem definidas no Workflow da Área. 
```
 

3.1 Para criar uma transição, o usuário deverá acessar o menu “Transições” <img src="../../_static/images/Botão de Transição.png" alt="Botão de Transição" style="zoom: 70%;" /> e em seguida clicar no botão “Novo” <img src="../../_static/images/Botão de Inclusão (+).png" alt="Botão de Inclusão (+)" style="zoom: 50%;" /> , localizado na parte superior esquerda da tela.

 
**Espécie Atividade Lançada:** campo para registro da Atividade gerada nesta transição;  

**Espécie Tarefa De:** campo para registro da tarefa objeto de execução;  

**Espécie Tarefa Para:** campo para registro da próxima tarefa a ser executada no Workflow. 

 

3.2 Após a criação da transição, ficará disponível ao usuário 4 novas opções para gerenciamento do registro criado. 

<img src="../../_static/images/Workflow - Transições_opções em tela.png"/>
<p style="text-align: center;"> Figura 4 - Tela de Transições de Processo </p> 

1) Editar. Permite editar a transição cadastrada. 

2) Ações. Permite incluir ações relacionadas a “Tarefa DE” da transição. Abaixo seguem as ações disponíveis no SUPER.br. 

**OFÍCIO**

- Gera automaticamente um ofício na tarefa

<img src="../../_static/images/Workflow - Transições_Opções_Ofício.png"/><p style="text-align: center;"> Figura 5 - Tela de Ofício de Processo </p> 


**COMPARTILHAMENTO**

- Compartilha a tarefa entre usuários

<img src="../../_static/images/Workflow - Transições_Opções_Compartilhamento.png"/>
><p style="text-align: center;"> Figura 6 - Exemplo de Compartilhamento de Processos</p> 


**DISTRIBUIÇÃO AUTOMÁTICA**

- Distribui as tarefas de forma automática ou por responsável

<img src="../../_static/images/Workflow - Transições_Opções_Distribuição automática.png"/>
><p style="text-align: center;"> Figura 7 - Tela de Distribuição de Tarefa</p> 

**MINUTA**

Gera automaticamente uma minuta na tarefa de acordo com o modelo pré-selecionado 

<img src="../../_static/images/Workflow - Transições_Opções_Minuta.png"/>><p style="text-align: center;"> Figura 8 - Tela de Minuta de Processos</p> 


3) Remover. Permite excluir o registro. 

4) Validações. Permite que o usuário indique se a tarefa DE deverá ser validada. Abaixo seguem as opções de validação disponíveis no SUPER.br.  


**UNIDADE**

<img src="../../_static/images/Workflow - Transições_Validações_Unidade.png"/>
><p style="text-align: center;"> Figura 9 - ******** </p> 

**ATRIBUIDO PARA**

<img src="../../_static/images/Workflow - Transições_Validações_Atribuído para.png"/>
><p style="text-align: center;"> Figura 10 - Tela de de Validação de Atribuição </p> 
 

**CRIADO POR**

<img src="../../_static/images/Workflow - Transições_Validações_Criado por.png"/>
><p style="text-align: center;"> Figura 11 - Tela de de Validação de Criado por</p> 
 
**SETOR DE ORIGEM**

<img src="../../_static/images/Workflow - Transições_Validações_Setor de Origem.png"/>
><p style="text-align: center;"> Figura 12 - Tela de Validação do Setor de Origem</p> 
 

**TIPO DE DOCUMENTO**

<img src="../../_static/images/Workflow - Transições_Validações_Tipo de Documento.png"/>
><p style="text-align: center;"> Figura 13 - Tela de Validação do tipo de Documento</p> 


Pronto, o seu Workflow está criado e pronto para ser utilizado. 