# JQuery - Seletores

> - Alguns seletores
>   - ``` $("*") ``` - todos elementos
>   - ``` $(this) ``` 
>   - ``` $("p.minhaClasse") ```
>   - ``` $("p:first") ```
>   - ``` $("ul li:first") ``` - primeiro li da primeira ul
>   - ``` $("ul li:first-child") ``` - primeiro li de todas ul
>   - ``` $("[href]") ``` - todos com atributo href
>   - ``` $("a[target='_blank']") ``` - todos <a> com atributo target igual a _blank
>   - ``` $("a[target!='_blank']") ``` 
>   - ``` $(":button") ``` - todos button e input type="button"
>   - ``` $("tr:even") ``` - todos tr pares
>   - ``` $("tr:odd") ``` - todos tr impares

## Exemplos

- TAG

    ~~~html
    $(document).ready(function () {
        $("p").click(function () {
            $(this).hide();
        });
    });
    ~~~

- Classe

    ~~~html
    $(document).ready(function () {
        $(".myClass").click(function () {
            $(this).hide();
        });
    });
    ~~~ 

- Id

    ~~~html
    $(document).ready(function () {
        $("#myId").click(function () {
            $(this).hide();
        });
    });
    ~~~
  
- Ocultando TAG e Classe

    ~~~html
    <script>
        $(document).ready(function () {
            $("button").click(function () {
                $(".minhaClasse").hide();
            });
        });
    </script>

    <button>Click</button> <br />
    <p class="minhaClasse">Meu texto</p>
    ~~~    
    
    
