mvc课堂学习
----------
###学习笔记


1. laeavel文档
2. orm会进行包装，返回的是一个对象
3. 增加、修改、删除。会帮你自动生成id，
4. orm会自动检测数据的类型
5. orm中有3个白名单和2个黑名单字段，黑名单不允许客户端修改，白名单允许客户端进行修改。
6. new在内存创建一条记录，create是直接在数据库里创建一条记录。
7. 软删除的方式，delete数据库里的东西就删除了，软删除是用字段标记已经删除，但是并未被删除，将来可以恢复的。
8. 时间戳，查询标记，要执行很长串的查询，并且要查询多次，每次查询的时候不想敲这么多代码，可以定一个书签，下次查询的时候调用下书签，动态书签，允许放参数，还有全局书签，不绑定任意对象。
9. 查询本身，数组对象不一样的
10. take方法和传入一个查询对象，比字符串拼接好处理多了，
11. PostModel=>post_model 用正則表达式的方式改变
12. 模式事件，观察者模式，
13. 本地全局作用域的内容
14. 字符串中有害的函数，用于过滤用户输入的字符串
15. html代码和php代码分开，代码与模版分离，把index变成两部分，一部分纯代码一部分纯模板
16. 消除重复，把重复的代码做成子模版，但是只有开头没有结尾的模版看起来很奇怪，解决方法，做一个结构，模版部分只做成窗口的部分，其他部分做成活动的部分
17. 模版里定义一个布局，侧边栏默认使用字符串，同时可以增加新的内容，blade，模版and活动窗口。
18. 布局文件，把所有页面的固定部分写入。
19. 把逻辑和显示分开，为了后期的代码重复做准备。
20. 以前的index文件是重定向，以后url的布局方式和文件的布局方式不一样，改成单路统一，single，方式，router，把单路方式翻译成文件路径。
21. 动态生成类，动态语法，不需要静态写文本量，
22. 八个文件变成八个函数
23. .mvc模式层都代表什么，存数据和取数据，交给v层渲染，controller层主要是连接m和v层的作用。
24. 有名字的路由，注重下全局观念，这样文件会大量减少，但模式文件下会多8个文件，
25. compact函数，返回的是两个脚本之间传递内容的方式，

##作业：重构博客，用新的方式。