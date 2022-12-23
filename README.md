# Vacunacion

Practica CSS3 de los temas vistos en el **LauncherLATAM**, el cual se tenia que clonar la página que esta en el siguiente enlace [Link](https://github.com/Launch-X-Latam/MisionFrontEnd/blob/main/03%20-%20CSS/practica/landingVacunaci%C3%B3n.png) by [Adhiari Subekti](https://dribbble.com/Adhiari_is).

Debe tener los siguientes requisitos:

* Maquetación del sition con HTML
* Estilos con CSS (Lo más acercado posible, pueden ser otras imágenes, íconos o colores).

---

Se implemento un nav con el estilo sticky

```HTML
        <nav class="item0">
                    <a href="#">Database</a>
                    <a href="#">Education</a>
                    <a href="#">News</a>
                    <a href="#">Regulation</a>
                    <a href="#">Hoax Buster</a>
        </nav>
```

```CSS
.container{
    position: sticky;
}
.item0 a{
    color: #585252;
    margin: 1rem 0rem 1rem 2rem;
    text-decoration: none;
    font-weight: bold;
    font-size: 20px;

    padding: 5px 30px;
    width: 80px;
    vertical-align: middle;
    transition-duration: 0.5s;
}
```

Así como cambios en el scrool para que tenga un estilo personalizado de color azul:

```CSS
body::-webkit-scrollbar{
    width: 10px;
    background: #021B79;
}
body::-webkit-scrollbar-thumb{
    background: rgba(255, 255, 255, 0.2);
    border-radius: 10px;
    border-right: 2px solid #021B79;
}
```

Se logro el objetivo esperado, Se recomienda mejorar y prácticar en el responsive...

[link](https://hydr0bius.github.io/Vacunacion/) de la práctica.
