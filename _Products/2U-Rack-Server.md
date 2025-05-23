---
layout: page
title: AI 服务器
description: 2U Rack Server

order: 4
---
# {{ page.title }}

> AI 服务器是{{ site.project.name }}研发的基于国产自主可控高性能  ARM  领域定制异构处理器(Domain Specific Heterogeneous Processsor)开发的企业级机架服务器，采用了全可靠的软硬件系统，单节点计算性能达到了业内领先水平，具有内核多，运行频率高，内存及 IO 通道带宽高等特点，是面向企业级应用及数据中心的高性能服务器产品。AI 服务器作为高性能、安全可靠的计算及存储平台，可针对云计算、大数据分析、软件定义数据中心提供出色的总体拥有成本（TCO），轻松应对低延迟、数据密集型工作负载。![layouts](Picture.png "AI 服务器"){:.ui.image}
{:.ui.info.message}

1. 高性能，高密度
    - 采用 ARM V9.0 Neoverse N2 高性能内核
    - 在双路形态下，最高可支持 256 物理内核，可支持 3.0GHz 主频
    - 高内存带宽设计能力， 支持 32 根 DDR5 内存条，最高速率 5200MT/s，加速内存密集型应用性能
    - 最高支持 28 个 NVMe U.2 硬盘，提供高速 IO 接口，解决传统硬盘访问慢的瓶颈
9. 高可扩展性
    - 支持多样的存储配置，可支持大存储配置，最大支持 33 块可热插拔硬盘
    - 支持扩展 12 个 PCIe Gen5 插槽，满足网络、存储控制等灵活扩展需求
    - 最高支持 4 块双宽 GPU 卡，提供强大的异构计算能力
7. 管理方便、易维护
    - 全面监测系统健康，可实现核心部件的监测诊断
    - 支持自动部署，固件升级，远程操作等功能，提升部署及运维的效率
    - 提供企业级管理功能和可靠性，设备自动值守、核心部件实时监控、 故障精细化分类上报，为数据中心运维提供全面保障
4. 绿色、节能、环保
    - 用 80PLUS 高能效电源模块，支持高压直流 ，低压直流技术，提高能源利用率
    - 风扇选用 8038/8056 高效风机，相同散热能力的情况下，功耗更低
    - 散热系统优化 PID 算法，支持风扇智能转速调节，噪音优化控制
    - 产品整体为无铅设计，绿色环保

## 技术规格

| <span>{% include icon.liquid id='cpu' %} <b>主机特性</b></span> |   |
|----------|---------|
| 形态      | U2    |
| 适配机柜     | 19  英 寸 ≧1000mm  深 机     |
| 处理器      | 支持 1~2 颗软银系列高性能 ARM v9.0 N2 内核处理器，每颗最大支持 128 个内核，可作为领域定制异构处理器（Domain Specific Heterogeneous Processsor）    |
| 内存插槽      | 32 个 DDR5 RDIMM ECC 内存插槽，最大内存容量可达 `8TB` 最高运行速率 `5200MT/s`    |
| 硬盘控制器     | 支持标准和自研存储  HBA、Raid  卡，支持  SAS4.0/SAS3.0/SATA3.0/PCIe5.0/ PCIe4.0    |
| 硬盘      | 提供多种前置存储盘位配置，支持热插拔，支持  HDD、SSD：<br>8x2.5”盘位，支持 SAS/SATA/U.2<br>16x2.5”盘位，支持 SAS/SATA/U.2<br>24x2.5”盘位，支持 SAS/SATA/U.2<br>25x2.5”盘位，支持 SAS/SATA，其中 8 个支持 U.2<br>12x3.5”盘位，支持 SAS/SATA/U.2<br>提供多种后置灵活存储模块配置，支持热插拔，支持  HDD、SSD：<br>2x2.5”盘位模块，支持 SAS/SATA/U.2，最大可配置 4  个硬盘    |
| 显卡     | 集成显示控制器，最大分辨率  1920x1080    |
| 系统管理     | WEB  中文管理界面，支持  `IPMI2.0` `SNMP` `SOL` `RedFish` `KVM Over IP`    |
| <span>{% include icon.liquid id='memory' %} <b>IO 模块 </b></span> |   |
| PCIe 插槽      | 最大可扩展 12 个 PCIe 插槽（含 2 个 OCP 3.0 插槽），支持 `32Gbps` 接口速率     |
| 外部设备接口     | 4  个  USB  接口（后部  2  个  USB3.0，  前部  1  个  USB3.0+1  个  USB2.0）<br>2 个  VGA  接口（前端  1  个，后端  1  个）<br>1 个 3.5MM  串口<br>1 个  IPMI GE  电口    |
| <span>{% include icon.liquid id='awesome-codepen' %} <b>物理特性</b></span> |   |
| 电源      | 2 个 CRPS 标准电源，支持热插拔，支持 1+1 冗余铂金电源，提供 550W~2000W 多种规格<br>支持多种供电制式：110/220VAC、-48VDC，240VDC、336VDC  供电    |
| 环境条件     | 工作温度：  5℃～40℃<br>存储温度：-40℃～65℃<br>工作湿度：  8％～90％  RH，无凝露<br>运输存储湿度：  5％～95％  RH，无凝露<br>海拔高度：3000  米    |
| 系统尺寸      | 19  英寸机架式，`432mm x 87.6mm x 780mm`（宽  x  高  x  深），不含侧耳、导轨    |
| 风扇      | 4个可插拔冗余中置风扇，支持动态智能风扇调速的散热系统    |
| 重量      | 满配置不超过  40kg  （不含导轨）    |
| 相关认证       | CCC、CQC、CE、RoHS  等    |
| <span>{% include icon.liquid id='awesome-television' %} <b>操作系统</b></span> |   |
| 兼容操作系统      | CGSL，Suse，Redhat，Centos，麒麟，红旗等操作系统<br>`注：具体支持的操作系统版本，可参考服务器兼容性列表`     |
{:.ui.collapsing.striped.table}