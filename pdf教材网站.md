https://web.thuhole.com/##140950 【精品】
求问树洞，有没有啥可以下PDF教材之类的比较好的网站（免费，一定付费（不要太贵）都可），dz急需pdf教材🙏 🙏 🙏 
（12-08 11:11:22 282关注 31回复）

[Alice] 可以蹲一下
[Bob] 鸠摩有很多，但不一定全能找到
[Carol] 鸠摩搜书
[Bob] 找不到就淘宝吧（
[Dave] http://gen.lib.rus.ec/
比较经典的英文教材都会有
[洞主] Re Carol: 鸠摩感觉教材还是比较少啊，还有其他推荐吗？
[洞主] Re Dave: OH，谢谢
[洞主] 大伙有中文版网站吗？
[Eve] https://b-ok.global/?regionChanged=&redirect=29190576
[Eve] 也可以用中文搜
[洞主] Re Eve: 太感谢了
[洞主] 哇 ，25关注，看来大家都有类似的问题啊，可是一般的网站要么不全要么收费啊(ﾟOﾟ)，咱们是不是该建议学校专门为我们搞一个电子书库啥的
[Bob] Re 洞主: 图书馆网站能找到电子教材，不过不能下载
[Francis] Re 洞主: 水木搜索可以搜索教材，我感觉学校有的教材版权还是比较多的，不过下载权限不尽相同啊，有能下pdf的，有要用各种阅读器的
[洞主] Re Bob: 啊，那也可以，就是不太方便了
[Grace] 推荐一下zlibrary，还挺全的


[Hans] gen.lib.rus.ec
[Hans] 啊好像被说过了
[Hans] 我其实想知道有没有日文小说网站（青空文库只到1950，因为版权原因）
[Isabella] 你甚至可以尝试北邮人
[Jason] Re Eve: 赞！
[Kate] 淘宝或者闲鱼，一般2-3块一本，省时间
[Louis] 电子书重度用户来了：
1.分享一个常用的搜书网站： https://ebook.chongbuluo.com/

2.市面上很多能够找到的pdf电子书基本在 全国图书馆参考咨询联盟(http://www.ucdrs.superlib.net/)能够找到，一个下载方式可以参考：
https://www.douban.com/group/topic/201271301/
但是需要多次操作比较麻烦

3.如果嫌麻烦的话可以下载这个脚本，一般一本书花个两三块可以直接拿到pdf版本
https://greasyfork.org/zh-CN/scripts/388744-%E7%BA%A2%E5%A4%AA%E7%8B%BC%E7%9A%84%E5%B9%B3%E5%BA%95%E9%94%85

基本这样能够找到大部分教材
[Margaret] https://www.pdfdrive.com/
[Nathan] 清华的教参平台上面是可以用爬虫爬下来的。。以前是swf文件格式，而且有的文件很奇怪不方便转换成pdf，现在已经都变成jpg文件了，很好搞了
[Olivia] Re Nathan: 不是不能下载吗？怎么爬啊
[Paul] 蹲
[Queen] libgen
[Nathan] Re Olivia: 是可以的，你可以打开google的开发者工具，从network里就能看见对应的文件网址，用爬虫搞下来就行。不过我是好久以前搞的了hhh，记得用爬虫搞好用户验证就行，就这个网址https://id.tsinghua.edu.cn/do/off/ui/auth/login/form/5bf6e5a699d63ff1cdb082836ebd50f9/0?/Account/LogIn
[Richard] 商法学
[Susan] Re Nathan: 写给小白的补充：
0. 新版edge chromium功能和chrome一样，小白没必要为此下载chrome
1. 教参平台的阅读页面拦截了右键和F12，可以在新标签页先按F12呼出开发者工具，再将阅读页面的地址复制到地址栏访问
2. 开发者工具最上方有几个选项卡，这里需要使用“网络”选项卡
3. 网络选项卡上方有一栏：全部 | Fetch/XHR JS CSS Img ...，这里我们选中Img
4. 按照2的方法访问的话，此时Img列表满满的，不方便找出需要的内容，可以在网络选项卡的左上角点击🛇符号清除现有记录，然后翻一页就能找到
5. 针对教参平台的直接可用的结果：
如果阅读页面地址是http://reserves.lib.tsinghua.edu.cn/book6//{book_id}/{book_id:volume_id}/mobile/index.html
那么资源地址就是http://reserves.lib.tsinghua.edu.cn/book6//{book_id}/{book_id:volume_id}/files/mobile/{page}.jpg
其中{}包裹的内容是变量，book_id和volume_id要根据不同书的不同”卷“（教参平台的分卷方式比较奇葩）进行替换，page就是阿拉伯数字的页码
以《大学物理学. 力学、热学（第4版）》的第二”卷“【第1 篇 力学】为例，book_id=00006705，volume_id=002，所以第一页的资源地址就是
http://reserves.lib.tsinghua.edu.cn/book6//00006705/00006705002/files/mobile/1.jpg
比较奇葩的是，这个资源地址是没有权限验证的，不需要登录就可以访问、下载