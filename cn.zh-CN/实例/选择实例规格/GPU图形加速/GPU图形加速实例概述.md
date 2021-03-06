# GPU图形加速实例概述 {#concept_t43_btz_wgb .concept}

本文介绍GPU可视化计算型实例规格族ga1，并列出了具体的实例规格。

## GPU可视化计算型实例规格族ga1 {#section_262_apr_whm .section}

ga1的特点如下：

-   I/O优化实例
-   仅支持SSD云盘和高效云盘
-   采用AMD S7150 GPU计算卡
-   处理器与内存配比为1:2.5
-   处理器：2.5 GHz主频的Intel ® Xeon ® E5-2682 v4（Broadwell）
-   高性能NVMe SSD本地盘
-   实例网络性能与计算规格对应（规格越高网络性能越强）
-   适用场景：
    -   渲染、多媒体编解码
    -   机器学习、高性能计算、高性能数据库
    -   其他需要强大并行浮点计算能力的服务器端业务

ga1包括的实例规格及指标数据如下：

|实例规格|vCPU|内存（GiB）|本地存储（GiB）|GPU|GPU显存（GB）|网络带宽能力（出/入）（Gbit/s）|网络收发包能力（出/入）（万PPS）|支持IPv6|多队列|弹性网卡（包括一块主网卡）|单块弹性网卡的私有IP|
|:---|:---|:------|:--------|:--|:--------|:------------------|:-----------------|:-----|:--|:------------|-----------|
|ecs.ga1.xlarge|4|10.0|1 \* 87|0.25 \* AMD S7150|2|1.0|20|否|1|3|10|
|ecs.ga1.2xlarge|8|20.0|1 \* 175|0.5 \* AMD S7150|4|1.5|30|否|1|4|10|
|ecs.ga1.4xlarge|16|40.0|1 \* 350|1 \* AMD S7150|8|3.0|50|否|2|8|20|
|ecs.ga1.8xlarge|32|80.0|1 \* 700|2 \* AMD S7150|2 \* 8|6.0|80|否|3|8|20|
|ecs.ga1.14xlarge|56|160.0|1 \* 1400|4 \* AMD S7150|4 \* 8|10.0|120|否|4|8|20|

**说明：** 

-   更多信息，请参见[创建ga1实例](cn.zh-CN/实例/选择实例规格/GPU图形加速/创建ga1实例.md#)。
-   您可以前往[ECS实例可购买地域](https://ecs-buy.aliyun.com/instanceTypes/#/instanceTypeByRegion)，查看本实例的可购情况。
-   指标的含义请参见[实例规格指标说明](cn.zh-CN/实例/实例规格族.md#section_e9r_xkf_z15)。

