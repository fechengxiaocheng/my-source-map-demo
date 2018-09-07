# 验证webpack中devtool属性值的demo

本项目作为快速验证webpack中devtool属性值的demo，可以在config/webpack.prod.js中设置devtool属性的值，来生成对应的source Map文件。观察打包之后的文件。使用Source Map可以方便线上debug，更多研究移步[深入理解Source Map](http://goddess.joeray61.com/2018/09/06/source-map/#more)。

## 使用

    git clone git@github.com:fechengxiaocheng/my-source-map-demo.git
    npm i
    npm run build

打开dist打报后的文件，在浏览器中打开index.html;点击click，查看console中的信息。
