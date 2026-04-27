# E1 Workspace

## 作用

这里是 `E1` 的协作入口，不复制共享 verifier 代码。

## 共享代码入口

- `artifacts/thc/scripts/t3_hetero_cli.py`
- `artifacts/thc/T3_hetero_runbook.md`

## 目录职责

- `logs/`：pairwise 结果表、结构化原始结果
- `tables/`：可直接进主稿的汇总表
- `figures/`：候选图
- `notes/`：一页说明、运行记录

真实 capture root 默认放在：

- `workspace/captures/E1/`

## 常用入口

```bash
bash paper1_veriedge/E1/run_capture.sh --split calibration
```

## 正式文件命名

- `exp_e1_<date>_<owner>_summary.csv`
- `exp_e1_<date>_<owner>_pairwise_details.csv`

## 不要做什么

- 不要把 `.npz` capture bundle 直接提交到 `paper1_veriedge/E1/logs/`
- 不要混用 calibration 与 evaluation
- 不要修改 shard plan 却不写进 notes
