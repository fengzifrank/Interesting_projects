# World_Cup_Predict
2018俄罗斯世界杯预测
世界杯要开始了，写了个算法预测，算法很简单，使用的特征也不多，到时候坐等被打脸。
另外，如果谁有参赛队伍的历年人员变动的数据可以提供一下吗？
# 2018.6.29更新
world_cup_GroupAnalysis+Top8.py
<br>  
要使用里面包含两部分，一是对上次小组赛结果的对比分析，二是八强预测
对于第一部分，我用的是欧赔平均，每场比赛投相同的钱，直接上结果  \<br>  
### 利率是 0.6328936170212762
<br> 恩，半个月63个点，跟着预测走，可以保你不上天台，还能赚一笔\<br> 
<br> 对八强的预测，算法有一丢丢的改变，净胜球应该要比小组赛要准一点\<br>
#### 好了，四强我们再见 ！
# 2018.7.5更新
world_cup_top4.py
<br>  
同样包含两部分，一是对世界杯开赛以来结果的分析，二是四强预测
第一部分，由于发现有些比赛不能单场买胜平负，所以加了一项2串1（按时间顺序买） 直接上结果  \<br>  
### 利率是 1.79010134545
<br> 开赛到现在是20天，这样买快180个点了，这个有点高了啊\<br> 
# 2018.7.10更新
world_cup_top2.py
<br>  
因为工作原因，没有对前面进行分析，不过4强赛预测的很烂，等世界杯结束会对整体做一个分析
# 2018.7.14更新
world_cup_top1.ipynb
<br>  
世界杯最后的预测了，半决赛预测的很好，最后的决赛不知道会怎样呢，不过 比利时vs英格兰算出来是0.190353
<br> 这个结果有点尴尬，比利时赢和平局可能性都很大，不过我设定的阈值是0.1。
<br> 最后，这个预测会继续持续下去，下一个是英超，数据我都爬好了，过一段时间会把自己的想法，特征选取，算法选择写下来，目前，这个实际上只是选择了一个特征
从实践来看，效果比较好，要到达更好的效果，肯定要构造其他的特征，这个需要的是脑洞和时间，也是不能急的
<br> 还有，以后这个里面会放一些比较有趣的项目，比如股票预测啥的
