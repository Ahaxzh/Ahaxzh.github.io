
 In this post, I `want` to share how to use bindkeys command to solve a few issues when using Zsh.
<!--more-->

## Can not use HOME and END keys normally
After using Zsh, I found that some terminals can not understand `Home` and End keys correctly, i.e., I can not go to the begining or end of the a line by pressing Home or End key.

This is because the key codes that terminal recognizes when you press certain keys can not be recognized by zsh. You can manually find which key code is sent when you `press` a key. You can use showkey -a to print the key codes. Here is what it shows when I press Home and End keys.


This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

[点击跳转至百度](http://www.baidu.com)

创建脚注格式类似这样 [^RUNOOB]。

[^RUNOOB]: 菜鸟教程 -- 学的不仅是技术，更是梦想！！！