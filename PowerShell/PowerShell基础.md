>Tips：使用 PowerShell 执行脚本语言可能会对计算机配置有所影响，请谨慎使用。

# 0. PowerShell 与 cmdlet
## What is PowerShell？
>“PowerShell 是一种命令行 shell 和脚本语言一体化工具。 PowerShell 由 Windows 推出。它原本是为了帮助实现管理任务自动化，但现已发展为跨平台，可用于执行多种任务。”[^1]

Windows PowerShell 在 .NET CLR 和 .NET Framework 的基础上构建，可以接受和返回 .NET 对象，而并非使用文本，这可以让 PowerShell 在一个管道中串联不同的命令。

##  Why PwerShell?
1. .NET Framework 令其可以更好地使用 .NET 平台下的类库，大大提高了拓展性
2. 基于 Microsoft 提供的强大支持以及平台可扩展性，令 PowerShell 具备包括但不限于 Windows 任务自动化、云管理、CI/CD 等功能。
3. 面向对象

## What is Cmdlet?
cmdlet 是在 PowerShell 环境中使用的一种轻量级命令。 PowerShell 运行时在命令行中提供的自动化脚本的上下文中调用这些 cmdlet。 PowerShell 运行时还通过 PowerShell Api 以编程方式调用它们。[^2]

关于 cmdlet 的使用，后续会逐步介绍并拓展

# 1. 启动和使用 PowerShell

## using PowerShell
在 Windows 平台下，可以通过右键开始菜单->Windows PowerShell 打开 PowerShell。（在 Windows 11 下，微软已经将默认命令终端应用程序替换为 Terminal，打开 Terminal 后同样可以使用 PowerShell）
![](https://cdn.jsdelivr.net/gh/PowerShell/202212051944839.png)

您同时也可以使用 Windows 下搜索功能搜索 PowerShell 应用直接打开原生 PowerShell 使用。

![](https://cdn.jsdelivr.net/gh/PowerShell/202212051944820.png)

# 2. PowerShell 的基本操作
## 1. using PowerShell Calculators
PowerShell 可以作为计算器使用，我们可以以键入命令行的方式来输入数学表达式并直接运算，在 PowerShell 中可以自动计算并输出结果。包括加减乘除运算以及各种进制运算皆可成功执行
![](https://cdn.jsdelivr.net/gh/PowerShell/202212051945721.png)
同时 PowerShell 底层也保存了计算机基本容量单位换算
![](https://cdn.jsdelivr.net/gh/PowerShell/202212051945190.png)

# 参考文献

[^1]:[探索 PowerShell - PowerShell | Microsoft Learn](https://learn.microsoft.com/zh-cn/powershell/scripting/discover-powershell?source=recommendations&view=powershell-7.2 )
[^2]: [Cmdlet 概述 - PowerShell | Microsoft Learn](https://learn.microsoft.com/zh-cn/powershell/scripting/developer/cmdlet/cmdlet-overview?view=powershell-7.2&viewFallbackFrom=powershell-6)

