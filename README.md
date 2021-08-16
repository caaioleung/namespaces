<img alt="CSS" src="img/css.png" align="right" width="64" height="64">

# Namespaces

## Base

**Seleciona o utilitário**
<br>
![Seleciona o utilitário](img/index.png)
```html
<span class="u-bold">Site</span>
```
![Seleciona o utilitário](img/utilities.png)
```css
.u-bold {
  /* Utilitário */
}
```

## Escopo

**Seleciona o escopo**
<br>
![Seleciona o escopo](img/index2.png)
```html
<header id="s-header">
  <!-- Cabeçalho -->
</header>
```
![Seleciona o escopo](img/s-header.png)
```css
#s-header {
  /* Escopo */
}
```

## Componente

**Seleciona o componente**
<br>
![Seleciona o componente](img/index3.png)
```html
<div class="c-alert">
  <!-- Alerta -->
</div>
```
![Seleciona o componente](img/c-alert.png)
```css
.c-alert {
  /* Componente */
}
```

## Escopo

**Seleciona o estado**
<br>
![Seleciona o estado](img/index4.png)
```html
<div class="c-alert is-success">
  <!-- Alerta -->
</div>
```
![Seleciona o estado](img/is-success.png)
```css
.is-success {
  /* Estado */
}
```

## Tema

**Seleciona o tema**
<br>
![Seleciona o tema](img/index5.png)
```html
<body id="t-default">
  <header id="s-header">
    <!-- Cabeçalho -->
  </header>
</body>
```
![Seleciona o tema](img/t-default.png)
```css
#t-default #s-header {
  /* Tema */
}
```
