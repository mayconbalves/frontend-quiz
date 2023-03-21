## Questões básicas de HTML5

Essas são perguntas bem básicas que vão prover um conhecimento para quem está iniciando
em algum projeto de frontend ou que está começando na área de desenvolvimento web. Não pule
nenhuma etapa se você está iniciando, é bem importante você criar uma boa base e para te ajudar
nessa trilha, além das perguntas e respostas, em toda pergunta será incluso alguns links para
complementar cada pergunta e resposta.

### Qual é a estrutura básica do HTML5 ?

<details>
  <summary>Veja a resposta</summary>
  
```html
<!DOCTYPE html>
<html lang="">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width" />
  <title>Titulo do documento</title>
</head>
  
<body>
</body>
  
</html>
```
  
  Dentro dessa estrutura temos algumas explicações vamos lá
  
  <details>
    <summary>Tag !DOCTYPE</summary>  
    Apesar da sintaxe parecida, o DOCTYPE não é uma tag do HTML. O DOCTYPE HTML é uma declaração para
    informar ao navegador qual é a versão do HTML (nesse caso a versão 5) utilizada no arquivo.
  </details>
  
  <details>
    <summary>Tag HTML</summary>  
    Representa a raiz de um documento `HTML`, ou seja, ele é o primeiro elemento dentro de um arquivo `HTML`.
    Dentro de todas as tags podemos receber atributos no exemplo acima usamos o `lang` dentro da tag `HTML` é
    um exemplo de atributo. No nosso caso, podíamos passar o valor `pt-br` para informar que o nosso documento `HTML`
    é em português do Brasil.
  </details>
  
  <details>
    <summary>Tag HEAD</summary>  
    Usamos essa tag para adicionar elementos externos, links, scripts de terceiros e também coisas que os browsers irão
    interpretar.
  </details>
  
</details>


