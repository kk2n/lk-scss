
ShortScss (简写：sscss)--简单的，简短的，缩写的，胡乱的，疯狂的Scss的简写混合（mixin）方法
----------------------------------------------------------------------------
<pre>
项目名：   ShortScss (简写：sscss)
版  本：   V1.0.0
作  者：   Likuan
关键词：   简单的，简短的，缩写的，胡乱的，疯狂的Scss的简写混合（mixin）方法。
开发目标： 简化CSS编写代码，提高工作效率，
使用方法： @include m();括号中写入简化代码，
格式为：   使用默认值：    (x x x);
          自定义值：     ((x n) (x n) (x n));
          多个自定义值：  ((x (n n)) (x (n n)) (x (n n)));

          例如：@include m(p);
          生成:padding:0;

          例如：@include m((p 30) m);
          生成:padding:30px;margin:0;

          例如：@include m(w (h 20) (p 30) m);
          生成:width:auto; height:20px; padding:30px; margin:0;

简写代码（如下）
----------------------------------------------------------------------------
显示类包括：        n          注释内容
                  dn         display:none
                  db         display:block
                  poa 或 po  position:absolute
                  por        position:relative
                  fl         float:left
                  fr         float:right
                  cb         clear:both
                  l          left:0
                  r          right:0
                  t          top:0
                  b          bottom:0
                  c          clip:auto
                  z 或 z-    z-index:1
                  jz         margin-left:auto; margin-right:auto
                  jzc        margin-left:auto; margin-right:auto; text-align:center
                  ...
尺寸间距及边框装饰： w          width
                  h          height
                  mw         min-width
                  maw        max-width
</pre>
