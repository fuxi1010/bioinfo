# awk
awk 'program'

awk will wait for us to input in the terminal untill we use Ctrl+d to end this;

if we want to excute program file, then : awk -f programfile     optional list of input files

Awk会对当前输入的行有多少个字段进行计数, 并且将当前行的字段数量存储在一个内建的称作 NF 的变量中
