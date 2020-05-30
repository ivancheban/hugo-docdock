+++
title = "Markdown Experiments"
description = ""
+++

## Code Highlighting
This is an example of code highlighting.

```css
.sey-item {
  cursor: pointer;
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
  padding: 7px;
```

```js
Reveal.addEventListener( 'ready', function() {

	QUnit.module( 'Markdown' );

	test( 'Vertical separator', function() {
		strictEqual( document.querySelectorAll( '.reveal .slides>section>section' ).length, 2, 'found two slides' );
	});

	test( 'Horizontal separator', function() {
		strictEqual( document.querySelectorAll( '.reveal .slides>section' ).length, 2, 'found two slides' );
	});

	test( 'Language highlighter', function() {
		strictEqual( document.querySelectorAll( '.hljs-keyword' ).length, 1, 'got rendered highlight tag.' );
		strictEqual( document.querySelector( '.hljs-keyword' ).innerHTML, 'var', 'the same keyword: var.' );
	});


} );

Reveal.initialize();
```

## Tables
This is an example of a table.

| Column 1 | Column 2 | Column 3 |
| -------- |:--------:|:--------:|
| Text     |   Text   |   Text   |
| Text     |   Text   |   Text   |
| Text     |   Text   |   Text   |



### YouTube
This is an example of YouTube video.

<iframe width="560" height="315" src="https://www.youtube.com/embed/lVXziMFEqX0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


<iframe width="560" height="315" src="https://www.youtube.com/embed/bIZsnKGV8TE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
