- Git 是什么？
    代码的管理软件
    版本控制能力
    1. 提交到GitHub, 电脑坏了
        多个地方存储  本地仓库
        远程仓库
    2. 一个文件， 反复修改， 文件版本
        精细化到你这一次改了哪一行
        
1. 将项目变成版本控制项目
    git init
    - .git 隐藏目录
        文件的每一次修改， 都像拍照片一样 放到  .git 目录下
        专业的， 不要乱动
    - 默认的仓库 master
    - 支持随时的查看一个文件的任何版本 很重要
    - .git 本地仓库  2步骤  慎重
        例如：
        超市 买东西
        git add readme.md       暂存区
        git commit -m 'add readme.md'   仓库
    - git log 命令
        hashID 唯一值  git config --global user.name "AiXueXiDeYu"


    - git status 当前仓库的状态
        
