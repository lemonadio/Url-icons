> 说明文档-1.1.0
> 
> 本CSS代码(版本1.1.0)由[柠酒(Lemonadio)](https://github.com/lemonadio)基于Obsidian1.1.16进行二创
> 
> 源文件取自Blue topaz主题自定义CSS代码，作者Cuman，[点我查看最新示例库地址](https://github.com/cumany/Blue-topaz-examples)
> 
> 资源网站:  
> 
> [图标大全](https://iconify.design/icon-sets)
> 
> [SVG转换至CSS代码](https://yoksel.github.io/url-encoder)

**************************************************
## 序言
本CSS文件分为深色模式CSS和浅色模式CSS，在阅读模式下展示图标。
使用markdown格式的HTML时，需要在链接中加入`https://`，否则将无法正常显示图标。
其他问题请发送邮件反馈至:lemonadio0507@gmail.com，邮件主题填写*图标插件bug反馈*
如有想要添加的网站图标以及任何建议也可反馈至上述邮箱，邮件主题填写*图标插件建议反馈*

p.s.
分成两个CSS是因为不知道怎么把两个模式设置到同一个CSS
所以分开两类设置了
希望有懂CSS的大佬指点一下
(个人认为浅色更好看哈哈哈)

**************************************************
## 支持的自定义通用网址图标：
*----在下面添加自定义浏览器通用网址图标:----*
- [x] *初始风格通用网址图标*
- [x] *360风格通用网址图标*
- [x] *Chrome风格通用网址图标*
- [x] *Firefox风格通用网址图标*
- [x] *IE风格通用网址图标*
- [x] *Quark风格通用网址图标*
- [x] *Edge风格通用网址图标*

若要使用某风格网址图标，则将其复制到代码底部即可
(本代码初始设置为Edge风格)

**************************************************
## 支持的自定义网址图标(共52个)：
(CSS代码中的先后顺序)
/*----在下面添加自定义网址:----*/
- [x] [*ALiYun(阿里云)*](http://www.aliyun.com)
- [x] [*ALiYun Drive(阿里云盘)*](https://www.aliyundrive.com/)
- [x] [*Amazon(亚马逊)*](https://www.amazon.com)
- [x] [*Apple*](https://www.apple.com)
- [x] [*AppStore*](https://apps.apple.com)
- [x] [*Archive Of Our Own(AO3)*](https://www.archiveofourown.com)
- [x] [*BaiDu(百度)*](https://www.baidu.com)
- [x] [*BaiDu Netdisk(百度网盘)*](https://pan.baidu.com)
- [x] [*BiliBili Share Url(B站分享外链)*](https://b23.tv)
- [x] [*BiliBili*](https://www.bilibili.com/)
- [x] [*BoKeYuan(博客园)*](https://www.cnblogs.com/)
- [x] [*CSDN*](https://csdn.net)
- [x] [*Discord*](https://discord.com)
- [x] [*DouBan(豆瓣)*](https://www.douban.com/)
- [x] [*Gitee*](https://gitee.com)
- [x] [*Github*](https://github.com)
- [x] [*Google*](https://www.google.com/)
- [x] [*HuaBan(花瓣)*](https://www.huaban.com)
- [x] [*IMDB*](https://www.imdb.com/)
- [x] [*IQiYi(爱奇艺)*](https://www.iqiyi.com/)
- [x] [*ITHome(IT之家)*](https://ithome.com)
- [x] [*JianShu(简书)*](https://www.jianshu.com/)
- [x] [*JingDong(京东)*](https://www.jd.com/)
- [x] [*LanZou Cloud(蓝奏云)*](https://www.lanzou.com)
- [x] [*MengNiang Pedia(萌娘百科)*](https://moegirl.org.cn)
- [x] [*Netease(网易)*](https://www.163.com)
- [x] [*Neteast Cloud Music(网易云音乐)*](https://music.163.com)
- [x] [*Obsidian*](https://obsidian.md)
- [x] [*OpenAI*](https://openai.com)
- [x] [*Pinterest*](https://www.pinterest.com/)
- [x] [*PronHub*](https://pornhub.com)
- [x] [*QQ Music(QQ音乐)*](https://y.qq.com)
- [x] [*QQ Zone(QQ空间)*](https://user.qzone.qq.com)
- [x] [*ShaoShuPai(少数派)*](https://sspai.com)
- [x] [*Sina Share Ur(新浪分享外链)l*](https://t.cn)
- [x] [*SouHu(搜狐)*](https://www.sohu.com)
- [x] [*Spotify*](https://open.spotify.com)
- [x] [*TaoBao(淘宝)*](https://www.taobao.com)
- [x] [*Tmall(天猫)*](https://www.tmall.com/)
- [x] [*Tumblr*](https://www.tumblr.com)
- [x] [*Twitter*](https://twitter.com/home)
- [x] [*Unsplash*](https://www.unsplash.com)
- [x] [*Weblio(Weblio辞典)*](https://www.weblio.jp)
- [x] [*WeiBo(微博)*](https://www.weibo.com)
- [x] [*Wechat(微信)*](https://weixin.qq.com/)
- [x] [*Weread(微信读书)*](https://weread.qq.com/)
- [x] [*Wikipedia(维基百科)*](https://www.wikipedia.com)
- [x] [*XiMaLaYa(喜马拉雅)*](https://www.ximalaya.com)
- [x] [*YouTube(油管)*](https://www.youtube.com)
- [x] [*ZhiHu(知乎)*](https://www.zhihu.com)
- [x] [*189Cloud(189云盘)*](https://cloud.189.cn)
- [x] [*360doc(360网盘)*](http://www.360doc.com/)

**************************************************
## 模板使用：
（可参考CSS文档）
```
*空白模板*  
.external-link[href*="{网址简式}"]::before {  
    content: 填从转换网站复制来的url信息;  
}

```

**************************************************
## 更新历史(当前最新CSS版本1.1.0)：
2023/4/10 1.1.0
- 添加新图标：
	- weblio辞典(浅色)
	- 喜马拉雅
	- 花瓣网
	- QQ空间
- 修改Readme文件
- 添加作者GitHub地址嘻嘻
---
2023/4/8  1.0.1
- 添加了英文版Readme文档;
- 将网址名称翻译成英文并附其中文名;
- 把代码按字母表重新排序;

- 修复部分图标不显示的bug.
- 修复README文档中网页无法直接打开的bug
---
2023/4/7  1.0.0
- 新建文档
