# hexo-theme-pln
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
A plain, text-friendly Hexo theme

一个纯文字友好的Hexo主题

![index](/screenShots/ver1.0-index.jpg)
![tags](/screenShots/ver1.0-tags.jpg)
![article](/screenShots/ver1.0-article.jpg)
![dropdown](/screenShots/ver1.0-dropdown.jpg)
*screenshots capcures at 2016-05-14, ver1.0*
***
# Install
Execute the following command in your `hexo` folder.

```
git clone https://github.com/gaoryrt/hexo-theme-pln.git themes/pln
```

Then find `theme` in `hexo/_config.yml`, make it look like this: `theme: pln`

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

请务必修改以下内容。

**Always adds `subtitle: ` to your `hexo/_config.yml` to avoid bug.**

```yml
subtitle: 'I am subtitle.'

...
If your site is put in a subdirectory, set root as '/<your subdirectory>/', for example: /blog/.
root: ''
```

**You should modify `hexo/themes/pln/_config.yml` file before deploying.**


```yaml
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

# FAQ
- [How to enable search / 启用搜索功能](https://github.com/gaoryrt/hexo-theme-pln/issues/9#issuecomment-242401562)
- [How to enable Latex / 启用 Latex](https://github.com/gaoryrt/hexo-theme-pln/issues/33)
- [No tags only categories / 只有分类没有 tag 吗](https://github.com/gaoryrt/hexo-theme-pln/issues/35)

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
- `2018-05-04`: optional TOC; Fixed [#27](https://github.com/gaoryrt/hexo-theme-pln/issues/27)
- `2020-01-04`: support deploy site to server subdirectory by [shuiRong](https://github.com/shuiRong)
- `2020-01-04`: fix [#33](https://github.com/gaoryrt/hexo-theme-pln/issues/33) and [#36](https://github.com/gaoryrt/hexo-theme-pln/issues/36])

# license
MIT

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="http://ioliu.cn"><img src="https://avatars2.githubusercontent.com/u/10877162?v=4" width="70px;" alt=""/><br /><sub><b>Nine</b></sub></a><br /><a href="#platform-xCss" title="Packaging/porting to new platform">📦</a> <a href="#tool-xCss" title="Tools">🔧</a></td>
    <td align="center"><a href="https://linshuirong.cn"><img src="https://avatars1.githubusercontent.com/u/16076993?v=4" width="70px;" alt=""/><br /><sub><b>林水溶</b></sub></a><br /><a href="https://github.com/gaoryrt/hexo-theme-pln/issues?q=author%3AshuiRong" title="Bug reports">🐛</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!