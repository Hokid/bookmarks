### DOM
`innerHTML` > [Читать](http://innerhtml.ru/)

### MySQL
Индексы MySQL > [Читать](http://ruhighload.com/post/%D0%A0%D0%B0%D0%B1%D0%BE%D1%82%D0%B0+%D1%81+%D0%B8%D0%BD%D0%B4%D0%B5%D0%BA%D1%81%D0%B0%D0%BC%D0%B8+%D0%B2+MySQL)

### CSS
Про специфичность селекторов > [Читать](http://sixrevisions.com/css/css-specificity/)

### input[type="number"]

Убрать стрелки +/- число(Mozilla, Webkit).

    input[type="number"] {
      -moz-appearance: textfield;
      margin: 0;
    }
    
    input[type="number"]::-webkit-inner-spin-button,
    input[type="number"]::-webkit-outer-spin-button {
      -webkit-appearance: none;
      margin: 0;
    }

