# E4 Workspace

## 作用

这里是 `E4` 的正式交付入口，默认直接产出结构化 overhead 表。

## 共享代码入口

- `artifacts/thc/src/overhead_report.py`

## 目录职责

- `logs/`：脚本直接生成的结构化 CSV
- `tables/`：主稿候选表
- `figures/`：如需补图，放这里
- `notes/`：一页说明、运行记录

## 常用入口

```bash
bash paper1_veriedge/E4/run_overhead.sh --capture-root /path/to/capture_root --owner johnlee
```

## 正式文件命名

- `exp_e4_<date>_<owner>_size_breakdown.csv`
- `exp_e4_<date>_<owner>_latency_breakdown.csv`
- `exp_e4_<date>_<owner>_storage_breakdown.csv`

## 不要做什么

- 不要只写“大概多少”
- 不要不带单位
- 不要把估算值写成实测值
