# Setor

Entende-se por SETOR no Super.BR um grupo de usuários (membros/servidores) que trabalham, em equipe, para o exercício de um conjunto de atribuições. Um usuário pode ser lotado em mais de um setor, inclusive exercendo funções diferentes em cada um deles. Cada setor deve ter pelo menos um Coordenador, que será responsável pela gestão dos modelos locais de documentos, dos repositórios locais de conhecimento e dos critérios de visibilidade dos processos/documentos avulsos. O acesso de Coordenador de Setor é concedido pelo Administrador de Sistema.

Relacionado à hierarquia dos grupos de pessoas, o Setor está abaixo da Unidade (e esta, por sua vez, abaixo de Órgão).


## Tela de Setores

Logo, para acessar um setor dentro do Super.BR, é necessário que o Órgão e a Unidade acima daquele Setor já tenham sido criados pelo Administrador do Sistema. O acesso à tela de Setor será descrito a seguir e permitirá desencadear outras ações.

<img src="../../_static/images/Setores - Tela de acesso ao cadastro via Unidades.png"/><p style="text-align: center;">Figura 1 – Tela de Unidades SUPP</p> 

Com acesso de Coordenador de Unidade (ou acesso superior Coordenador de Órgão ou de Administrador do sistema), acessar a lista de Unidades e, na respectiva Unidade que se deseja acessar o setor, clicar no botão de Setores. 

A partir da tela de Setores, é possível realizar as ações de Criar, Editar, Lotar, Criar Localizador e Transferir Processos para o Protocolo.

<img src="../../_static/images/Setores - Tela Principal.png"/>
<p style="text-align: center;">Figura 2 – Tela de de Setores SUPP</p>

1) Novo. Utilizado para criar um Setor;

2) Colunas. Por esta opção será possível gerenciar as colunas que serão disponibilizadas em tela;

3) Recarregar. Opção permite a atualização dos registros apresentados em tela; 

4) Filtro. Opção possibilita filtrar um intervalo de dados com base em critérios definidos;

5) Editar os dados de um setor;

6) Lotações. Maiores detalhes na Seção de Lotações adiante;

7) Localizadores. Maiores detalhes na Seção de Localizadores adiante;

8) Transferir Processos para o Protocolo;

9) Opção permite configurar a quantidade de registros a serem mostrados em tela;

10) Tarja indica a quantidade de páginas relacionadas a consulta em tela. A navegação entre as páginas poderá ser feita por meio do uso das setas disponíveis.


### Como criar um Setor

Após acessar a tela de setor, deve-se seguir os seguintes passos para a criação do Setor.

```{note}
Nota: Todos os campos marcados com * são de preenchimento obrigatório.
```


01.	Clicar no botão “Novo” <img src="../../_static/images/Botão de Inclusão (+).png" alt="Botão de Inclusão (+)" style="zoom: 50%;" /> e preencher todos os campos que aparecerem na tela subsequente: 

* **Nome:** Campo obrigatório, destinado ao preenchimento do nome do Setor.

* **Sigla:** Campo obrigatório, destinado ao preenchimento da Sigla do Setor.

* **Prefixo NUP:** Campo obrigatório, destinado ao preenchimento do Prefixo NUP.

* **Endereço:** Campo opcional, destinado ao preenchimento do endereço que o setor se encontra.

* **Espécie Setor:** Campo obrigatório, destinado ao preenchimento da espécie do setor. A espécie de setor é uma seleção pré-definida pela Unidade, cadastrada no Menu Espécie de Setores disponível para o Administrador de Sistema.

* **Município:** Campo obrigatório, destinado ao preenchimento do município que o setor se encontra.

* **Setor Pai:** Campo opcional, destinado ao preenchimento de um possível setor Pai que o este setor pertence. Usado, exclusivamente, para fins de consumo de ferramentas de BI.

* **Ativo:** Seleção opcional, destinado a indicar se o setor está ativo ou não.

* **Distribuidor:** Seleção opcional, destinado se o setor terá usuários distribuidores ou não.

* **Distribuição Automática:** (Seguem explicações breves dos seguintes campos, caso necessário essa sessão será descrita com mais detalhes na seguinte página: Distribuição automática)

* **Tipo Prevenção Absoluta:** Dígito x Centena – Essa seleção permitirá que a distribuição automática de um processo seja por meio do último digito ou da centena do NUP (Ex.: NUP 00400.001269/2021-01, caso for selecionado a Prevenção Absoluta por Dígito será por meio do “9”, ou seja, último digito; ou caso for selecionada a Prevenção Absoluta por Centena será por meio do “69”, ou seja a centena).

```{note}
Nota: A atribuição dos dígitos/centenas está sob responsabilidade do Coordenador de Unidade (ou superior) na tela do usuário na respectiva lotação do Setor. 
Para o Administrador do Sistema, o caminho a ser percorrido é Unidades > Setores > Lotações, para o Coordenadores, Setores da Unidade > Lotações.
```

* **Prazo Máximo de Equalização:** 7 dias x 30 dias – O prazo máximo de equalização da média de tarefas distribuídas no Setor. Utilizada em casos de afastamento, quando a média de tarefas distribuídas fica defasada.
*Exemplo:* Caso um usuário seja afastado por 15 dias, ao retornar, a sua média de tarefas se torna baixa e para alcançar a média de tarefas do setor, mais tarefas serão encaminhadas a ele. Caso seja selecionado 7 dias, a distribuição precisa atingir que a média de tarefas distribuídas para o usuário afastado precisaria ser equalizada no máximo em 7 dias. 

* **Divergência Máxima Diária:** Pequena x Grande - A Divergência Máxima Diária é o volume da diferença entre as distribuições entre os usuários daquele setor. Caso a seleção seja pequena, o algoritmo da distribuição automática permite um maior transbordo das tarefas com determinado usuário, de forma a deixar a diferença pequena entre quantidades de tarefas dos usuários. Em casos de a seleção ser grande, a permissibilidade do transbordo é menor.
	
```Sugestão: Realizar testes para verificar o comportamento de cada um dos parâmetros```

* **Desconsiderar Distribuição Manual:** Seleção que, se marcada a opção, o cálculo da média de tarefas distribuídas automaticamente não levará em conta a distribuição manual realizadas no período. Caso a opção não seja marcada, a Distribuição Manual será considerada. 

* **Aplicar Prevenção Relativa:** Seleção que se marcada a opção, o sistema tentará realizar transbordo para equalização da distribuição das tarefas.


## Lotações

As Lotações são designações de usuários para dentro dos setores para realização das tarefas daquele setor e sua configuração está sob responsabilidade do Coordenador de Unidade (ou perfil de acesso Superior). Naturalmente, para lotar usuários dentro dos setores, é necessário que Usuários já estejam cadastrados dentro da Unidade. Essa etapa é descrita em [Usuários](configuraçao/Usuários.md).

Para cada lotação, há configurações destinadas para cada usuário, descritas a seguir (boa parte delas, dependentes de outros conceitos que são abordados, como Distribuição Automática)


### Tela de Lotações

Dentro de um setor é possível criar, editar e remover as respectivas lotações para cada um dos usuários. Para isso, o Coordenador de unidade (ou o Administrador de Sistema) deve acessar a lotação respectiva ao setor, clicar no botão de Lotações <img src="../../_static/images/Botão de Lotação.png" alt="Botão de Lotação" style="zoom: 50%;" /> (indicado como 3 na Figura 2) referente ao setor a ser lotado. 
 
<img src="../../_static/images/Setores - Tela de cadastro de Lotações.png"/>
<p style="text-align: center;">Figura 3 – Tela de Cadastro de Lotações SUPP</p>

1) Novo. Utilizado para criar uma lotação;

2) Editar os dados de um setor;

3) Excluir lotação. Ao excutar esta ação, a lotação não está mais disponível no setor.


### Criar Lotação

01.	Clicar no botão de "Novo" <img src="../../_static/images/Botão de Inclusão (+).png" alt="Botão de Inclusão (+)" style="zoom: 50%;" />, e preencher todos os campos que aparecerem na tela subsequente:

* **Unidade:** Campo obrigatório, destinado à seleção da unidade que será criada a lotação;

* **Setor:** Campo obrigatório, destinado à seleção do setor que será criada a lotação;

* **Usuário:** Campo obrigatório, destinado à seleção do usuário que será definida a lotação;

* **Campos habilitáveis:**

* **Principal:** Campo obrigatório, referente se o setor é o principal do usuário

* **Distribuidor:** Campo opcional, mostrando se o usuário será o distribuidor de tarefas daquele setor

* **Dígitos:** Campo opcional, mostra quais dígitos do NUP serão destinados ao usuário na distribuição automática;

```{note}
Nota: 
É possível que ocorra intersecção ou lacunas de dígitos (ou centenas) para os usuários.
Para esses casos, a prevenção absoluta da distribuição automática atua da seguinte forma:
01.	O dígito/centena não tem dono: a tarefa é sorteada entre todos os usuários do setor;
02.	O dígito/centena tem mais de um dono: a tarefa é sorteada entre esses donos do setor;
03.	O dígito/centena tem dono, mas ele está afastado, a tarefa é sorteada entre todos os usuários do setor.

Lembrar que caso haja sorteio, é levado em conta o Peso, conceito explicado a seguir.
```

* **Peso:** Campo opcional, valor numérico compreendendo entre 0 (zero) e 100 (cem), com referência proporcional a um maior direcionamento para os usuários com maior peso, isto é, quanto maior o peso, maior o direcionamento de tarefas para aquele usuário.

02.	Clicar em Salvar.

```o item acima precisa de correção: no arquivo .md ele aparece com 02 e na previsão HTML volta à contagem 01
``

Uma vez criadas as lotações, é possível editá-las ou excluí-las (respectivamente botões 2 e 3 da figura 3)


## Localizadores

Os localizadores são configurações dos Setores destinadas a localizar fisicamente do Setor.

### Tela de Localizadores

Dentro de um setor é possível criar, editar e remover os respectivos localizadores. Para isso, deve-se acessar a lotação respectiva ao setor, clicar no botão de Localizadores (indicado como 4 na Figura 2) referente ao setor.

<img src="../../_static/images/Setores - Tela de cadastro de Localizadores.png"/>
<p style="text-align: center;">Figura 4 – Tela de Cadastro de Localizadores SUPP</p>

### Criar Localizadores: 

01.	Clicar no botão de "Novo" <img src="../../_static/images/Botão de Inclusão (+).png" alt="Botão de Inclusão (+)" style="zoom: 50%;" /> (indicado como 1 na Figura 4), e preencher todos os campos que aparecerem na tela subsequente:

**Nome:** Campo obrigatório, destinado ao nome do localizador do setor;

**Descrição:** Campo obrigatório, destinado à descrição do localizador do setor;

02.	Clicar em Salvar.

```
o item acima precisa de correção: no arquivo .md ele aparece com 02 e na previsão HTML volta à contagem 01
```

Uma vez criados os localizadores, é possível editá-los ou excluí-los.
