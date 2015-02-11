# Calc Grid

CSS and Sass provided, not sure if the Sass will work just yet. I haven't used it in a project at this stage. Mixin's may break

This grid focuses heavily on consistent gutters and margins in a responsive environment. Most flexible grids use percentages for the spacing, but these use a fixed ( relative ) value.

I would recommend to use the Mobile-First: Base Styles, and insert this code CSS into the document, or add the Sass file in the partial.

## HTML Structure

```
<main class="wrapper">

  <article class="col-2 cf">
      <h1>Column Two</h1>
      <section><h3>Hello</h3><p>Sed posuere consectetur est at lobortis.</p></section>
      <section><h3>Hello</h3><p>Sed posuere consectetur est at lobortis.</p></section>
  </article>

  <article class="col-3 cf">
      <h1>Column Three</h1>
      <section><h3>Hello</h3><p>Sed posuere consectetur est at lobortis.</p></section>
      <section><h3>Hello</h3><p>Sed posuere consectetur est at lobortis.</p></section>
      <section><h3>Hello</h3><p>Sed posuere consectetur est at lobortis.</p></section>
  </article>

  <article class="col-4 cf">
      <h1>Column Three</h1>
      <section><h3>Hello</h3><p>Sed posuere consectetur est at lobortis.</p></section>
      <section><h3>Hello</h3><p>Sed posuere consectetur est at lobortis.</p></section>
      <section><h3>Hello</h3><p>Sed posuere consectetur est at lobortis.</p></section>
      <section><h3>Hello</h3><p>Sed posuere consectetur est at lobortis.</p></section>
  </article>

  <article class="col-5 cf">
      <h1>Column Three</h1>
      <section><h3>Hello</h3><p>Sed posuere consectetur est at lobortis.</p></section>
      <section><h3>Hello</h3><p>Sed posuere consectetur est at lobortis.</p></section>
      <section><h3>Hello</h3><p>Sed posuere consectetur est at lobortis.</p></section>
      <section><h3>Hello</h3><p>Sed posuere consectetur est at lobortis.</p></section>
      <section><h3>Hello</h3><p>Sed posuere consectetur est at lobortis.</p></section>
  </article>

</main>
```