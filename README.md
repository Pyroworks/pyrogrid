# Pyroworks - pyrogrid
The grid of Pyroworks (https://pyro.works) in SCSS

See: https://pyro.works/dev/style-guide/css-utilities#pyrogrid

## Examples
### Example 1: Navigation and main area

```html
<div class="grid">
    <main column="2/4 last around" offset="1/4" rel="main">
        <section class="container">
            <h1>Main area</h1>
            <p>This is the main area.</p>
        </section>

        <section class="container">
            <h1>Another container</h1>
            <p>More containers are possible.</p>

            <div class="articles grid">
                <article>
                    <h2>Grid in a grid</h2>
                    <p>A grid inside a grid is also possible.</p>
                </article>
        </section>
    </main>

    <div column="1/4 first top">
        <nav class="container" rel="navigation">
            <ul>
                <li>
                    <a href="#page1" title="Page 1">Page 1</a>
                </li>
                <li>
                    <a href="#page2" title="Page 2">Page 2</a>
                </li>
                <li>
                    <a href="#page3" title="Page 3">Page 1</a>
                </li>
            </ul>
        </nav>
    </div>
</div>
```

### Example 2: Using all widths and offset

```html
<div class="grid">
    <div column="full">
        <div class="container">full 1/1</div>
    </div>

    <div column="2/3">
        <div class="container">2/3</div>
    </div>
    <div column="1/3">
        <div class="container">1/3</div>
    </div>

    <div column="1/4" offset="1/4">
        <div class="container">1/4</div>
    </div>
    <div column="1/2">
        <div class="container">1/2</div>
    </div>

    <div column="1/4">
        <div class="container">1/4</div>
    </div>
    <div column="3/4">
        <div class="container">3/4</div>
    </div>

    <div column="1/5">
        <div class="container">1/5</div>
    </div>
    <div column="4/5">
        <div class="container">4/5</div>
    </div>

    <div column="2/5">
        <div class="container">2/5</div>
    </div>
    <div column="3/5">
        <div class="container">3/5</div>
    </div>
</div>
```

### Example 3: Ordering and aligning

```html
<div class="grid">
    <div column="2/3 last">
        <div class="container">last</div>
    </div>
    <div column="1/3 first">
        <div class="container">first</div>
    </div>
</div>

<div class="grid" style="height: 100px;">
    <div column="1/3 top">
        <div class="container">aligned top</div>
    </div>
    <div column="1/3 middle">
        <div class="container">aligned middle</div>
    </div>
    <div column="1/3 bottom">
        <div class="container">aligned bottom</div>
    </div>
</div>

<div class="grid reverse">
    <div column="1/4 around" offset="1/4">
        <div class="container">space around with offset of 1/4, and will show at last</div>
    </div>
    <div column="1/4">
        <div class="container">1/4</div>
    </div>
    <div column="1/4">
        <div class="container">1/4</div>
    </div>
</div>
```

# License
GPL-3
