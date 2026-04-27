# E5 Workspace

## 作用

这里是 `E5` 的协作入口，用于把 orchestration 运行结果整理成正式 policy compare 表。

## 共享代码入口

- `artifacts/inference-E2E/requester/matrix_control.py`
- `artifacts/inference-E2E/requester/make_comparison_table.py`
- `artifacts/equivalence/`

## 目录职责

- `logs/`：结构化原始结果、导出的 cell summary
- `tables/`：policy compare 正式表
- `figures/`：候选图
- `notes/`：一页说明、运行记录

批量运行目录默认放在：

- `workspace/runs/E5/`

## 常用入口

```bash
bash paper1_veriedge/E5/run_matrix.sh
bash paper1_veriedge/E5/build_policy_table.sh /path/to/summary_by_cell.csv
```

## 正式文件命名

- `exp_e5_<date>_<owner>_policy_compare.csv`
- `exp_e5_<date>_<owner>_policy_config.json`

## 不要做什么

- 不要只报 latency，不报 success / challenge / verifier workload
- 不要把 welfare / pricing 结果当作 E5 主结果
- 不要把整个 batch run 目录直接当正式交付物
