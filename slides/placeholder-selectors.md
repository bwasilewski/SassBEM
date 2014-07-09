## Placeholder Selectors

Sass selectors that only compile if extended.

Inherit styles from a "silent" selector. Override as necessary.

```css
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

<aside class="notes">
    <ul>
        <li>Disclaimer: this is only MY approach - there are others</li>
        <li>Use placeholder ("silent") selectors</li>
        <li>Not compiled unless extended by another selector</li>
    </ul>
</aside>
