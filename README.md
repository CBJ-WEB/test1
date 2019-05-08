# test1

情况:有远程仓库。直接clone远程仓库到本地（这个不需要关联），在这个本地仓库各种操作后提交本地仓库的代码到远程仓库
1.初始化一个本地仓库（.git文件，默认是不可见的）
git clone https://github.com/CBJ-WEB/test1.git
2.在git的同级的路径下，添加代码。添加新变化的 代码到暂缓区
git add .
4.提交暂缓区的代码到本地仓库
git commit -m"xxxxx"
5.提交本地仓库的代码到关联的远程仓库
git push origin master
