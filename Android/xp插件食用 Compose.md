# 非常小的一个问题
最近在 xp 模块上用 Compose 去做布局，然后因为不太熟练的原因遇到了一个白屏问题

在 [韵の祈姐姐](https://github.com/teble) 的帮助下，找到了问题原因（使用 NavHost 导致的）

大概的解决思路是加了一个加载动画，判断是否是第一次加载

暂时放弃 Compose，因为 ComponentActivity 出现了暂时无法解决的问题