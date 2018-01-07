# 12306-SMS-to-Calender
iOS上的Workflow实用例子


### 一、缘由
网上有许多iOS的Workflow分享, 其中就有火车票短信的转日历的, 但碍于网上分享的许多都不完善, 还需要自己手动输入短信中没有的信息, 所以决心写一个完善的, 特此春节来临之际, 分享给大家, 希望好使

### 二、流程
大概就是先用正则匹配出短信中的有用信息, 然后调取jisuapi的免费接口, 获取到车次相关信息后, 再进行处理, 最后生成日历项目, 为了确保接口能调通, 需要大家自己去申请apikey, 每个key都有1000次免费的机会, 用完了还可以买, 当然我没有分享key, 就是因为1000次一个人使用是绰绰有余的

请用 iPhone 的 Safari 打开, 然后点击 GET WORKFLOW, 请务必确认自己已经安装了Workflow
链接:[https://workflow.is/workflows/79dbdbcf38ee4c048d58839b792adf5b](https://workflow.is/workflows/79dbdbcf38ee4c048d58839b792adf5b)

api请自己去申请:[https://www.jisuapi.com](https://www.jisuapi.com)

### 三、效果
为了演示, 修改了之前的某条短信信息, 结果大概就是这个样子
![](https://raw.githubusercontent.com/dominic-lian/12306-SMS-to-Calender/master/IMG_5943.PNG)
![](https://raw.githubusercontent.com/dominic-lian/12306-SMS-to-Calender/master/IMG_5944.PNG)
![](https://raw.githubusercontent.com/dominic-lian/12306-SMS-to-Calender/master/IMG_5945.PNG)

