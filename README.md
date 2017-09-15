# sticky-for-typecho
Typecho的置顶插件 by Willin
因为原来的下载地址不见了，网上也不好找，故上传一份

使用方法：
1. 上传至plugins文件夹
2. 在 index.php 的 $this->title(); 前面加上 $this->sticky(); 
例如: 

    <h2 class="title"><a href="<?php $this->permalink() ?>"><?php $this->sticky(); $this->title() ?></a></h2>

3. 在插件设置里输入要置顶文章的cid，如15, (注意：如只置顶一个帖子，数字后需要加上逗号)
4. cid查看方法是在 ‘管理文章’页面，鼠标悬停于你的文章，浏览器底部状态栏即可显示

