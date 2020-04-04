Game File 火炬之光2游戏文件解析
==============================================================================

Steam 版火炬之光游戏版本: 1.25.6

- Steam 版火炬之光游戏目录: ``C:\Program Files\Steam\steamapps\common\Torchlight II``
- 游戏数据存储目录: ``C:\Users\username\OneDrive\Documents\my games\runic games\torchlight 2``
- 人物存档: ``C:\Users\username\OneDrive\Documents\my games\runic games\torchlight 2\save\charactername_{uuid}.restore``
- 共享存储箱中的物品文件: ``C:\Users\username\OneDrive\Documents\my games\runic games\torchlight 2\save\sharedstash.bin``


利用游戏 Bug 刷装备
------------------------------------------------------------------------------

**通过备份** ``sharedstash.bin`` **复制装备的详细过程**:

原理:

共享存储箱中的物品信息保存在 ``C:\Users\username\OneDrive\Documents\my games\runic games\torchlight 2\save\sharedstash.bin`` 文件中. 而人物物品栏中的物品信息保存在 ``charactername_{uuid}.restore`` 文件中.

操作:

将打到的暗金装备放到共享存储箱中. 然后返回游戏主界面 (保存游戏). 备份 ``sharedstash.bin`` 文件到其他位置. 进入游戏, 将共享存储箱中的物品取出来. 将备份的 ``sharedstash.bin`` 文件拷贝回去. 这样共享存储箱中的物品就乘2了.

**通过备份** ``charactername_{uuid}.restore`` **文件无限刷 Boss**.

操作:

在打Boss之前 (传送之前), 保存游戏, 并将 ``charactername_{uuid}.restore`` 文件备份到其他位置. 杀死 Boss 后回城, 将战利品放入共享存储箱. 然后恢复 ``charactername_{uuid}.restore`` 文件. 就可以再次杀 Boss 了.
