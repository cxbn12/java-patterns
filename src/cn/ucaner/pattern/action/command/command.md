# 命令模式（Command Pattern）

> 将请求 封装成一个对象，从而让你使用不同的请求把客户端参数化，对请求排队或者记录请求日志，可以提命令的撤销和恢复功能

话不多说 直接撸码

举个栗子

在平时开发中   基本上都是老板一个命令，然后下面的人都要XXXX（此处省略32个字）



比如你们有以下几个（产品，UI，开发）小组，老板每次都直接找需求，找UI，或者找开发，直接改东西（自行想象老板让开发的搞完之后产品不知道，UI也不知道，让UI改完之后开发不知道吧啦啦啦啦小魔仙。。等等）



于是乎，，，



上代码



| 类名             | 描述     |
| -------------- | ------ |
| Command        | 处理命令   |
| Group          | 抽象执行者  |
| AddPageCommand | 新增一个页面 |
| Invoker        | 负责人    |
| Code           | 你自己    |
| Product        | 产品经理   |
| UI             | UI     |





优缺点请参考XMind文件里的总结

