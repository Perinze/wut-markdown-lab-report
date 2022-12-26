# wut-markdown-lab-report
武汉理工大学实验报告模板markdown

不能生成Word文档

# 使用方法

在VSCode安装Markdown PDF插件

```
ext install yzane.markdown-pdf
```

修改template.md中所有以$开头的变量名为你的信息
（建议使用查找），
并在合适的div中添加报告内容。

然后使用Markdown PDF插件生成HTML文件，
再用浏览器打印成PDF。

打印PDF预览时你可能会发现内容比一页长，
在需要分页的地方添加

```html
</div>
<div class="body">
```

在所有需要分页的地方添加这两行，
就可以生成PDF报告了。

# 起因

Linux下的Office替代软件非常难用，
但学校只提供Word实验报告模板，
于是自己搓了一个Markdown（HTML）的。

HTML是临时查文档凑上去的，
有建议欢迎提issue。
