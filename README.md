# bootstrap 学习   
初衷，   
经常使用bootstarp模板，简单大气，且兼容手机端 但是用不好经常会丢失一些模板的东西。所以需要系统的学习下bootstrap了。不求能设计好的页面模板，但求能用的顺手。

学习教程以慕课网教程为准。
# day1 2018年4月26日
day1-1.html
1.bootstrap 封装了一系列常用的按钮，标签，布局之类的东西
2.可以通过class + 相应的名字进行调用

day1-2.html
1.bootstrap 对标题的标签做了优化
2.非标题标签可以使用<class="h1">,<class="h2">,<class="h3"> 之类的进行调用

day1-3.html
副标题，对于一级标题的副标题 在bootstrap中可以使用<small>标签进行标记

day1-4.html
对段落做设置,bootstrap中的全局样式字体为14px,行高约为20px

day1-5.html
对于段落中的内容 class="lead" 进行强调

day1-6.html
对段落内容进行加强，普通元素可以使用font-weight 设置进行加粗.
对于<b><strong> 标签进行加粗

day1-7.html
在bootstrap 中可以通过<i><em> 对字体做加斜处理

# day2 2018年4月27日
day2-1.html
对字体进行颜色设置， text-muted 浅灰色，text-primary 深蓝色, text-success 绿色, text-info 浅蓝, text-warning 黄色, text-danger 红色

day2-2.html
文本对其,bootstrap 对齐做了简化处理 text-left 左对齐, text-center 居中对齐, text-right 右对齐, text-justify 两端对齐

day2-3.html
对列表做简单的讲述

无序列表
<ul><li>..</li></ul>

有序列表
<ol><li>..</li></ol>

定义列表
<dl>
<dt>..</dt>
<dd>..</dd>
</dl>

day2-4.html

对于无序列表，有序列表中的点或数字可以通过 class="list-unstyled" 进行去除

day2-5.html
在bootstrap 中可以通过list-inline 进行内联表设置，内联表一般是用来做水平导航的。
bootstrap 4 中list-inline不生效，bootstrap3 可以正常使用

day2-6.html
定义列表 ,bootstrap 调整了行边距

day2-7.html
bootstrap 在自定义列表中可以受用  class=“dl-horizontal” 来进行水平调整

day2-8.html
bootstrap 代码支持
<code></code> 适用于单个或多个单词类的代码
<pre></pre> 适用于多行代码
<kbd></kbd> 用于显示用户输入的代码

如果代码量过多有不想占用较大的空间可以使用class="pre-scrollable" 进行滚动显示

day2-9.html
bootstrap 表格，bootstrap 提供了不同类型的表格如下
1.class="table" 基础表格
2.class="table-striped" 斑马线表格
3.class="table-bordered" 带边框表格
4.class="table-hover" 悬停高亮表格
5.class="table-condensed" 紧凑型表格
6.class="table-responsive" 响应式表格

day2-10.html
bootstrap 为表格设置了不同颜色的类 class="active",class="success",class="info",class="warning",class="danger"
