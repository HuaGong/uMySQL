# uMySQL
 S7 Portal Connect To MySQL
2019年8月27日 By 华文博(Amita)
    博途版本为V15.1
    MySQL版本 5.5.28
    1、测试连接uMySQL_Connect可以连接数据库，输出状态正常
    2、测试uMySQL_Query执行MySQL语句正常，但是输出状态还未完善
    3、根据架构，原本设计为在uMySQL_Query中加载TSend和TRcv收发数据，但是多次尝试发现TSend可以多次调用，采用不同的背景数据块，但是TRCV多次调用编译无法通过。解决方案还在考虑。