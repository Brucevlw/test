
==方法一：根据网页的时间戳查询==

第一步：打开up主的个人空间

第二步：在右边的板块找到up主的UID，记下这串数字（网址栏也能看到）

![[Others/Attachments/b2a9eb4e664f4578dbd86910cb23673d_MD5.png|500]]

第三步：在链接 https://api.bilibili.com/x/space/acc/relation?mid= 的等号后粘贴前面的UID数字，回车，访问这个网址

![[Others/Attachments/4c306c17cc491442ead07e7fed8419a5_MD5.png]]

第四步：找到`mtime`后的一串数字，即账号关注的时间戳（可按ctrl+f快速查找）

![[Others/Attachments/c495803813e8e1a0aaf896f91bd045ad_MD5.png]]

第五步：找个时间戳转换网站，转换成可读的北京时间。如 https://www.wetools.com/timestamp-convert

==方法二：有些现成网站、工具（浏览器插件、油猴脚本、软件等）提供此功能==