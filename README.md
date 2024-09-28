# git-handbook
git 常用指南，记录git操作。  
![git_logo](https://git-scm.com/images/logo@2x.png)

## 回滚
> git reset --hard FETCH_HEAD  

我常用这个命令回滚，适合想要快速实现本地和远端代码一致的情况。理由是本地可以通过`stash` 或者其他方式保存代码，本地操作异常或者合并中，变基中都可以快速回滚。

------------------------------  
