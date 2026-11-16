# 紫微层入口 — 任务路由与执行流

紫微侧入口：任务路由、执行流与断语口径。结果以工具返回为准。

## 任务路由

| 信息需求（应用词） | 领域卡 | 侧查询 |
| --- | --- | --- |
| 事业本命 | `references/natal-ziwei-gong12.md`、`references/natal-ziwei-zhuxing.md` | 本命判断（事业） |
| 事业应期 | `references/natal-ziwei-liunian.md`、`references/natal-ziwei-yingqi.md` | 应期判断 |
| 婚姻本命 | `references/natal-ziwei-gong12.md`、`references/natal-ziwei-zhuxing.md` | 本命判断（婚姻） |
| 婚姻应期 | `references/natal-ziwei-yingqi.md` | 应期判断 |
| 财运本命 | `references/natal-ziwei-gong12.md` | 本命判断（财运） |
| 房产 | `references/natal-ziwei-gong12.md` | 本命判断（房产） |
| 健康 / 精神 | `references/natal-ziwei-gong12.md`、`references/natal-ziwei-yingqi.md` | 本命判断（健康 / 精神） |
| 学业 | `references/natal-ziwei-yingqi.md`、`references/natal-ziwei-gong12.md` | 本命判断（学业） |
| 性格 | `references/natal-ziwei-gexing.md`、`references/natal-ziwei-zhuxing.md` | 本命判断（性格） |
| 六亲 | `references/natal-ziwei-gong12.md` | 本命判断（家庭） |
| 相貌 | `references/natal-ziwei-xiangmao.md` | 本命判断（外貌） |
| 合盘 | `references/natal-ziwei-gong12.md` | 合盘 |
| 考时校准 | `references/natal-ziwei-calibration.md` | 校准交叉验证 |
| 基础（排盘 / 格局 / 流年） | `references/natal-ziwei-calibration.md`、`references/natal-ziwei-geju.md`、`references/natal-ziwei-liunian.md` | 排盘 / 格局 / 流年 |

## 输入约定

公共输入口径见 `references/natal-ENTRY.md`「本命输入约定」。

## 执行流

1. 历法与排盘：出生信息 → 取时间事实（运行时自举时间候选归一能力）；历史时制提示或多候选须先向用户确认，不静默取一 → 农历 / 时辰 → 十二宫与大限。
2. 因子：因子快照（本侧不含用神裁决，星曜与宫位提供独立证据）。
3. 本命判断：因子快照 + 问题域 → 本侧断语。
4. 应期判断：因子快照 + 时间层 + 问题域 → 大限 / 流年 / 流月 / 流日断语。
5. 完成时以 `完成任务` 提交：盘面要点、断语、依据摘要、不确定项。

## 断语口径

- 技域是 `ziwei`；公共断语口径见 `references/natal-ENTRY.md`「本命断语公共口径」。
- 本侧不含用神裁决；星曜与宫位提供独立证据。

## 硬边界

- 只做紫微侧；八字走八字侧入口，六爻、奇门、黄历择日、起名、风水走对应领域入口。
- 星曜与宫位提供独立证据。

## 流派口径

Liki 紫微当前对齐 iztro 兼容数据源，采用三合派基础口径：

| 规则 | 口径 |
|---|---|
| 四化表 | 按生年天干查标准四化表 |
| 星曜亮度 | 庙 / 旺 / 得 / 地 / 平 / 不 / 陷 |
| 宫位互涉 | 三方四正 + 对宫 |
| 大限起排 | 阳男阴女顺行、阴男阳女逆行 |

不支持飞星派自化、钦天四化飞宫逻辑。如需其他流派口径请提交反馈。
