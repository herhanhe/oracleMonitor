# <a name='preface'> Oracle Dba 监控脚本</a>

>Oracle无疑是当今最优秀的数据库之一，在功能、性能等方面都非常的卓越。但要学好、掌握好Oracle也是一件不易的事件。

>笔者曾经维护开发过一个广东省省集中的大型系统，典型的项目紧、时间短、数据量大、业务复杂、并发高。上线初期，各种应用问题频出：界面打不开、SQL运行慢、数据库c pu使用率高达95%、IO持续高位不降。
>
>当时面对紧急状况，为定为问题，查看各种性能视图，执行百度、google 搜索回来或临时编写的sql脚本，可谓手忙脚乱，还经常出错，高峰期过了，问题还没有定位到。下次问题来了，又是手忙脚乱。
>
>领导不满意，能力受到质疑，自己的面子也挂不住呀。

> 后来使用一些监控工具，感觉工具使用起来比较繁琐
>
> * 需要监控的信息，有时要点击好几层菜单，才能出来结果
> * 信息显示不够友好，需要的信息没有或显示在了另一个界面里
> * 有些监控工具，在后台安装一堆脚本，也不知道是干嘛用的
> * 如果功能不满足，还是要自己动手写
> * 当作日常维护还可以，拿来快速全面地定位问题、分析问题不够直观

> 我认为比较理想的情况应该是：在sqlplus里输入简单的指令，输出全面的、格式化的、直观的有用信息。
>
> 如果这些信息统一输出到一个文件目录，形成文件，方便以后查看，对比分析，那就非常好了。
>
> 本套脚本就是为了达到上面的效果，由笔者根据多年工作经验总结完成。

> 不管是Oracle刚入门新人、还是工作多年的老司机，我相信都能够从这套脚本学到东西，并提高工作效率，使自己的工作更得心应手。

[session监控](/docs/session.md)
  [Lock监控](/docs/session.md#lock)
