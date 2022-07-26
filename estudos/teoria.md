# JQuery

- Usando o JQuery hospedado no CDN do Google:

    ~~~html
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"> </script>
    ~~~
  
- Sintaxe Básica

    ``` $(selector).action() ```
    
- Documento "carregado"

    - Jeito 1:

        ~~~javascript
        $(document).ready(function () {
            // jQuery methods go here...
        });
        ~~~

    - Jeito 2:

        ~~~javascript
        $(function () {
            // jQuery methods go here...
        });
        ~~~
   
