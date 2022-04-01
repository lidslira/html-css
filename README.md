# HTML and CSS
![símbolo do html e css](htmlecss.png)

HTML (*Hypertext Markup Language*) e CSS (*Cascading Style Sheets*) são duas das principais tecnologias para a construção de páginas da Web. Enquanto o **HTML** fornece a estrutura da página, o **CSS** traz o layout (visual e auditivo), para uma variedade de dispositivos. Junto com gráficos e scripts, HTML e CSS são a base da construção de páginas e aplicativos da Web.

## HTML

Seu nome tem origem do inglês _Hyper Text Markup Language_, que significa “linguagem de marcação de hipertexto”. Sim, HTML não é uma linguagem de programação como as demais, e sim de marcação.

Como assim?! 🤔 Bom, imagine uma página web, como essa mesmo do GitHub. É possível perceber que existem diversos elementos separados, como cabeçalho, título, parágrafos, imagens e muitos outros. Toda a organização desses elementos é feita pelo HTML. Ele é utilizado para criar toda a estrutura da página e, para isso, utiliza as famosas *tags* (etiquetas) para sinalizar onde cada tipo de elemento será implementado.

Um exemplo básico de um código HTML é:
> `
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>[Título da página]</title>
    </head>
    <body>
      [o corpo/conteúdo fica aqui]
      <h1>Aqui é como se fosse a manchete da página</h1>
      <p>Esse é um parágrafo.</p> 
    </body>
</html>
` 

Para saber mais um pouco sobre HTML, você pode visitar o [site do desenvolvedor da mozilla](https://developer.mozilla.org/pt-BR/docs/Web/HTML) ou o [site da W3Schools](https://www.w3schools.com/html/)


## CSS

*CSS* (*Cascading Style Sheets* ou Folhas de Estilo em Cascata) é a linguagem para descrever a estilização das páginas da Web, incluindo cores, layout e fontes. 

Ela também permite adaptar a aplicação a diferentes tipos de dispositivos, como telas grandes, telas pequenas, telas de celular dando responsividade a mesma. CSS é independente do HTML e pode ser usado com qualquer linguagem de marcação baseada em XML. 

A separação do HTML do CSS facilita a manutenção de sites.

Esse é um exemplo de um arquivo CSS:
> 
`
body {
  background-color: lightblue;
}

h1 {
  color: white;
  text-align: center;
}

p {
  font-family: verdana;
  font-size: 20px;
}
`

Para saber mais um pouco sobre CSS, você pode visitar o [site do desenvolvedor da mozilla](https://developer.mozilla.org/pt-BR/docs/Web/CSS) ou o [site da W3Schools](https://www.w3schools.com/css/)
