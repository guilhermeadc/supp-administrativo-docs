# Manual do Usuário Básico Super.GOV.BR 2.0 – Criar tarefa

## Disposições Gerais

O documento seguinte é uma divisão do Manual do Usuário Básico Super.GOV.BR 2.0. Para acessá-lo e ter maiores informações gerais sobre as funcionalidades do sistema, <ins>clique aqui</ins>.

Criar tarefa é uma atribuição recorrente do Usuário. Existem várias maneiras de criar uma tarefa, entretanto, ela depende de um processo já criado. Para entender como um processo é criado, <ins>clique aqui</ins>.

A tarefa é um dos pilares centrais e diferenciadores do Super.GOV.BR 2.0 como SIGAD frente aos outros Sistemas de Processo Eletrônico. Ela pode ser definida como uma ação a ser executada dentro de um processo de forma a criar produtos (mais conhecidos como “Atividades”) que irão compor o processo como um todo. 

Um usuário abre uma tarefa para outro usuário quando necessitar que uma ou mais **atividades** sejam realizadas, em um dado prazo.

Formas possíveis para Criar uma tarefa:
- Ao criar um processo, a guia de Distribuição 
- Na tela de Processos (por meio de uma busca no campo de Pesquisa, por exemplo);
- Na tela de Tarefas Administrativas;

Esse último será descrito já que é mais abrangente que as outras duas formas. Após a explicação do passo a passo de criação de tarefas, as particularidades de outras formas serão apresentadas. 

## Tela de Criação de Tarefa

A Figura 1 abaixo é a Tela de criação de Tarefas: 

<img src="../../manual/figuras/Tela_criacao_tarefas_administrativas.png"/><p style="text-align: center;">*Figura 1 – Tela de Criação de Tarefas Administrativas*</p>

## Como Criar uma Tarefa (Tela de Tarefas Administrativas) 

Conforme indicado anteriormente, iremos utilizar a forma mais abrangente de criação de Tarefas, na tela de Tarefas Administrativas. 

Com o perfil de Usuário Básico, para acessar a tela de criação de tarefa, é preciso acessar o painel de Tarefas Administrativas e clicar em “Criar” (indicador 1 da Figura 2, abaixo):

<img src="../../manual/figuras/Tela_painel_tarefas_administrativas.png"/><p style="text-align: center;">*Figura 2 – Tela do Painel de Tarefas Administrativas*</p>

Ao acessar a tela do Formulário para Criação de Tarefa, deve-se seguir com os seguintes passos:


```{note}
Nota: Os campos assinalados com * tem preenchimento obrigatório.
```

1. Preencher campos e selecionar habilitação de flags (caso conveniente): 

	**Bloco de Processos**: Flag obrigatória que orienta se a Tarefa será feita para vários processos. Caso habilitada, ela abre um grid de processos a serem incluídos. Caso não habilitada, será feito para apenas um.

* Preencher campos:

	**Processo***: Campo que permite preenchimento para pesquisa (por meio do NUP ou outro número quando acionado o botão “Alterar filtro de busca de processo”). 
	
	<img src="../../manual/figuras/Grid_bloco_de_processos.png"/><p style="text-align: center;">*Figura 3 – Grid de Bloco de Processos ao criar uma tarefa para vários processos*</p>
	
	**Espécie de Tarefa***: Campo que irá especificar qual o tipo de tarefa a ser executada. 
	
* Responsável:
	
	**Distribuição automática**: flag que, quando ativada, é responsável por ativar um comando que encaminha automaticamente para um usuário executor da tarefa, sem necessidade de um distribuidor no setor;
	
	**Bloco de Responsáveis**: flag que, quando ativada, é responsável por ativar campo de Grupos de contatos para preenchimento/seleção e encaminhar a tarefa a esse grupo; 

	Para cadastrar um Grupo de contatos há uma sessão específico para isso no documento Configurar Perfil. Para mais detalhes, <ins>clique aqui</ins>.

	**Unidade Responsável***: Campo que indica qual é a Unidade cujo Usuário será responsável pela execução da tarefa. Após preenchimento/seleção da Unidade, o campo de “Setor Responsável” é habilitado para preenchimento;
	
	**Setor Responsável***: Campo que indica qual é o setor cujo Usuário será responsável pela execução da tarefa. Esse campo é habilitado após preenchimento do campo de Unidade Responsável.
	
* Prazo

	**Em dia(s)**: Campo não obrigatório que indica a quantidade de dias que a tarefa precisa ser executada; 
	
	**Dias úteis**: Seleção não obrigatório que indica se a quantidade de dias indicados para a tarefa ser executada seja contada em dias úteis (caso acionado) ou em dias corridos (caso flag não acionado);

	**Início do prazo***: Campo que indica quando o início do prazo será contado para execução da tarefa;

	**Final do Prazo***: Campo que indica quando é o final do prazo após a quantidade de dias; 

	**Setor Origem***: Campo que indica qual é o Setor de Origem que a tarefa está sendo originada. São os setores que o Usuário criador da tarefa está lotado;

	**Urgente**: Seleção não obrigatória que indica se a tarefa tem urgência para ser concluída. Essa seleção irá ativar um sinal de “!” na lista de tarefas do Usuário executor da tarefa;
	
	<img src="../../manual/figuras/Sinalizacao_urgencia.png"/><p style="text-align: center;">*Figura 4 – Amostra da sinalização de urgência na lista de tarefas do Usuário destinatário (executor) da tarefa, originado pelo Usuário criador da tarefa*</p>

	**Observação**: Campo não obrigatório que permite inserções de informações gerais da tarefa que o Usuário criador da tarefa julgar pertinente informar ao Usuário executor.
	
2. Clicar em Salvar.

Pronto, o Usuário executor da tarefa criada irá receber a tarefa e também será sinalizado com uma notificação.

## Particularidades na Criação de Tarefas via Distribuição

A criação de Tarefas via Criação de Processo contempla algumas diferenças se comparado com o procedimento na Tela de Tarefas Administrativas: 

O primeiro deles é a tela onde se encontra:

<img src="../../manual/figuras/Tela_processo_especifico.png"/><p style="text-align: center;">*Figura 5 – Tela de Criação de Tarefas Administrativas por meio da tela de um processo específico*</p>

A guia “Distribuição” é a parte final da Criação do processo e o campo inicial “Processo*” (NUP) já está preenchido e travado, já que a tarefa já foi atrelada nesse caso. 

Outra diferenciação nesse procedimento é o de não ter a seleção de Bloco de Processos, já que a criação de tarefa é de um processo específico.

No mais, o restante do procedimento seria o mesmo.

## Particularidades na Criação de Tarefas via tela de processos

Após a criação de um processo, é possível acessá-lo por exemplo por meio do campo de pesquisas, localizado na barra superior do Super.GOV.BR 2.0.

Ao localizar o Processo, depara-se com a tela de Processo, onde é possível executar uma série de comandos referentes a ele. O comando Editar é um dos mais recorrentes e nele abre uma série de informações editáveis.

<img src="../../manual/figuras/Criacao_tarefas_do_processo.png"/><p style="text-align: center;">*Figura 6 – Tela de Processos que fornecem acesso à criação de novas tarefas dentro daquele processo*</p>

Entre elas, encontra-se a opção “Tarefa” (Figura 5). Ao clicar nessa opção, temos um grid de tarefas onde é possível entre outras tarefas, acrescentar nova tarefa, clicando em “+” (Figura 6).

<img src="../../manual/figuras/Grid_criacao_tarefas.png"/><p style="text-align: center;">*Figura 7 – Tela de Processos com grid de tarefas, com destaque em vermelho para criação de Tarefas*</p>

<img src="../../manual/figuras/Criacao_tela_processo_especifico.png"/><p style="text-align: center;">*Figura 8 – Tela de Criação de Tarefas Administrativas por meio da tela de um processo específico*</p>

Novamente, como estamos lidando já com a criação de uma tarefa de um processo já existente, naturalmente, o campo “Processo*” já está preenchido e travado, além de a seleção de Bloco de Processos não estar disponibilizada, já que a criação de tarefa é de um processo específico.