---
theme: default

fonts:
  sans: JetBrains Mono
  mono: JetBrains Mono
  serif: JetBrains Mono

class: bg-white text-black

drawings:
  persist: false

transition: slide-down
comark: true
duration: 15min
---

<style>
:root {
  --slidev-theme-font-family: 'JetBrains Mono', monospace;
}
</style>

<link
  rel="stylesheet"
  href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@100..800&display=swap"
/>

# argo 

ballad of argo tactical

<div @click="$slidev.nav.next" class="mt-12 py-1 cursor-pointer hover:bg-gray-100">
  Let's get kraken <carbon:arrow-right />
</div>

<!-- bottom-right image -->
<img
  src="./images/lower-right-corner.jpg"
  class="absolute bottom-0 right-0 w-64"
/>

<!--
Presenter slide notes. It is visible and editable in Presenter Mode along with the slide. 
-->

---
src: ./slides/post.md
---
