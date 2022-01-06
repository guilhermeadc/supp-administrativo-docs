# Tipos de Relatórios


Opção permite que o usuário administrador cadastre ou edite os relatórios que ficarão disponíveis no SUPER.br. 

 

## Tela Tipos de Relatório no SUPER.br 


<img src="../../_static/images/Tipos de Relatórios - Tela Principal.png"/>
 <p style="text-align: center;">Figura 1 – Tela Tipos de Relatório SUPP</p>

1) Novo. Utilizado para criar um registro de Tipo de Relatório; 

2) Colunas. Por esta opção será possível gerenciar as colunas que serão disponibilizadas na tela;

3) Recarregar. Opção permite a atualização dos registros apresentados em tela;  

4) Filtro. Opção possibilita filtrar um intervalo de dados com base em critérios definidos; 

5) Mostrar inativos. Se selecionada, a opção permite que os cadastros inativos fiquem visíveis em tela. 

6) Editar o cadastro de Tipo de Relatório; 

7) Visibilidade;
```Dúvida: Para que serve este botão? Sempre que clico nele retorna uma mensagem de acesso negado.

8) Opção permite configurar a quantidade de registro a serem mostrados em tela;

9) Tarja indica a quantidade de páginas relacionadas a consulta em tela. A navegação entre as páginas poderá ser feita por meio do uso das setas disponíveis. 

 

## Como Cadastrar um Tipo de Relatório

Para criação de um Tipo de Relatório no SUPER.br, o usuário deverá acessar o Menu “Tipos de Relatório”, existente na visão Administrador, e clicar no botão “Novo” <img src="../../_static/images/Botão de Inclusão (+).png" alt="Botão de Inclusão (+)" style="zoom: 50%;" />, localizado na parte superior esquerda da tela. 
 
Em seguida, deverá preencher os campos disponíveis no formulário para o cadastro do Tipo de Relatório desejado.  

 
```{note}
Nota: Todos os campos marcados com * são de preenchimento obrigatório. 
```

<img src="../../_static/images/Tipos de Relatórios - Tela com a Lista de Campos.png"/>


* **Nome:** campo obrigatório para registro nome do Tipo de Relatório em questão; 


* **Descrição:** campo obrigatório destinado ao registro de uma breve descrição do tipo de relatório em questão. 
 

* **Espécie:** campo obrigatório utilizado para registro da espécie do relatório. Abaixo seguem algumas opções disponíveis. 

 

|Espécie                      |Gênero      |
|-----------------------------|------------|
|TAREFAS                      |OPERACIONAL |
|ATIVIDADES                   |OPERACIONAL |
|COMUNICAÇÕES                 |OPERACIONAL |
|PROCESSOS/DOCUMENTOS AVULSOS |OPERACIONAL |
|TABELAS                      |SISTEMA     |
|TRAMITAÇÕES                  |OPERACIONAL |
|FLUXO DE TRABALHO            |GERENCIAL   |
|DÍVIDA ATIVA                 |OPERACIONAL |
|RECURSOS HUMANOS             |GERENCIAL   |
|INTIMAÇÕES                   |OPERACIONAL |
|USUÁRIOS                     |SISTEMA     |
 

* **Template HTML:**

```
Dúvida: Este campo é para registro do caminho ou modelo do relatório? 
```

* **Parâmetros:** campo obrigatório para indicação das colunas (campos) que serão disponibilizadas no relatório.    

```
Essa explicação sobre o campo Parâmetros estava destacada no documento original (word) por algum motivo?
```

* **DQL:** campo obrigatório para registro do código da consulta a ser aplicada no relatório. 


* **Ativo:** Flag que indicará se o Tipo de Relatório está disponível para uso ou não.Caso esteja marcada estará ativa e disponível. Caso contrário, estará inativa e indisponível. 
