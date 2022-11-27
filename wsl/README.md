## 环境安装教程

[https://github.com/yuk7/ArchWSL](https://github.com/yuk7/ArchWSL)
下载arch，并且配置好wsl
[https://daisilia.com/projects/wsl-%E6%BC%94%E7%A4%BA-neovim-%E9%85%8D%E7%BD%AE%E5%AE%89%E8%A3%85/](https://daisilia.com/projects/wsl-%E6%BC%94%E7%A4%BA-neovim-%E9%85%8D%E7%BD%AE%E5%AE%89%E8%A3%85/)
[https://www.bilibili.com/video/BV1C44y1g7Sg/?vd_source=bf2eb56a3cf8bfab8a0055c7e65696f1](https://www.bilibili.com/video/BV1C44y1g7Sg/?vd_source=bf2eb56a3cf8bfab8a0055c7e65696f1)



## wsl注意事项
cat /etc/resolv.conf
得到类似下面的输出：
nameserver 8.8.8.8
proxy 出外面的加速器


```
brew install neovim
curl -L https://raw.githubusercontent.com/RunningIkkyu/dotfiles/main/nvim/config_nvim.sh | bash
# 进入neovim后
:PackerSync 
:LspInstall pylsp （pyright   golsp）跳转
:GoInstallBinaries
pip install 'python-lsp-server[all]'
yarn global add diagnostic-languageserver
ripgrep
```


# 使用教程a
```
gd跳转，ctrl o跳回
u撤回       ctrl r回退操作
，p 全局搜索  （需要安装ripgrep）
空格 p 文件搜索
，n 目录树
alt w关闭当前窗口
（）切换tab
ctrl w v/s 横/竖
ctrl w w 切换tab
*号选中单词高亮
选中文本//搜索
选中c代替
viw    viW 选中
vip 选中一整段
t 跳转
, h 1跳转
:Git blame 每行的commit
:BlamerShow
:DiffviewOpen 所有未提交的改动
[ d 跳转错误
\RN  重命名
zM zo 折叠
:%s/jasdiouqoi/hsdfuoihwseiuf/g
gs 查看
:DiffViewShow
zz 居中
\mt merge 报错
\d 选中
v $ 选中后吗对内容
ctrl w = 均分窗口
J 两行合并
A最后 I最前 
ctrl z   fg
gc 注释
```
