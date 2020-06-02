# pythontools
 Some python script helped me to work.

------

## 项目介绍

[微信读书笔记工具：微信读书助手wereader](https://github.com/liuhao326/pythontools/tree/master/wereader)

使用：[介绍](https://www.cnblogs.com/Higurashi-kagome/p/12872060.html)

[为本地Markdown文件生成目录（可在GitHub上正常显示）](https://github.com/liuhao326/pythontools/blob/master/TOC.py)

使用：[示例](https://www.cnblogs.com/Higurashi-kagome/p/12724993.html#使用实例)

[为本地Markdown文件的标题编号](https://github.com/liuhao326/pythontools/blob/master/AddTitleNumber.py)

使用：[示例](https://www.cnblogs.com/Higurashi-kagome/p/12747857.html#使用实例)

------

[Markdown图片居中并将图片大小设置为80%](https://github.com/liuhao326/pythontools/blob/master/MClipChange.py)

使用：[示例](https://www.cnblogs.com/Higurashi-kagome/p/12497640.html)

[Markdown文字居中](https://github.com/liuhao326/pythontools/blob/master/Mcenter.py)

使用：[示例](https://www.cnblogs.com/Higurashi-kagome/p/12724875.html)

[依次复制图片URL和标题后生成Markdown格式的文本到剪切板](https://github.com/liuhao326/pythontools/blob/master/Mclips.py)

使用：[示例](https://www.cnblogs.com/Higurashi-kagome/p/12497601.html#使用实例)

---
## 使用说明
1. 先卸载依赖库
pip uninstall -y -r requirement.txt
2.  再重新安装依赖库
pip install -r requirement.txt
3. 开始运行
python main.py

## 补充说明
### .gitignore 不生效
.gitignore只能忽略那些原来没有被track的文件，如果某些文件已经被纳入了版本管理中，则修改.gitignore是无效的
```shell script
git rm -r --cached .
git add .
git commit -m 'update .gitignore'
```

### 导出项目依赖文件
```shell script
pip install pipreqs
pipreqs ./ --encoding=utf8
等待一会就会生成一个 requirements.txt  文件
```

