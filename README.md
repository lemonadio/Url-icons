# Url-icons
The CSS snippet of Obsidian.
> readme-version1.1.0
> 
> This CSS snippet(version1.1) rewritten with Obsidian1.1.16 by [Lemonadio](https://github.com/lemonadio) was based on the CSS snippet in Blue topaz theme written by Cuman.
> [Click me to check the latest example url](https://github.com/cumany/Blue-topaz-examples)
> 
> Resources to help with icons:
> [Search for icons](https://iconify.design/icon-sets); 
> [Convert the SVG code into CSS ready code](https://yoksel.github.io/url-encoder)

**************************************************
## Preface:
This CSS snippet has light mode and dark mode, which will show the icons in reading mode.

For showing the icons correctly, HTMLs in markdown need to add `https://` before url.

If you have any question, please email to: lemonadio0507@gmail.com, and write *Icon plugin's bug feedback*

If you want some new icons to add in, or you have any advice, please email to the above address, and write *Icon plugin's advice feedback*



p.s.

I don't know how to combine two modes into one CSS snippet, so I separated them.

I hope someone who understands CSS can give me some advice:p

(Personally, I think light mode looks better, hahaha)


**************************************************
## Proview(A part of all):
![image](https://user-images.githubusercontent.com/113871946/230942661-942652cf-5c02-468a-aae0-a9b8e6e7d80f.png)

**************************************************
## Customizable browser icons:
/*----Add your browser icons here:----*/
- [x] *origin style browser icons*
- [x] *360style browser icons*
- [x] *Chrome style browser icons*
- [x] *Firefox style browser icons*
- [x] *IE style browser icons*
- [x] *Quark style browser icons*
- [x] *Edge style browser icons*

If you want to use some style browser icon, paste the css snippet to bottom of their CSSs.

(This origin style is *Edge style browser icons*)

**************************************************
## Customizable site icons (total 52):
/*----Add your site icons here:----*/
- [x] [*ALiYun*](http://www.aliyun.com)
- [x] [*ALiYun Drive*](https://www.aliyundrive.com/)
- [x] [*Amazon*](https://www.amazon.com)
- [x] [*Apple*](https://www.apple.com)
- [x] [*AppStore*](https://apps.apple.com)
- [x] [*Archive Of Our Own*](https://www.archiveofourown.com)
- [x] [*BaiDu*](https://www.baidu.com)
- [x] [*BaiDu Netdisk*](https://pan.baidu.com)
- [x] [*BiliBili Share Url*](https://b23.tv)
- [x] [*BiliBili*](https://www.bilibili.com/)
- [x] [*BoKeYuan*](https://www.cnblogs.com/)
- [x] [*CSDN*](https://csdn.net)
- [x] [*Discord*](https://discord.com)
- [x] [*DouBan*](https://www.douban.com/)
- [x] [*Gitee*](https://gitee.com)
- [x] [*Github*](https://github.com)
- [x] [*Google*](https://www.google.com/)
- [x] [*HuaBan*](https://www.huaban.com)
- [x] [*IMDB*](https://www.imdb.com/)
- [x] [*IQiYi*](https://www.iqiyi.com/)
- [x] [*ITHome*](https://ithome.com)
- [x] [*JianShu*](https://www.jianshu.com/)
- [x] [*JingDong*](https://www.jd.com/)
- [x] [*LanZou Cloud*](https://www.lanzou.com)
- [x] [*MengNiang Pedia*](https://moegirl.org.cn)
- [x] [*Obsidian*](https://obsidian.md)
- [x] [*OpenAI*](https://openai.com)
- [x] [*Pinterest*](https://www.pinterest.com/)
- [x] [*PronHub*](https://pornhub.com)
- [x] [*QQ Music*](https://y.qq.com)
- [x] [*ShaoShuPai*](https://sspai.com)
- [x] [*Sina Share Url*](https://t.cn)
- [x] [*SouHu*](https://www.sohu.com)
- [x] [*Spotify*](https://open.spotify.com)
- [x] [*TaoBao*](https://www.taobao.com)
- [x] [*Tmall*](https://www.tmall.com/)
- [x] [*Tumblr*](https://www.tumblr.com)
- [x] [*Twitter*](https://twitter.com/home)
- [x] [*Unsplash*](https://www.unsplash.com)
- [x] [*Netease*](https://www.163.com)
- [x] [*Neteast Cloud Music*](https://music.163.com)
- [x] [*Weblio*](https://www.weblio.jp)
- [x] [*WeiBo*](https://www.weibo.com)
- [x] [*Wechat*](https://weixin.qq.com/)
- [x] [*Weread*](https://weread.qq.com/)
- [x] [*Wikipedia*](https://www.wikipedia.com)
- [x] [*XiMaLaYa*](https://www.ximalaya.com)
- [x] [*YouTube*](https://www.youtube.com)
- [x] [*ZhiHu*](https://www.zhihu.com)
- [x] [*189Cloud*](https://cloud.189.cn)
- [x] [*360doc*](http://www.360doc.com/)

**************************************************
## Template to Add More Icons：
(Refer to CSS documentation)
```
/*Template*/
.external-link[href*="{site.}"]::before {  
    content: CSS ready code from the SVG converter;  
}

```

**************************************************
## Update History(The lastest CSS version 1.1.0)：
2023/4/10 1.1.0
- New icons:
	- weblio(Light mode)
	- XiMaLaYa
	- Huaban
	- QQzone
- Revise Readme
- add Creator GitHub link ;)
---
2023/4/8  1.0.1
- Translate Readme into English;
- Sort the code in alphabet;

- Fix the bug: Icon didn't show correctly;
- Fix the bug: The urls in README can't open;
---
2023/4/7  1.0.0
- Create the css.
