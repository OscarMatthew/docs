# [HTML][CSS] Logo Limits

## HTML

```html
<div class="logo">
  <a href="#">
    <img alt="" src="images/logo2x.png">
    <!-- Logo Text Fallback if No <img> -->
  </a>
</div>
```

## CSS

```css
/* ======= Primary Nav - Mobile+ ======= */

/*Logo*/

.logo {
  margin: 10px 0; /*Change according to design*/
  max-height: 40px;
}

.logo img {
  max-width: 120px;
  max-height: 40px;
}

.logo a {
    /*If user does not provide logo, then the text of the  title of their site will go in the <a> element in place of the <img>, so be sure to style to a plain text (non-image) logo*/
    font-family: ;
    font-size: ;
    text-decotration: none;
    color: ;
}

/* ======= Primary Nav - Tablet+ ======= */

@media (min-width: 768px) {

  .logo {
    margin: 22px 0; /*Change according to design*/
  }

  .logo img {
    max-width: 200px;
  }

}

/* ======= Primary Nav - Desktop+ ======= */

@media (min-width: 992px) {

  .logo {
    margin: 22px 0; /*Change according to design*/
    max-height: 50px;
  }

  .logo img {
    max-width: 200px;
    max-height: 50px;
  }

}
```