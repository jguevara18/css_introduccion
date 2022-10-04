# Desafío: CSS

## Nombre de Desafío: css_background

## Instrucciones

I. Establezca el color de fondo de la página en rojo.

<style>
body{
background-color: red;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>
```

II. Establezca el color de fondo de la página en rojo, usando un estilo en línea.


<body style="background-color: red;>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>
```

III. Establezca el color de fondo del elemento `<h1>` en "azul claro".


<style>
h1 {
  background-color: lightblue;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>


IV. Haz que la imagen de fondo se repita solo verticalmente.


<style>
body {
  background-image: url("img_tree.png");
  background-repeat:repeat-y;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>
```

V. Establezca el color de fondo en rojo cuando pase el mouse sobre un enlace.


<style>
 a: hover {
  background-color: red;
}
</style>

<body>

<h1>This is a header.</h1>
<p>This is a paragraph.</p>
<a href="https://larnu.app/#/">This is a link.</a>

</body>


VI. Establezca el color de fondo en rojo, cuando pase el mouse sobre elementos con la clase "maestro".


<style>
.master: hover {
background-color: red;
}
</style>

<body>

<h1 class="master">This is a header.</h1>
<p class="master">This is a paragraph.</p>
<p>This is a paragraph.</p>

</body>
```

III. Establezca el color de fondo en rojo, de cualquier elemento `<p>` que sea el primer hijo de cualquier elemento.


<style>
p:nth-child(1) {
background-color: red;
</style>

<body>

<p>This is a paragraph.</p>
<p>This is a paragraph.</p>

</body>
```

VI. Establezca el color de fondo en rojo, de cualquier elemento `<input>` que esté enfocado.


<style>
input:focus {
background-color: red;
}
</style>

<body>

<form>
  Name:
  <input type="text" name="fname">
  Age:
  <input type="text" name="age">
</form>

</body>
```

VII. Establezca el color de fondo en rojo, de la primera línea del párrafo.


<head>
<style>
.intro:first-line {
background-color: red;
}
</style>

<body>

<p class="intro">
In my younger and more vulnerable years
my father gave me some advice that I've
been turning over in my mind ever since.
'Whenever you feel like criticizing anyone,' he told me,
'just remember that all the people in this world
haven't had the advantages that you've had.'
</p>

</body>
```

VIII. Establezca el color de fondo en rojo, para la primera letra del elemento `<p>`.


<style>
.intro:first-letter {
background-color: red;
}
</style>

<body>

<p class="intro">
In my younger and more vulnerable years
my father gave me some advice that I've
been turning over in my mind ever since.
'Whenever you feel like criticizing anyone,' he told me,
'just remember that all the people in this world
haven't had the advantages that you've had.'
</p>

</body>
```

IX. Inserte la imagen "smiley.gif" antes y después de cualquier elemento `<p>`, utilizando los pseudoelementos ::before y ::after.

<style>
 p::before {
  content: url('smiley.gif');
}
 p::after {
  content: url('smiley.gif');
}
</style>

<body>

<p>This is a paragraph.</p>
<p>This is a paragraph.</p>

</body>
```

X. Crear un nuevo archivo llamado `index.html` donde deberás realizar lo siguiente:

```
- Deberá tener un hero banner, es decir, una imagen que cubra todo el viewport
- Deberá tener un titulo denominado:Hero Image hecho por  [Su nombre]
- Deberá tener un parrafo que contenga una descripción lorem
- Deberá contar con un boton el cual dirija a la página de LarnU
- Todos los textos deberán estar centrados y dentro de nuestro hero banner
- Para el uso de html deberemos usar la metodologia BEM
- Añadir estilos a los textos como al boton
```