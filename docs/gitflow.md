#git flow

- 是什么？

1. 根据git来定义的一套开发流程规范；
2. 它拥有一些一些自己的扩展命令；使用脚本对于git命令的捆绑，本质执行的还是git命令；

- 规范流程
1. master    分支与线上同步；
2. develop   最新的开发完成后的合并代码，并最终与master分支代码，保持一致；
3. 。。。。

- 怎么使用
1. git flow init 初始化项目，默认操作即可；
2. git flow feature start 特性名称 创建新特性的开发分支，【开发，修复，提交，保存】
3. git flow feature finish 特性名称 将开发好的特性分支，合并到develop，并删除此分支

- 注意点
1. 不要在master,develop分支做开发工作



#git 

- 技巧
1. 设置当前仓库的姓名，邮箱       git config user.name/user.email