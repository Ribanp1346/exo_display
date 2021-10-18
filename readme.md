# &#128526; Cours sur les display CSS
Code fait en classe

```css
    header h1{
    text-align: center;
    background-color: rgb(100,5,5);
    line-height: 6.5rem;
    font-weight: normal;
    color: #fff;
}
main{
    max-width: 80.0rem;
    margin: 5.0rem auto;
    border: solid .1rem #222;
}
main ul li img{
    display: block;
    width: 100%;
}
main ul{
    padding: 1.0rem;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-gap: 1rem;
}
main ul li:last-child{
    grid-column: 1 / 5;
    grid-row: 3;
}
footer{
    text-align: center;
}
```
## Liste des display
* display block
* display inline-block
* display grid

## Composition du répertoire
* index.html
* css/style.css
* asset/
* [E-mail](ewan.angoujard@gmail.com)