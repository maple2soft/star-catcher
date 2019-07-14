# star-catcher
cocos creator official sample rebuild version

“坑爹”的摘星星小游戏

## git的一些基本语法

    参考
    [从零做一个前端开源项目](https://www.imooc.com/article/28240)

## 更新.gitignore文件

更新了.gitignore文件，并且修正了其中一处错误
library/
temp/
build/
local/

*.meta

## 往往我们新建一个项目，有些让都会忘记写.gitignore，直接提交到了远程仓库。

导致了把一些ide到配置文件提交上去，这个时候再去写.gitignore 去忽略是没有用到，因为这个文件已经在远程仓库了。

解决方法: 

    `git rm --cache -r filename`
    `git add`

然后提交推送至远程仓库即可。

