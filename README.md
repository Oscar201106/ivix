# ivix
中国波指的计算
vix指数的计算方法如下（ivix也是一样）：

http://vix.readthedocs.io/en/latest/

http://www.cboe.com/products/vix-index-volatility/vix-options-and-futures/vix-index/the-vix-index-calculation

中国波指，作为一个波动率指数，也叫情绪指数，具有一定的预测作用。

目前是用于计算历史日间的中国波指，在使用获取数据的py文件的时候，要有WindPy库才可用，不然无法获取期权数据。（目前所有数据也上传了，不需要再次获取）

数据截止日期为2018年7月5日的。需要新的数据自己进行获取了。

后续将会更新实时计算日内的中国波指；同时也会把wind接口全部换成爬虫接口。
