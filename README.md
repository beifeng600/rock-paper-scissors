# rock-paper-scissors
基于Rasa3 的 rock-paper-scissors 游戏。会用到 entities、slots、actions。

# 环境

需要安装 python环境，建议 3.8

如果是用conda，请切换到该 环境

# 运行


## 训练
命令行中输入
`rasa train`
会在models生成新的模型，比如 20220816-085245-eager-mozzarella.tar.gz

## 运行
需要打开两个命令行窗口
 
窗口1，输入
`rasa run actions`
会输出几条信息，如下图
![rasa_run_actions](https://user-images.githubusercontent.com/8060693/184768625-60bb2778-c391-4ec3-be2b-b348383ff9e7.png)


窗口2，输入
`rasa shell`

加载模型结束后，会出现提示输入信息。
![E1UOXHM(QTFSH 4JLNJNPHP](https://user-images.githubusercontent.com/8060693/184769024-5407c4a5-ac00-4c20-9741-dfe0f28fccdb.png)
