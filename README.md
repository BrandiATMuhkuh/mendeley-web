# mendeley-web
I really like mendeley desktop but honestly, we can do better. I'll try to create a web client for mendeley. The main focus is on annotations. This will probably be done by combining [pdf.js](http://mozilla.github.io/pdf.js/) and [annotator.js](http://annotatorjs.org/). A example of pdfjs + annotatorjs can already be found here: https://github.com/hypothesis/pdf.js-hypothes.is.

http://dev.mendeley.com/methods/?shell#introduction

## future
Since this is a future project and I like to learn new things every time I so something I have decided to use "future" tools. Lets call it ES6. On the server I will use [babel](https://babeljs.io/) and cliente (not sure yet) [aurelia](http://aurelia.io/). 


## Techniques
To select text we can use the `window.getSelection().toString()`. See [Mozilla Docs](https://developer.mozilla.org/en-US/docs/Web/API/Window.getSelection): 

## Interaction
 * To mark text
  * Mark a text
  * Click the mark button
 * To add a note
  * Click add note
  * Click somewhere on the text
  * Note opens and note symbol will be added
