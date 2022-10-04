# Git_tutorial
For gdpu_cs_org

~~在GitHub上面写教程绝对不是我没法写博客~~

## Pre 
    Git/GitHub 有什么用? 
        在你玩RPG游戏的时候,你应该会体验过存档这个功能。
        Github就是存放你代码(项目)的地方,通过存档你可以的做到: 版本控制/回档  
        Git 就是一个存档工具

        毕竟谁也不想让自己的代码消失吧 = = 
## Step 0
    准备: 
        Shell 
        git                 最稳定
        tabby_terminal      https://github.com/Eugeny/tabby

## Step 1 

    首先我们要生成ssh密钥(其实就是 .ssh文件夹)
        切换到根目录 ~ 下 : ssh-keygen

        cd .ssh
        
        cat id_rsa.pub      复制 -> 注册到 SSH settings

## Step 2
    注册一个仓库捏

    打开shell -> gitclone http/ssh 

    //接着开始配置全局变量
    git config --global user.name "Name"
    git config --global user.email "Email"

## Step3 

    随便写点东西

    git add . 

    git commit -m "add README" 

    git push 

## Step 4 

    学习下回档咯

    git -reset --hard "hash"
    