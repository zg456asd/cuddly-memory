# 4.核密度分析


#灏嗕綅缃潗鏍囦粠dataframe涓彁鍙栧嚭鏉?
mm.ppp<-ppp(newdata3$qx,newdata3$qy,window=owin(xrange=c(0,16),yrange=c(0,6)))
ds<-density(mm.ppp,bw="nrdo",adjust = 1.5)
plot(ds,main='鏍稿瘑搴﹀垎鏋愬浘')
detach(data)
！[image]（https://github.com/zg456asd/cuddly-memory/blob/master/411.png）
