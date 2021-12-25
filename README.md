Microsoft Defender的恶意软件样本测试

测试对象：收集到的所有样本容量>=100的样本包

注意：除非经过特殊说明，测试用的Microsoft Defender均使用ConfigureDefender调至最高（MAX）防护级别。测试结果仅代表测试时软件的水平且仅供参考。

此类样本包的通用处理方式：
1.下载样本包，用Nanazip解压
2.暂停实时保护，用统计工具进行测前准备
3.重启实时保护，用命令行进行扫描（因为UI的扫描存在bug，不会显示所有的扫描出的样本，处理时亦然）
4.用统计工具进行统计，输出结果

第一期测试：https://anylnk.github.io/20211225.html

末尾附一些测试工具

样本联系上报请转至：
微软漏报且文件鉴定结果分析错误+长期分析未入库样本上报帖（微软上报样本）
https://bbs.kafan.cn/forum.php?mod=viewthread&tid=2223364&fromuid=1275892
(出处: 卡饭)


https://pan.huang1111.cn/s/byoDUY

如有问题请到https://github.com/ANYLNK/ANYLNK.github.io/issues反馈

（本博客依然在更新、维护、调试中）
