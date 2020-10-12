# hexo-theme-pln
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-5-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
[🇨🇳 中文](/README.zh.md) [🖼 screenshots](/screenShots/index.md)

A plain, text-friendly Hexo theme

## Install
1. `git clone https://github.com/gaoryrt/hexo-theme-pln.git themes/pln`
2. Modify your [hexo configuration](https://hexo.io/docs/configuration.html), [change `theme`](https://hexo.io/docs/configuration.html#Extensions) to `pln`.

## Update
`cd themes/pln && git pull`

## Uninstall
`cd themes && rm -rf pln`

## Configuration
Modify your [`theme/pln/_config.yml`](https://github.com/gaoryrt/hexo-theme-pln/blob/master/_config.yml) file.

## Got a question?
[Issues](https://github.com/gaoryrt/hexo-theme-pln/issues) are always welcomed.

### How to enable site-searching
Simply use [hexo-generator-search](https://github.com/wzpan/hexo-generator-search). Or change [`theme/pln/layout/_partial/search.ejs`](https://github.com/gaoryrt/hexo-theme-pln/blob/master/layout/_partial/search.ejs) file using [hexo search helper](https://hexo.io/docs/helpers.html#search-form)
### How to enable Latex
```
brew install Pandoc
npm uninstall hexo-renderer-marked --save
npm install hexo-renderer-pandoc --save
```
then enable it in [theme configuration](https://github.com/gaoryrt/hexo-theme-pln/blob/beecf303914f4b4a76e22026bcc8c3b15c47b6fa/_config.yml#L17).

## License
MIT

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="http://ioliu.cn"><img src="https://avatars2.githubusercontent.com/u/10877162?v=4" width="70px;" alt=""/><br /><sub><b>Nine</b></sub></a><br /><a href="#platform-xCss" title="Packaging/porting to new platform">📦</a> <a href="#tool-xCss" title="Tools">🔧</a></td>
    <td align="center"><a href="https://github.com/willmasters"><img src="https://avatars0.githubusercontent.com/u/743296?v=4" width="70px;" alt=""/><br /><sub><b>Will Masters</b></sub></a><br /><a href="https://github.com/gaoryrt/hexo-theme-pln/issues?q=author%3Awillmasters" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://linshuirong.cn"><img src="https://avatars1.githubusercontent.com/u/16076993?v=4" width="70px;" alt=""/><br /><sub><b>林水溶</b></sub></a><br /><a href="https://github.com/gaoryrt/hexo-theme-pln/issues?q=author%3AshuiRong" title="Bug reports">🐛</a></td>
    <td align="center"><a href="http://aloisdg.github.io/"><img src="https://avatars2.githubusercontent.com/u/3449303?v=4" width="70px;" alt=""/><br /><sub><b>Alois</b></sub></a><br /><a href="https://github.com/gaoryrt/hexo-theme-pln/issues?q=author%3Aaloisdg" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://gaoryrt.com"><img src="https://avatars3.githubusercontent.com/u/5306513?v=4" width="70px;" alt=""/><br /><sub><b>gaoryrt</b></sub></a><br /><a href="https://github.com/gaoryrt/hexo-theme-pln/commits?author=gaoryrt" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->
