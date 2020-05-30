# NodeJS

O **NodeJS** é um interpretador EcmaScript (ou JavaScript como é popularmente conhecido). Sua arquitetura permite que possamos executar blocos de códigos de forma assíncrona (enquanto uma tarefa é executada, outras podem ir sendo executadas/processadas em paralelo) o que dá um ganho de desempenho gigantesco nas aplicações feitas utilizando Node. A possibilidade de fazer com que o JavaScript seja executado no backEnd também é um bônus, já que JS é uma linguagem de programação presente nos web browsers e que também está presente em alguns bancos de dados **NoSQL**, o que possibilita que um programador seja fullStack utilizando uma **única linguagem de programação**.

Vamos começar? Para começarmos a programar em *Node.js*, vamos precisar instalar o Node no nosso ambiente de desenvolvimento.

- No Ubuntu ou Debian, abra um terminal e siga os passos da documentação oficial.

https://github.com/nodesource/distributions/blob/master/README.md#debian-and-ubuntu-based-distributions

- No nosso caso, vamos usar o node versão 13

```
$ curl -sL https://deb.nodesource.com/setup_13.x | sudo -E bash -

$ sudo apt-get install -y nodejs
```

Comumente, para que possamos gerar aplicações REST precisamos utilizar métodos presentes no protocolo HTTP, para que não precisemos gastar horas programando essas interfaces e estabelecendo as regras de negócio para utilização dessas interfaces, podemos utilizar frameworks que geram essas interfaces (GET, PUT, …) um framework de abstração de REST muito famoso utilizado junto ao Node.JS é o *Express*. No entanto, ultimamente um Framework que vem tendo uma notoriedade grande é o **Fastify** e através dele temos algumas features a mais como:

* Logs de transações entre API e aplicações clientes
* Detalhamentos de estado de rotas
* Também padronização de respostas à requisição sem que precisemos programar cada uma delas como:
  * 200 (OK)
  * 4XX (pagina não encontrada)
  * 5XX (erro no servidor)




[Anterior](./01Introducao.md) <---- | ----> [Avançar]()