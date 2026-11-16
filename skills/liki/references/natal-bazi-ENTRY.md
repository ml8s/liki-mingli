# 八字层入口 — 任务路由与执行流

八字侧入口：任务路由、执行流与断语口径。结果以工具返回为准。

## 任务路由

| 信息需求（应用词） | 领域卡 | 侧查询 |
| --- | --- | --- |
| 事业本命 | `references/natal-bazi-career.md`、`references/natal-bazi-wangshuai.md`、`references/natal-bazi-shishen.md` | 本命判断（事业） |
| 事业应期 | `references/natal-bazi-dayun.md` | 应期判断 |
| 婚姻本命 | `references/natal-bazi-shishen.md`、`references/natal-bazi-gongwei.md` | 本命判断（婚姻） |
| 婚姻应期 | `references/natal-bazi-dayun.md` | 应期判断 |
| 财运本命 | `references/natal-bazi-wealth.md`、`references/natal-bazi-shishen.md` | 本命判断（财运） |
| 财运应期 | `references/natal-bazi-dayun.md` | 应期判断 |
| 健康 / 精神 | `references/natal-bazi-wuxing-health.md`、`references/natal-bazi-hehui.md`、`references/natal-bazi-dayun.md` | 本命判断（健康 / 精神） |
| 学业 | `references/natal-bazi-study.md`、`references/natal-bazi-dayun.md` | 本命判断（学业） |
| 性格 | `references/natal-bazi-shishen.md`、`references/natal-bazi-wangshuai.md` | 本命判断（性格） |
| 六亲 | `references/natal-bazi-family.md`、`references/natal-bazi-gongwei.md`、`references/natal-bazi-hehui.md` | 本命判断（家庭） |
| 合盘 | `references/natal-bazi-hepan.md` | 合盘 |
| 考时校准 | `references/natal-bazi-calibration.md` | 校准编排 |
| 基础（排盘 / 用神 / 结构） | `references/natal-bazi-yongshen.md`、`references/natal-bazi-geju.md`、`references/natal-bazi-tiaohou.md` | 排盘 / 因子 / 用神裁决 |

## 输入约定

公共输入口径见 `references/natal-ENTRY.md`「本命输入约定」。

## 执行流

1. 校准与排盘：出生信息 → 取时间事实；返回历史时制提示（如夏令时）或时间落在边界产生的多候选时，候选即本流程候选项，须先向用户确认，不静默取一 → 排四柱。
2. 因子与用神：因子快照内含唯一用神裁决，直接消费同一份，不自行裁决、不改口径。
3. 本命判断：因子快照 + 问题域 → 本侧断语。
4. 应期判断：因子快照 + 时间层 + 问题域 → 大运 / 流年 / 流月断语。
5. 完成时以 `完成任务` 提交：盘面要点、裁决与断语、依据摘要、不确定项。

## 断语口径

- 技域是 `bazi`；公共断语口径见 `references/natal-ENTRY.md`「本命断语公共口径」。
- 因子快照内含唯一用神裁决，排盘与断语层直接消费同一份。

## 硬边界

- 只做八字侧；紫微走紫微侧入口，六爻、奇门、黄历择日、起名、风水走对应领域入口。
