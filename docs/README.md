## 我的文档

> 一个神奇的文档站点生成器。

## 如何使用docsify

1.全局安装 docsify-cli ，可以实现在本地初始化和预览网站。
```
npm i docsify-cli -g
```
2.在 ./docs 子目录中编写文档，可以使用 init 命令。
```bash
docsify init ./docs
```
3.After the `init` is complete, you can see the file list in the `./docs` subdirectory.

- `index.html` as the entry file
- `README.md` as the home page
- `.nojekyll` prevents GitHub Pages from ignoring files that begin with an underscore
4.在docs的上一级目录，以 docsify serve 运行本地服务器。您可以在浏览器中预览您的网站 http://localhost:3000
```bash
docsify serve docs
```
5.部署到github

```bash
在github上创建一个以账户名开头的仓库（liubo0056.github.io）
git clone 克隆仓库的本地
把前面创建的项目放到本地仓库中
避坑：要在liubo0056.github.io内部再右键git bash here.
git status
git add .
git commit -m 'tips'
git push
```
代码上传后还要设置页面目录
![image](images/cf819e74-2a4a-4d02-84ad-cb94726d6f57.png)


## Features

- No statically built html files
- Simple and lightweight
- Smart full-text search plugin
- Multiple themes
- Useful plugin API
- Emoji support
- Compatible with IE11
- Support server-side rendering ([example](https://github.com/docsifyjs/docsify-ssr-demo))

## Examples

Check out the [Showcase](https://github.com/docsifyjs/awesome-docsify#showcase) to see docsify in use.

## Donate

Please consider donating if you think docsify is helpful to you or that my work is valuable. I am happy if you can help me [buy a cup of coffee](https://github.com/QingWei-Li/donate). :heart:

## Community

Users and the development team are usually in the [Discord server](https://discord.gg/3NwKFyR).
