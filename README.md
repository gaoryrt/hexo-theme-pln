# hexo-theme-pln
a plain, text-friendly Hexo theme
一个纯文字友好的Hexo主题  
![index](/screenShots/ver1.0-index.jpg)
![tags](/screenShots/ver1.0-tags.jpg)
![article](/screenShots/ver1.0-article.jpg)
![dropdown](/screenShots/ver1.0-dropdown.jpg)
*screenshots capcured at 2016-05-14, ver1.0*
***
# Install
Execute the following command under your `hexo` folder.

```
git clone https://github.com/gaoryrt/hexo-theme-pln.git themes/pln
```

Then find `theme` in `hexo/_config.yml`, make it looks like this: `theme: pln` 

# Update
Execute the following command to update Pln.

```
cd themes/pln
git pull
```

# Uninstall
Execute the following command to uninstall Pln.
```
cd themes
rm -rf pln
```
***
# After install
**You should modify `hexo/themes/pln/_config.yml` file before deploy.    
Always add `subtitle: ` to your `hexo/_config.yml` file to avoid bug**  
请务必修改以上内容。  


Here's what it looks like/means:  
```
menu:
  main: /
  archives: /archives

logo: **word on the left-top end**

more:
  **link title**: **link url**
  rss: /rss2.xml

about:
  title: **blue words fixed on the right end**
  link: **url of the blue words**

disqus_shortname: **as it described, find it on your disqus site**

excerpt_num: **number of auto excerpt words**

footer_info: **black words fixed on the right end**
```
***
# Issues
[Issues](https://github.com/gaoryrt/hexo-theme-pln/issues) are always welcome.  
欢迎您对本项目提供和意见和建议。  
(请直接提issue，或在[微博](http://weibo.com/R1T1AN)上私信，一般回复时间不超过12小时)
***
# Changelog
- `2016-04-12`: init
- `2016-04-13`: disqus showing same comments bug fix
- `2016-04-13`: read more link add
- `2016-04-13`: no-tag but icon bug fix
- `2016-04-13`: pass theme unit test
- `2016-04-14`: see [2016-04-12 意见和建议](https://github.com/gaoryrt/hexo-theme-pln/issues/1)
- `2016-04-17`: archives header bug fix
- `2016-04-24`: forgot to add a css file last commit, maybe that's why nobody gives a star
- `2016-04-25`: missing tag icon bug fix
- `2016-04-26`: ul list unstyle bug fix
- `2016-04-27`: **add google_analytics, add `google_analytics: YOURTOKENHERE` in `hexo/_config.yml` file to enable**
- `2016-05-01`: no subtitle layout bug fix
- `2016-05-04`: new footer rule, .behind layout upgrade
- `2016-05-06`: upgrade cssstyle, button filter bug fix
- `2016-05-08`: upgrade js ?: operator，fasten loading speed, busuanzi added
- ------------ VERSION 1.0 ------------
- `2016-05-14`: pln ver1.0, searching function is loading
- `2016-05-15`: css -> SCSS (`sass --style compressed main.scss:m.min.css`), footer wrap bug fix
- `2016-05-27`: more pln in `behind`, `busuanzi`, `meta`, `afterfooter`
- `2016-05-29`: `h2 > code` style bug fixed
- `2016-07-03`: https web-font bug fix
- `2016-07-05`: search added
- `2016-07-10`: disqus bug fix
- `2016-08-08`: apple-touch-icon added
- `2016-08-18`: font update
- `2016-08-29`: i18n: en
- `2016-11-06`: Bug fix: the tab bar can not be scrolled when there are too many tabs. 增加了分享到微信朋友圈的图片，需要将一张名为 wx_share.png 的 大于 300*300 的图片放在根目录（public）下。
- `2017-02-04`: dropdown-content css upgrade
- `2017-08-27`: remove wx_share.png; remove fontawesome, use inline SVG
- `2018-02-03`: support TOC, finally
- `2018-05-04`: optional TOC; Fixed #27

# license
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
