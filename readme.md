#一个纯Lua的excel解析库
在游戏开发中需要建立许多数据表，提供给程序读取配置。一般采用excel表的形式，然后通过某种方式转换为程序使用的数据。

我就写了这么一个纯lua的代码来解析这些数据，当然，这里的excel是另存为xml格式的表格，而不是.xls文件，其内容并不会有什么变化。为什么没用csv逗号分隔格式呢，因为xml支持一个文档中包含多个表格，这样才和xls完全一致。

代码完成度不算100%，因为肯定不会符合你的实际使用情况，最后还是需要你自己修改代码。