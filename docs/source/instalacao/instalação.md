# Configuração inicial da instalação


## Disposições Gerais

O seguinte documento irá descrever algumas das configurações iniciais que a instalação do sistema precisa ter, de forma a habilitar funções e comandos para que os cadastros iniciais e até mesmo o uso dele seja aderente às necessidades diárias daquele órgão que elegeu o Super.GOV.BR 2.0 o sistema estruturante de tramitação de processos. 

## Tela de Recepção de Remessa Manual

Variáveis que precisam ser definidas no arquivo .env pelo gestor em conjunto com a área de TI na criação de um novo ambiente de Super.gov.br 2.0:


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