# Respostas
1) Qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)?
R: Corresponde ao nivel 2 de maturidade.

2) Qual a relação entre os metodos HTTP e o CRUD?
R: Hoje, a implementação mais comum do estilo arquitetural REST é baseado no protocolo HTTP e, consequentemente, nos verbos do HTTP: POST, GET, PUT e DELETE. É comum desenvolvedores implementarem esses verbos mapeando-os em termos CRUD - Create, Read, Update e Delete (Criar, Ler, Atualizar e Excluir).

3) O que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?
R: Sim, pois a API estará completamente organizada trazendo informações que ajudarão seu consumidor entender a estrutura dos recursos disponíveis.

4) O que quer dizer quando dizemos que uma API é indepotente?
R: Que tem a propriedade de poder ser aplicado mais do que uma vez sem que o resultado se altere.

5) Qual a diferença entre os métodos PUT e PATCH?
R:O método de requisição HTTP PATCH aplica modificações parciais a um recurso. O método HTTP PUT permite apenas substituições completas de um documento. Em contraste ao PUT , o método PATCH não é idempotente, ou seja, requisições sucessivas idênticas podem obter efeitos distintos


Fontes:https://www.infoq.com/br/news/2009/08/CRUDREST/
https://www.youtube.com/watch?v=P92SBaN42mQ
