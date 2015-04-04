# git-config

## 让git log变成彩色
命令：
````
git config [--global] color.ui true
````
.git/config配置文件
````
[color]
  ui = true
````
## 让git log每条记录显示为一行
命令：
````
git log --pretty-oneline
````
样式：oneline, short, medium, full, fuller, email, raw, format:<string>
    defaults to medium.
.git/config配置文件
````
[format]
  pretty = oneline
  
``
git config core.editor <vim>  # interactive commands
git config merge.tool <opendiff>  # merging/conflicts
``
