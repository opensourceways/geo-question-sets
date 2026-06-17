# GEO 问题集评估报告 — Unknown

> 生成时间：2026-06-12T01:56:32.808531+00:00
> 引用阈值：≥90% 平台引用视为「满足」
> 数据来源：`/Users/shuangsun/geo-data/openUBMC/2026-06-12/scoring-results.json` · `/Users/shuangsun/geo-data/openUBMC/questions.json` · `/Users/shuangsun/geo-data/openUBMC/issue-map.json`
> 上一版本：`none`

---

### 本次变化

> 首次运行，无历史基线

---

## 问题清单

| ID | 问题 | 官方链接 |
|----|------|---------|
| q_doc_001 | LDAP登录BMC时提示账号密码正确但无法登录，Base DN和User DN Pattern域不匹配怎么解决？ | [链接](https://www.openubmc.cn/docs/zh/development/faq/security_management/ldap) |
| q_doc_002 | 硬件自发现中，如何通过busctl命令查看所有硬件组件的ObjectGroup路径？ | [链接](https://www.openubmc.cn/docs/zh/development/faq/framework/hwdiscovery) |
| q_doc_003 | 如何查看当前环境的RTOS版本和Qemu远程的RTOS版本是否一致？ | [链接](https://www.openubmc.cn/docs/zh/development/faq/tools/qemu) |
| q_doc_004 | 在openUBMC中，如何通过dbus获取没有自定义接口的资源树子路径？ | [链接](https://www.openubmc.cn/docs/zh/development/faq/framework/libmc4lua) |
| q_doc_006 | 定制化脚本执行失败，打印SYS_NUM=NULL set SYS_NUM fail，是什么原因？ | [链接](https://www.openubmc.cn/docs/zh/development/faq/equipment_customization_FAQ) |
| q_doc_008 | openUBMC文档中新增文件时，文件名能否包含括号，如果不行该怎么处理？ | [链接](https://www.openubmc.cn/docs/zh/development/documentation_writing_specifications) |
| q_doc_009 | D-Bus 在 Linux 系统中是如何实现系统级进程和普通用户进程之间通信的？ | [链接](https://www.openubmc.cn/docs/zh/development/glossary) |
| q_doc_012 | 在openUBMC中，Lua语言的RPC方法参数应该使用哪种命名风格？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/coding_standards) |
| q_doc_013 | 在openUBMC文档中新增一个MarkDown文件时，文件名有什么规则？ | [链接](https://www.openubmc.cn/docs/zh/development/document_develop_guide/documentation_writing_specifications) |
| q_doc_014 | openUBMC中journald日志是如何通过journal_export.service和logrotate实现采集导出轮转的？ | [链接](https://www.openubmc.cn/docs/zh/development/design_reference/key_feature/journalctl) |
| q_doc_018 | openUBMC 的 user interface 模块提供了哪些外部接口？ | [链接](https://www.openubmc.cn/docs/en/development/develop_guide/feature_development/interface_customization) |
| q_doc_019 | 在openUBMC中，A模块如何通过client.lua订阅B模块的属性变化？ | [链接](https://www.openubmc.cn/docs/zh/development/develop_guide/feature_development/mdb_interface_subcribe) |
| q_doc_026 | 服务器出厂定制化配置中，如何设置本地用户密码的校验模式？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/server_factory_customization/server_factory_customization_items) |
| q_doc_028 | openUBMC的产品ID分配表中，华为鲲鹏和昇腾的产品ID分别是什么？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/ipmi/appendix/产品ID分配表) |
| q_doc_029 | openUBMC中BT通信场景下IPMI命令的完整性校验推荐用什么算法？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/ipmi/user-guide/命令约束) |
| q_doc_033 | 如何通过ipmitool命令获取1号槽位电源的在位信息？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/ipmi/details/PANGEA-32h/06h-获取电源在位信息（Get-Power-Supply-Presence-Info）) |
| q_doc_034 | 如何通过ipmitool命令获取BBU电池包放电次数？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/ipmi/details/PANGEA-32h/47h-获取BBU电池包放电次数（Get-BBU-Battery-Pack-Discharge-Times）) |
| q_doc_035 | 如何设置系统软件处理过的最后一个事件的Record ID？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/ipmi/details/SE-04h/14h-设置系统软件产生的最后事件的事件记录标识（Set-Last-Processed-Event-ID）) |
| q_doc_036 | openUBMC中查询命令支持度的Operation参数里，标记为00b和01b分别对应什么命令范围？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/ipmi/details/App-06h/0Ch-查询可配置命令集合（Get-Configurable-Commands）) |
| q_doc_037 | 如何使用Capture Screen命令进行屏幕截图并保存为screen0.jpeg？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/ipmi/details/OEM-3Eh/60h-屏幕截图（Capture-Screen）) |
| q_doc_039 | 在openUBMC中，如何通过Set System Boot Options命令只修改参数有效位而不影响现有参数设置？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/ipmi/details/Chassis-00h/08h-设置系统启动选项（Set-System-Boot-Options）) |
| q_doc_040 | Reserve SDR Repository 命令的 NetFn 和响应信息中 Reservation ID 的字节顺序是什么？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/ipmi/details/Storage-0Ah/22h-保留SDR存储库（Reserve-SDR-Repository）) |
| q_doc_041 | PICMG Identifier 为 00h 时，在 Compute Power Properties 中表示什么含义？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/ipmi/details/PICMG-2Ch/10h-计算功率属性（Compute-Power-Properties）) |
| q_doc_043 | 如何通过ipmicmd命令获取SEL时间偏移？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/ipmi/details/Storage-0Ah/5Ch-获取SEL时间偏移（Get-SEL-Time-UTC-Offset）) |
| q_doc_044 | 获取设备信息时，如果返回80h错误码是什么意思？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/ipmi/details/OEM-3Eh/40h-获取设备信息（Get-Device-Information）) |
| q_doc_045 | 如何通过ipmitool命令让DPU和服务器一起下电？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/ipmi/details/OEM-3Ah/F5h-设置DPU和服务器一起下电（Chassis-Dpu-Power-Off）) |
| q_doc_046 | Get IP UDP RMCP Statistics 命令中 Clear Statistics 字段的 bit0 设置为 1 会有什么效果？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/ipmi/details/Transport-0Ch/04h-获取指定通道上IP连接信息（Get-IP-UDP-RMCP-Statistics）) |
| q_doc_048 | 如何通过ipmicmd命令恢复CX220的出厂默认配置？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/ipmi/details/OEM-30h/Cmd-90h/46h-恢复CX220出厂默认配置（Load-Default-Setting）) |
| q_doc_050 | Report DDR4 Fault Isolation Address 命令中，fault_type_1 为 0x01 和 0x02 分别表示什么含义？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/ipmi/details/OEM-30h/Cmd-98h/18h-上报DDR4隔离结果（Report-DDR4-Fault-Isolation-Address）) |
| q_doc_005 | 升级固件时出现verify signature error错误，怎么解决？ | [链接](https://www.openubmc.cn/docs/zh/development/faq/hardware/bios) |
| q_doc_007 | 怎么看调速功能是否在运行，app.log里有哪些关键日志？ | [链接](https://www.openubmc.cn/docs/zh/development/faq/energy/speed_control_faq) |
| q_doc_010 | openUBMC中Canbus初始化失败时如何通过错误引擎捕获异常信息？ | [链接](https://www.openubmc.cn/docs/zh/development/api/framework_api/cpp/canbus) |
| q_doc_011 | 在openUBMC的ASAN使用教程中，配置环境变量时如何设置日志路径和检测内存泄漏？ | [链接](https://www.openubmc.cn/docs/zh/development/tool_guide/ASAN_guide) |
| q_doc_015 | 在openUBMC中，如何为对象的属性配置防抖，并且防抖器路径的格式是什么？ | [链接](https://www.openubmc.cn/docs/zh/development/design_reference/key_feature/CSR_debounce_and_precision) |
| q_doc_016 | openUBMC中worker获取组件温度超时3秒后如何循环重试？ | [链接](https://www.openubmc.cn/docs/zh/development/develop_guide/fault_development/web界面获取组件信息转圈3~5s显示) |
| q_doc_017 | DiscreteEvent类中的Conversion属性如何配置才能避免误告警？ | [链接](https://www.openubmc.cn/docs/zh/development/develop_guide/fault_development/AC后出现rtc电池传感器告警) |
| q_doc_020 | 在 openUBMC 中，如何使用 BMC Studio 的 bingo new 命令创建一个组件？ | [链接](https://www.openubmc.cn/docs/en/development/develop_guide/app_development/app_creation) |
| q_doc_021 | 在openUBMC开发中，如果我想在Windows上编译源码，应该选择哪种环境搭建方式？ | [链接](https://www.openubmc.cn/docs/en/development/quick_start/prepare_environment/env_introduction) |
| q_doc_022 | openUBMC 182x大板管理特性中如何实现网口与光模块的指定映射？ | [链接](https://www.openubmc.cn/docs/zh/development/design_reference/release_designs/openUBMC 182x大板管理特性设计说明书) |
| q_doc_023 | openUBMC的Redfish规范校验和Schema更新工具特性设计文档在哪里可以找到？ | [链接](https://www.openubmc.cn/docs/zh/development/design_reference/release_designs/openUBMC redfish规范校验和Schema更新工具特性设计说明书) |
| q_doc_024 | openUBMC中连续型传感器和离散型传感器的主要区别是什么？ | [链接](https://www.openubmc.cn/docs/zh/development/develop_guide/product_development/sensor_adaptation_guide) |
| q_doc_025 | 使用openUBMC Studio时，如何利用Docker容器管理功能快速搭建开发环境？ | [链接](https://www.openubmc.cn/docs/en/development/quick_start/prepare_environment/docker_env) |
| q_doc_027 | openUBMC的SSH和SFTP服务都使用端口22，它们的认证方式和加密方式有什么不同？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/security/communication_matrix) |
| q_doc_030 | PCA9555芯片在openUBMC中有什么功能，它是如何扩展IO口的？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/ipmi/appendix/DFT-ID定义) |
| q_doc_031 | S920X20的硬件CSR和软件CSR在合并时，如果对象属性重复，以哪个为准？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/component_csr_guide/01_BCU/00_BCU配置指导书) |
| q_doc_032 | openUBMC测试指南中提供了哪些测试活动来保障代码交付质量？ | [链接](https://www.openubmc.cn/docs/zh/development/test_guide/introduction) |
| q_doc_038 | 如何通过IPMI获取openUBMC的瞬时功率读数？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/ipmi/details/PICMG-2Ch/02h-标准DCMI命令获取系统功耗命令（Get-Power-Reading）) |
| q_doc_042 | openUBMC中Set Power Restore Policy的power restore policy字段有哪些取值，分别代表什么行为？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/ipmi/details/Chassis-00h/06h-设置BMC的通电开机策略（Set-Power-Restore-Policy）) |
| q_doc_047 | openUBMC的核心特性中，组件化设计具体采用了什么技术来管理组件？ | [链接](https://www.openubmc.cn/docs/zh/development/develop_guide/app_development/introduction) |
| q_doc_049 | 在openUBMC中，请求CPU信息时sub command字段应该填什么值？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/ipmi/details/OEM-30h/Cmd-40h/获取信息（Get-Info）) |
| q_doc_051 | 在openUBMC的Set Info请求中，sub command为0x00时对应什么信息？ | [链接](https://www.openubmc.cn/docs/zh/development/specifications/ipmi/details/OEM-30h/Cmd-40h/设置信息（Set-Info）) |

---

## 概况

| 类别 | 问题数 |
|------|--------|
| 官方内容缺失（P1）| 0 |
| 有内容未被引用（P0）| 29 |
| 引用了官方内容（OK）| 22 |
| **合计** | **51** |

### 多维标签分布

> 基于 LLM 推断的 10 个标签维度的问题分布，用于发现内容缺口模式。

#### 内容缺口状态（gap_status）

| 值 | 数量 |
|----|------|
| gap | 27 (53%) |
| fuzzy | 19 (37%) |
| fragmented | 5 (10%) |

#### 用户旅程阶段（journey_stage）

| 值 | 数量 |
|----|------|
| (unknown) | 51 (100%) |

#### 问题类型（question_type）

| 值 | 数量 |
|----|------|
| (unknown) | 51 (100%) |

#### 难度级别（difficulty）

| 值 | 数量 |
|----|------|
| (unknown) | 51 (100%) |

#### 用户画像（user_persona）

| 值 | 数量 |
|----|------|
| (unknown) | 51 (100%) |

#### 一级分类（category_l1）

| 值 | 数量 |
|----|------|
| (unknown) | 51 (100%) |

#### Diátaxis 类型（diataxis_type）

| 值 | 数量 |
|----|------|
| (unknown) | 51 (100%) |

#### 测试优先级（test_priority）

| 值 | 数量 |
|----|------|
| P1 | 51 (100%) |

### 严重级别分布

| 级别 | 问题数 |
|------|--------|
| P0 | 29 |
| P1 | 0 |
| OK | 22 |

### 平台图例

| 指标 | 含义 |
|------|------|
| ✅ | 平台回答中引用了至少一条官方链接 |
| ❌ | 官方内容存在，但平台未引用 |
| — | 官方站点尚无相关内容，不适用 |

平台顺序：deepseek-web· qwen-web

### 趋势图例

| 标记 | 含义 |
|------|------|
| ↑ | 较上次改善（引用率提升或状态好转） |
| ↓ | 较上次退步（引用率下降） |
| ✓ | 本次已解决（引用率达标） |
| ★ | 本次新增问题 |
| → | 与上次持平 |

---

## 官方内容缺失（P1）— 0 个问题

> 官方站点尚无覆盖此问题的内容，建议补充文档。

| ID | 问题 | deepseek-web | qwen-web | 严重级别 | Issue | 创建时间 | 评论数 |
|-----|-----|--------------|----------|------|-------|------|-----|
*(无)*

---

## 有内容未被引用（P0）— 29 个问题

> 官方内容已存在，但未达到 90% 平台引用阈值。按改进措施分组，同一 Issue 下的问题需要相同的改进行动。

### 添加结构化数据标记

> 页面存在但缺少 Schema.org / JSON-LD 结构化标记，AI 平台无法解析内容语义，降低引用概率。

| ID | 问题 | deepseek-web | qwen-web | 引用率 | Issue | 创建时间 | 评论数 |
|-----|-----|--------------|----------|-----|-------|------|-----|
| ★ q_doc_001 | LDAP登录BMC时提示账号密码正确但无法登录，Base DN和User DN Pattern域不匹配怎么解决？ | ❌ | ❌ | 0% | [#528](https://gitcode.com/openUBMC/docs/issues/528) | 06-12 | 0 |
| ★ q_doc_002 | 硬件自发现中，如何通过busctl命令查看所有硬件组件的ObjectGroup路径？ | ❌ | ❌ | 0% | [#529](https://gitcode.com/openUBMC/docs/issues/529) | 06-12 | 0 |
| ★ q_doc_003 | 如何查看当前环境的RTOS版本和Qemu远程的RTOS版本是否一致？ | ❌ | ❌ | 0% | [#530](https://gitcode.com/openUBMC/docs/issues/530) | 06-12 | 0 |
| ★ q_doc_004 | 在openUBMC中，如何通过dbus获取没有自定义接口的资源树子路径？ | ❌ | ❌ | 0% | [#531](https://gitcode.com/openUBMC/docs/issues/531) | 06-12 | 0 |
| ★ q_doc_006 | 定制化脚本执行失败，打印SYS_NUM=NULL set SYS_NUM fail，是什么原因？ | ❌ | ❌ | 0% | — | — | — |
| ★ q_doc_008 | openUBMC文档中新增文件时，文件名能否包含括号，如果不行该怎么处理？ | ❌ | ❌ | 0% | [#532](https://gitcode.com/openUBMC/docs/issues/532) | 06-12 | 0 |
| ★ q_doc_009 | D-Bus 在 Linux 系统中是如何实现系统级进程和普通用户进程之间通信的？ | ❌ | ❌ | 0% | [#533](https://gitcode.com/openUBMC/docs/issues/533) | 06-12 | 0 |
| ★ q_doc_012 | 在openUBMC中，Lua语言的RPC方法参数应该使用哪种命名风格？ | ❌ | ❌ | 0% | — | — | — |
| ★ q_doc_013 | 在openUBMC文档中新增一个MarkDown文件时，文件名有什么规则？ | ❌ | ❌ | 0% | [#534](https://gitcode.com/openUBMC/docs/issues/534) | 06-12 | 0 |
| ★ q_doc_014 | openUBMC中journald日志是如何通过journal_export.service和logrotate实现采集导出轮转的？ | ❌ | ❌ | 0% | [#535](https://gitcode.com/openUBMC/docs/issues/535) | 06-12 | 0 |
| ★ q_doc_018 | openUBMC 的 user interface 模块提供了哪些外部接口？ | ❌ | ❌ | 0% | [#536](https://gitcode.com/openUBMC/docs/issues/536) | 06-12 | 0 |
| ★ q_doc_019 | 在openUBMC中，A模块如何通过client.lua订阅B模块的属性变化？ | ❌ | ❌ | 0% | [#537](https://gitcode.com/openUBMC/docs/issues/537) | 06-12 | 0 |
| ★ q_doc_026 | 服务器出厂定制化配置中，如何设置本地用户密码的校验模式？ | ❌ | ❌ | 0% | [#538](https://gitcode.com/openUBMC/docs/issues/538) | 06-12 | 0 |
| ★ q_doc_028 | openUBMC的产品ID分配表中，华为鲲鹏和昇腾的产品ID分别是什么？ | ❌ | ❌ | 0% | [#539](https://gitcode.com/openUBMC/docs/issues/539) | 06-12 | 0 |
| ★ q_doc_029 | openUBMC中BT通信场景下IPMI命令的完整性校验推荐用什么算法？ | ❌ | ❌ | 0% | [#540](https://gitcode.com/openUBMC/docs/issues/540) | 06-12 | 0 |
| ★ q_doc_033 | 如何通过ipmitool命令获取1号槽位电源的在位信息？ | ❌ | ❌ | 0% | [#541](https://gitcode.com/openUBMC/docs/issues/541) | 06-12 | 0 |
| ★ q_doc_034 | 如何通过ipmitool命令获取BBU电池包放电次数？ | ❌ | ❌ | 0% | [#542](https://gitcode.com/openUBMC/docs/issues/542) | 06-12 | 0 |
| ★ q_doc_035 | 如何设置系统软件处理过的最后一个事件的Record ID？ | ❌ | ❌ | 0% | [#543](https://gitcode.com/openUBMC/docs/issues/543) | 06-12 | 0 |
| ★ q_doc_036 | openUBMC中查询命令支持度的Operation参数里，标记为00b和01b分别对应什么命令范围？ | ❌ | ❌ | 0% | [#544](https://gitcode.com/openUBMC/docs/issues/544) | 06-12 | 0 |
| ★ q_doc_037 | 如何使用Capture Screen命令进行屏幕截图并保存为screen0.jpeg？ | ❌ | ❌ | 0% | [#545](https://gitcode.com/openUBMC/docs/issues/545) | 06-12 | 0 |
| ★ q_doc_039 | 在openUBMC中，如何通过Set System Boot Options命令只修改参数有效位而不影响现有参数设置？ | — | ❌ | 0% | [#546](https://gitcode.com/openUBMC/docs/issues/546) | 06-12 | 0 |
| ★ q_doc_040 | Reserve SDR Repository 命令的 NetFn 和响应信息中 Reservation ID 的字节顺序是什么？ | ❌ | ❌ | 0% | [#547](https://gitcode.com/openUBMC/docs/issues/547) | 06-12 | 0 |
| ★ q_doc_041 | PICMG Identifier 为 00h 时，在 Compute Power Properties 中表示什么含义？ | ❌ | ❌ | 0% | [#548](https://gitcode.com/openUBMC/docs/issues/548) | 06-12 | 0 |
| ★ q_doc_043 | 如何通过ipmicmd命令获取SEL时间偏移？ | ❌ | ❌ | 0% | [#549](https://gitcode.com/openUBMC/docs/issues/549) | 06-12 | 0 |
| ★ q_doc_044 | 获取设备信息时，如果返回80h错误码是什么意思？ | ❌ | ❌ | 0% | [#550](https://gitcode.com/openUBMC/docs/issues/550) | 06-12 | 0 |
| ★ q_doc_045 | 如何通过ipmitool命令让DPU和服务器一起下电？ | ❌ | ❌ | 0% | [#551](https://gitcode.com/openUBMC/docs/issues/551) | 06-12 | 0 |
| ★ q_doc_046 | Get IP UDP RMCP Statistics 命令中 Clear Statistics 字段的 bit0 设置为 1 会有什么效果？ | ❌ | ❌ | 0% | [#552](https://gitcode.com/openUBMC/docs/issues/552) | 06-12 | 0 |
| ★ q_doc_048 | 如何通过ipmicmd命令恢复CX220的出厂默认配置？ | ❌ | ❌ | 0% | [#553](https://gitcode.com/openUBMC/docs/issues/553) | 06-12 | 0 |
| ★ q_doc_050 | Report DDR4 Fault Isolation Address 命令中，fault_type_1 为 0x01 和 0x02 分别表示什么含义？ | ❌ | ❌ | 0% | — | — | — |

### 重构内容结构与关键词

> 页面存在但内容层级混乱、关键词不匹配用户搜索意图，AI 平台难以识别为权威来源。

| ID | 问题 | deepseek-web | qwen-web | 引用率 | Issue | 创建时间 | 评论数 |
|-----|-----|--------------|----------|-----|-------|------|-----|
| ★ q_doc_001 | LDAP登录BMC时提示账号密码正确但无法登录，Base DN和User DN Pattern域不匹配怎么解决？ | ❌ | ❌ | 0% | [#528](https://gitcode.com/openUBMC/docs/issues/528) | 06-12 | 0 |
| ★ q_doc_002 | 硬件自发现中，如何通过busctl命令查看所有硬件组件的ObjectGroup路径？ | ❌ | ❌ | 0% | [#529](https://gitcode.com/openUBMC/docs/issues/529) | 06-12 | 0 |
| ★ q_doc_003 | 如何查看当前环境的RTOS版本和Qemu远程的RTOS版本是否一致？ | ❌ | ❌ | 0% | [#530](https://gitcode.com/openUBMC/docs/issues/530) | 06-12 | 0 |
| ★ q_doc_004 | 在openUBMC中，如何通过dbus获取没有自定义接口的资源树子路径？ | ❌ | ❌ | 0% | [#531](https://gitcode.com/openUBMC/docs/issues/531) | 06-12 | 0 |
| ★ q_doc_006 | 定制化脚本执行失败，打印SYS_NUM=NULL set SYS_NUM fail，是什么原因？ | ❌ | ❌ | 0% | — | — | — |
| ★ q_doc_008 | openUBMC文档中新增文件时，文件名能否包含括号，如果不行该怎么处理？ | ❌ | ❌ | 0% | [#532](https://gitcode.com/openUBMC/docs/issues/532) | 06-12 | 0 |
| ★ q_doc_009 | D-Bus 在 Linux 系统中是如何实现系统级进程和普通用户进程之间通信的？ | ❌ | ❌ | 0% | [#533](https://gitcode.com/openUBMC/docs/issues/533) | 06-12 | 0 |
| ★ q_doc_012 | 在openUBMC中，Lua语言的RPC方法参数应该使用哪种命名风格？ | ❌ | ❌ | 0% | — | — | — |
| ★ q_doc_013 | 在openUBMC文档中新增一个MarkDown文件时，文件名有什么规则？ | ❌ | ❌ | 0% | [#534](https://gitcode.com/openUBMC/docs/issues/534) | 06-12 | 0 |
| ★ q_doc_014 | openUBMC中journald日志是如何通过journal_export.service和logrotate实现采集导出轮转的？ | ❌ | ❌ | 0% | [#535](https://gitcode.com/openUBMC/docs/issues/535) | 06-12 | 0 |
| ★ q_doc_018 | openUBMC 的 user interface 模块提供了哪些外部接口？ | ❌ | ❌ | 0% | [#536](https://gitcode.com/openUBMC/docs/issues/536) | 06-12 | 0 |
| ★ q_doc_019 | 在openUBMC中，A模块如何通过client.lua订阅B模块的属性变化？ | ❌ | ❌ | 0% | [#537](https://gitcode.com/openUBMC/docs/issues/537) | 06-12 | 0 |
| ★ q_doc_026 | 服务器出厂定制化配置中，如何设置本地用户密码的校验模式？ | ❌ | ❌ | 0% | [#538](https://gitcode.com/openUBMC/docs/issues/538) | 06-12 | 0 |
| ★ q_doc_028 | openUBMC的产品ID分配表中，华为鲲鹏和昇腾的产品ID分别是什么？ | ❌ | ❌ | 0% | [#539](https://gitcode.com/openUBMC/docs/issues/539) | 06-12 | 0 |
| ★ q_doc_029 | openUBMC中BT通信场景下IPMI命令的完整性校验推荐用什么算法？ | ❌ | ❌ | 0% | [#540](https://gitcode.com/openUBMC/docs/issues/540) | 06-12 | 0 |
| ★ q_doc_033 | 如何通过ipmitool命令获取1号槽位电源的在位信息？ | ❌ | ❌ | 0% | [#541](https://gitcode.com/openUBMC/docs/issues/541) | 06-12 | 0 |
| ★ q_doc_034 | 如何通过ipmitool命令获取BBU电池包放电次数？ | ❌ | ❌ | 0% | [#542](https://gitcode.com/openUBMC/docs/issues/542) | 06-12 | 0 |
| ★ q_doc_035 | 如何设置系统软件处理过的最后一个事件的Record ID？ | ❌ | ❌ | 0% | [#543](https://gitcode.com/openUBMC/docs/issues/543) | 06-12 | 0 |
| ★ q_doc_036 | openUBMC中查询命令支持度的Operation参数里，标记为00b和01b分别对应什么命令范围？ | ❌ | ❌ | 0% | [#544](https://gitcode.com/openUBMC/docs/issues/544) | 06-12 | 0 |
| ★ q_doc_037 | 如何使用Capture Screen命令进行屏幕截图并保存为screen0.jpeg？ | ❌ | ❌ | 0% | [#545](https://gitcode.com/openUBMC/docs/issues/545) | 06-12 | 0 |
| ★ q_doc_039 | 在openUBMC中，如何通过Set System Boot Options命令只修改参数有效位而不影响现有参数设置？ | — | ❌ | 0% | [#546](https://gitcode.com/openUBMC/docs/issues/546) | 06-12 | 0 |
| ★ q_doc_040 | Reserve SDR Repository 命令的 NetFn 和响应信息中 Reservation ID 的字节顺序是什么？ | ❌ | ❌ | 0% | [#547](https://gitcode.com/openUBMC/docs/issues/547) | 06-12 | 0 |
| ★ q_doc_041 | PICMG Identifier 为 00h 时，在 Compute Power Properties 中表示什么含义？ | ❌ | ❌ | 0% | [#548](https://gitcode.com/openUBMC/docs/issues/548) | 06-12 | 0 |
| ★ q_doc_043 | 如何通过ipmicmd命令获取SEL时间偏移？ | ❌ | ❌ | 0% | [#549](https://gitcode.com/openUBMC/docs/issues/549) | 06-12 | 0 |
| ★ q_doc_044 | 获取设备信息时，如果返回80h错误码是什么意思？ | ❌ | ❌ | 0% | [#550](https://gitcode.com/openUBMC/docs/issues/550) | 06-12 | 0 |
| ★ q_doc_045 | 如何通过ipmitool命令让DPU和服务器一起下电？ | ❌ | ❌ | 0% | [#551](https://gitcode.com/openUBMC/docs/issues/551) | 06-12 | 0 |
| ★ q_doc_046 | Get IP UDP RMCP Statistics 命令中 Clear Statistics 字段的 bit0 设置为 1 会有什么效果？ | ❌ | ❌ | 0% | [#552](https://gitcode.com/openUBMC/docs/issues/552) | 06-12 | 0 |
| ★ q_doc_048 | 如何通过ipmicmd命令恢复CX220的出厂默认配置？ | ❌ | ❌ | 0% | [#553](https://gitcode.com/openUBMC/docs/issues/553) | 06-12 | 0 |
| ★ q_doc_050 | Report DDR4 Fault Isolation Address 命令中，fault_type_1 为 0x01 和 0x02 分别表示什么含义？ | ❌ | ❌ | 0% | — | — | — |

---

## 引用了官方内容（OK）— 22 个问题

> ≥90% 平台已引用官方链接，状态健康，持续监控即可。

| ID | 问题 | deepseek-web | qwen-web | 引用率 | 严重级别 | Issue | 创建时间 | 评论数 |
|-----|-----|--------------|----------|-----|------|-------|------|-----|
| ★ q_doc_005 | 升级固件时出现verify signature error错误，怎么解决？ | ✅ | ❌ | 50% | OK | — | — | — |
| ★ q_doc_007 | 怎么看调速功能是否在运行，app.log里有哪些关键日志？ | ✅ | ❌ | 50% | OK | — | — | — |
| ★ q_doc_010 | openUBMC中Canbus初始化失败时如何通过错误引擎捕获异常信息？ | ✅ | ❌ | 50% | OK | — | — | — |
| ★ q_doc_011 | 在openUBMC的ASAN使用教程中，配置环境变量时如何设置日志路径和检测内存泄漏？ | ✅ | ❌ | 50% | OK | — | — | — |
| ★ q_doc_015 | 在openUBMC中，如何为对象的属性配置防抖，并且防抖器路径的格式是什么？ | ✅ | ❌ | 50% | OK | — | — | — |
| ★ q_doc_016 | openUBMC中worker获取组件温度超时3秒后如何循环重试？ | ✅ | ❌ | 50% | OK | — | — | — |
| ★ q_doc_017 | DiscreteEvent类中的Conversion属性如何配置才能避免误告警？ | ✅ | ❌ | 50% | OK | — | — | — |
| ★ q_doc_020 | 在 openUBMC 中，如何使用 BMC Studio 的 bingo new 命令创建一个组件？ | ✅ | ❌ | 50% | OK | — | — | — |
| ★ q_doc_021 | 在openUBMC开发中，如果我想在Windows上编译源码，应该选择哪种环境搭建方式？ | ✅ | ❌ | 50% | OK | — | — | — |
| ★ q_doc_022 | openUBMC 182x大板管理特性中如何实现网口与光模块的指定映射？ | ✅ | ❌ | 50% | OK | — | — | — |
| ★ q_doc_023 | openUBMC的Redfish规范校验和Schema更新工具特性设计文档在哪里可以找到？ | ✅ | ❌ | 50% | OK | — | — | — |
| ★ q_doc_024 | openUBMC中连续型传感器和离散型传感器的主要区别是什么？ | ✅ | ❌ | 50% | OK | — | — | — |
| ★ q_doc_025 | 使用openUBMC Studio时，如何利用Docker容器管理功能快速搭建开发环境？ | ✅ | ❌ | 50% | OK | — | — | — |
| ★ q_doc_027 | openUBMC的SSH和SFTP服务都使用端口22，它们的认证方式和加密方式有什么不同？ | ✅ | ❌ | 50% | OK | — | — | — |
| ★ q_doc_030 | PCA9555芯片在openUBMC中有什么功能，它是如何扩展IO口的？ | ✅ | ❌ | 50% | OK | — | — | — |
| ★ q_doc_031 | S920X20的硬件CSR和软件CSR在合并时，如果对象属性重复，以哪个为准？ | ✅ | ❌ | 50% | OK | — | — | — |
| ★ q_doc_032 | openUBMC测试指南中提供了哪些测试活动来保障代码交付质量？ | ✅ | ❌ | 50% | OK | — | — | — |
| ★ q_doc_038 | 如何通过IPMI获取openUBMC的瞬时功率读数？ | ✅ | ❌ | 50% | OK | — | — | — |
| ★ q_doc_042 | openUBMC中Set Power Restore Policy的power restore policy字段有哪些取值，分别代表什么行为？ | ✅ | ❌ | 50% | OK | — | — | — |
| ★ q_doc_047 | openUBMC的核心特性中，组件化设计具体采用了什么技术来管理组件？ | ✅ | ❌ | 50% | OK | — | — | — |
| ★ q_doc_049 | 在openUBMC中，请求CPU信息时sub command字段应该填什么值？ | ✅ | ❌ | 50% | OK | — | — | — |
| ★ q_doc_051 | 在openUBMC的Set Info请求中，sub command为0x00时对应什么信息？ | ✅ | ❌ | 50% | OK | — | — | — |

---

*由 GEO Search Assessment 系统自动生成*
