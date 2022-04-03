# readme-become-better
本仓库致力于推荐让自己的github-readme个人页面变得更好的方法和资源

## Github 统计卡片
>Github 有很多动态生成的官方统计信息，利用这些统计信息我们可以更清晰地展现个人 Github 中的提交、分类、热门等信息。

### github - stats
将`username=`自己的gitHub名字

stats卡片链接：`https://github-readme-stats.vercel.app/api?username=dongyuanwai&theme=dark&show_icons=true`

👇把下面的这段代码复制到你的README.md文档中，就可以得到卡片样式
```html
![dongyuanwai's GitHub stats](https://github-readme-stats-ouuan.vercel.app/api?username=dongyuanwai&show_icons=true)
```
![dongyuanwai's GitHub stats](https://github-readme-stats-ouuan.vercel.app/api?username=dongyuanwai&show_icons=true)


github-readme文档可以不仅可以使用mardown语法，还支持html语法。所以你可以进行插入图片、设置位置等操作

```html
<div align="center">
  <img  src="https://github-readme-stats.vercel.app/api?username=dongyuanwai&show_icons=true&theme=radical&hide=contribs,prs" />
</div>
```
<div align="center"><img  src="https://github-readme-stats.vercel.app/api?username=dongyuanwai&show_icons=true&theme=radical&hide=contribs,prs" /></div>


通过对卡片链接的操作,您可以进行修改theme值进行改变样式，hide隐藏图标、数据等操作

更多的内容可以查看官方的文档[GitHub Readme Stats ](https://github.com/anuraghazra/github-readme-stats/blob/master/docs/readme_cn.md)