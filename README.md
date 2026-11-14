# Bioinformatics Skills

可复用的生物信息分析 skill 初版。目前包含 `skills/bioinformatics-analysis`，提供输入检查、方法选择、流程执行和结果验证规范，尚未配套具体工具的可执行流程。

## 内容

- `skills/bioinformatics-analysis/SKILL.md`：触发条件、分析流程和交付规范。
- `skills/bioinformatics-analysis/agents/openai.yaml`：界面名称和说明。

## 使用示例

在支持该 skill 格式的工具中加载后：

```text
使用 $bioinformatics-analysis 检查这个 RNA-seq 项目的样本表和分析脚本，
确认分组、配对关系与输入矩阵是否适用于现有差异表达设计，
修复发现的问题，并记录实际完成的验证。
```

本仓库仅保存 skill 和必要配套代码、文档。分析软件、数据库及计算环境由使用时的项目提供。当前版本已进行结构校验，尚未完成真实数据分析的端到端验证。
