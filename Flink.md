显示Markdown预览效果：ctrl+k + v
# 1.Flink的定位
大数据流处理框架
# 2.Why Flink?
- 流数据更真实反映我们的生活方式
- 传统的数据架构师基于有限数据集的
- 我们的目标：低延迟、高吞吐、准确性、容错性
# 3.传统数据处理架构
- 事务处理OLTP（业务）
- 分析处理OLAP（分析）  
流式处理引擎的演进：
1. 有状态的流式处理
2. lambda架构 流处理+批处理
3. Flink架构
# 4.Flink的主要特点
- 事件驱动
- 基于流的世界观（离线：有界流，实时：无界流）
- 分层API(越顶层越抽象，越底层越具体)
- 支持事件时间和处理时间
- 精确一次的状态一致性保证
- 低延迟，毫秒级
- 与众多常用存储系统的连接
- 高可用，动态扩展