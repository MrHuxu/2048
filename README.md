#2048 by TDFJ  

用Ruby写的在终端里跑的2048，上下左右键操作，q退出，操作后按回车确定  

如果按下没反应，请自行修改方向键的判断字符串  

实现了2048游戏的大部分功能，还有两个地方没有解决：  

1. 成功玩到2048，没有相应的提示。其实我已经写好了判断胜利的方法，但是我目前还没有玩到过，就懒得调用这个方法了  

2. 游戏失败的判断方法没有完成。我现在只写了一个判断又没有空格的语句，实际的2048游戏在格子被填满后，还要判断是否有相邻的相同的数字，如果有就不算失败，略麻烦懒得写了  

---  

update @ 2014.07.10: 修正数字没有变动时仍然会出现心数字的情况