 # Api REST e RESTFul

API REST é um conjunto de princípios arquiteturais e diretrizes para projetar serviços web que sejam escaláveis, flexíveis e de fácil manutenção. O termo "REST" foi cunhado por Roy Fielding em sua tese de doutorado em 2000. Essa abordagem utiliza os conceitos fundamentais do HTTP (Hypertext Transfer Protocol) e dos recursos da web.

Principais Características da API REST:

Stateless (Sem Estado): Cada requisição do cliente para o servidor contém toda a informação necessária para entender e processar a requisição. O servidor não mantém nenhum estado sobre o cliente entre as requisições.

Recursos Identificáveis: Os recursos (dados ou serviços) são identificados por URLs únicas. Cada recurso pode ser acessado e manipulado usando os métodos HTTP padrão, como GET, POST, PUT e DELETE.

Representações: Os recursos podem ter diferentes representações, como JSON ou XML. O cliente pode negociar a representação desejada com o servidor.

Navegabilidade (HATEOAS): O cliente interage com a aplicação inteiramente através dos hiperlinks dinâmicos fornecidos de forma explícita pelas aplicações servidores.
Implementação RESTful:

Uma API que segue os princípios REST é chamada de "RESTful". Aqui estão alguns pontos-chave na implementação RESTful:

URI (Uniform Resource Identifier): Cada recurso é identificado por uma URI única. A estrutura da URI deve ser significativa e seguir convenções para facilitar a compreensão.

Métodos HTTP:
GET: Obtém dados de um recurso.
POST: Cria um novo recurso.
PUT/PATCH: Atualiza um recurso existente.
DELETE: Remove um recurso.
Representação de Recursos: Os dados enviados e recebidos são geralmente formatados em JSON ou XML. A escolha do formato depende da aplicação e das necessidades do cliente.

HATEOAS (Hypermedia As The Engine Of Application State): Inclui links navegáveis nos dados da aplicação, permitindo que o cliente descubra e interaja com os recursos de forma dinâmica.

Status Code: O servidor retorna códigos de status HTTP apropriados para indicar o resultado da requisição (200 OK, 201 Created, 404 Not Found, etc.).

A implementação RESTful visa criar serviços web que sejam interoperáveis, escaláveis e simples de entender. Ao seguir esses princípios, as APIs REST fornecem uma abordagem eficaz para o desenvolvimento de sistemas distribuídos na web.

## Diferenças entre REST e RESTFul

REST:

Definição Geral: REST é uma arquitetura que define um conjunto de princípios para projetar serviços web.

Stateless: REST é stateless, o que significa que cada requisição do cliente para o servidor contém toda a informação necessária. O servidor não mantém nenhum estado sobre o cliente entre as requisições.

Padrões Abstratos: REST fornece os princípios abstratos para a arquitetura, mas não define padrões específicos.

Flexibilidade: REST é flexível e permite implementações que não sigam todos os princípios estritamente.

RESTful:

Implementação de REST: RESTful refere-se à implementação prática dos princípios REST.

Conformidade com Princípios REST: Uma API é considerada RESTful quando segue os princípios fundamentais do REST, como recursos identificáveis, métodos HTTP, representações de recursos e statelessness.

Padrões Concretos: RESTful especifica padrões concretos para implementar os princípios REST, tornando a arquitetura mais tangível.

Padrões de URI: RESTful APIs geralmente seguem convenções específicas para a estrutura das URIs para garantir consistência e facilidade de compreensão.

HATEOAS (Hypermedia As The Engine Of Application State): RESTful APIs frequentemente incorporam o princípio HATEOAS, fornecendo links navegáveis nos dados da aplicação para permitir a descoberta dinâmica de recursos.

Formatos Padrão de Representação: RESTful APIs frequentemente especificam formatos padrão de representação, como JSON ou XML, para facilitar a interoperabilidade.

  ## HTTP verbs
Os HTTP verbs (métodos HTTP) são ações que indicam a intenção do cliente ao interagir com um recurso na web. Cada verbo representa uma operação específica sobre o recurso identificado pela URL. 

  ## HTTP Status Code
  
Os códigos de status HTTP são indicadores numéricos fornecidos pela resposta do servidor para informar ao cliente o resultado da requisição HTTP. Eles ajudam a entender o estado da comunicação entre o cliente e o servidor.

AUTOR DO RESUMO: Cauã Victor Guedes Alves - 01588771
  
