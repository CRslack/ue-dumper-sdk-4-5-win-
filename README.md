# ue-dumper-sdk-4-5-win-
介绍了ue4-5的主流dump工具
https://github.com/guttir14/UnrealDumper-4.25 外部dumper sdk 支持4.23-4.27
![image](https://github.com/user-attachments/assets/689f592d-877a-4cf4-95af-8570df9b7b54)
在engine.cpp中填写游戏名称和对应的特征码

https://github.com/GoLang1337/UE4Dumper-Kernel?tab=readme-ov-file
如果遇到游戏保护可以尝试此项目，在上面项目的基础上，对接了驱动黑骨库，主要使用了模块查询和内存读写，但是此项目内核层写死了游戏名。

https://github.com/Encryqed/Dumper-7
此项目为dll注入游戏进程，利用特征码和findobject 修复结构并获取所有偏移，对于没有加密的游戏基本能做到通杀，注意在某些反作弊中检测线程和需要内核注入
![)$9()_OTREMZQ(O`YID7(W7](https://github.com/user-attachments/assets/2efd89a5-812b-4cd1-82ce-7b5a7aa290e5)








我的项目为修改https://github.com/GoLang1337/UE4Dumper-Kernel?tab=readme-ov-file项目使内核接收三环参数进行返回
