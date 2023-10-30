<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 11 
# Actividad: Propiedades CSS, SeudoClases, SeudoElementos y Reglas

<!-- Su documentación aquí -->
##Archivo HTML

```java  
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body >
    
    <div class="contenedor">
         este es un  titulo 

    </div>
    <div class="h1"> 
        Este es otro titulo de ejemplo
    </div>
    <div class="p">
        Otro titulo de ejemplo
    </div>
</body>
</html>
```
##Archivo CSS

```java
.contenedor {
    background-color: blueviolet;
    width: 50%;
    height: 50vh;
    margin: 30px;
    padding: 30px;
    font-family: sans-serif;
    font-size: 16px;
    border: 1px solid black;
  }
  
  .h1 {
    background-color: brown;
    width: 50%;
    height: 100px;
    margin: 10px auto;
    padding: 20px;
    font-family: 'Times New Roman', serif;
    font-size: 24px;
    font-weight: bold;
    border-width: 20px;
    border-style: dashed;
    border-color: blueviolet;
  }
  
  .p {
    background-color: red;
    float: left;
    width: 50%;
    height: 100px;
    margin: 10px;
    padding: 20px;
    background-image: url(ladygaga.jpg); 
    background-repeat: repeat-y;
    background-position: center;
    font-style: italic;
    font-variant: small-caps;
  }
```





