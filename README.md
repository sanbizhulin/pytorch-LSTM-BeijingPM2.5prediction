# pytorch-LSTM-BeijingPM2.5prediction
Thanks for others result, I comment and summary from other result and run their demos in order to understand LSTM of Pytorch

代码用的是pytorch框架，在我本机上跑通了，我用的环境是
Anaconda3
Pycharm 2017.3.3 Professioal 版
LSTM经典思想：
date作为index，没有放入模型里训练。
个人觉得数据预处理的关键是，用前一个小时的PM2.5值作为当前小时的一列新特征

