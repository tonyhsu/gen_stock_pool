#简介

利用东方财富网的基金数据，选出基金重仓、基金增仓的股票，例如增仓大于5%、
持股3亿并且增仓35%以上、持股大于1亿、流通占比超过5%，选出不同风格的基金持仓股票，
股票池.xlsx是所有数据，可供2次选择。
fin.txt是基金重仓且增仓，且过去一个季度持股人数减少的股票，这样的股票如果不是高位，未来涨的概率比较高。

#重要

1,东方财富网的数据链接未来可能改变，每个季度的url日期本身也需要改变，可以用firefox的F12调出network面板来观察更新之。
2,基金也可能做股票失败，特别是遇到系统性风险的时候。所以需要参考https://github.com/alextooter/bigdeal 中的大单取向，
注意观察市场主流力量的态度。
