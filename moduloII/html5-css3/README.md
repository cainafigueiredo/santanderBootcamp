# HTML 5

- **Elemento HTML:** Abertura de tag (possivelmente com atributos) + conteúdo + fechamento de tag.

- **Estrutura básica:** Se estiver usando o VSCode, basta digitar html5 e apertar TAB para assim criar toda a estrutura mais rapidamente. 

<!DOCTYPE html>
<html>
    <head>
        <meta>
        <title></title>
    </head>
    <body>
    </body>
</html>

- **Semântica:** <section>, <header>, <article>, <aside>, <footer>, <h1>-<h6>

- **Textos e links:** <h1>-<h6>, <p>, <a> (atributos principais: _href_ e _target_)

- **Imagens:** <img> (atributos principais: _src_ e _alt_). Podemos usar o site [TinyPNG](tinypng.com) para reduzir o tamanho das imagens.

- **Listas:** <ul> (lista não ordenada), <ol> (lista ordenada), <li> (item da lista)

# CSS 3

- **Regras CSS:** Seletores + Declarações. Ex.:

a, p, h1, h3 {
    color: blue;
    font-size: 14px;
}

Nesse caso, os seletores são: a, p, h1 e h3. As declarações são as linhas entre as chaves e são compostas pelo nome da propriedade e pelo seu valor.

- **ID x Classe:** Permite aplicar os estilos a elementos HTML específicos. Exemplos de aplicação de estilos usando *id* e *classes*, respectivamente:

.header {
    padding: 10px;
}

#header {
    padding: 15px;
}

- **Box Model:** O navegador representa cada elemento HTML como uma caixa retangular. Existem 4 áreas: Margin (espaçamento entre elementos), border (circundam o padding e o conteúdo), padding (espaçamento entre a borda e o conteúdo) e content (texto, imagem, vídeo, ...).