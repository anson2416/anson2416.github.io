# README

这是一个使用Hexo生成并部署的博客。

**2017-10-15** :white_check_mark: ✔

参照文章为**代码块**添加**一键复制**功能。

[ HEXO优化之（二）----添加复制功能](https://zhuzhuyule.xyz/2017/06/12/HEXO/HEXO%E4%BC%98%E5%8C%96%E4%B9%8B%EF%BC%88%E4%BA%8C%EF%BC%89-%E6%B7%BB%E5%8A%A0%E5%A4%8D%E5%88%B6%E5%8A%9F%E8%83%BD/)

需要注意的是的，默认生成的按钮跟我的博客模板不一致。
所以我自己把按钮的位置调整了一下。
修改位于`hexo\themes\next\source\js\src`的`custom.js`

```javascript
//$copyBtn.css("left", -$copyBtn.width() - 3);
$copyBtn.css("right", -$copyBtn.width() + 88);
```
