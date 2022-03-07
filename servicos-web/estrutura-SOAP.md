# Estrutura SOAP



### O que é SOAP?

- SOAP - Simple Object Access Protocol.

- É um protocolo baseado em XML para acessar serviços web principalmente por HTTP.

- Pode-se dizer que SOAP é uma definição de como serviços web se comunicam.

- Foi desenvolvido para facilitar integrações entre aplicações.





### Vantagens

- Permite integrações entre aplicações, independente de linguagem, pois usa como linguagem comum o XML.

- É independente de plataforma e software.

- Meio de transporte genérico, ou seja, pode ser usado por outros protocolos além do HTTP.



### O que é XML?

- XML - Extensible Markup Language.

- É uma linguagem de marcação criada na década de 90 pela W3C.

- Facilita a separação de conteúdo.

- Não tem limitação de criação de tags.

- Linguagem comum para integrações entre aplicações.



### Estrutura SOAP

- O "SOAP Message" possui uma estrutura única que deve sempre ser seguida.

<img title="" src="file:///C:/Users/luizc/OneDrive/Documents/CURSO JAVA/Screenshot_1.png" alt="" data-align="center">

- SOAP Envelope é o primeiro elemento do documento e é usado para encapsular toda a mensagem SOAP.

- SOAP Header é o elemento onde possui informações de atributos e metadados da requisição.

- SOAP Body é o elemento que contém os detalhes da mensagem.



### Mensagem SOAP

<img title="" src="file:///C:/Users/luizc/OneDrive/Documents/CURSO JAVA/Screenshot_2.png" alt="">

A tag Envelope engloba a tag Header e a tag Body.
