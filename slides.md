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

<div class="grid grid-cols-2 grid-gap2 px-15">

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

<div class="grid grid-cols-[45%_1fr] grid-gap2 px-10">

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
image: ./public/image/alignment.png
---

<h1 class="fzdbsjw">对齐（<span class="fzlthjw">Alignment</span>）</h1>

<div class="fzlthjw text-xl">任何东西都不能在页面上随意安放。每个元素都应当与页面上的另一个元素有某种视觉联系。这样能建立一种清晰、精巧而且清爽的外观。
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

<div class="flex flex-col items-center justify-center flex-gap1 h-full px-30 pb-20">
    <img v-click="1" src="./public/image/ppt_1.png">
    <img v-click="2" src="./public/image/ppt_2.png">
</div>

<!--
https://www.foundertype.com/index.php/News/newsdetails/id/76.html
-->


---
class: px-20
transition: slide-left
---

<h1 class="fzdbsjw">亲密性原则</h1>

<div class="grid grid-cols-[45%_1fr] grid-gap2 px-10">

<div class="flex flex-col items-center flex-gap2">
  <div>
    <img v-click="1" src="./public/image/dog_card_1.png">
  </div>
  <div >
    <img v-click="2" src="./public/image/dog_card_2.png">
  </div>
</div>
<div>
  <div v-click="3" class="flex flex-col items-start flex-gap2 h-full w-full justify-center">
    <li>标题被放大了一些，这样它就和照片对齐了。</li>
    <li>副标题被归入更亲的亲密性中。</li>
    <li>保持了底部明显的右对齐，为网址单独设立了一行，这样做让信息更清晰。</li>
    <li>网址中加入了大写字母，所以读起来更容易。</li>
    <li>下半页的第二个logo 被削减了一些，所以它不会和上面那个争夺注意力。</li>
  </div>
</div>

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
class: px-50
transition: slide-left
---

<h1 class="fzdbsjw">重复原则</h1>

<div class="flex flex-row items-center justify-center flex-gap1 h-full pb-20">
  <div>
    <img v-click="1" src="./public/image/book_page_1.png">
  </div>
  <div>
    <img v-click="2" src="./public/image/book_page_2.png">
  </div>

  <Arrow v-click="3" x1="110" y1="140" x2="230" y2="123" width="1" color="gray"/>
  <p v-click="3" class="absolute bottom-93 left-5 opacity-80 transform text-sm">所有页面上都有一致的双线。</p>

  <Arrow v-click="4" x1="100" y1="280" x2="220" y2="308" width="1" color="gray"/>
  <p v-click="4" class="absolute bottom-60 left-5 opacity-80 transform text-sm">
        <div>标题和子标题字体一致，而</div>
        <div>且每个标题和子标题之上有</div>
        一致的空白。
  </p>

  <Arrow v-click="5" x1="100" y1="420" x2="220" y2="460" width="1" color="gray"/>
  <p v-click="5" class="absolute bottom-30 left-5 opacity-80 transform text-sm">
        <div>页码放在每一页上的同一个</div>
        <div>位置，而且字体相同。</div>
  </p>

  <Arrow v-click="6" x1="860" y1="205" x2="760" y2="260" width="1" color="gray"/>
  <p v-click="6" class="absolute bottom-80 left-197 opacity-80 transform text-sm">
        <div>这一列很宽，占了两列的宽</div>
        <div>度，从而维持外边框的一致性。</div>
  </p>

  <Arrow v-click="7" x1="785" y1="320" x2="653" y2="357" width="1" color="gray"/>
  <p v-click="7" class="absolute bottom-45 left-197 opacity-80 transform text-sm">
    <div>注意列表和上一页图题中重</div>
    <div>复使用了三角形。这个形状</div>
    <div>可能还在这个出版物的其他</div>
    <div>位置用到。</div>
  </p>

  <Arrow v-click="8" x1="860" y1="435" x2="760" y2="455" width="1" color="gray"/>
  <p v-click="8" class="absolute bottom-25 left-197 opacity-80 transform text-sm">
        <div>每一页的底部都重复出现这</div>
        <div>条单线。</div>
  </p>
</div>



---
class: px-50
transition: slide-left
---

<h1 class="fzdbsjw">重复原则</h1>

<div class="grid grid-cols-[40.7%_1fr] grid-gap5 px-10">
  <div>
    <img v-click="1" border="rounded" src="./public/image/light_orange_card.png">
  </div>
  <div>
    <img v-click="2" border="rounded" src="./public/image/light_green_card.png">
  </div>
</div>

<!--
workshop 名称使用的标题字体。
副标题和页脚的衬线体。

每个workshop 中的衬线斜体。
两种颜色。

Workshop 之间的间距。
点划线。

字和点划线之间的间隔。

用字体选择、间距、适合的剪贴画、无边框来避免业余的居中对齐。
-->


---
class: px-20
transition: slide-left
---

<h1 class="fzdbsjw">重复原则</h1>

<div class="grid grid-cols-2 grid-gap2 px-35">

<div class="flex flex-col items-center flex-gap2">
  <div>
    <img v-click="1" border="rounded" src="./public/image/repeat_card_1.png" alt="">
  </div>
  <div >
    <img v-click="2" border="rounded" src="./public/image/repeat_card_2.png" alt="">
  </div>
</div>
<div class="flex flex-col items-center flex-gap2 fzlthjw">
  <div>
    <img v-click="3" border="rounded" src="./public/image/repeat_card_3.png" alt="">
  </div>
  <div v-click="4" class="flex flex-col items-start flex-gap2 h-full w-full justify-center">
    <li>重复使用相同的字体。</li>
    <li>没有使用居中对齐。</li>
    <li>运用了对比性原则。</li>
  </div>
</div>

</div>



---
class: px-20
transition: slide-left
---

<h1 class="fzdbsjw">重复原则</h1>

<div class="grid grid-rows-2 px-25">

<div class="flex flex-row items-center flex-gap2">
  <div class="flex-none w-72">
    <img v-click="1" src="./public/image/repeat_orange_card.png">
  </div>
  <div v-click="2">
    <li>两个字体。</li>
    <li>精巧的大写。</li>
    <li>文本颜色中的背景颜色。</li>
    <li>第二种颜色蓝和橙色的互补色。</li>
    <li>正文和题目文字水平对齐。</li>
  </div>
</div>

<div class="flex flex-row items-center flex-gap2">
  <div class="flex-none w-72">
    <img v-click="3" src="./public/image/repeat_green_card.png">
  </div>
  <div v-click="4" class="flex flex-col items-start flex-gap2 h-full w-full justify-center">
    <li>深栗色。</li>
    <li>泡泡的绿色。</li>
    <li>框的明显对齐和文本的明显对齐。</li>
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
class: px-20
transition: slide-left
---

<h1 class="fzdbsjw">对比原则</h1>

<div class="grid grid-cols-[43%_1fr] grid-gap2 px-10">

<div class="flex flex-col items-center flex-gap2">
  <div>
    <img v-click="1" class="shadow-md" src="./public/image/purple_card_3.png" alt="">
  </div>
  <div >
    <img v-click="2" class="shadow-md" src="./public/image/purple_card_4.png" alt="">
  </div>
</div>


<div>
  <div v-click="3" class="flex flex-col items-start flex-gap2 h-full w-full justify-center">
    <li>去掉了 Times New Roman 字体。</li>
    <li>用手写体作为标题，用无衬线体作为其余文本的字体。</li>
    <li>增加了深紫色色带。</li>
    <li>为了配合衬线粗体字加入了深紫色。</li>
    <li>为了增加对比，去掉了浅紫色背景。</li>
    <li>为了让心形图案不过度干扰文字，减小了心形的面积。</li>
    <li>心的位置提高了，打开了空间。</li>
  </div>
</div>

</div>



---
class: px-20
transition: slide-left
---

<h1 class="fzdbsjw">对比原则</h1>

<div class="grid grid-cols-[25%_1fr] grid-gap2 px-10">

<div class="flex flex-col items-center flex-gap2">
  <div>
    <img v-click="1" src="./public/image/pie_1.png" alt="">
  </div>
  <div >
    <img v-click="2" src="./public/image/pie_2.png" alt="">
  </div>
</div>
<div>
  <div v-click="3" class="flex flex-col items-start flex-gap2 h-full w-full justify-center">
    <li>边框被改得更细（半磅）。</li>
    <li>把全大写变成大小混写。</li>
    <li>删掉了诸如telephone（电话）、zip code（邮编）、area code（区号）（因为这是本地报纸上登的本地广告）这样的不必要信息，腾出了更大的空间。</li>
    <li>放大派并且让它飘起来（可以用Photoshop 把背景变得透明）。</li>
    <li>调整了派的种类之后，它们更好地配合了空间。</li>
    <li>大多数文字靠左对齐了；一些元素靠右对齐。</li>
    <li>派店的口号重复了店名的字体。</li>
    <li>派店的口号被设置成曲线形。</li>
    <li>把a pie gallery（派的美术馆）挪到了标题位置，因为店里确实有派艺展览。</li>
  </div>
</div>

</div>



---
class: px-50
transition: slide-left
---

<h1 class="fzdbsjw">对比原则</h1>

<div class="grid grid-cols-[28%_28%_1fr] grid-gap2 px-0">
  <div>
    <img v-click="1" border="rounded" src="./public/image/iread_1.png">
  </div>
  <div>
    <img v-click="2" border="rounded" src="./public/image/iread_2.png">
  </div>
  <div v-click="3" class="flex flex-col items-start flex-gap2 h-full w-full justify-center">
    <li>背景是深厚的黑色（百分之二十的蓝绿色、品红以及黄色，还有百分之百的黑色）。</li>
    <li>题目更大了。</li>
    <li>标题和logo 字体匹配（重复原则）。</li>
    <li>字体使用了常规磅数而非细体磅数，所以在黑色中反白的时候效果更好。</li>
  </div>
</div>




---
class: px-50
transition: slide-left
---

<h1 class="fzdbsjw">对比原则</h1>

<div class="grid grid-cols-2 grid-gap5">
  <div>
    <img v-click="1" border="rounded" src="./public/image/yellow_1.png">
  </div>
  <div>
    <img v-click="2" border="rounded" src="./public/image/yellow_2.png">
  </div>
</div>

