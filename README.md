<!DOCTYPE html>
<html>
<head>
    <title>Style LaTeX with CSS</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/3.2.0/es5/tex-mml-chtml.js"></script>
    <style>
        /* Style for LaTeX content */
        .mjx-math {
            font-size: 20px;
            color: darkblue;
        }
        .mjx-mn {
            color: green; /* Numbers */
        }
        .mjx-mi {
            font-style: italic;
            color: red; /* Variables */
        }
    </style>
</head>
<body>
    <p>Here is some styled LaTeX:</p>
    <script type="math/tex">
        E = mc^2
    </script>
</body>
</html>
