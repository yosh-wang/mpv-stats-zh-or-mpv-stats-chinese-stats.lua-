MPV内置代码连接

未翻译的英文原始文件地址：

https://github.com/mpv-player/mpv/blob/master/player/lua/stats.lua


<img width="3837" height="2154" alt="微信图片_2026-03-01_112007_816" src="https://github.com/user-attachments/assets/34541caf-e934-4ef8-84f4-75fa6c37e707" />


步骤 1：编辑主配置文件

在你的 mpv.conf 文件中，添加或确认以下一行。这行代码会关闭 mpv 内置的英文版统计脚本，为我们的中文版脚本让路。
在你的mpv.conf文件中，添加或确保有以下行。
这禁用了内置的英文统计脚本，以便为我们的中文版本腾出空间。

在 mpv.conf 中添加：
#关闭内置统计脚本 [stats.lua] (默认启用)，以使用外部中文版
#禁用内置的统计脚本[stats.lua]（默认启用）以使用外部中文版本
加载统计覆盖=否

步骤 2：放置中文版脚本
步骤 2：放置中文文本
将我们翻译好的 stats.lua 文件，放入 mpv 的脚本文件夹中。
将我们的翻译 stats.lua 文件放入 mpv 的 scripts 文件夹。


目标位置 / 目的地: portable_config/scripts/
绝对路径示例
Windows: C:\Users\你的用户名\AppData\Roaming\mpv\scripts¥
Linux/macOS: ~/.config/mpv/scripts/


步骤 3：开始享用
步骤 3：享受吧！

完成以上两步，你的配置就大功告成了！现在，无论你使用的基础综合配置是什么，都可以：
一旦完成这两个步骤，您的设置就完成了！现在，无论您使用的是什么基础综合配置，您都可以：

按 i 键：临时查看全中文的播放统计信息。

按 I (大写) 键：让统计信息常驻屏幕。
按 Shift + I: 让统计信息常驻屏幕。

按 1-5 或 0 键：在不同信息页面间切换。


