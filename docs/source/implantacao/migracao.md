# Migração de Dados

## Disposições Gerais 

A migração de dados obedece a estratégia de migração de dados definida do planejamento da implantação (inserir link).

Essa fase contempla o levantamento e especificação, a execução e a homologação dos dados migrados de forma a permitir seu uso por toda a instituição. 

Carga de dados que compreendem usuários, permissões, processos e documentos. 

## Levantar e Especificar os dados a serem migrados

O Comitê Gestor de Implantação e a área de Tecnologia do Órgão, fazem o levantamento de todos os dados precisam ser migrados para o Super.Br.

Após o levantamento dos dados, é necessário realizar a especificação dos dados para que quando a carga for dada, os dados (tanto os dados correntes quanto os históricos) possam ser transformados de forma adequada.

Objetivo dessa fase é ter um Relatório com todas as entidades e conjuntos de dados, com a carga feita no Super.BR, utilizando preferencialmente a API de serviços *(“Rest”)* do Super.BR.

## Realizar migração de dados - conforme escopo

Baseado no levantamento feito, a área de TI do Órgão faz a implementação da migração dos dados. Inicialmente com a extração da fonte de dados da origem, a migração dos dados conforme especificação com a devida transformação dos dados origem para o modelo destino e posterior carga dos dados, utilizando a API de Serviços do Super.BR 

Após realização da migração de dados, é feita uma validação da carga migrada para verificar o procedimento de operação. Após essa validação inicial, o próximo passo é a Homologação dos dados migrados. 

Importante: Não é sugerida a carga de dados diretamente no banco de dados do Super.BR por riscos de quebra de integridade de regras de negócio e dos dados, além dessa prática burlar mecanismos de auditoria de permissionamento. 

## Homologar os dados migrados 

Após a implementação da migração dos dados pela área de Tecnologia do Órgão, os membros do Comitê de Implantação ficam responsáveis por validar o correto funcionamento do sistema e a qualidade dos dados sistema de origem. Entre eles: 

\- Estrutura de dados (integridade); 

\- Estrutura de Usuários (Dados dos dados, lotação, etc); 

\- Estrutura de Processos (tarefas, atividades e workflow); 

\- Integridade e ordem correta dos documentos. 

<!--A próxima etapa do projeto de implantação do Super.Br é a Integração com os sistemas internos (inserir link)-->