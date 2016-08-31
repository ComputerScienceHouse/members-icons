#CSH Members Portal Icons <img src="https://assets.csh.rit.edu/uploads/csh-icons8.svg" height="20px">

A CSS sprite sheet of icons for the CSH member's portal. Now in SVG!

Usage
-----
1) Download the project and add the `css` and `img` directories to your project.

2) Include either of the .css files on your page. This will add the base styles and load in the sprite sheet.

```html
<link rel="stylesheet" href="./members-icons/css/members_icons.css">
```

3) Add a bit of CSS to your project to style/size the icons.

```css
/* Make icons 64x64 pixels and centered in their containers */
.icon {
  width: 64px;
  height: 64px;
  margin: auto;
}
```

4) Add the following markup (or something similar) to add an icon to the page. Replace "icon-drink" with the class name of the icon you want.

```html
<div class="icon-box">
  <div class="icon icon-drink"></div>
</div>
```