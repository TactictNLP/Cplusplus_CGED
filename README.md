# Cplusplus_CGED

中文语法检纠错项目，应用于文本自动生成后的自动检纠（大大解放我司编辑妹子们的生产力），用于HSK的作文评分等场景。


原始代码来自@DancingSoul,感谢作者分享。本项目分只享改进的关键代码，数据和分词预训练模型较大，暂不上传，项目近期持续更新中。


初步运行结果如下:（CGED比赛官方提供了评测工具，评测是基于句子的；这里使用自己的评测，基于标签的；）

Label| Precision | Recall | F1-score | Support 
|-|:-:| :-: | :-: | :- 
0 |0.97| 0.99|0.95|144319
B-R|0.44|0.32|0.37|791
I-R|0.55|0.24|0.34|376
B-M|0.39|0.34|0.36|923
I-M|0.00|0.00|0.00|0
B-S|0.48|0.38|0.42|1605
I-S|0.55|0.38|0.45|1280
B-W|0.73|0.28|0.41|277
I-W|0.79|0.29|0.43|1248


部分检测结果如下：

![cged_0](http://wx3.sinaimg.cn/mw690/aba7d18bgy1fu4mjgm3dvj213z0kmjvl.jpg)

![cged_1](http://wx3.sinaimg.cn/mw690/aba7d18bgy1fu4mjh7a48j21440ln0xd.jpg)
