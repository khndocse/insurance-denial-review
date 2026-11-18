# 保险拒赔案件审核评估 Skill

适用于律师、保险理赔复核人员及法务初查。把拒赔通知、保单和证据放在一起核对，整理争议焦点、九档初评、条件金额和优先补证清单。

覆盖医疗险、重疾险、学平险、团体意外险和雇主责任险。社区版提供五类核查表、九档判定说明、报告模板及虚构演练，适合在 Codex 等支持 Agent Skills 的客户端按案使用。使用 Markdown 指令和参考文件即可运行。法律和裁判检索使用你有权访问且已配置的来源。

## 安装到 Codex

在装有 Node.js 的环境执行下列命令，安装后重新打开 Codex 对话。

```sh
npx skills add khndocse/insurance-denial-review --skill insurance-denial-review --agent codex
```

也可以下载仓库，按客户端支持的方式放入技能目录。Codex 的项目级路径示例为 `.agents/skills/insurance-denial-review/`，保留 `SKILL.md`、`references/` 和 `examples/` 的相对位置。

## 试用

先用仓库中的[虚构演练](examples/fictional-review.md)熟悉结果，或提供已脱敏的保单及条款、拒赔通知和证据材料。

> 用 $insurance-denial-review 帮我审核这起医疗险拒赔。请逐条对应拒赔理由和保单条款，标出证据页码，给出初评、两种可能的金额和优先补证清单。

资料很少时，也可以先要求只盘点材料和梳理拒赔争点。初评供人工复核，金额随条款、付款归属及证据变化而重算。社区版使用虚构演练材料，实际案件由使用者自行提供所需资料。

## 许可证

[MIT](LICENSE)
