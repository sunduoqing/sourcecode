# jquery基础

## 事件相关函数

1. bind()/unbind()

    原理应该是给该元素绑定监听事件，因此无法进行动态绑定

2. on()/off()
3. one()
4. live()/die()

    可以实现动态绑定，原理是利用事件代理，但是父元素选择了根节点，在根节点上绑定了各种监听事件的处理函数，导致性能问题。

5. delegate()/undelagate()

    事件代理
