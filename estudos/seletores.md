# JQuery - Seletores

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
