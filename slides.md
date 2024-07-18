---
theme: seriph
background: https://cover.sli.dev
title: coderResume
titleTemplate: '%s - 孔大夫'
info: false
author: 孔大夫
class: text-center
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-left 
mdc: true
monaco: 'dev'
---

# coderResume

  <span @click="$slidev.nav.next" class="rounded cursor-pointer" hover="bg-white bg-opacity-10">
    查看目录  <carbon:arrow-right class="inline"/> 
  </span>

 
<span>💻 ⬅️➡️ 翻页 /🖱️左下角</span>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/kongdf" target="_blank" alt="GitHub" title="打开GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div> 
 
---
 src: ./pages/nav.md
---

---
src: ./pages/jj.md
---

---
src: ./pages/jsz.md
---
 
---
src: ./pages/gsjl.md
---

---
src: ./pages/xmjl.md
---

---
src: ./pages/zp.md
---



