# CSS

## Como Funciona o CSS:



## Tipos de CSS

### CSS Inline
Css que aplicamos diremente na TAG HTML a partir da propriedade Style.

Exemplo:

```html
<header style="background-color: red;">
    <h1>Infinity Store</h1>
    <nav>
        <ul>
            <li><a href="">Inicio</a></li>
            <li><a href="">Promoções</a></li>
            <li><a href="">Camisetas</a></li>
            <li><a href="">Eletrônicos</a></li>
        </ul>
    </nav>
</header>
```

### CSS Interno

```html
<style>
    header {
        color: white;
        background-color: red;
    }
</style>
<header>
    <h1>Infinity Store</h1>
    <nav>
        <ul>
            <li><a href="">Inicio</a></li>
            <li><a href="">Promoções</a></li>
            <li><a href="">Camisetas</a></li>
            <li><a href="">Eletrônicos</a></li>
        </ul>
    </nav>
</header>
```

### CSS Externo

Para utilizar o CSS Externo precisamos criar um arquivo ".css"

style.css
```
````