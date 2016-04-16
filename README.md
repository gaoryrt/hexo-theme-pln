# hexo-theme-pln
A plain theme for hexo  
[demo](http://gaoryrt.com)  
![index](http://7xs4ih.com1.z0.glb.clouddn.com/index.jpg)
![tags](http://7xs4ih.com1.z0.glb.clouddn.com/tags.jpg)
![article](http://7xs4ih.com1.z0.glb.clouddn.com/article.jpg)
![dropdown](http://7xs4ih.com1.z0.glb.clouddn.com/dropdown.jpg)
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
You should modify `hexo/themes/pln/_config.yml` file before deploy.  

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
see and leaves your [issues here](https://github.com/gaoryrt/hexo-theme-pln/issues).
***
# Changelog
- `2016-04-12`: init
- `2016-04-13`: disqus showing same comments bug fix
- `2016-04-13`: read more link add
- `2016-04-13`: no-tag but icon bug fix
- `2016-04-13`: pass theme unit test
- `2016-04-14`: see [2016-04-12 意见和建议](https://github.com/gaoryrt/hexo-theme-pln/issues/1)
- `2016-04-17`: archives header bug fix
