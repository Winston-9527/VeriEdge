# exp_e4_20260511_equal_budget_live_ab

- Selected configs source: /Users/siyuan/Developer/Veriedge/VeriEdge/paper1_veriedge/E2/tables/exp_e2_20260511_equal_budget_live_ab_selected_summary.csv
- Context: same live A/B 40-calibration / 200-evaluation captures used by equal-budget E2.
- Commitment bytes count only digest-chain storage; reveal payload bytes count sketch disclosure on challenge path.
- Detail CSV: /Users/siyuan/Developer/Veriedge/VeriEdge/paper1_veriedge/E4/tables/exp_e4_20260511_equal_budget_live_ab_detail.csv
- Summary CSV: /Users/siyuan/Developer/Veriedge/VeriEdge/paper1_veriedge/E4/tables/exp_e4_20260511_equal_budget_live_ab_summary.csv
- Main table CSV: /Users/siyuan/Developer/Veriedge/VeriEdge/paper1_veriedge/E4/tables/exp_e4_20260511_equal_budget_live_ab_main_table.csv
- Figure: /Users/siyuan/Developer/Veriedge/VeriEdge/paper1_veriedge/E4/figures/exp_e4_20260511_equal_budget_live_ab_payload_latency.png

## Main comparison

- projcos16: reveal=3072 B/trace, hetero latency=3.613842 ms, tamper latency=3.489169 ms, hetero detect rate=0.12, tamper detect rate=1.0.
- projcos4: reveal=768 B/trace, hetero latency=3.369694 ms, tamper latency=3.315379 ms, hetero detect rate=0.02, tamper detect rate=1.0.
- scalar16: reveal=192 B/trace, hetero latency=3.455666 ms, tamper latency=3.256636 ms, hetero detect rate=0.15, tamper detect rate=1.0.
- scalar64: reveal=768 B/trace, hetero latency=3.390844 ms, tamper latency=3.242923 ms, hetero detect rate=0.415, tamper detect rate=1.0.
