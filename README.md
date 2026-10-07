# 园区能源演示 v3.2

https://jinyh.github.io/energy-campus/

2026年6月仿真场景；基于 SimBench 2016 年连续历史曲线，非2026年实测。完整月度三方案预计算回放，30天、2880个15分钟时段。车辆和建筑位置为示意；设备、线路端点功率、费用和状态来自同一执行记录。

静态站不提交计算任务、不调用模型；其他月份和重算在本机版进行。三方案差额是工程调度收益，RSI未验证优势。研究按冻结规则停止，模型调用和晋升均为0。

数据为公开 SimBench 数据的仿真派生投影，遵循 ODbL 1.0 / DbCL 1.0，原许可和署名见 licenses/。来源映射见 replay/monthly/6623649e55247c05/source.json；投影清单及原结果SHA256见 replay-manifest.json。前端随包包含 Three.js、React、ECharts，许可见 licenses/。

下载PPT与PDF见 downloads/。method-results.md 为本次方法及核验结果报告。完整原始仿真执行记录和复算环境在本机交付包中，未上传524MB原结果或本机私有资料。
