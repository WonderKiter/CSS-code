## CSS布局
### float布局
* 步骤
    * 子元素上加float:left和width
    * 在父元素上一个class="clearfix"并且在css里加上.clearfix
    * 有经验的会留一些空间或者最后一个不设置不设置whith。
    * 不需要作响应式，因为手机上没有IE，而这个布局专门为IE准备的
    * IE 6、7存在双倍margin bug，解决办法有两个
      1. 一是将错就错，针对IE6、7把margin减半
      2. 二是神来一笔，再加一个display:inline-black
   