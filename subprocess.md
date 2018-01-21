### subprocess
subprocess.Popen参数的
`shell=False`和`shell=True`的区别

1 False的情况是由python执行命令
`cmd=['ls', '-a']` 使用list传递参数

2 True是使用shell执行命令
`cmd='ls -a'` 使用完整的命令字符串传递参数

communicate方法
与进程进行交互，将数据发送到stdin，从stdout和stderr中读取数据，直到文件末尾，等待进程终止，可选参数input是发送给子进程的字符串，如果没有要发给子进程的数据则为None，communicate方法返回一个元祖(stdout, stderr), 该方法会把命令执行变为了同步，不执行完成就一直阻塞
