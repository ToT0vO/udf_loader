# 简介
利用mysql的udf机制，将shellcode加载到内存中执行

# 效果
根据测试可以过360的核晶模式执行命令，因为进程是mysql，所以360并不会将其关闭，直接拦截操作
更详细的效果可以参考笔者的另一篇文章
> https://github.com/ToT0vO/Whitelist/blob/main/Whitelist_lateral_movement.pdf

