# 执行命令
- fork, 新开进程执行脚本，脚本中的变量不会传到父进程, 执行结束回到父进程, sh xx.sh or ./xx.sh 
- source, 在当前进程执行, 脚本变量能传到父进程, 执行结束继续执行, source xx.sh or . ./xx.sh
- exec, 不新开进程，替换当前进程，所以该行之后的脚本不会再执行, exec cmd
