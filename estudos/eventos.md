# JQuery - Eventos

- Click()

    ~~~html
    <script>
        $(document).ready(function () {
            $("p").click(function () {
                $(this).hide();
            });
        });
    </script>
    
    <p>Teste 1</p>    
    ~~~
 
 - Dblclick()

    ~~~html
    <script>
        $(document).ready(function () {
            $("p").dblclick(function () {
                $(this).hide();
            });
        });
    </script>
    
    <p>Teste 1</p>    
    ~~~
    
- Mouseenter()

    ~~~html
    <script>
        $(document).ready(function () {
            $("p").mouseenter(function () {
                alert("Olá");
            });
        });
    </script>
    
    <p>Teste 1</p>
    ~~~
    
- Mouseleave()

    ~~~html
    <script>
        $(document).ready(function () {
            $("p").mouseleave(function () {
                alert("Até mais");
            });
        });
    </script>
    
    <p>Teste 1</p>
    ~~~
    
- Mousedown()

    ~~~html
    <script>
        $(document).ready(function () {
            $("p").mousedown(function () {
                alert("Mousedown");
            });
        });
    </script>
    
    <p>Teste 1</p>
    ~~~
    
- Mouseup()

    ~~~html
    <script>
        $(document).ready(function () {
            $("p").mouseup(function () {
                alert("Mouseup");
            });
        });
    </script>
    
    <p>Teste 1</p>
    ~~~    
    
- Hover()

    > - Combina as funções mouseenter() e mouseleave()

    ~~~html
    <script>
        $(document).ready(function () {
            $("p").mousehover(
                function () {
                    alert("Entrou");
                },
                function () {
                    alert("Saiu");
                });
        });
    </script>

    <p>Teste 1</p>
    ~~~
    
- Focus()

    ~~~html
    ~~~  
    
- Blur()

    ~~~html
    ~~~    
    
- On()

    ~~~html
    ~~~    
    
    
    
    
    
