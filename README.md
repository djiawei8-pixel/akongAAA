# GALOMANA Malaysia · 运营工作台

面向 TikTok Shop Malaysia 的轻量运营资料与任务入口。中文用于内部协作，面向消费者的内容使用自然的 Bahasa Melayu（BM）与 English（EN）。

## 从这里开始

1. 在 [SKU 资料区](skus/README.md) 找到产品卡；未核实字段保持“待确认”。
2. 复制 [任务模板](tasks/TEMPLATE.md) 到 `tasks/YYYY-MM-DD-role-topic.md`，由 Lead 填写目标、负责人、输入和验收标准。
3. 把任务文件路径交给对应 Agent；执行者只读取该任务及相关资料，将产出保存在岗位目录。
4. 执行者在任务文件记录结果链接与交接信息，状态改为 Review；Lead 验收后改为 Done。

仓库提供资料和协作约定，不会自动连接、启动或恢复电脑上的四个 Agent 会话。现阶段不需要安装依赖。

## 目录与分工

| 入口 | 负责人 | 保存内容 |
| --- | --- | --- |
| [lead/](lead/README.md) | Lead | 优先级、派工、复核、决策 |
| [market-data/](market-data/README.md) | Market & Data | 竞品观察、价格口径、视频数据分析 |
| [content-localization/](content-localization/README.md) | Content & Localization | BM/EN Listing、Hook、脚本、主图文案 |
| [influencer-collaboration/](influencer-collaboration/README.md) | Influencer Collaboration | 合作标准、邀约草稿、匿名交付记录 |
| [skus/](skus/README.md) | Lead 维护，其他岗位引用 | 产品事实与证据索引 |
| [tasks/](tasks/README.md) | 四岗位共用 | 唯一任务状态与交接记录 |
| [automation/](automation/README.md) | 后续按需扩展 | 自动化接入约定，当前未启用 |
| [AGENTS.md](AGENTS.md) | AI 执行者 | 工作边界、上下文与交接规则 |

## 最小工作约定

- 每项任务只有一个主负责人；岗位是职责，不是已创建的 GitHub 账号。
- 状态：Todo → Doing → Review → Done；受阻使用 Blocked，说明原因与恢复条件。
- 文件命名：`YYYY-MM-DD-sku-topic.md`；日期与截止时间使用马来西亚时间（Asia/Kuala_Lumpur，UTC+8）。
- 任务状态只维护在 tasks 文件中；暂不创建第二套 Issue/看板状态。
- 数据注明来源、采集时间、统计范围和局限；禁止用估算充当已验证事实。
- 对外文案需完成产品事实与 BM/EN 语义核对；缺少证据的功效不得直接发布。

## 公开仓库的资料边界

此仓库当前公开。仅保存可公开的说明、空白模板、公开资料和经过脱敏的产出。
不要上传采购成本、未公开定价、合同、客户/达人电话与地址、账号凭据或未经许可的后台导出。
内部资料留在获授权的私有位置，本仓库仅记录不含敏感内容的资料编号；不要放带访问令牌的分享链接。
.gitignore 只能减少误提交，不能替代内容检查。

## 建议的第一项任务

Lead 复制任务模板，建立“核实一个 SKU 的产品资料卡”，补齐可公开的包装信息及证据；
完成后再派发该 SKU 的 BM/EN 内容任务。当前产品卡均为占位，不代表已验证资料。
