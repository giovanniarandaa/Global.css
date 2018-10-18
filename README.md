# CSS Global

El *CSS Global* contiene clases hechas para facilitar al maquetador.

Contiene margins, paddings, fonts, etc.

## Margin

Las clases de margin esta dividida en 2 letras y el número de pixeles:

* mg = margin
* mt = margin-top
* mb = margin-bottom
* ml = margin-left
* mr = margin-right

*Número de pixeles (px)*: 0, 5, 10, 15, 20, 30, 40, 50, 60, 70, 80, 90, 100.

*Ejemplo:*

```css
.mg0{
  margin: 0px !important;
}

.mt5{
  margin-top: 5px !important;
}

.mb10{
  margin-bottom: 10px !important;
}

.ml15{
  margin-left: 15px !important;
}

.mr20{
  margin-right: 20px !important;
}
```

**Los números más grandes son mas relevantes que los números pequeños.**

*Ejemplo: En este ejemplo tomará primero ml10 que ml5*

```html
<div class="ml5 ml10"></div>
```

Tomará en cuenta primero **ml10**.

## Padding

Las clases de padding esta dividida en 2 letras y el número de pixeles:

* pd = padding
* pt = padding-top
* pb = padding-bottom
* pl = padding-left
* pr = padding-right

*Número de pixeles (px)*: 0, 5, 10, 15, 20, 30, 40, 50, 60, 70, 80, 90, 100.

*Ejemplo:*

```css
.pg0{
  padding: 0px !important;
}

.pt5{
  padding-top: 5px !important;
}

.pb10{
  padding-bottom: 10px !important;
}

.pl15{
  padding-left: 15px !important;
}

.pr20{
  padding-right: 20px !important;
}
```

**Los números más grandes son mas relevantes que los números pequeños.**

*Ejemplo: En este ejemplo tomará primero pl10 que pl5*

```html
<div class="pl5 pl10"></div>
```

## Fonts
Estas clases nos ayudan ajustar los textos, en base al tamaño principal. Se miden con **rem**.

* Extra small
* Small
* Normal
* Big
* Extra big

*Prototipo:*

```css
.f_extra_small{
    font-size: .5rem !important;
}

.f_small{
    font-size: .8rem !important;
}

.f_normal{
    font-size: 1rem !important;
}

.f_big{
    font-size: 1.2rem !important;
}

.f_extra_big{
    font-size: 1.5rem !important;
}
```

## Width

Estas clases nos ayudan ajustar el ancho del elemento por medio de (*%*).

*Número de porcentaje (%)*: 0, 5, 10, 15, 20, 30, 40, 50, 60, 70, 80, 90, 100.

*Ejemplo*

```css
.w0p{
  width: 0% !important;
}

.w10p{
  width: 10% !important;
}

...

.w100p{
  width: 100% !important;
}
```
**Los números más grandes son mas relevantes que los números pequeños.**

*Ejemplo: En este ejemplo tomará primero w80p que w10p*

```html
<div class="w10p w80p"></div>
```

## Position

En estas clases forzaran a tener una posición.

* Relative
* Absolute
* Relative

*Prototipo*

```css
.pos_fix{
    position: fixed !important;
    z-index: 1;
}
.pos_abs{
    position: absolute !important;
    z-index: 1;
}
.pos_rel{
    position: relative !important;
    z-index: 1;
}
```

## Font styles

Estas clases forzan a tener estilos.

* Bold
* Italic

*Prototipo*
```css
.bold{
    font-weight: bold !important;
}

.italic{
    font-style: italic !important;
}
```

## Extras

Clases extras.

* Cursor: Pointer.

```css
.pointer{
    cursor: pointer;
}
```
