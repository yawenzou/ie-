# ie-
各个浏览器出现问题以及解决方法
###ie8下event事件
<pre><code>var eve = event||window.event;
var objEle = eve.target || eve.srcElement;</code></pre>
<p>ie8下event事件是通过window.event来获取，当前元素是用srcElement</p>
