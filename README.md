# 创建基于 github 的毕设项目

1. 安装 git

1.1 下载 git

1.2 安装 git

2. 注册 github 账号

```
WYZ214
1713654484@qq.com
wyz19990214
```

3. 创建 github 仓库（repository）

仓库名字以`姓名项目名`方式命名，使用驼峰拼写

4. 创建公钥私钥

4.1 配置 git 账户

4.2 创建密钥

4.3 将公钥`id_rsa.pub`中的内容在 github 中建立密钥

5. 将 github 上建立的项目 clone 到本地磁盘，比如 e 盘底下某个目录

这步执行有问题，可以多试几遍 git clone 命令，每次试之前要把上次 clone 的目录删掉

6. 以后可以执行同步脚本`sys.bat`

以后可以直接在本页面下载该文件到你的仓库即可，每次修改完仓库内容，可以点击执行该bat文件完成同步，也可以在IDE中进行同步，下面会介绍

7. 在IDEA中进行git操作

这是可以仍旧使用`syn.bat`进行同步，也可以通过IDEA进行操作，直接进行`VCS->Commit`提交至本地仓库操作，然后使用`VCS->Git->Push`更新至github远程仓库，不是IDEA操作的文件，比如这里的文本文件就不会被IDEA更新至github，仍然需要使用`syn.bat`进行同步