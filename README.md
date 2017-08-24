# ife2017

### 写下前面：
本内容是基于2017年[百度前端学院](http://ife.baidu.com/)所给任务的完成情况写的，涵盖了平时常用到的一些场景，当做小练习，放在这里作为记录及查阅所用。参考资料部分的链接也来自百度前端学院。

#### 注：下面代码皆为个人理解所给出的解决方案，难免有些地方不准确，仅作参考所用！

### 介绍：
前三个学院任务中不涉及其他框架等内容，全部使用原生的HTML、CSS、JS来实现。其中小薇学院为HTML和CSS部分，斌斌学院为JS基础部分，耀耀学院则为基础综合学院，最后糯米学院属于涉及框架或第三方库的综合性学院。
    

### 1. 小薇学院：

- **task01 - 零基础编程**

    > *任务说明*：完成一个HTML页面代码编写（不写CSS，不需要关注样式，只关注文档结构） 
      
    + [源码地址](https://github.com/visugar/ife2017/blob/master/01xiaowei/task01/index.html)
    + [预览地址](https://visugar.github.io/ife2017/01xiaowei/task01/index.html)
    + 小结:通过此任务了解了HTML的基本标签，及其含义、用法，同时运用一些语义化标签来构建页面。
    + 参考资料：
        - [Web相关名词通俗解释](https://www.zhihu.com/question/22689579)
        - [MDN HTML入门](https://developer.mozilla.org/zh-CN/docs/Web/Guide/HTML/Introduction)
        - [慕课HTML+CSS基础教程视频](http://www.imooc.com/learn/9)
      
- **task02 - 零基础HTML及CSS编码(一)**
    > *任务说明*：在任务代码基础上增加CSS样式代码的编写 
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/01xiaowei/task02/index.html)
    + [预览地址](https://visugar.github.io/ife2017/01xiaowei/task02/index.html)
    + 小结：使用CSS选择器为元素添加不同的样式，并实践了CSS的颜色、字体、背景、边框、盒模型、简单布局样式的使用方式
    + 参考资料：
        - [MDN CSS入门教程](https://developer.mozilla.org/zh-CN/docs/Web/Guide/CSS/Getting_started)

- **task03 - 三栏式布局**
    > *任务说明*： 实现三栏式布局（左右两栏宽度固定，中间一栏根据父元素宽度填充满，最外面的框应理解为浏览器。背景色为#eee区域的高度取决于三个子元素中最高的高度。）
          
    + [源码地址](https://github.com/visugar/ife2017/tree/master/01xiaowei/task03)
    + 预览地址: [float方式](https://visugar.github.io/ife2017/01xiaowei/task03/float.html) / [position方式](https://visugar.github.io/ife2017/01xiaowei/task03/position.html) / [双翼布局](https://visugar.github.io/ife2017/01xiaowei/task03/both_wings.html) / [flex方式](https://visugar.github.io/ife2017/01xiaowei/task03/flex.html)
    + 小结：同时尝试了几种不同的方式来实现三栏布局，但实现的过程中发现使用场景不一样，并且有些极端情况并且很好的优化，还有前后文的影响，使用时择优选择。
    + 参考资料：
        - [MDN：position](https://developer.mozilla.org/zh-CN/docs/Web/CSS/position)：了解 CSS position 属性的基本知识
        - [MDN：float](https://developer.mozilla.org/en-US/docs/Web/CSS/float)：了解 CSS float 属性的基本知识
        - [Learn CSS Positioning in Ten Steps](http://www.barelyfitz.com/screencast/html-training/css/positioning/)：通过具体的例子熟悉 position 属性
        - [清除浮动（clearfix hack）](http://zh.learnlayout.com/clearfix.html)：清除浮动是什么，如何简单地清除浮动
        - [StackOverflow：Which method of ‘clearfix’ is best?](http://stackoverflow.com/questions/211383/what-methods-of-clearfix-can-i-use)：清除浮动黑科技完整解读

- **task04 - 定位和居中问题**
    > *任务说明*：实践HTML/CSS布局方式,深入了解position等CSS属性(深入了解position等CSS属性)
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/01xiaowei/task04)
    + 预览地址：[方式一](https://visugar.github.io/ife2017/01xiaowei/task04/position_shade.html) / [方式二](https://visugar.github.io/ife2017/01xiaowei/task04/position_shade2.html) / [方式三](https://visugar.github.io/ife2017/01xiaowei/task04/position_shade3.html)
    + 小结:水平垂直居中涉及到中间块的宽高是否固定，上面针对不同情况的具体实现。
    + 参考资料：
        - [HTML和CSS高级指南之二——定位详解]()：大漠老师手把手教你，这次彻底搞懂定位问题
        - [Centering in CSS: A Complete Guide](https://css-tricks.com/centering-css-complete-guide/)：完整讨论了不同情况下的居中方案，建议自己思考之后再看答案
        - [Get HTML & CSS Tips In Your Inbox](http://howtocenterincss.com/)：有人写了一个作弊工具生成居中代码，但是看着代码你明白为什么吗

- **task05 - 零基础HTML及CSS编码(二)**
    > *任务说明*：能够基于设计稿来合理规划HTML文档结构，理解语义化，合理地使用HTML标签来构建页面，掌握CSS选择器的含义和用法，实践并掌握CSS的颜色、字体、背景、边框、盒模型、简单布局等样式的定义方式
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/01xiaowei/task05/two_layout.html)
    + [预览地址](https://visugar.github.io/ife2017/01xiaowei/task05/two_layout.html)
    + 小结：页面部分内容随浏览器窗口大小而变化，其中10张图片需要永远都完整展现，所以会随着宽度变窄，从两行变成三行甚至更多，也有可能随着宽度变宽，变成一行。

- **task06 - 通过HTML及CSS模拟报纸排版**
    > *任务说明*：根据给出的PSD设计稿，进一步掌握CSS中的字体、背景、颜色等属性的设置，且进一步练习CSS布局
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/01xiaowei/task06/index.html)
    + [预览地址](https://visugar.github.io/ife2017/01xiaowei/task06/index.html)
    + 小结：本任务实现的是固定布局，根据psd稿实现页面开发，实现效果与样例基本一致，暂时只在chrome符合标准，其他浏览器未作兼容

- **task07 - 实现常见的技术产品官网的页面架构及样式布局**
    > *任务说明*：通过实现一个常见的技术产品官网，加深对于HTML，CSS的实战能力，学习掌握如何在没有标注的情况下实现设计稿到页面的精确转变
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/01xiaowei/task07/index.html)
    + [预览地址](https://visugar.github.io/ife2017/01xiaowei/task07/index.html)
    + 小结：通过HTML和CSS实现设计稿，当浏览器窗口小于一定宽度是，出现横向滚动条，页面内容保持不变，窗口大于设计稿宽度时，页面部分内容与浏览器窗口保持一致。（chrome完美实现，其他浏览器未作兼容）
 
- **task08 - 响应式网格（栅格化）布局**
    > *任务说明*：使用 HTML 与 CSS 实现类似 BootStrap 的响应式 12 栏网格布局，根据屏幕宽度，元素占的栏数不同。 
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/01xiaowei/task08/index.html)
    + [预览地址](https://visugar.github.io/ife2017/01xiaowei/task08/index.html)
    + 小结：根据给出案例实现具体效果，使用CSS选择器为元素添加不同的样式，并实践了CSS的颜色、字体、背景、边框、盒模型、简单布局样式的使用方式
    + 参考资料：
        - [BootStrap 官网](http://getbootstrap.com/)：如果你没用过的话，至少了解一下它是做什么的
        - [Bootstrap grid examples](https://getbootstrap.com/examples/grid/)：改变浏览器宽度，查看不同类名元素的表现，理解网格系统的作用。然后，通过“审查元素”查看对应 CSS，思考这一系统是如何实现的
        - [BootStrap 带 offset 的网格系统](http://getbootstrap.com/2.3.2/scaffolding.html#gridSystem)
        - [Creating Your Own CSS Grid System](Creating Your Own CSS Grid System)：你可以先自己想想怎么实现，没有思路的话看看别人的做法

- **task09 - 使用HTML/CSS实现一个复杂页面**
    > *任务说明*：通过实现一个较为复杂的页面，加深对于HTML，CSS的实战能力
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/01xiaowei/task09/index.html)
    + [预览地址](https://visugar.github.io/ife2017/01xiaowei/task09/index.html)
    + 小结：这个任务实现的主要实现一个复杂的后台管理页面，涉及到较多常用的东西。

- **task010 - Flexbox 布局练习**
    > *任务说明*：学习如何flex进行布局，学习如何根据屏幕宽度调整布局策略。 
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/01xiaowei/task010/index.html)
    + [预览地址](https://visugar.github.io/ife2017/01xiaowei/task010/index.html)
    + 小结：根据给出的效果图实现flex的响应式布局
    + 参考资料：
        - [Flexbox详解](https://segmentfault.com/a/1190000002910324)：了解 Flexbox 属性的含义
        - [Flexbox——快速布局神器](http://www.w3cplus.com/css3/flexbox-basics.html)
        - [使用 CSS 弹性盒](https://developer.mozilla.org/zh-CN/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes)
        - [MDN flex属性](https://developer.mozilla.org/zh-CN/docs/Web/CSS/flex)

- **task011 - 移动Web页面布局实践**
    > *任务说明*：进行移动开发时的HTML及CSS实践,掌握移动Web开发在页面架构和布局的方法及差异性,掌握移动Web开发页面调试的方法。（不作为重点,留作后用） 
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/01xiaowei/task011/index.html)
    + [预览地址](https://visugar.github.io/ife2017/01xiaowei/task011/index.html)
    + 小结：本任务只涉及HTML及CSS部分，某些模块用到了CSS3中的flex布局。
    + 参考资料：
        - [MDN:手机网页开发](https://developer.mozilla.org/zh-CN/docs/Web/Guide/Mobile)
        - [MDN:在移动浏览器中使用viewport元标签控制布局](https://developer.mozilla.org/zh-CN/docs/Mobile/Viewport_meta_tag)
        - [移动前端开发和 Web 前端开发的区别是什么](https://www.zhihu.com/question/20269059)
        - [Alloyteam移动开发规范概述](http://alloyteam.github.io/Spirit/modules/Standard/)
        - [手机/移动前端开发需要注意的20个要点](http://sentsin.com/web/54.html)
        - [w3cplus响应式技术资源](http://www.w3cplus.com/responsive)
        - [浅谈移动Web开发](http://www.infoq.com/cn/articles/development-of-the-mobile-web-deep-concept)
        - [Alloyteam Mars](https://github.com/AlloyTeam/Mars)
        - [移动WEB开发入门](http://junmer.github.io/mobile-dev-get-started/)
        - [移动开发资源集合](https://github.com/jtyjty99999/mobileTech)
        - [The Mobile Web Handbook](https://quirksmode.org/mobilewebhandbook/)
        - [MobileWeb 适配总结](https://www.w3ctech.com/topic/979)
        - [移动前端不得不了解的html5 head 头标签](http://www.css88.com/archives/5480)

- **task012 - 学习CSS 3的新特性**
    > *任务说明*：学习了解CSS都有哪些新特性，并选取其中一些进行实战小练习 
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/01xiaowei/task012/index.html)
    + [预览地址](https://visugar.github.io/ife2017/01xiaowei/task012/index.html)
    + 小结：使用css3的伪元素选择器，对表格填写样式，边框+阴影，还有使用css3新特性实现轮播图。
    + 参考资料：
        - [图解CSS3](https://github.com/visugar/read-books/blob/master/css/%E3%80%8A%E5%9B%BE%E8%A7%A3CSS3%E3%80%8B-%E5%A4%A7%E6%BC%A0.md)
        - [《精通CSS》高级web标准解决方案](https://github.com/visugar/read-books/blob/master/css/%E3%80%8A%E7%B2%BE%E9%80%9ACSS%E3%80%8B%E9%AB%98%E7%BA%A7web%E6%A0%87%E5%87%86%E8%A7%A3%E5%86%B3%E6%96%B9%E6%A1%88.md)
        - [W3SchoolCSS3教程](http://www.w3school.com.cn/css3/index.asp)
        - [MDN CSS 3](https://developer.mozilla.org/zh-CN/docs/Web/CSS/CSS3)
    
---
### 2. 斌斌学院：

- **task11 - 零基础JavaScript编码（一）**
    > *任务说明*：初步明白JavaScript的简单基本语法，如变量、函数，了解JavaScript的事件，了解JavaScript中的DOM
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/02binbin/task11/index.html)
    + [预览地址](https://visugar.github.io/ife2017/02binbin/task11/index.html)
    + 小结：用户在输入框输入任何内容，点击‘确认’按钮，用户输入的值出现在右边。
    + 参考资料：
        - [JavaScript入门篇](http://www.imooc.com/learn/36)
        - [MDN JavaScript](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript)

- **task12 - 零基础JavaScript编码（二）**
    > *任务说明*：学习JavaScript中的if判断语法，for循环语法，学习JavaScript中的数组对象，学习如何读取、处理数据，并动态创建、修改DOM中的内容
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/02binbin/task12/index.html)
    + [预览地址](https://visugar.github.io/ife2017/02binbin/task12/index.html)
    + 小结：用for循环对数据进行遍历，同时对数据进行过滤，最后输出结果

- **task13 - 零基础JavaScript编码（三）**
    > *任务说明*：接触一下JavaScript中的高级选择器，学习JavaScript中的数组对象遍历、读写、排序等操作，学习简单的字符串处理操作
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/02binbin/task13/index.html)
    + [预览地址](https://visugar.github.io/ife2017/02binbin/task13/index.html)
    + 小结：根据要求实现了基本功能，其中用到了一个排序方法对数据进行排序，且动态生成元素

- **task14 - 基础JavaScript练习（一）**
    > *任务说明*：模拟一个队列，队列的每个元素是一个数字，初始队列为空，给出不同的按钮对队列进行操作。
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/02binbin/task14/index.html)
    + [预览地址](https://visugar.github.io/ife2017/02binbin/task14/index.html)
    + 小结：可将input中输入的数据从左侧插入，从右侧插入，删除队列中的数值可以从第一个位置开始，也可以从最后一个位置开始。同时利用事件委托来完事点击某数值时删除该元素。

- **task15 - 基础JavaScript练习（二）**
    > *任务说明*：基于上一任务，对输入的数字进行限制（10-100），且最多只能输入60个数字，当删除某数字时，弹出被删除的数值，队列中元素的高度等于输入的数值大小。
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/02binbin/task15/index.html)
    + [预览地址](https://visugar.github.io/ife2017/02binbin/task15/index.html)
    + 小结：实现了上述基本要求，将数字转成视觉效果。

- **task16 - 基础JavaScript练习（三）**
    > *任务说明*：基于上一任务，实践JavaScript数组、字符串相关操作
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/02binbin/task16/index.html)
    + [预览地址](https://visugar.github.io/ife2017/02binbin/task16/index.html)
    + 小结：将输入框改成textarea，由于一次输入多个内容，格式可以为数字，中文，英文等，可以用逗号回车空格等作为内容的分隔符，并增加一个可查询到按钮，进行模糊匹配，查询匹配成功后将该内容标识。
    + 参考资料：
        - [归并排序算法可视化](http://v.youku.com/v_show/id_XNTM1NTQxMDMy.html)
        - [15种排序算法可视化展示](http://v.youku.com/v_show/id_XNjIwNTEzMTA0.html?from=y1.2-1-176.3.3-2.1-1-1-2-0)

- **task17 - JavaScript和树（一）**
    > *任务说明*：学习树这种数据结构的基本知识，在页面中展现一颗二叉树的结构，提供一个按钮，显示开始遍历，点击后，以动画的形式呈现遍历的过程，当前被遍历到的节点做一个特殊显示，每隔一段时间再遍历下一个节点
          
   + [源码地址](https://github.com/visugar/ife2017/blob/master/02binbin/task17/index.html)
    + [预览地址](https://visugar.github.io/ife2017/02binbin/task17/index.html)
    + 小结：展示树的部分使用到的是flexbox布局，实现了前序、中序、后序三种遍历方式，同时借助setTimeout及闭包来实现具体效果。
    + 参考资料：
        - [js数据结构和算法 二叉树](https://segmentfault.com/a/1190000000740261)
        - [Data Structures With JavaScript: Tree](https://code.tutsplus.com/articles/data-structures-with-javascript-tree--cms-23393)
        - [Computer science in JavaScript: Binary search tree](https://www.nczonline.net/blog/2009/06/09/computer-science-in-javascript-binary-search-tree-part-1/)

- **task18 - JavaScript和树（二）**
    > *任务说明*：将上节任务的二叉树变成了多叉树，且每个节点都带有内容，增加了查询框，以动画形式查询节点内容与输入框中内容是否一致，找到则给出特殊标识。
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/02binbin/task18/index.html)
    + [预览地址](https://visugar.github.io/ife2017/02binbin/task18/index.html)
    + 小结：本任务中只使用了前序遍历来以动画形式遍历多叉树，同时在setTimeout中进行查询。
    

---
### 3. 耀耀学院：

- **task301 - 表单（一）单个表单项的检验**
    > *任务说明*：加强对JavaScript的掌握，熟悉常用表单处理逻辑
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/03yaoyao/task301/index.html)
    + [预览地址](https://visugar.github.io/ife2017/03yaoyao/task301/index.html)
    + 小结：页面实现输入框与按钮，点击按钮之后对输入的内容进行校验，校验结果显示在输入框下方。
    + 参考资料：
        - [JavaScript 表单验证](http://www.w3school.com.cn/js/js_form_validation.asp)
        - [HTML表单指南](https://developer.mozilla.org/zh-CN/docs/Learn/HTML/Forms)

- **task302 - 表单（二）多个表单项的动态校验**
    > *任务说明*：根据上一任务添加多个表单，表单获取焦点时，填写规则显示在该输入框下方，验证失败则变成红色输入框，红色描述文字显示在输入框下方，验证结果正确则为绿色，点击提交按钮时验证全部输入框。
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/03yaoyao/task302/index.html)
    + [预览地址](https://visugar.github.io/ife2017/03yaoyao/task302/index.html)
    + 小结：实现效果与说明基本一致。

- **task303 - 表单（三）联动**
    > *任务说明*：根据给出的效果图，切换单选框的不同选项时，下方的表单随之切换，一个select的选中项改变，则其后的select下拉框内容也改变。
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/03yaoyao/task303/index.html)
    + [预览地址](https://visugar.github.io/ife2017/03yaoyao/task303/index.html)
    + 小结：使用到是select下拉列表的onchange事件。随之形成表单的联动。

- **task304 - 听指令的小方块（一）**
    > *任务说明*：练习JavaScript在DOM、字符串处理相关知识，练习对于复杂UI，如何进行数据机构建模。
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/03yaoyao/task304/index.html)
    + [预览地址](https://visugar.github.io/ife2017/03yaoyao/task304/index.html)
    + 小结：实现了一个类似期盼的格子空间，每个格子用两个数字可以定位，给出不同的按钮，根据按钮上的命令，使红色小方块移动，但同时小方块不能超出格子间。（画方格是个力气活~）

- **task305 - 听指令的小方块（二）**
    > *任务说明*：在上一任务的基础上，添加更多更复杂的命令，并增加相应的动画。
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/03yaoyao/task305/index.html)
    + [预览地址](https://visugar.github.io/ife2017/03yaoyao/task305/index.html)
    + 小结：具体见预览，未作兼容，在chrome中可全部实现，给出的命令。

- **task306 - UI组件之浮出层**
    > *任务说明*：综合HTML、CSS、JavaScript实现布局功能，实现一个付出曾是的UI组件。
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/03yaoyao/task306/index.html)
    + [预览地址](https://visugar.github.io/ife2017/03yaoyao/task306/index.html)
    + 小结：浮出层默认在屏幕正中，滚动时，浮出层位置不随之改变，浮出层意外则为遮罩，任意点击浮出层外区域则默认为关闭浮出层，关闭按钮也可以关闭浮出层。同时还实现了浮出层的拖拽功能，按住浮出层可将其拖到任意位置。

- **task307 - UI组件之排序表格**
    > *任务说明*：将给出的数据插入到通过JS动态生成的表格中，并给出升序降序按钮，使其实现无刷新表格排序功能。
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/03yaoyao/task307/index.html)
    + [预览地址](https://visugar.github.io/ife2017/03yaoyao/task307/index.html)
    + 小结：其中三角按钮的也是力气活！其他的不多说，见代码和预览效果。

---
### 4. 糯米学院：
- **task401 - 有趣的鼠标悬浮模糊效果**
    > *任务说明*：实现文字的流光渐变动画，背景图需要进行模糊处理，实现按钮边框的从中间到两边扩展开的效果

    + [源码地址](https://github.com/visugar/ife2017/blob/master/04nuomi/task401/index.html)
    + [预览地址](https://visugar.github.io/ife2017/04nuomi/task401/index.html)
    + 小结：使用background-image：-webkit-linear-gradient()实现背景渐变的效果，利用-webkit-background-clip: text;把背景颜色渐变的效果应用到文本的文字上，通过中间内容的追加元素实现边框的伸展效果。

- **task406 - 自定义checkbox， radio样式**
    > *任务说明*：深入了解html、label标签，了解CSS边框、背景、伪元素、伪类（注意和伪元素区分）等属性的设置，了解CSS中常见的雪碧图，并能自己制作使用雪碧图
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/04nuomi/task406/index.html)
    + [预览地址](https://visugar.github.io/ife2017/04nuomi/task406/index.html)
    + 小结：通过label与input的关系，以及伪类:checked，追加元素::after来实现checkbox，radio的自定义图标，同时也可以利用背景图片实现同样的功能，原始的input标签需要隐藏。
    + 参考资料：
        - [MDN label](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/label)：了解html中label的基本知识
        - [MDN background-position](https://developer.mozilla.org/en-US/docs/Web/CSS/background-position)：了解背景图片定位相关知识
        - [MDN :checked](https://developer.mozilla.org/en-US/docs/Web/CSS/:checked)：了解input的:checked伪类的基本知识以及应用场景
        - [MDN :before](https://developer.mozilla.org/en-US/docs/Web/CSS/::before)：了解input的:before伪元素的基本知识
        - [MDN :after](https://developer.mozilla.org/en-US/docs/Web/CSS/::after)：了解input的:after伪元素的基本知识

- **task408 - 自定义网页右键菜单**
    > *任务说明*：了解js中的oncontextmenu事件，了解如何获取鼠标位置，了解如何实现页面屏蔽右键菜单
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/04nuomi/task408/index.html)
    + [预览地址](https://visugar.github.io/ife2017/04nuomi/task408/index.html)
    + 小结：利用js中的oncontextmenu事件，阻止网页中的默认右键菜单，自定义自己需要的菜单
    + 参考资料：
        - [oncontextmnue](http://www.runoob.com/jsref/event-oncontextmenu.html)：了解JavaScript中oncontextmenu的基本知识
        - [event那些事](http://xchb.work/2016/07/25/event%E9%82%A3%E4%BA%9B%E4%BA%8B/)： 收集整理的事件相关资料
       
- **task409 - 使用CSS实现折叠面板**
    > *任务说明*：深入理解html中radio的特性，深入理解CSS选择器以及伪元素的使用
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/04nuomi/task409/index.html)
    + [预览地址](https://visugar.github.io/ife2017/04nuomi/task409/index.html)
    + 小结：使用input的radio单选框特性结合css中的伪元素，再加上label的合作，实现面板折叠的效果，纯css及html完成，且只能显示一个面板。
    + 参考资料：
        - [MDN label](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/label)：了解html中label的基本知识
        - [MDN Adjacent sibling selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/Adjacent_sibling_selectors)： 了解CSS中的兄弟相邻选择器
    
- **task410 - 正则表达式之入门**
    > *任务说明*：掌握JavaScript正则表达式编写规则，了解JavaScript中的正则表达式的特殊字符，了解JavaScript提供的正则表达式相关方法，能用正则表达式做一些简单文本或者数字校验
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/04nuomi/task410/index.html)
    + [预览地址](https://visugar.github.io/ife2017/04nuomi/task410/index.html)
    + 小结：使用正则表达式测试是否为正确的手机号，其中用到了select的onchange事件，regExp是根据实际生活中手机号开头来写的。然后是判断一个输入的字符串是否有相邻
    的重复单词，要考虑到每个单词的边界，然后input表单用到了list及datalist特性，即同时可输入也可以下拉选择，在给定的词中还有自动补全的功能。
    + 参考资料：
        - [MDN Regular Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions)：了解JavaScript中正则表达式的基本知识
        - [正则表达式30分钟入门教程](https://deerchao.net/tutorials/regex/regex.htm)： 30分钟入门
        
- **task412 - CSS3饼状loading效果**
    > *任务说明*：学习和掌握水平垂直居中布局，学习和掌握利用HTML和CSS构造简单规则图形，学习和掌握和使用CSS3动画新特性
          
    + [源码地址](https://github.com/visugar/ife2017/blob/master/04nuomi/task412/index.html)
    + [预览地址](https://visugar.github.io/ife2017/04nuomi/task412/index.html)
    + 小结：用到了border-radius来实现圆和半圆，四分之三圆环则是由border来实现，使用到了水平垂直都居中的知识点，用到了z-index来控制半圆的显示与隐藏来配合动画的完成。且只使用css不使用js。
    + 参考资料：
        - [MDN CSS3](https://developer.mozilla.org/zh-CN/docs/Web/CSS/CSS3)
        - [CSS3实现鸡蛋饼饼状图loading等待转转转](http://www.zhangxinxu.com/wordpress/2014/04/css3-pie-loading-waiting-animation/)

- **task413 - CSS3实现3D 轮播图**
    > *任务说明*：了解CSS的定义、概念、发展简史，掌握CSS选择器的含义和用法，实践并掌握CSS的颜色、字体、背景、边框、盒模型、简单布局等样式的定义方式，理解 css 3d 和 景深的原理

    + [源码地址](https://github.com/visugar/ife2017/blob/master/04nuomi/task413/index.html)
    + [预览地址](https://visugar.github.io/ife2017/04nuomi/task413/index.html)
    + 小结：通过CSS3的animation实现轮播动画，只实现了初步功能，后续要接着完善。