# awk
awk 'program' :

awk会将program应用于你在终端中接着输入的任意数据行，直到你输入一个文件结束信号 Ctrl+d;

if we want to excute program file, then : awk -f programfile     optional list of input files

Awk会对当前输入的行有多少个字段进行计数, 并且将当前行的字段数量存储在一个内建的称作 NF 的变量中

Awk提供了另一个内建变量, 叫做 NR, 它会存储当前已经读取了多少行的计数
