TAB设置**不能保存**，每次打开编辑器都要重设置。
#### 解决方式
在项目（repo）根创建`.editorconfig`文件，内容：
```
[*]
indent_style = tab
indent_size = 4
```
填写成自己需要的即可。

##### 注意BUG
设置后也**只对修改有效，新建文件无效！**
没找到解决方案，只能创建文件时手动设置，
还是可以接受的。
