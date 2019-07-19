# tests
test1 solved output descripition
throughput definition:the amount of data sent in a given period of time\
throughput=bytes/send.time\
average throughput=throughput/total number of data sent\
the keys that can be added are senderid,recieverid ,ackno and grouping can be done by for the data that is sent and ack is recieved.\
based on ack grouping is done so it helps to know what are the data that is send to reciever\
code in rlanguage\
df<-read.table("data.txt",header=TRUE,sep=",")\
print(df)\
Tbytes=sum(df$bytes)\
Tbytes\
Tsend.time=sum(df$send.time)\
Tsend.time\
 throughput=Tbytes/Tsend.time\
throughput\
avgthroughput=throughput/20\
avgthroughput\




