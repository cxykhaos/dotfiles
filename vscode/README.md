# Vscode 配置

在做代码跳转或切换标签页等操作时，我们都是在编辑器界面的 vim 插件里，所以这些键绑定由 vim 插件管理，配置写在settings.json里。

而在文件浏览器界面或搜索结果界面时，我们不是在 vim 插件里，vim 就管不了这里了，这些键绑定由 vscode 自身管理，配置写在keybindings.json里。

### 下文中的<leader>键指的是空格键

代码跳转
1. 转到定义 gd
2. 转到引用 gr
3. 转到实现 gi
4. 跳回 ctrl o
lsp
1. 代码格式化 <leader>lf
2. 变量重命名 <leader>lr
3. 定义速览 K
4. 代码注释 gc
5. 代码动作 ctrl+. vscode 自带
6. 代码诊断 ctrl+shift+m vscode 自带
7. 代码折叠 zc vim 插件自带
8. 代码展开 zo vim 插件自带
9. 代码全部折叠 <leader>zc
10. 代码全部展开 <leader>zo
搜索
1. 全局搜索文件 <leader>ff
2. 全局搜索文字 <leader>fw
3. 全局搜索后聚焦到结果列表 enter
4. 从搜索结果列表回到搜索输入框 esc
5. 从搜索输入框回到编辑器 esc
6. 普通搜索 ctrl+f vscode 自带
当前编辑器
1. 保存 <leader>w
2. 关闭 <leader>c
3. 退出 vscode <leader>q
编辑器组
1. 上一个标签页 (
2. 下一个标签页 )
3. 上一个标签组 ctrl+h
4. 下一个标签组 ctrl+l
5. 移动到上一个标签组 <leader>H
6. 移动到下一个标签组 <leader>L
7. 关闭组内所有标签 <leader>gc
8. 缩小 ctrl+left
9. 扩大 ctrl+right
文件操作
1. 打开文件浏览器 <leader>e
2. 关闭文件浏览器 ctrl+b vscode 自带
3. 在文件浏览器里上下浏览 j k
4. 打开文件 o 或 enter
5. 在新标签组打开文件 O
6. 新建文件 a
7. 新建文件夹 A
8. 删除 d
9. 复制 y
10. 剪切 x
11. 粘贴 p
12. 重命名 r
13. 刷新文件浏览器 R
