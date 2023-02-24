# Atividade em Sala/Homework = Build a web site with SCSS and FlexBox 

## Enunciado

A atividade consite em seguir o [tutorial de SCSS](https://www.youtube.com/watch?v=Zz6eOVaaelI), criar o app junto com o professor e depois implementar uma abordagem arquitetural dentre as expostas em sala de aula. Deve ser entregue o código no Github, juntamente com um arquivo Readme.md, explicando o porque da abordagem arquitetural escolhida.

## Arquitetura escolhida

Para realizar esse trabalho, foi selecionada a arquitetura BEM, visto que ela é uma boa opção de estilização juntao ao SASS.

Para poder utilizá-la, foi alterado o arquivo HTML, o arquivo SASS do `header` foi alterado para `hello-card`.

Um ponto negativo observado, foi que o `@extend` não interage bem com os itens aninhados utilizando o operador `&`, mas, quando utilizando diretamente a tag `button` funciona perfeitamente.
