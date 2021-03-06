# Smart  Parking

![img](https://raw.githubusercontent.com/douglaszuqueto/estacionamento/master/.github/diagrama.png)

## Sumário

* [Introdução](#introdução)
* [Ecossistema](#ecossistema)
* [Diagramas](#diagramas)
  * [Hardware](#hardware)
  * [Software](#software)
* [Tecnologias utilizadas](#tecnologias-utilizadasframeworks-e-bibliotecas)
* [Referências](#referências)

## Introdução

Este projeto foi originado a partir [deste repositório](https://github.com/douglaszuqueto/estacionamento-realtime) onde foi desenvolvido uma pequena
solução para validar tecnologias de tempo real, tais como Socket.IO no back-end juntamente com a funcionalidade *changes* do RethinkDB.

O projeto em si, já possui uma arquitetura bem diferente e mais desacoplada do projeto anterior, visando ser de fácil mantimento e escalável.

## Ecossistema

O ecossistema do projeto, basicamente subdivide-se em: Hardware, Software e Infraestrutura.

Todo o ecossistema irá se conversar através de integrações(protocolos): HTTP, WebSocket e MQTT.

* Hardware
  * Vagas
  * Cancelas
  * Displays
* Software
  * Back-end
    * API
    * Socket.IO
    * Subscribers
    * RethinkDB
  * Front-end
    * Aplicação para usuário final
    * Aplicação para administração do estacionamento
    * Aplicação para administração geral
* Infraestrutura
  * Docker

## Maquete

...em breve

## Diagramas

### Hardware
![img](https://raw.githubusercontent.com/douglaszuqueto/estacionamento/master/.github/diagrama-hardware.png)

... explicação


### Software
![img](https://raw.githubusercontent.com/douglaszuqueto/estacionamento/master/.github/diagrama-software.png)

... explicação


## Tecnologias utilizadas(frameworks e bibliotecas)

* Front-end
  * [VueJS](https://vuejs.org/)
  * [Bootstrap](http://getbootstrap.com/)
  * [Axios](https://github.com/axios/axios)
* Back-end
  * [NodeJS](https://nodejs.org/)
  * [Express](http://expressjs.com)
  * [Socket.IO](https://socket.io/)

* Banco de Dados
  * [RethinkDB](https://www.rethinkdb.com/)

## Referências
