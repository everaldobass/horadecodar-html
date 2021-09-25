# Oque é HTML
- Acrônimo para Hypertext Matkup Languagem;
- Uma linguagem para estruturar o layout das páginas web;
- Não podemos realizar: if/else, loops, funções
- Faz parte da triade: HTML, CSS, JS;
- Pode ser executada diretamente no navegador, não precisa de um setup;
- Toda página web tem na sua composição HTML;

### O que forma a estrutura?
- Vamos criar elementos que são parecidos com os do word, onde estruturamos um texto, exemplo:
- Títulos;
- Paragráfos;
- Listas;
- Tabelas;
- Imagens;

### Como executar HTML
- Para Executar HTML basta um navegador;
- Vamos criar o no código em algum editor, sugiro o VS Code;
- Salvar o arquivo do projeto com a extensão .html;
- E abrir este arquivo pelo navegador, copiando o seu caminho relativo;
- Vamos para a prática;

### Oque são tags?
- Os elementos do html são escritos através de tags;
- Temos uma sintaxe semelhante para quase todas as tags;
- Sintaxe é uma forma de como é codigicado algo em uma linguagem de programação;
- Tag <p> de Abertura e de Fechamento </p>;
Exemplo:
<p>Paragráfo</p>
<h1>Titúlo<h1>

### Os atributos do HTML
- Atributos são como opções especiais para configurar determinadas tags;
```
 <a href="https://www.google.com.br/" target="_blank">Ir para Página do Google</a>
```
- Esta tag gera um elemento clicável, que nos leva até uma outra página;
- E o link desta página é determinada pelo atributo href;

### Encadeamento (Nesting)
- Encadeamento, também chamado de nesting, é quando adicionamos um elemento dento de outro;
- Uma técnica importante do HTML, para criar sessões, exemplo:

```
<div>
    <h1> Meu título </h1>
    <p> Meu paragráfo </p>
</div>

```
- Aqui temo uma div com um titulo e uma páragrafo, ambos encadeados;


### Tags sem fechamento
- Há tags que não possuem fechamento;
- Geralmente é quando ela não tem conteúdo;
- Um exemplo é a imagem, veja:
```
  <div>
    <h3> Imagem</h3>
    <img src="https://c0.wallpaperflare.com/preview/920/519/697/abstract-php-c-analytics.jpg" alt="wallpaperflare">
    </div>
```
- Os atributos configuram a tag completamente;
- Inserindo o caminho(src)e uma descrição(alt)

### Estrutura básica do HTML
- Todo documento de HTML tem uma estrutura muito semelhante, composta por tags, exemplo:
```
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Título </title>
</head>
<body>

    <h1>Conteúdo do Site</h1>
 
</body>
</html>
```
- Comentários em HTML
```
 <!------Comentários em HTML------------>
```