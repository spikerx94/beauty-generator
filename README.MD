# Generator opisów produktowych mrozbike.pl


## Instalacja

Szablon główny

```html
<div class="container__product">
        <div class="container__product__items">
            <!-- WKLEJ PRZED TYM ZNACZNIKIEM BOX UŻYTKOWY -->
        </div>
</div>
```

## BOXY UŻYTKOWE

Napis po lewej/ zdjęcie po prawej stronie
```html
 <!-- Tekst -->
<div class="container__product__items__box">
                <div class="container__product__items__box-text">
                    <h3>Tytuł akapitu</h3>
                    <p>Akapit</p>
                </div>
</div>
 <!-- Zdjęcie -->
<div class="container__product__items__box">
                <div class="container__product__items_box-image">
                    <img src="link do zdjęcia">
                </div>
</div>
```
Napis po prawej/ zdjęcie po lewej stronie
```html 
 <!-- Zdjęcie -->
            <div class="container__product__items__box">
                <div class="container__product__items_box-image">
                    <img src="link do zdjęcia">
                </div>
            </div>
 <!-- Tekst -->
            <div class="container__product__items__box">
                <div class="container__product__items__box-text">
                    <h3>Tytuł akapitu</h3>
                    <p>Akapit</p>
                </div>
            </div>
```
Zdjęcie na całą szerokość
```html 
 <!-- Zdjęcie -->
<div class="container__product__items__box__full">
                <div class="container__product__items__box__full-image">
                    <img  src="link do zdjęcia">
                </div>
</div> 
```

## Uwagi

Jeśli w sekcji nie ma akapitu należy usunąć cały tag <h3></h3>
