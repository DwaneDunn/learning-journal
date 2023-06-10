#### Prettier

https://prettier.io/docs/en/ignore.html

JavaScript
// prettier-ignore

JSX

<div>
  {/* prettier-ignore */}
  <span     ugly  format=''   />
</div>

HTML

<!-- prettier-ignore -->
<div         class="x"       >hello world</div            >

<!-- prettier-ignore-attribute -->
<div
  (mousedown)="       onStart    (    )         "
  (mouseup)="         onEnd      (    )         "
></div>

<!-- prettier-ignore-attribute (mouseup) -->
<div
  (mousedown)="onStart()"
  (mouseup)="         onEnd      (    )         "
></div>

CSS

/_ prettier-ignore _/
.my ugly rule
{

}

Markdown

<!-- prettier-ignore -->
Do   not    format   this
