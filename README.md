# -小技巧tis
## 1. linux下利用 > ls sh 写入文件并命令执行
利用场景:限制命令执行长度</br>
linux下 >xx\\\\ 生成xx\\文件 \\\\转义\\ \\表示还输入未完 拼接文件名</br>
下面执行命令为 curl www.baidu.com
倒序划分 长度不超过7(包括空格和\\)</br>
![1.jpg](https://i.loli.net/2019/06/10/5cfd5f8e1c43d31940.jpg)</br>
具体执行</br>
![2.jpg](https://i.loli.net/2019/06/10/5cfd5f8e1f07723833.jpg)</br>
ls -t>a 以创建时间顺序写入a文件</br>
![3.jpg](https://i.loli.net/2019/06/10/5cfd5f8e2bf8c51890.jpg)</br>
sh a 执行a文件</br>
![4.jpg](https://i.loli.net/2019/06/10/5cfd5f8e6bcf946926.jpg)</br>
未完待续....</br>
