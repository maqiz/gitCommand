# gitCommand
$ git config --global user.email '450526344@qq.com'		设置邮箱
$ git config --global user.name 'qq450526344'			设置github用户名
$ git mkdir test 						新建子目录文件
$ pwd								当前目录
$ ls								当前文件地址
$ git init							当前目录里新建一个.git的隐藏文件，存储仓库信息的 
$ touch a1.html							新建一个html文件
$ git add a1.html						文件从工作区域添加到暂存区域
$ git commit -m 'add description'				将暂存区域文件提交到仓库
$ vi a1.html							修改文本内容
i || insert							命令模式改成编辑模式
ESC								退出编辑模式，回到命令模式
ZZ || :wq							保存修改并退出vi
:w								回车后底行会提示写入操作结果，并保持停留在命令模式。
4、放弃所有文件修改：
（1）放弃所有文件修改：按下 "ESC" 键进入命令模式，键入 ":q!" 回车后放弃修改并退出vi。
（2）放弃所有文件修改，但不退出 vi ，即回退到文件打开后最后一次保存操作的状态，继续进行文件操作：按下 "ESC" 键进入命令模式，键入 ":e!" ，回车后回到命令模式。

$ rm -rf a1.html						删除工作区文件
$ git rm a1.html						删除暂存区文件删除或需要提交到仓库
$ cd test							进入到某个目录
$ git config --list						查看配置
