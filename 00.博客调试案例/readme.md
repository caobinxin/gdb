参照博客：https://www.cnblogs.com/azraelly/archive/2012/12/22/2829256.html

until 退出循环
ptype 

b if i=5打断点
watch i i值发生变化后，打断点
观察点使用参考：http://blog.chinaunix.net/uid-22996709-id-3354587.html
watch i 写观察点
rwatch i 读观察点
awatch i 读写观察点

info breakpoints 查看断点信息
info watch 查看观察点信息
disable 4 取消观察点和断点

finish 退出真个函数

bt 查看堆栈信息



gdb 参数
GDB启动时，可以加上一些GDB的启动开关，详细的开关可以用gdb -help查看。我在下面只例举一些比较常用的参数：
 
    -symbols <file> 
    -s <file> 
    从指定文件中读取符号表。
 
    -se file 
    从指定文件中读取符号表信息，并把他用在可执行文件中。
 
    -core <file>
    -c <file> 
    调试时core dump的core文件。
 
    -directory <directory>
    -d <directory>
    加入一个源文件的搜索路径。默认搜索路径是环境变量中PATH所定义的路径。

