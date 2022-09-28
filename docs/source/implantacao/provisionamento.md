# Provisionamento da Infraestrutura

O Provisionamento de Infraestrutura do Super.BR é feito pelo provedor contratado junto ao Ministério da Economia. 

Serão disponibilizados 3 ambientes com os devidos serviços para devida utilização, em seus respectivos momentos do projeto. 


## Parâmetros Principais do sistema: 

É necessário que o Gestor/Área de TI Responsável pela Infraestrutura do Sistema defina os seguintes parâmetros da instância do Super.GOV.BR 2.0, informando dentro do arquivo php-secret.yaml (caso esteja sendo utilizado kubernetes) ou nas environments (caso esteja sendo utilizado somente docker com docker-compose) as informações indicadas abaixo:


A definição das variáveis abaixo é essencial para que a identidade visual do Super.GOV.BR 2.0 esteja de acordo com as necessidades do órgão aderente e deve ser aplicado em cada ambiente que for criado: 


LOGO_SISTEMA ex: data:image/png;base64,iVBORw0KGgoAAAANSUhEUgA.... (imagem em formato base64 para uso em todo o sistema)
ICONE_SISTEMA ex: data:image/png;base64,iVBORw0KGgoAAAANSUhEUgA... (imagem em formato base64 para uso em todo o sistema)

NOME_SISTEMA ex: "SUPER.GOV.BR"
SIGLA_SISTEMA ex: "SUPER.GOV.BR"

NOME_INSTITUICAO ex: "Ministério da Economia"

SIGLA_UNIDADE_ARQUIVO_INT ex: MECON (sigla de uma unidade existente no cadastro do sistema responsável pelo Arquivo Intermediário)

SIGLA_UNIDADE_ARQUIVO_DEF ex: MECON (sigla de uma unidade existente no cadastro do sistema responsável pelo Arquivo Definitivo)

CNPJ_INSTITUICAO ex: 26994558000...

LOGO_INSTITUICAO ex: "<img src=\"data:image/png;base64,iVBORw0KG..." />"

EMAIL_SUPORTE ex: suporte-superbr@orgao.gov.br

LOGIN_INTERNO_ATIVO ex: true Desta forma o sistema habilitará uma base interna de usuários e permitirá o cadastro pela tela inicial

LOGIN_GOVBR_ATIVO ex: true Desta forma o sistema habilitará o login via Gov.br, porém é necessário solicitar as chaves de acesso junto a Secretaria de Governo Digital, , necessária configuração das variáveis adicionais com prefixo SSO_GOV_BR*

LOGIN_LDAP_ATIVO ex: true Desta forma o sistema habilitará o login usando base externa de usuários via AD/LDAP existente do órgão, necessária configuração das variáveis adicionais LDAP_CONF
 
CERTIFICATE_* variáveis com este prefixo são utilizadas para configurar o certificado que sera usado para Assinar os Documentos dentro do sistema, necessário possuir certificado da cadeia ICP-Brasil válido


## Ambiente de Homologação/Teste e Ambiente de Treinamento

O Ambiente de Homologação do Super.BR tem o objetivo de proporcionar testes, configurações iniciais, aderência de funcionalidades para o Órgão, ajustes de Regras de Negócio, para os Usuários-chave que conhecem bem os processos e são escolhidos pelo Órgão. 

O Ambiente de Treinamento do Super.Br tem o objetivo de capacitar os Usuários e Multiplicadores do Órgão para uso e familiarização do sistema. 

Para o Ambiente de Homologação (também chamado de ambiente de teste), quanto para o Ambiente de Treinamento, os serviços disponibilizados são bastante semelhantes. 

Em ambos a instalação do sistema é feita pelo Provedor contratado junto ao Ministério da Economia. 

Em ambos também é feita a parametrização básica do Super.Br, isto é, definição do nome da instituição, endereço de onde os ambientes estarão disponíveis, configuração de servidor de e-mails e acesso a base de usuários do órgão, parametrização da conexão do sistema com o comitê de protocolo com o barramento de serviço são alguns dos serviços disponibilizados para a configuração básica em ambos os ambientes. 

A diferença entre esses dois ambientes está no direcionamento do público alvo: no Ambiente de Homologação é direcionado a usuários-chave do Órgão (Comitê de Implantação do Super.BR). Já no Ambiente de Treinamento, o direcionamento é para os Usuários para serem capacitados e treinados com as funcionalidades do Super.BR, não somente para o comitê de Implantação do Super.BR. 

## Ambiente de Produção 

Após a realização do treinamento, o ambiente de produção também é disponibilizado pelo Provedor de serviços, bem como sua instalação do Super.BR para uso. 

O ambiente de produção possui muito mais recursos, sendo mais robusto, frente aos ambientes anteriores. Essa alocação de recursos tem requisitos bem diferentes (Rotinas de Backup, replicação de dados; planos de contingência para evitar queda e perda de dados). 

Além da disponibilização do ambiente de produção, outros serviços também são feitos pelo Provedor de Serviço, a saber os principais: Aplicação de parametrização em produção; Implementação de redundâncias; Implementação de monitoramento; Elaboração de planos de contingências; Implementação de políticas de backup e plano de restauração e Implementação de barreiras de segurança.

Maiores detalhes sobre configurações e serviços disponibilizados no ambiente de produção podem ser disponibilizados no ato do ingresso Órgão com o Super.BR por meio do Provedor de Serviços.