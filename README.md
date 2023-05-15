# miniprogram

api/componen css templete using by ttml

# 前端框架跑到小程序上

关于前端框架跑到小程序上，大致可以分类两类：

1. 基于模版 template 的，对于这类往往我们只需要对应框架实现数据变更的方式变为小程序的 setData，其他的 css 保存为 ttss，template 变为 ttml 即可
2. 基于 jsx 的，这类往往我们需要实现一个 dom 接口来模拟变更。虚拟 dom 接口就像 taro 那样，通过递归 template 方式来实现。

实际上只要我们模拟出来了 dom 接口其他前端框架都可以跑起来，之所有 uniapp 那样做，是因为他们省去了一个运行时会更加节约性能。
