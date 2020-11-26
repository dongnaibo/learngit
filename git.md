**版本库**  
![stage暂存区 master主分支](https://www.liaoxuefeng.com/files/attachments/919020037470528/0)
<br><br>

**git常用命令**  
|命令|简要说明|
|-|-|
|`mkdir repository`|创建文件夹repository|
|`pwd`|显示当前目录|
|`git init`|将该目录变成Git可以管理的仓库|
|`touch readme.txt`|新建readme.txt文件|
|`vi readme.txt i :wq`|编辑readme.txt文件|
|`git add readme.txt`|将readme.txt文件添加到暂存区|
|`git commit -m "wrote a file"`|把文件提交到仓库|
|`git status`|查看仓库当前的状态|
|`git diff readme.txt`|查看文件的变化|
|`git log`可以加上`--pretty=oneline`显示在一行|显示从最近到最远的提交日志|
|`git reset --hard HEAD^`|回退到上一个版本|
|`git reset --hard`+commit id|回退到某个版本|
|`cat readme.txt`|查看readme.txt文件的内容|
|`git reflog`|查看被记录下来的命令|
|`git restore readme.txt`|把readme.txt文件在工作区的修改全部撤销|
|`git restore --staged readme.txt`|把暂存区的修改撤销掉|
|`git rm test.txt` `git commit -m "remove test.txt"`|从版本库中删除test.txt文件|
