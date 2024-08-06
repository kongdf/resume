---
theme: seriph
background: https://cover.sli.dev
title: 孔大夫的在线简历
titleTemplate: "%s - 孔大夫"
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
monaco: "dev" 
htmlAttrs:
  dir: ltr
  lang: zh-cn
---

<div >


<img border="rounded" style="border-radius:50%;margin:0 auto;" src="https://static.kongdf.com/self.jpeg" width="130" alt="">



<div style="width:50%;float:left;">

  <div style="margin-top:20px;float:right;text-align:left;">

  - 🧝‍♂️ 孔祥斌/男/1995
  - 🧑‍💻 工作年限：8 年
  - 📱 手机/微信：18519100092
  - 📮 Email：kxb51812@gmail.com
  - 📖 博客: http://blog.kongdf.com
  - <carbon-logo-github /> Github: https://github.com/kongdf 
  - 📄 简历: http://resume.kongdf.com

  </div>

</div>
<div style="float:left;margin-left:5%;">

  <div style="margin-top:20px;text-align:left;">


  <!-- <Toc   minDepth="1" maxDepth="2"></Toc> -->
  <ol>

  <li class="rounded cursor-pointer" hover="bg-white bg-opacity-10" @click="$slidev.nav.next()">个人优势与技术栈 <carbon:arrow-right class="inline"/></li>
 <li class="rounded cursor-pointer" hover="bg-white bg-opacity-10" @click="$slidev.nav.go(3) ">公司经历 <carbon:arrow-right class="inline"/>
    <ol>
      <li class="rounded cursor-pointer" hover="bg-white bg-opacity-10" @click="$slidev.nav.go(3)">河北御芝林 (2021年11月 ~ 至今)<carbon:arrow-right class="inline"/></li>
      <li class="rounded cursor-pointer" hover="bg-white bg-opacity-10" @click="$slidev.nav.go(4)">北京鸿业云建 (2021年2月 ~ 2021年10月)<carbon:arrow-right class="inline"/></li>
      <li class="rounded cursor-pointer" hover="bg-white bg-opacity-10" @click="$slidev.nav.go(5)">容联云通讯 (~ 2021年)<carbon:arrow-right class="inline"/></li>  
  </ol>
 </li>
  <li class="rounded cursor-pointer" hover="bg-white bg-opacity-10" @click="$slidev.nav.go(6)">项目经验 <carbon:arrow-right class="inline"/></li>
  <li>开源作品 <carbon:arrow-right class="inline"/></li>
  </ol>

 
  </div>

</div>

<div style="clear:both;"> </div>
<p style="margin-top:50px;">💻 ⬅️➡️ 翻页 /🖱️左下角</p>

</div>

---
src: ./pages/jj.md
---

---
src: ./pages/gsjl.md
---

---
src: ./pages/xmjy.md
---