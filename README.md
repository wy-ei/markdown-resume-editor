## Markdown editor

支持编辑预览，具有本地保存功能，支持关闭页面后下次继续编辑。考虑到有可能需要打印成pdf文件，所以添加了打印预览功能，可以利用浏览器自身的打印功能导出pdf文件。

点击 [这儿](http://wy-ei.github.io/markdown-editor) 尝试使用。

## 改版说明

+ 2015-08-20 第一次改版：由于调用`window.print()`函数，chrome会进入打印预览页面，而firefox和IE则进入选择打印设备的页面，而且还默认添加了页眉页脚，所以我在第二次修改的过程中不再调用`window.print()`函数，而是进入打印页面，希望用户根据浏览器的不同选择合适的操作进入预览页面，根据自己的需求调整页面。

## License

Copyright (c) 2015 wy-ei. (MIT License)