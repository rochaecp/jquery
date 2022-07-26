# JQuery - Seletores

> - Alguns seletores
>   - ``` $("*") ```
>   - ``` $(this) ```
>   - ``` $("p.minhaClasse") ```
>   - ``` $("p:first") ```
>   - ``` $("ul li:first") ```
>   - ``` $("ul li:first-child") ```
>   - ``` $("[href]") ```
>   - ``` $("a[target='_blank']") ```
>   - ``` $("a[target!='_blank']") ```
>   - ``` $(":button") ```
>   - ``` $("tr:even") ```
>   - ``` $("tr:odd") ```

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
    
    
