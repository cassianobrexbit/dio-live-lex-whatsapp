# DIO Live - Integrando seu Chatbot com o WhatsApp Usando Amazon Lex

### Repositório com instruções para o Live Coding do dia 11 de novembro de 2021

## Serviços utilizados

- Amazon Lex
- Whatsapp
- Twilio

## Etapas

- Criar um chatbot no Amazon Lex
- Criar uma conta no Twilio
- Integrar com Whatsapp

## Criando uma conta no Twilio

- Acessar https://www.twilio.com/
- Validar email e número de celular

## Criando um chatbot de exemplo no Amazon Lex

 - AWS Console -> Lex -> Bots -> Create bot -> Start with an example -> Book Trip -> Bot name [escolher um nome] -> Create a role with basic Amazon Lex permissions -> Children’s Online Privacy Protection Act (COPPA) [No] -> Next
 - Language en-US -> Done
 - Build -> Test

## Integrando o Amazon Lex com o Whatsapp via Twilio

- Twilio Console -> My account -> Copiar SID e Token
- Amazon Lex Console -> Bot versions -> Deployment -> Channel Integrations -> Add channel -> Platform - Twilio SMS -> Inserir Account SID e Authentication token -> Create -> Copiar url de endpoint gerado
- Twilio Console -> Messaging -> Settings -> Whatsapp sandbox settings -> Colar endpoint copiado em WHEN A MESSAGE COMES IN

## Testando a integração

- Enviar mensagens e verificar as respostas
