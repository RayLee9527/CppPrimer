练习6.20：引用形参什么时候应该是常量引用？如果形参应该是常量引用，由我们将其设为了普通引用，会发生什么情况？

不需要修改其绑定对象时应该设置成常量引用。

如果应该为常量引用而实际用了普通引用，那么函数可能不经意间修改了引用绑定的对象。并且无法传递一个常量对象给
形参。