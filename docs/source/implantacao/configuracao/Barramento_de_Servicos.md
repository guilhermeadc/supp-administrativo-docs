# Barramento de Serviços
 

## O que é o Barramento de Serviços 

 
O Barramento de Serviços é uma plataforma centralizada, desenvolvida pelo Ministério da Economia, que permite que processos e/ou documentos tramitem de forma 100% digital entre o SUPER.BR e outras aplicações utilizadas na administração como: o SEI, o SAPIENS, o eDOC, o SIPAC, o SUAP, entre outros. Desta forma, os Órgãos e entidades que possuam diferentes sistemas de gestão e tramitação processual poderão atuar de forma horizontal no tratamento de suas demandas mantendo a segurança, a transparência, a confiabilidade e a rastreabilidade das informações/documentos. 


## Pré-requisitos para utilização do barramento em conjunto com o SUPER.br 

 
O primeiro passo para aderir ao Barramento de Serviços é solicitar a criação do Comitê Gestor de Protocolo em ambiente de homologação no Portal do Barramento (link para o portal). Esta etapa é obrigatória antes de entrar em produção. 

 
O Comitê Gestor de Protocolo é o conjunto de usuários da instituição que poderão gerir os parâmetros de integração dentro do Barramento de Serviços, assim como definir o conjunto de unidades que poderão realizar o envio e recebimento de processos. Cada membro é um gestor de protocolo. 

 
A instituição/órgão que aderir ao Barramento de Serviços deverá ter ao menos um Gestor de Protocolo, que terá, dentre outras, as seguintes competências mínimas: 


1. Ser responsável pelo protocolo da instituição; 

 
2. Definir quais unidades administrativas irão realizar envios externos de processo e receber processos de outras instituições; 

 
3. Realizar as configurações necessárias para a integração do sistema de processo eletrônico do seu órgão ou entidade ao Barramento de Serviços; 


4. Realizar a configuração do sistema de processo eletrônico do seu órgão ou entidade para a integração com o Barramento de Serviços; 

 
5. Proceder na homologação do trâmite dos processos dentro do seu órgão ou entidade. 

 
Abaixo seguem algumas condições fundamentais para a utilização do SUPER.BR: 

 
* Ter instalada minimamente a versão 1.6.(...) do SUPER.br (Confirmar a versão a ser utilizada) 

 
* Ter usuário de acesso ao banco de dados do SUPER.br e SIP com permissões para criar estruturas no banco de dados. (Como fazer para ter estas permissões?) 

 
* Ter certificado digital de autenticação de sistema no Barramento do PEN emitido pela equipe do processo Eletrônico Nacional após aprovação do comitê Gestor de protocolo; 


Para iniciar os procedimentos de configuração, será necessário registrar no Barramento de Serviços do PEN às unidades administrativas que poderão realizar o envio e recebimento de processos externos no SUPER.br. (link para o passo a passo do portal de barramento):

 
Este procedimento precisa ser realizado pelo Gestor de Protocolo previamente habilitado no portal de Barramento de Serviços. Lembrando que os testes devem ser feitos primeiro em ambiente de homologação, para posteriormente a utilização em produção ser liberada. 
 

É necessário que o Gestor/Área de TI Responsável pela Infraestrutura do Sistema habilite os devidos parâmetros de conexão da instância do SUPER.BR com o Barramento de Serviços, informando dentro do arquivo php-secret.yaml (caso esteja sendo utilizado kubernetes) ou nas environments (caso esteja sendo utilizado somente docker com docker-compose) as informações indicadas abaixo: 


## BARRAMENTO 

BARRAMENTO_MODULO=1 (0 desabilitado, 1 habilitado) 

BARRAMENTO_CERT_SENHA= ***** (senha do certificado) 

BARRAMENTO_REPOSITORIO_SIORG=1 (conforme cadastrado no portal do barramento) 

BARRAMENTO_ID_ORGANIZACIONAL=11111 (id da unidade conforme cadastrado no portal do barramento) 

BARRAMENTO_URL_SOAP=https://homolog.api.processoeletronico.gov.br/interoperabilidade/soap/v2/?wsdl (endpoint de homolog ou produção) 

BARRAMENTO_CERT='/caminho/completo/exemploAll.pem' (localização do arquivo de certificado digital (certificado e chave privada no mesmo arquivo no padrão .pem) 


Para o correto funcionamento do barramento, é necessário que as espécies documentais cadastradas no Barramento de Serviços sejam idênticas aos tipos de documentos cadastrados no SUPER.br.  

 
A manutenção/incremento das configurações relativas ao barramento de Serviços, inclusive relativas às espécies de documentos, poderá ser feita pelo Órgão Responsável da Infraestrutura, por meio do arquivo config/services.yaml (disponível por meio do link). A partir da linha 92, se inicia o bloco de configurações de integracao_barramento, não é necessário ajustá-las por padrão, somente se o órgão tiver particularidades. 
 

modalidade_interessado; 

modalidade_qualificacao_pessoa; 

modalidade_genero_pessoa; 

modalidade_doc_identificador; 

tipo_documento_barramento; 

tipo_conteudo; 

mimetype; 

extensões; 

motivo_recusa. 
 

Para solicitação de acesso aos ambientes, acessar os seguintes endereços: 


Homologação: https://homolog.gestopen.processoeletronico.gov.br/ 

Produção: https://gestopen.processoeletronico.gov.br/ 

 
Para garantir o correto funcionamento do Barramento de Serviços, será necessário realizar a confirmação/execução de parametrizações no SUPER.br. São elas: 


* Para que seja possível o recebimento de processos por Unidades previamente cadastradas no barramento de serviços, é necessário que a sigla da Unidade cadastrada no SUPER.br seja a mesma sigla habilitada no Barramento de Serviços.

 
* Para visualizar as siglas previamente habilitadas no Barramento de Serviços, acesse a página de cadastro do Comitê Gestor de Protocolo da sua instituição.

 
A visualização das siglas cadastradas no menu Unidades do SUPER.br poderá ser realizado pelo usuário com perfil Administrador, por meio do caminho: Administrador > Unidades. 

 
Maiores informações relacionadas ao menu Unidades poderão ser acessadas na seção Unidades. (link) 

 
Para envio de processo via Barramento de Serviços é necessário que as Unidades Externas estejam previamente cadastradas como contatos no SUPER.br. 


O cadastramento de contatos deverá ser feito pelo usuário com o perfil Administrador por meio do menu: Administrador > Pessoas. (link para a seção)
 

Após cadastrar os dados da unidade externa, acessar o menu Vinculação ao Barramento, existente na tela de cadastro de pessoas e adicionar a vinculação conforme orientações disponíveis na seção Pessoas. (link)