# 关于krkrz中的tjs2文档汉化说明
krkr2就已经有了tjs2的汉化文档，不知道具体的krkr2对应版本但我推测是2.28，
krkrz的tjs文档也是以该文档为基础的。
krkrz相对于krkr2 2.28的tjs有一定变化（有些变化是2.32已经出现的，不一定是krkrz的改动），但整体基本一致，在这里列出所有已知的变化：
1. Array类的save方法增加了b的模式
2. Array类增加了push、pop、shift、unshift和pack五个方法。
3. 字节串增加unpack方法。
4. 正则表达式去掉了l标志。增加RegExp.last方法。变更了依赖库为鬼车。
5. String类indexOf方法增加开始下标的参数。
6. 文档一些错误的修正。