# 論文圖片索引

[回到專案 README](../../README.md)

本資料夾保存上傳的 24 張論文原始圖片，保留原始檔名與內容。重新執行 Notebook 產生的圖檔寫入另外的執行輸出目錄，不覆蓋這些圖片。

每組包含 α、β 的估計軌跡，以及價格、流量的迭代軌跡。前兩組與原始兩路 Notebook 版本相關，尚未確認能以目前程式逐張精確重現；其餘圖組依程式中的輸出檔名對應。圖片展示的是保存時的模擬結果。

## 原始兩路版本

| 圖組與相關 Notebook | α | β | 價格 | 流量 |
| --- | --- | --- | --- | --- |
| 第一部分：[價格式學習](../../notebooks/01_price_based_learning.ipynb) | [alpha_evolution.jpg](alpha_evolution.jpg) | [beta_evolution.jpg](beta_evolution.jpg) | [price_evolution.jpg](price_evolution.jpg) | [flow_evolution.jpg](flow_evolution.jpg) |
| 第二部分：[最佳化式流量](../../notebooks/02_optimization_based_flow.ipynb) | [alpha_part2_updated.png](alpha_part2_updated.png) | [beta_part2_updated.png](beta_part2_updated.png) | [price_part2_updated.png](price_part2_updated.png) | [flow_part2_updated.png](flow_part2_updated.png) |

## Series-parallel network：線性模型

預設網路為 `3 × 4 + 1`，共 8 條邊、13 條路徑。兩組程式位於同一份 Notebook 的兩個 code cells。

| 圖組與對應 Notebook | α | β | 價格 | 流量 |
| --- | --- | --- | --- | --- |
| 第一個 cell：[價格式路徑流量](../../notebooks/03_series_parallel_linear.ipynb) | [part1_alpha_all_paths.png](part1_alpha_all_paths.png) | [part1_beta_all_paths.png](part1_beta_all_paths.png) | [part1_price_all_paths.png](part1_price_all_paths.png) | [part1_flow_all_paths.png](part1_flow_all_paths.png) |
| 第二個 cell：[最佳化式路徑流量](../../notebooks/03_series_parallel_linear.ipynb) | [part2_alpha_all_paths.png](part2_alpha_all_paths.png) | [part2_beta_all_paths.png](part2_beta_all_paths.png) | [part2_price_all_paths.png](part2_price_all_paths.png) | [part2_flow_all_paths.png](part2_flow_all_paths.png) |

## Series-parallel network：Semi-log 模型

沿用相同網路；Semi-log 指訊號模型中的 `log(T / T_REF)`，圖表座標仍為線性。

| 圖組與對應 Notebook | α | β | 價格 | 流量 |
| --- | --- | --- | --- | --- |
| 第一部分：[價格式路徑流量](../../notebooks/04_series_parallel_semilog_price.ipynb) | [part1_semilog_alpha_all_paths.png](part1_semilog_alpha_all_paths.png) | [part1_semilog_beta_all_paths.png](part1_semilog_beta_all_paths.png) | [part1_semilog_price_all_paths.png](part1_semilog_price_all_paths.png) | [part1_semilog_flow_all_paths.png](part1_semilog_flow_all_paths.png) |
| 第二部分：[最佳化式路徑流量](../../notebooks/05_series_parallel_semilog_optimization.ipynb) | [part2_semilog_alpha_all_paths.png](part2_semilog_alpha_all_paths.png) | [part2_semilog_beta_all_paths.png](part2_semilog_beta_all_paths.png) | [part2_semilog_price_all_paths.png](part2_semilog_price_all_paths.png) | [part2_semilog_flow_all_paths.png](part2_semilog_flow_all_paths.png) |
