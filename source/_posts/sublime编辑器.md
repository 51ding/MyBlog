---
title: Sublime编辑器
date: 2018-11-05 18:45:00
---

####  命令面板


```
Ctrl + Shift + P
```
<!-- more -->
### 常用快捷键

- 打开一个新页面 **Ctrl + N**
- 页面跳转 **Ctrl + Tab**
- 选择当前行 **Ctrl + L**
- 合并两行 **Ctrl + J**
- 添加缩进  **Ctrl + ]**
- 取消缩进 **Ctrl + [ **
- 在当前行之下添加新行 **Ctrl + Enter**
- 在当前行之上添加新行 **Ctrl + Shift + Enter**
- 操作粒度 **Ctrl + 键盘← **每次往左移动移动一个单词
- 选中一个单词 **Ctrl + Shift + 键盘←**
- 查看快捷键历史 **Ctrl +`(反引号)** ，在命令行输入`sublime.log_commands(True)`
- 根据名称查找文件 **Ctrl +_ P**，输入的内容分为三种
  - 直接输入名称，查找包含这个名称的文件
  - 名称:行号 `a.js:10`意思为跳转到a.js的第10行
  - 名称@函数名称  `a.js:function B(这里编辑器会有自动提示功能)`跳转到function B所在的行
- 查找字符串 **Ctrl  + f**,查找到匹配项之后键入**Enter**，查找下一项，键入**Shift + Enter**
- 光标停留在单词之上，键入**Ctrl + D**,就会选中这个单词，多次键入就会多次选中，之后所有单词进入多点编辑模式，可以统一修改这些单词，相当于替换操作，之后键入**Esc**，推出多点编辑模式
- 

#### sublime自定制 

通过选择 Preference -》 Browers packages  -》 User 就能看到用户自定义的文件

**Preferences.sublime-settings**这个文件就是用户自定义的配置文件其中有一些常用的配置项

- folder_exclude_patterns 要忽略的文件夹-格式 ` "folder_exclude_patterns": [".svn", ".git"],`

- file_exclude_patterns 要忽略的文件 - 格式 `"file_exclude_patterns": ["*.pyc", "*.pyo", "*.exe", "*.dll", "*.obj","*.o", "*.a", "*.lib", "*.so", "*.dylib", "*.ncb", "*.sdf", "*.suo", "*.pdb", "*.idb", ".DS_Store", "*.class", "*.psd", "*.db", "*.sublime-workspace"]` 


#### suiblime包管理

[包管理网站](https://packagecontrol.io/)
#### 使用方法

常用·插件

- advanceNewFile：快速创建文件 快捷键 **Ctrl + Alt + N**

- SideBarEnhancements ：增强侧边栏功能
- DocBlockr：快速添加注释

#### 代码相关

##### 菜单栏的Goto anything



