# trade_tool
大学毕业设计所做的一个量化交易分析的小玩具，其中用到了wxpython桌面编程与基本的数据分析Pandas与numpy以及可视化的matplotlib库和一系类的金融分析包，功能包括：
* 股票行情与其常用金融指标展示
* 根据交易策略所进行的回测后，买卖详情以及收益的展示
* 根据自己的要求进行新股添加

## __文件结构如下:__
__GUI_QuantTradeSys.py:__ 实现界面交互，比如按钮事件触发、页面切换等
__StockDataMod.py:__ 实现数据获取和基础数据的处理
__IndicatStrateMod.py:__ 实现指标计算和策略执行
__RedefPanelMod.py:__ 实现界面的图形化,MPL_Panel_Base类为行情界面的图形定义，Loop_Panel_Base类为回测界面的图形定义

-----------------

## __启动__
运行GUI_QuantTradeSys.py文件作为其作为启动总工程的主文件入口

## __展示如下__
![choise](https://github.com/callmehero/trade_tool/blob/master/static/input.png)
![dispaly](https://github.com/callmehero/trade_tool/blob/master/static/display.png)
![backdisplay](https://github.com/callmehero/trade_tool/blob/master/static/backdisplay.png)
