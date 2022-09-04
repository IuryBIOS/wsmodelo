### Conteúdo <!-- omit in toc -->
- [Download](#download)
- [Importação](#importação)
- [Confifurações](#configurações)

## Download

Para baixar o projeto basta o clonar utilizando o aplicativo desktop do github, usar o link https://github.com/IuryBIOS/wsmodelo.git para dar clone direto no terminal ou fazer download da pasta zipada.

## Importação

Para importar o projeto no eclipse vá em File>Import>Maven>Existing Maven Projects e escolha a pasta onde o projeto foi salvo. Depois de importado aguarde o eclipse fazer as atualizações necessárias.

## Configurações

O projeto está configurado como wsmodelo, caso deseje utilizar esse modelo para começar um novo projeto de produção é necessário alterar algumas coisas.

### Web.xml

Em WebContent>WEB-INF>web.xml altere todos os lugares que existir wsmodelo para o nome do novo projeto.

### Pom.xml

Em pom.xml altere todos os lugares que existir wsmodelo para o nome do novo projeto.

### Context.xml

Em WebContent>META-INF>context.xml altere /wsmodelo para /nome-do-novo-projeto

