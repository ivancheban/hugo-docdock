+++
title = "revealjs"
slug = "revealjs"
description = "present content as a reveal.js slide"
+++

This shortcode will format the enclosed markdow to render it with [reveal.js](http://lab.hakim.se/reveal-js/) at runtime (client-side)

Read more on [revealjs github repo](https://github.com/hakimel/reveal.js/#markdown).

## Usage

`revealjs` can use the following named parameters :

* theme
* transition
* controls
* progress
* history
* center


{{%warning title="Important" %}}Even if the enclosed content is a mardown, use `<` shortcode notation instead of the `%` notation {{%/warning %}}

### Content formating and slide delimiters

[read more on this here]({{% relref "page-slide.md"%}})

## Demo


{{<revealjs theme="moon" progress="true">}}

# Use code to build your presentation

___

## Use Markdown syntax

- Turn your markdown file into a slide
- Use RevealJS technology

___

## Create your presentations with Markdown

- No PowerPoint
- Play slides from your browser

---

# Technical writing skills

___

## Show your code

- Open Markdown file
- Present to colleagues

___

## Wrapping up

- Contacts
- Questions

{{</revealjs>}}

## Source :

{{%expand "Show code ..."%}}

```
{{</*revealjs theme="moon" progress="true"*/>}}

# Use code to build your presentation

___

## Use Markdown syntax

- Turn your markdown file into a slide
- Use RevealJS technology

___

## Create your presentations with Markdown

- No PowerPoint
- Play slides from your browser

---

# Technical writing skills

___

## Show your code

- Open Markdown file
- Present to colleagues

___

## Wrapping up

- Contacts
- Questions

{{</*revealjs*/>}}

```

{{%/expand%}}

* [{{%icon "sunglasses" %}} click here to view raw content](https://raw.githubusercontent.com/vjeantet/hugo-theme-docdock/master/exampleSite/content/shortcodes/revealjs.md)