# koa-spider
Node.js下载漫画图片,图片的名称按照漫画的顺序命名
## 适用范围
漫画url有明显的规律,比如：
```
http://aaaaaaaaa/xemh/491.html,
http://aaaaaaaaa/xemh/491_2.html,
http://aaaaaaaaa/xemh/491_3.html,
```
## 转换成cbz，mobi，epub漫画
1. 把图片压缩成zip包
2. 安装Kindle Comic Converter，选择zip包转换
3. 生成对应的漫画文件

## 安装Node.js >= 7.6
http://nodejs.org/download/
## 安装依赖包
npm install
## 运行程序
npm start
