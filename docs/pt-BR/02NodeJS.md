# NodeJS

O **NodeJS** é um interpretador EcmaScript (ou JavaScript como é popularmente conhecido). Sua arquitetura permite que possamos executar instruções em códigos de forma assíncrona (enquanto uma tarefa é executada, outras podem ir sendo executadas/processadas em paralelo). Isso dá um ganho de desempenho gigantesco nas aplicações que rodam em Node. A possibilidade de fazer com que o JavaScript seja executado no backEnd também é um bônus, já que JS é uma linguagem de programação presente nos web browsers e que também está presente em alguns bancos de dados **NoSQL**, o que possibilita que um programador seja fullStack (programador multidisciplinar) utilizando uma **única linguagem de programação**.

## Instalação do Node.js

Vamos começar? Para começarmos a programar em *Node.js*, vamos precisar instalar o Node no nosso ambiente de desenvolvimento.

- No nosso caso, vamos instalar o node versão 13 no Pop'OS que é uma distro baseada no ubuntu!

```
$ curl -sL https://deb.nodesource.com/setup_13.x | sudo -E bash -

$ sudo apt-get install -y nodejs
```

- Ou caso prefira, no Ubuntu ou Debian, abra um terminal e siga os passos da documentação oficial.

https://github.com/nodesource/distributions/blob/master/README.md#debian-and-ubuntu-based-distributions

## Instalação do VSCode no ubuntu

Uma outra taréfa importante para quem está pretendendo inicar uma aplicação, e ter um ambiente de desenvolvimento que nos possibilite agilidade no desenvolvimento e nas entregas de códigos legiveis e bem estruturados. Assim, a utilização do (Visual Studio Code)[https://code.visualstudio.com/] é imprescindivel para quem está iniciando e para quem já é programador. O visual studio é um *canivete suiço* na vida do programador moderno. Além de possibilitar ganho de desempenho no desenvolvimento de projetos, pela sua estrutura de visualização e navegação entre arquivos de código que compõem um sistema; ele também tem uma gama gigantesca de plugins que vão desde sugestões de auto-complete de codigos, find and replace em multiplos files, até minificadores de codigos. O negocio é xique :)

No ubuntu e derivados, a instalação do VSCode pode ser feita seguindo os passos abaixo:

> Vá até a pagina do VSCode https://code.visualstudio.com e faça o donwload no botão ".deb"

Depois de baixar, acesse o diretório onde fez o donwload do VSCode e instale seguindo os passos abaixo. No meu caso, o download foi feito em /home/usuario/Downloads

```
$ cd /home/alnetosilva/Downloads/
$ dpkg -i code_numero_da_versao_amd64.deb

```
*obs: onde está escrito "numero_da_versao" você coloca a versão do VSCode baixado. Recomendo o uso do <tab> para auto-completar.*

Comumente, para que possamos gerar aplicações REST precisamos utilizar métodos presentes no protocolo HTTP, para que não precisemos gastar horas programando essas interfaces e estabelecendo as regras de negócio para utilização dessas interfaces, podemos utilizar frameworks que geram essas interfaces (GET, PUT, …) um framework de abstração de REST muito famoso utilizado junto ao Node.JS é o *Express*. No entanto, ultimamente um Framework que vem tendo uma notoriedade grande é o **Fastify** e através dele temos algumas features a mais como:

* Logs de transações entre API e aplicações clientes
* Detalhamentos de estado de rotas
* Também padronização de respostas à requisição sem que precisemos programar cada uma delas como:
  * 200 (OK)
  * 4XX (pagina não encontrada)
  * 5XX (erro no servidor)




[Anterior](./01Introducao.md) <---- | ----> [Avançar](./03AmbienteDEV.md)