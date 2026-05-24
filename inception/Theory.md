### Write a code Hello world program in html
    

        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Namaste React</title>
        </head>
        <body>
            <div id="root">
                <h1>Hello world</h1>
            </div>
        </body>
        </html>



### Write a code Hello world program in JS

```
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Namaste React</title>
    </head>
    <body>
        <div id="root">
            
        </div>
        <script>
        const root = document.getElementById("root");
        const heading = document.createElement("h1");
            heading.innerText = "Namaste React";
            root.appendChild(heading);
        </script>
    </body>
    </html>

```

### Write a code Hello world program in React

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Namaste React</title>
</head>
<body>
    <div id="root">
        
    </div>
    <script crossorigin src="https://unpkg.com/react@18/umd/react.development.js"></script>
    <script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>
    <script>
        const parent = React.createElement("div", {id: "parent"}, 
            React.createElement("div", {id: "child"}, 
                React.createElement("h1", {}, "I am h1 tag"),
                React.createElement("h2", {}, "I am h2 tag")
            )
        );
        const root = document.getElementById("root");
        ReactDOM.render(parent, root);

    </script>
</body>
</html>