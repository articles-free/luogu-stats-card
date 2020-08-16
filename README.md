> 注意：为了不滥用洛谷服务器流量，本项目利用 vercel 的边缘缓存功能缓存了2小时数据，即同一个用户卡片**24小时内最多只会向洛谷服务器请求12次数据**。
## 简介

`luogu-stats-card`是一个动态生成洛谷用户练习数据卡片的工具，可以展示自己的做题情况。可以用于个人主页、博客、github等可以插入图片的地方。

## 效果预览

[![wangao的练习情况](https://luogu.vercel.app/api?id=313209)](https://github.com/wao3/luogu-stats-card)

## 如何使用

1. 仅使用图片，直接复制以下内容到任意 markdown 编辑器中，并将`?id=`后面的数字更改为自己的 id 即可（id是洛谷个人主页地址的一串数字）。

   ```md
   ![wangao的练习情况](https://luogu.vercel.app/api?id=313209)
   ```

2. 使用图片链接，复制以下内容，第二个小括号内的地址是点击该图片跳转的地址，建议设置为洛谷个人主页。

   ```md
   [![wangao的练习情况](https://luogu.vercel.app/api?id=313209)](https://github.com/wao3/luogu-stats-card)
   ```

## 自行部署

如果想要自行试验或者二次开发可以自行部署到自己的 vercel 服务器，登录 [vercel](https://vercel.com/)后，点击下方按钮即可部署。

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/wao3/luogu-stats-card)

## 如何贡献

#### 提供bug反馈或建议

使用 [issue](https://github.com/wao3/luogu-stats-card/issues) 反馈bug时，尽可能详细描述 bug 及其复现步骤

#### 贡献代码的步骤

1. fork项目到自己的repo
2. 把fork过去的项目也就是你的项目clone到你的本地
3. 修改代码
4. commit后push到自己的库
5. 在Github首页可以看到一个 pull request 按钮，点击它，填写一些说明信息，然后提交即可。
6. 等待作者合并

## 其他

如果对你有所帮助的话，希望能在右上角点一个 star (★ ω ★)

## LICENSE

[MIT](https://github.com/wao3/luogu-stats-card/blob/master/LICENSE)