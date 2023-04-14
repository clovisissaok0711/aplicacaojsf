# aplicacaojsf

ERP DESENVOLVIDO COM JSF + HIBERNATE + PRIMEFACES + SPRING SECURITY

<b>FERRAMENTAS UTILIZADAS:</b><br />
POSTGRESQL     -> 11.19.2<br />
JAVA	       -> 8<br />
APACHE TOMCAT  -> 9<br />
ECLIPSE OXYGEN -> JAVA EE<br />

<b>MODO PARA FAZER A INSTALAÇÃO DO PROJETO NO ECLIPSE:</b><br />
-> DESCOMPACTA O ZIP<br />
-> ABRE O ECLIPSE<br />
-> MENU -> FILE -> IMPORT<br />
-> SELECIONE -> GENERAL -> EXISTING PROJECTS INTO WORKSPACE<br />
-> SELECIONA O PROJETO E FAZ A  IMPORTAÇÃO<br />

<b>CONFIGURANDO SERVIDOR:</b><br />
-> MENU -> PROJECT -> TARGETED RUNTIMES -> NEW<br />
-> SELECIONE A SUA VERSÃO DO APACHE TOMCAT, RECOMENDO A 9<br />

<b>CONFIGURANDO O BANCO DE DADOS:</b><br />
-> USUÁRIO E SENHA UTILIZADO NO PROJETO: username: postgres e senha: admin -> Pode ser alterada no arquivo /WEB-CONTENT/META-INF/context.xml -> username & password<br /><br />
-> NOME DO BANCO DE DADOS -> aplicacaojsf -> Pode ser alterada no arquivo /WEB-CONTENT/META-INF/context.xml -> url<br /><br />
-> APÓS ISSO SELECIONE O CONTEUDO DO ARQUIVO banco.backup E DENTRO DO SEU BANCO RODE TODO ESSE BACKUP COM INSTRUÇÕES SQL, FARÁ O INSERT DE ALGUNS DADOS PARA EXEMPLIFICAR O SISTEMA<br /><br />

-> APÓS TUDO ISSO APENAS BASTA IR NO SERVIDOR -> ADD AND REMOVE... -> FAZER A IMPORTAÇÃO DO PROJETO aplicacaojsf<br /><br />
-> ASSIM QUE O SERVIDOR FIZER O DEPLOY DA APLICAÇÃO, BASTA DIGITAR http://localhost:porta_do_seu_servidor_aqui/aplicacaojsf<br /><br />
-> E AS CREDENCIAIS PADRÃO É usuário -> admin e senha -> admin<br /><br />

:D
