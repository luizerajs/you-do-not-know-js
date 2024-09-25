### O nome JavaScript

Teve varios no início como Mocha, nome que um dos criadores (Brendan Eich) deu. Mas o nome JavaScript ganhou como voto popular no seu lançamento.

A origem vem do objetivo de atrair desenvolvedores Java na época, e a palavra "script" tinha uma conotação para programas leves.

Existem semelhanças entre as linguagens além do nome, pois elas se baseam em linguagens de baixo nível como C (e até certo ponto C++).

Exemplos disso são aberturas de chaves `{}` para indicar o início e fechamento de blocos de código e `;` para finalizar uma declaração.

Mas o nome "JavaScript" fazendo um paralelo a uma empresa, seria o nome fantasia. Por problemas de patentiamento, o nome oficial da linguagem dentro do órgão de padronização da ECMA é **"ECMAScript"**

### A Web governa o JS

Por mais que a linguagem JS esteja se expandindo durantes os anos (navegadores, servidores, robôs, lampadas, etc), a forma como o JS é implementado para navegadores web é, com toda a praticidade, a única realidade que importa.

Então daria para entender que todas as atualizações das especificação do JS, o browser vai entender, certo? Quem dera... rs

Vale lembrar que a especificação do JavaScript define novos comportamentos ou ajustes, mas esses podem não funcionar exatamente da mesma forma nos navegadores. Isso acontece porque os motores de JavaScript dos navegadores têm mais de 20 anos de comportamentos conhecidos, especialmente em casos específicos ou "pegadinhas" da linguagem.

Muitos sites já dependem desses comportamentos antigos, então, se os navegadores mudarem para seguir as novas regras da especificação, alguns sites podem parar de funcionar corretamente. Por isso, os navegadores às vezes preferem manter o comportamento antigo para evitar que o conteúdo da web seja prejudicado.

### Nem tudo é JS

Capítulo bom pois explica que nem tudo que achamos que é Javascript, é de fato. O que acontece é que muito do que utilizamos na Web ou em servidores como NodeJs são APIs fornecidas por eles. Então quando chamamos um `fetch(..)` ou `getCurrentLocation(..)`, isso não são funções especificadas pelo ECMAScript, e sim APIs da Web.

Isso vale pra NodeJS, quando precisamos ler arquivos, importamos dos módulos que eles diponibilizam e chamamos o método `fs.readFile(..)`.

### Muitas faces
