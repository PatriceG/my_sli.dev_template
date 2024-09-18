---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: 
# some information about your slides (markdown enabled)

# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true

#enable PDF generation
download: true

title: Presentation Title
class: text-center
---

# Presentation Title

subtitle

presenter name

presenter email

<div class="w-75 h-px bg-gray absolute bottom-5 left-0 text-sm">Menu here&nbsp;&nbsp;|&nbsp;&nbsp;← → to move between slides.
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
---

# Table of Contents

<Toc minDepth="1" maxDepth="1"></Toc>

<!-- import other slides from the slides/ folder -->
---
src: slides/examples.md
---

---

# Learn More

[Documentation](https://sli.dev) · [GitHub](https://github.com/slidevjs/slidev) · [Showcases](https://sli.dev/showcases.html)

<PoweredBySlidev mt-10 />
