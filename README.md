python的socket编程(主要指tcp)我很喜欢用，但是又一直很让我头疼，主要在于总是会出现各种各样的错误导致程序终止运行，需要处理的东西太多。每次也都会重新定义一个应用层协议，总之很麻烦。于是我想设计一个`自用的`socket编程的模块，其中硬编码进去一个我觉得合适的应用层协议，同时将常用的功能进行封装，处理各种Exception，目标在于简化socket编程，同时让程序更加稳定，不易出错。

现在已经做出了一个python版本的模块，并且昨天到今天已经优化到了第二个版本，同时，今天也在这个模块的基础上做了一些样例，例如新版的Filer局域网点对点文件与短消息传输工具。

第一个版本的模块在2019年末完成，旧版本的说明和代码保存在archive仓库的script文件夹中，现将新版本单独建立一个仓库，便于管理。

时间不早了，明天再写详细介绍。