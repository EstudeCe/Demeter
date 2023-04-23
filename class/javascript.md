## DOM

A DOM é uma forma padrão de representar um document, que é o nosso código HTML. Com essa forma padrão de representar os nossos elementos, conseguimos realizar alterações utilizando JavaScript, Python, entre outras linguagens. E as alterações serão refletidas para o nosso código HTML.

Dessa forma, utilizamos a manipulação da DOM para realizar as alterações no documento HTML. Permitindo adicionar elementos, alterar, modificar os atributos, entre outras funcionalidades.

## Vinculando o HTML e o código JavaScript

Para realizar o vínculo entre o nosso arquivo JavaScript e o arquivo HTML, vamos adicionar antes de encerrar a tag body, uma tag script. E vamos passar para o atributo src o path do arquivo de scripts da nossa aplicação.

```
  <script src="script.js"></script>
</body>
```

## Acessando os elementos da DOM

Para acessar os elementos da DOM, podemos atribuir esse elemento a uma variável JavaScript, e vamos acessar o document.

```
const button = document.getElementById
const button = document.getElementsByClassName
```
