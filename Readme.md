<h1>ESTUDANDO API REST<h1>

<hr>


<h2>HTTP</h2>

<hr>
<p>O QUE É HTTP ?</p>
<hr>

É um protocolo de transferencia de dados na Web que podem ser acessados por qualquer computador que esteja conectado na internet...

Ex:
O usuario  acessa o link https://google.com.br , ao acessar esse site o usuario redirecionado para o site da google que esta hospedado em <br> servidor atravez do protocolo HTTP que permite que o usuario acesse o site.

<hr>
<h2> Verbos (Metodos) HTTP </h2>
<hr>

<p>São tipos de requisões diferentes que são feitas a determinada aplicação Web hospedada em  servidor:</p>

Os metodos HTTP são:

GET => PEGAR (RETORNAR) AS INSFORMAÇOES DE UMA API OU BANCO DE DADOS. <br>
POST => SALVAR OU ARMAZENAR DADOS EM UMA API OU BANCO DE DADOS ATRAVÉS DE FORMULARIOS. <br>
PUT => ATUALIZAR TODOS OS DADOS DE UMA API OU EM BANCO DE DADOS. <br>
PATCH => ATUALIZAR PARCIALMENTE OS DADOS DE UMA API. <br>
DELETE => DELETAR OU APAGAR OS DADOS DE UMA API OU BANCO DE DADOS.<br>

<hr>
<h2> Status CODE</h2>
<hr>

Serve para informar ao usuário ou o desenvolvendor se houve algum erro durante a uso da aplicação.

Existem vario tipos de erros, alguns deles são:

100 - Respostas Informacionais, indica que a solicitação feita ao um servidor foi recebida com secesso, e rotorna-se o status 

200 - 200 OK
Resposta padrão para solicitações HTTP bem-sucedidas. A resposta real dependerá do método de solicitação utilizado. Em uma solicitação GET, a resposta conterá uma entidade correspondente ao recurso solicitado.

<hr>
<h2> API</h2>
<hr>

API - Aplication programing Interface ou Interface de Programação de Aplicação, ela permite que sua solição ou serviço se comunique com outros produtos e serviços sem precisar saber como eles foram implementados simplificando o desenvolvimento de aplicações, gerando econimia de tempo e dinheiro.

<hr>
<h2> WEBSERVICES</h2>
<hr>

Web Service é uma solução utilizada na integração de sistemas e na comunicação entre aplicações diferentes.<br> Com esta tecnologia é possível que novas aplicações possam interagir com aquelas que já existem e que sistemas desenvolvidos em plataformas diferentes sejam compatíveis.<br>
Os Web Services são componentes que permitem às aplicações enviar e receber dados.


<hr>
<h2> REST </h2>

<hr>
Padrão de desenvolvimento de webservices:<br>
1 - Cliente Sevidor:<br>
    A api deve somente servir os dados ou que envie dados para o mesmo.<br>
2 - Stateless
    Não deve salvar nenhuma informação da requisição sobre o ciente.
3 - Cacheável:
    permitir fazer cache de dados.
4 - Interface Uniforme e direta:
    As rotas da API devem ser diretas, sem rodeios, seguindo os protocolos HTTP

Tipos de retornos:

1 - XML<br>
2 - JSON<br>
3- PDF<br>
4- Arquivos para Download<br>
5 - Imagens <br>
etc

<hr>
