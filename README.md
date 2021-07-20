```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <title>CKEditor 5 Framework – Implementing a simple widget</title>
    </head>
    <body>
        <div id="ed">
            <p>Editor content goes here.</p>
        </div>

        <div id="ed1">
            <p>Editor content goes here.</p>
        </div>

        <script src="../dist/bundle.js"></script>
        <script>
            window.editor.show("#ed", ["Valor 1", "Valor 2"], "Tips");
            window.editor.show("#ed1", ["Valor 1", "Valor 2", "Valor 3"]);            
        </script>
    </body>
</html>
```