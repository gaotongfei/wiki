Mac OSX 安装: `brew install ctags`

在你想要创建tags的目录下执行: `ctags -R .`

可能出现的问题: `illegal option -- R`

解决方法: `alias ctags="brew --prefix/bin/ctags"`

打开vim, 使用`ctrl+]`可以跳转到对应的源文件中, 用`ctrl+t`跳回去

