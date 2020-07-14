## Read: 08 - More CSS Layout
**Notes:**
- ```<div>``` elements are often used as containing elements to group together sections of a page. Exaample:

```
<body>
<div id="header">
 <h1>Logo</h1>
 <div id="nav">
 <ul>
 <li><a href="">Home</a></li>
 <li><a href="">Products</a></li>
 </ul>
 </div>
</div>
<div id="content">
 <div id="feature">
 <p>Feature</p>
 </div>
 <div class="article column1">
 <p>Column One</p>
 </div>
 <div class="article column2">
 <p>Column Two</p>
 </div>
 <div class="article column3">
 <p>Column Three</p>
 </div>
</div>
<div id="footer">
 <p>&copy; Copyright 2011</p>
</div>
</body>
```

- Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.
- The float property moves content to the left or right of the page and can be used to create multi-column layouts. (Floated items require a defined width.)
- Pages can be fixed width or liquid (stretchy) layouts.
- Designers keep pages within 960-1000 pixels wide, and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling).
- Grids help create professional and flexible designs.
- CSS Frameworks provide rules for common tasks.
- You can include multiple CSS files in one page.