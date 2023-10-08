# JavaScript

JavaScript is a programming language that is primarily used for creating interactive web pages. It is a high-level, dynamic, and interpreted language that is executed on the client-side.

## History of JavaScript

JavaScript was created by Brendan Eich in just 10 days in May 1995. It was originally called Mocha, then changed to LiveScript, and finally renamed to JavaScript. JavaScript was first introduced in Netscape Navigator 2.0 in September 1995. Since then, it has evolved significantly and is now supported by all modern web browsers.

## How to Use JavaScript

To include JavaScript in an HTML file, you can use the `<script>` tag. Here's an example:
```
<!DOCTYPE html>
<html>
    <head>
        <title>My Web Page</title>
    </head>
    <body>
        <h1>Hello, world!</h1>
        <script>
            alert('Hello, world!');
        </script>
    </body>
</html>
```

## Vanilla JS
```// Define a variable
var myVariable = "Hello, world!";

// Log the variable to the console
console.log(myVariable);
```


<!DOCTYPE html>
<html>
    <head>
        <title>My Web Page</title>
    </head>
    <body>
        <h1 id="myHeading">Hello, world!</h1>
        <button onclick="changeText()">Click me</button>
        <script>
            function changeText() {
                document.getElementById("myHeading").innerHTML = "Hello, Vanilla JS!";
            }
        </script>
    </body>
</html>
