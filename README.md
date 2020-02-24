1. npm run serve  开发
2. npm run build 准备打包
3. 将dist/index.html   所有的css js 链接改成 ./ 相对
上线的代码都在dist 下
4. git checkout -b gh-pages 
  删除代码， 就把dist/ 所有代码放到根目录下， 
5. git push origin gh-pages
  源码在master分支， 上线的代码在  dist/