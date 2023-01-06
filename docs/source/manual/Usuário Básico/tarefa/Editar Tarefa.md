# Manual do Usuário Básico Super.GOV.BR 2.0 – Editar tarefa

## Disposições Gerais

O documento seguinte é uma divisão do Manual do Usuário Básico Super.GOV.BR 2.0. Para acessá-lo e ter maiores informações gerais sobre as funcionalidades do sistema, <ins>clique aqui</ins>.

Editar uma tarefa é uma atribuição recorrente do Usuário. Naturalmente, para editar uma tarefa, é preciso que essa já esteja criada, dentro de um processo (para maiores detalhes em como criar uma tarefa, <ins>clique aqui</ins> e para maiores informações de como criar um processo, <ins>clique aqui</ins>). Assim, é possível fazê-la de duas formas: 

* Selecionando a tarefa na lista de tarefas na tela de Tarefas Administrativas;
* Selecionando a tarefa no grid de tarefas, tela de processos.

Além disso, é possível realizar essa edição de tarefas em bloco, ou seja, realizar a edição em mais de uma tarefa simultaneamente. Para maiores detalhes, <ins>clique aqui</ins>.

## Tela de Edição de Tarefa

A Figura 1 abaixo é a Tela de Edição de Tarefas:

<img src="../../manual/figuras/Tela_de_Tarefas_Administrativas_Botao_Minutas.png"/><p style="text-align: center;">*Figura 1 – Tela de Criação de Tarefas Administrativas*</p>

Note que o campo de "***Processo****"está bloqueado para edição, já que ele é um número identificador do processo.

## Como Editar uma Tarefa pela Tela de Tarefas Administrativas

Conforme indicado anteriormente, será abordada a forma mais abrangente de criação de Tarefas, na tela de Tarefas Administrativas

Com o perfil de Usuário Básico, para acessar a tela de edição de tarefa, é preciso selecionar o a tarefa a ser editada na lista de tarefas, na tela de Tarefas Administrativas. Com a seleção da tarefa, são habilitados comandos referentes àquela tarefa:

1. Clicar em Editar;

2. Preencher campos e selecionar habilitação de flags (caso conveniente): 


	```{note}
	Nota: Os campos assinalados com * tem preenchimento obrigatório.
	```

	**Processo***: Campo não habilitado que permite preenchimento para pesquisa (por meio do NUP ou outro número quando acionado o botão “Alterar filtro de busca de processo”). 

	**Espécie de Tarefa***: Campo que irá especificar qual o tipo de tarefa a ser executada. 
	
* Responsável

	**Distribuição automática**: flag que, quando ativada, ativa um comando que encaminha automaticamente para um usuário executor da tarefa, sem necessidade de um distribuidor no setor. Também, quando desativada, naturalmente habilita o campo de Responsável;

	**Bloco de Responsáveis**: flag que, quando ativada, é responsável por ativar campo de Grupos de contatos para preenchimento/seleção e encaminhar a tarefa a esse grupo. Para cadastrar um Grupo de contatos há uma sessão específico para isso no documento Configurar Perfil. Para mais detalhes, <ins>clique aqui</ins>.

	**Unidade Responsável***: Campo que indica qual é a Unidade cujo Usuário será responsável pela execução da tarefa. Após preenchimento/seleção da Unidade, o campo de “Setor Responsável” é habilitado para preenchimento.

	**Setor Responsável***: Campo que indica qual é o setor cujo Usuário será responsável pela execução da tarefa. Esse campo é habilitado após preenchimento do campo de Unidade Responsável.

	**Usuário Responsável***: Campo que é habilitado quando a seleção de Distribuição automática é desabilitada. Quando necessário preenchimento, a tarefa será encaminhada diretamente àquele Usuário lotado selecionado dentro do setor responsável.
	
* Prazo

	**Em dia(s)**: Campo não obrigatório que indica a quantidade de dias que a tarefa precisa ser executada;

	**Dias úteis**: Seleção não obrigatório que indica se a quantidade de dias indicados para a tarefa ser executada seja contada em dias úteis (caso acionado) ou em dias corridos (caso flag não acionado);
	
	**Início do prazo***: Campo que indica quando o início do prazo será contado para execução da tarefa;

	**Final do Prazo***: Campo que indica quando é o final do prazo após a quantidade de dias; 

	**Setor Origem***: Campo que indica qual é o Setor de Origem que a tarefa está sendo originada. São os setores que o Usuário criador da tarefa está lotado;

	**Urgente**: Seleção não obrigatória que indica se a tarefa tem urgência para ser concluída. Essa seleção irá ativar um sinal de “!” na lista de tarefas do Usuário executor da tarefa;

	<img src="../../manual/figuras/Tela_de_Tarefas_Administrativas_Botao_Minutas.png"/><p style="text-align: center;">*Figura 2 – Amostra da sinalização de urgência na lista de tarefas do Usuário destinatário (executor) da tarefa, originado pelo Usuário criador da tarefa*</p>

	**Observação**: Campo não obrigatório que permite inserções de informações gerais da tarefa que o Usuário criador da tarefa julgar pertinente informar ao Usuário executor.
	
3.	Clicar em Salvar.

Pronto, o Usuário executor da tarefa editada irá receber a tarefa e será sinalizado com uma notificação.

## Particularidades na Criação de Tarefas via tela de processos

Após a criação de um processo, é possível acessá-lo por exemplo por meio do campo de pesquisas, localizado na barra superior do Super.GOV.BR 2.0.

Ao localizar o Processo, depara-se com a tela de Processo, onde é possível executar uma série de comandos referentes a ele. O comando Editar é um dos mais recorrentes e nele abre uma série de informações editáveis.

<img src="../../manual/figuras/Tela_de_Tarefas_Administrativas_Botao_Minutas.png"/><p style="text-align: center;">*Figura 3 – Tela de Processos que fornecem acesso à edição de novas tarefas dentro daquele processo*</p>

Entre elas, encontra-se a opção “**Tarefa**” (Figura 3). Ao clicar nessa opção, temos um grid de tarefas onde é possível entre outras ações, editar tarefa , clicando em  <img src="../../manual/figuras/Botao_Clipe.png" style="zoom: 50%;" /> (Figura 4).

<img src="../../manual/figuras/Tela_de_Tarefas_Administrativas_Botao_Minutas.png"/><p style="text-align: center;">*Figura 4 – Tela de Processos com grid de tarefas, com destaque em vermelho para edição de Tarefas*</p>

A partir dessa ação, o Usuário irá acessar a Tela de Edição de Tarefas e poderá realizar os passos a partir do passo 02, da Como Editar uma Tarefa pela Tela de Tarefas Administrativas.