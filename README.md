# getelementbyclassname
<html>
    <head>
        <title>getElementByClassName</title>
        <script type="text/javascript">
            function changeStyling()
            {
                var element=document.getElementsByClassName("mypara");
                for(var x=0;x<element.length;x++)
                {
                    element[x].style.color="green";
                    element[x].style.bold="p"
                }
            }

        </script>
    </head>
    <body>
        <p>This is paragraph 1</p>
        <p>This is paragraph 2</p>
        <p class="mypara">This is paragraph 3</p>
        <p>This is paragraph 4</p>
        <br>
        <button onclick="changeStyling()">Click Me</button>
    </body>
</html>
