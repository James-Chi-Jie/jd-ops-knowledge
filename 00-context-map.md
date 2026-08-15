# 京东运营上下文地图

本文件用于说明不同类型的问题应该优先读取哪些知识文件。

## 读取总原则

任何京东运营问题先读取：

1. `README.md`
2. 本文件 `00-context-map.md`

再根据问题类型继续读取专项文件。

涉及具体商品、SKU、成本、售价、活动、推广、订单、库存、实收、运营日志或复盘时，必须继续读取 Google Drive 中京东资料库的入口 README，并按其当前目录结构读取事实数据。

## 当前开店阶段

读取：

- `01-current-status.md`
- `02-store-context.md`
- `07-decision-log.md`

适用：

- 当前优先做什么
- 是否应该上更多商品
- 是否开始推广
- 是否应该参加活动
- 首月经营目标如何设定

## 资质、药品合规、OTC / RX

读取：

- `03-rules.md`
- `08-open-questions.md`

适用：

- 入驻资质
- 药品网络销售
- 处方药展示、审方与销售
- 商品图片、标题、详情页合规
- 评价、客服、药师职责边界
- 禁售药品与特殊管理药品

## 商品上架与选品

读取：

- `04-products.md`
- `03-rules.md`
- `07-decision-log.md`

涉及具体商品时，再读取 Google Drive 商品资料。

适用：

- 首批上哪些商品
- 商品标题 / SKU / 详情怎么设计
- OTC 与 RX 如何区别处理
- 哪些商品做验证款、利润款、引流款

## 活动、优惠与自然流量

读取：

- `05-activities.md`
- `06-data-dictionary.md`
- `07-decision-log.md`
- `08-open-questions.md`

涉及具体商品时，再读取成本、售价、实收与优惠叠加数据。

适用：

- 是否参加活动
- 活动价是否亏损
- 优惠如何叠加
- 自然搜索流量如何诊断

## 付费推广

快速判断先读取：

- `11-paid-promotion.md`
- `01-current-status.md`

需要计算或复盘时继续读取：

- `06-data-dictionary.md`
- `07-decision-log.md`
- `08-open-questions.md`
- Google Drive 中具体商品成本、实际实收、广告数据和运营日志

适用：

- 是否开始推广
- 预算设置
- ROI / ROAS / CPA 如何理解
- 如何止损、扩量
- 哪些商品适合投放

注意：不得直接使用拼多多的 ROI 阈值、预算、全店托管经验判断京东推广。

## 后台指标与数据解释

读取：

- `06-data-dictionary.md`
- 推广问题再读取 `11-paid-promotion.md`

适用：

- 曝光、访客、点击率、转化率
- 成交金额、实收、客单价
- 广告 ROI / ROAS / 花费
- 退款、拒收、售后
- 经营利润

## 存储、资料库和 Project 指令

读取：

- `00-storage-routing.md`
- `README.md`

适用：

- 什么写进 GitHub
- 什么存 Google Drive
- 哪些内容属于 Project 指令
- 如何避免京东与拼多多数据混用

## 历史决策与待确认事项

读取：

- `07-decision-log.md`
- `08-open-questions.md`
- `09-meeting-notes/`

遇到平台规则、费用、时效、广告归因等未确认信息，先查 `08-open-questions.md`，不得直接把经验值当成平台规则。
