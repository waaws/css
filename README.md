

# Si



#### Usar clases 
```css
/* Componente  */
.header{
  height:60px;
} 

/* Elemento interno */
.header__logo{
  width:100px;
} 

/* Modificador */
.header--inverse{
  color:white;
  background-color:black;
} 

```

**Ojo!** Hay que estar atentos a los elementos internos ya que es probable que muchos se conviertan en componentes y está super bien.

#### Componentizar

```css
/* Ejemplos */
.header{}
.footer{}
.banner{}
.slider{}
.product-thumnail{}
.products-grid{}
.product-detail{}
.product-image-slider{}
.about-info{}
```

#### Usar flexblox

https://css-tricks.com/snippets/css/a-guide-to-flexbox/

```css
.header{
  display:flex;
  justify-content:space-between;
} 
.header__logo{
}
.header__menu{
  flex:1;
}

```

# No :(

#### Usar IDs
```css
#header{
  height:60px;
} 
```

#### Usar Float 
... a menos que sea este el caso

![alt tag](http://www.axure.com/c/attachments/forum/7-0-newbie-questions/3330d1393251182-text-float-figure016.gif)

```css
.header__logo{
  float:left;
} 
```

#### Usar subclases
```css
.header .logo{
  height:60px;
} 
```

- usar clases ( .header{} )
- 

# Naming convention

####block__element--modifier

Basado en http://getbem.com/naming/
