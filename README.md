# escmd
ElasticSearch运维命令工具集

<img width="373" alt="aaa" src="https://user-images.githubusercontent.com/122374043/222353155-3474d7fd-cd91-410e-bb35-7f23b5ce61e6.png">


tools目录  【用于收集es运维常用工具】

scripts目录  【用于收集es运维常用语句】

escmd mem  --获取es内存使用情况，用于排查诊断es的内存消耗在哪

escmd cpu  --获取es cpu使用情况，用于排查诊断es cpu消耗情况

escmd disk  --获取es磁盘使用情况，用于排查诊断es磁盘空间占用情况

escmd health  --用于检测es的健康情况

escmd master  --用于获取es集群主节点信息

escmd tasks  --获取es的会话情况

escmd tdetailed --获取es会话的详细情况

escmd idxshard  --获取es索引的信息

escmd  jvm   --获取es的jvm分配和使用情况 (待写脚本)
