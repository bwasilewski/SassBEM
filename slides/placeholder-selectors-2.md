You can also do this:

```css
.nav,
%nav {
    display: block;
    position: absolute;
}

.nav--primary,
.nav--secondary {
    @extend %nav;
}

.nav-secondary {
    display: inline-block;
}
```
Helpful if you want to use .nav.
