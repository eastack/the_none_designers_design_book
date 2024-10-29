---
theme: default
background: https://cover.sli.dev
title: Welcome to Slidev
transition: fade-out
---

<div class="fzdbsjw text-6xl" >写给大家看的设计书</div>
<div class="fzlthjw text-2xl opacity-75">The Non-Designer's Design Book</div>
<div class="fzlthjw text-xl opacity-75">Robin Patricia Williams</div>

<!--
-->




---
transition: none
layout: image-left
image: ./public/image/joshua-tree.png
---

<h1 class="fzdbsjw">约书亚树</h1>
<div class="fzlthjw text-xl">
    很多年前的一个圣诞节，我收到一份圣诞礼物，是一本关于如何认识各种树的书。
当时我住在父母家，所有礼物都打开后，我决定出去走走，认一认邻居家的树。出去之前我读了书的一部分。其中提到的第一种树是约书亚树，只需要两个线索就能认出它。由于约书亚树相当怪异，所以看到书中它的照片时，我对自己说：“哦，北加利福尼亚绝对没有这种树。这种树太怪异了。如果我见过，肯定应该有印象，可我以前从来没有见过。”
</div>




---
transition: none
layout: image-left
image: ./public/image/joshua-tree.png
---
<div class="fzlthjw text-xl">
    之后我拿着这本书走出家门。我的父母住在一个小巷子里，这里共有 6 家住户。其中 4 家的前院里都赫然立着约书亚树。我住在那里已经有 13 年了，此前居然从未注意过约书亚树。我在这个街区转了转，发现至少 80% 的住家前院都种有约书亚树。而我在此之前居然从来没有注意过！在我知道了这种树之后，我是说在我能够说出它的名字后，它就无处不在了。
</div>




---
transition: fade-out
layout: image-left
image: ./public/image/joshua-tree.png
---

<span class="fzdbsjw text-2xl">一旦能够说出什么东西的名字，就会很容易注意到它。你就会掌握它，拥有它，让它受你所控。
</span>



---
layout: center
transition: slide-left
---

<h1 class="fzdbsjw">四大基本原则</h1>

<li class="fzdbsjw">对比（<span class="fzlthjw">Contrast</span>）</li>
<li class="fzdbsjw">重复（<span class="fzlthjw">Repetition</span>）</li>
<li class="fzdbsjw">对齐（<span class="fzlthjw">Alignment</span>）</li>
<li class="fzdbsjw">亲密性（<span class="fzlthjw">Proximity</span>）</li>



---
layout: image-left
image: ./public/image/proximity.png
---
<h1 class="fzdbsjw">亲密性（<span class="fzlthjw">Proximity</span>）</h1>

<div class="fzlthjw text-xl">彼此相关的项应当靠近，归组在一起。如果多个项相互之间存在很近的亲密性，它们就会成为一个视觉单元，而不是多个孤立的元素。这有助于组织信息，减少混乱，为读者提供清晰的结构。
</div>



---
class: px-20
transition: slide-left
---

<h1 class="fzdbsjw">亲密性原则</h1>

<div class="grid grid-cols-2 grid-gap2 px-10">

<div class="flex flex-col items-center flex-gap2">
  <div>
    <img v-click="1" border="rounded" src="./public/image/card_1.png" alt="">
  </div>
  <div >
    <img v-click="2" border="rounded" src="./public/image/card_2.png" alt="">
  </div>
</div>


<div class="flex flex-col items-center flex-gap2 fzlthjw">
  <div>
    <img v-click="3" border="rounded" src="./public/image/card_3.png" alt="">
  </div>
  <div v-click="4" class="flex flex-col items-start flex-gap2 h-full w-full justify-center">
    <li>把相关的元素分为一组。</li>
    <li>统一使用了居中对齐。</li>
    <li>对姓名的字体适当加粗。</li>
  </div>
</div>

</div>


---
class: px-40
transition: slide-left
---

<h1 class="fzdbsjw">亲密性原则</h1>

<div class="grid grid-cols-[1fr] grid-gap2">
    <div class="flex flex-col items-center flex-gap8">
      <div>
        <img v-click="1" border="rounded" src="./public/image/areas_1.png" alt="">
      </div>
      <div>
        <img v-click="2" border="rounded" src="./public/image/areas_2.png" alt="">
      </div>
    </div>
</div>


---
class: px-20
transition: slide-left
---

<h1 class="fzdbsjw">亲密性原则</h1>

<div class="grid grid-cols-[47%_1fr] grid-gap2 px-10">

<div class="flex flex-col items-center flex-gap2">
  <div>
    <img v-click="1" border="rounded" src="./public/image/purple_card_1.png" alt="">
  </div>
  <div >
    <img v-click="2" border="rounded" src="./public/image/purple_card_2.png" alt="">
  </div>
</div>


<div>
  <div v-click="3" class="flex flex-col items-start flex-gap2 h-full w-full justify-center">
    <li>标题更大。</li>
    <li>其他部分的字更小。</li>
    <li>三种服务列在独立的三行。</li>
    <li>把相关元素集中在一起。</li>
    <li>把邮箱和网址的字母大写，让它们更易读。</li>
    <li>去掉多余的心形。</li>
    <li>去掉 available 这个词。</li>
    <li>把心形变浅，不要让它和文字争夺注意力。</li>
    <li>把心形放大，让它和文本重叠融为一体。</li>
  </div>
</div>

</div>


---
class: px-50
transition: slide-left
---

<h1 class="fzdbsjw">亲密性原则</h1>

<div class="grid grid-cols-[1fr]">
    <div class="flex flex-col items-center flex-gap8">
      <div>
        <img v-click="1" border="rounded" src="./public/image/moon_1.png" alt="">
      </div>
      <div>
        <img v-click="2" border="rounded" src="./public/image/moon_2.png" alt="">
      </div>
    </div>
</div>



---
layout: image-left
transition: slide-left
image: ./public/image/contrast.png
---

<h1 class="fzdbsjw">对比（<span class="fzlthjw">Contrast</span>）</h1>

<div class="fzlthjw text-xl">对比的基本思想是，要避免页面上的元素太过相似。如果元素（字体、颜色、大小、线宽、形状、空间等）不相同，那就干脆让它们截然不同。要让页面引人注目，对比通常是最重要的一个因素，正是它能使读者首先看这个页面。
</div>




---
layout: image-left
image: ./public/image/repetition.png
transition: slide-left
---

<h1 class="fzdbsjw">重复（<span class="fzlthjw">Repetition</span>）</h1>

<div class="fzlthjw text-xl">让设计中的视觉要素在整个作品中重复出现。可以重复颜色、形状、材质、空间关系、线宽、字体、大小和图片，等等。这样一来，既能增加条理性，还可以加强统一性。
</div>



---
layout: image-left
transition: slide-left
image: ./public/image/alignment.png
---

<h1 class="fzdbsjw">对齐（<span class="fzlthjw">Alignment</span>）</h1>

<div class="fzlthjw text-xl">任何东西都不能在页面上随意安放。每个元素都应当与页面上的另一个元素有某种视觉联系。这样能建立一种清晰、精巧而且清爽的外观。
</div>



---
class: px-20
transition: slide-left
---

<h1 class="fzdbsjw">对齐原则</h1>

<div class="grid grid-cols-[49.3%_1fr] grid-gap2 px-10">

<div class="flex flex-col items-center flex-gap2">
  <div>
    <img v-click="1" border="rounded" src="./public/image/paper_card_1.png" alt="">
  </div>
  <div >
    <img v-click="2" border="rounded" src="./public/image/paper_card_1.5.png" alt="">
  </div>
</div>

<div class="flex flex-col items-center flex-gap2 fzlthjw">
  <div>
    <img v-click="3" border="rounded" src="./public/image/paper_card_2.png" alt="">
  </div>
  <div v-click="4" class="flex flex-col items-start flex-gap2 h-full w-full justify-center">
    <li>将信息按照亲密性原则进行分组。</li>
    <li>统一使用左对齐。</li>
    <li>将字重适当加重。</li>
    <li>左对齐比居中对齐边界更硬，对齐更明确</li>  </div>
</div>

</div>



---
class: px-50
transition: slide-left
---

<h1 class="fzdbsjw">对齐原则</h1>

<div class="flex flex-row items-center justify-center flex-gap1 h-full pb-20">
  <div>
    <img v-click="1" border="rounded" src="./public/image/eye_1.png">
  </div>
  <div>
    <img v-click="2" border="rounded" src="./public/image/eye_2.png">
  </div>
  <div>
    <img v-click="3" border="rounded" src="./public/image/eye_3.png">
  </div>
</div>


---
class: px-20
transition: slide-left
---

<h1 class="fzdbsjw">对齐原则</h1>

<div class="grid grid-cols-2 grid-gap5 px-60">

<div class="flex flex-col items-center flex-gap5 h-full">
  <div>
    <img v-click="1" border="rounded" src="./public/image/pie_day_1.png" alt="">
  </div>
  <div >
    <img v-click="2" border="rounded" src="./public/image/pie_day_2.png" alt="">
  </div>
</div>


<div class="flex flex-col items-center flex-gap5 fzlthjw">
  <div>
    <img v-click="3" border="rounded" src="./public/image/pie_day_3.png" alt="">
  </div>
  <div>
    <img v-click="4" border="rounded" src="./public/image/pie_day_4.png" alt="">
  </div>
</div>

</div>

<!--
2. 不同行长让居中布局看起来确实很居中。
行之间的间隔在引用文字中是一致的。
字体不那么又大又长。

字体很可爱。

3. 有趣的字体
有趣的图画。

居中对齐是很明确的居中。

4. 粗壮有力
文字后面有黑色带，文字反转出来。

微妙地利用合适的装饰。
-->



---
class: px-50
transition: slide-left
---

<h1 class="fzdbsjw">对齐原则</h1>

<div class="flex flex-row items-center justify-center flex-gap1 h-full pb-20">
  <div>
    <img v-click="1" src="./public/image/one_night_1.png">
  </div>
  <div>
    <img v-click="2" src="./public/image/one_night_2.png">
  </div>
</div>



---
class: px-50
transition: slide-left
---

<h1 class="fzdbsjw">对齐原则</h1>

<div class="flex flex-row items-center justify-center flex-gap1 h-full pb-20">
  <div>
    <img v-click="1" src="./public/image/country_1.png">
  </div>
  <div>
    <img v-click="2" src="./public/image/country_2.png">
  </div>
</div>
