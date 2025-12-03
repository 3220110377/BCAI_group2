# BCAI_group2
## 📁 Repository Contents

| File / Folder | Description |
|---------------|-------------|
| `question.xlsx` | Stores all questions: each has an ID, available options, and their associated scores. |
| `decision.csv` | Contains choices and scores of 53 participants on questions 21–60; entries with multiple or incomplete selections have been removed. |
| `preference_transformed.csv` | Contains each participant’s likeability ratings (1–4) for every word option, based on their responses to questions 1–20. |
| `statistical_analysis.ipynb` | Analyses preference and score distributions: generates violin plots and histograms for option preferences and score distributions. Results are saved under the `statistical_analysis_result/` folder. |
| `Strategy_fit_degree.ipynb` | Simulates nine candidate decision strategies and computes similarity (“fit degree”) between strategy predictions and participants’ actual choices. Results saved under `strategy_fit_degree/`. |
| `average_score.ipynb` | Computes and visualises the average score of six static strategies. Visual results are saved under `average_score/`. |
| `quantization_ML.ipynb` | Uses a machine-learning model to extract feature parameters representing each participant’s decision strategy and makes predictions. |
| `quantization_ML final.ipynb` | Extends the ML model by adding parameter-update visualisation. |
| `lr.csv` | Stores, for each participant, the learning rate that yielded the highest prediction accuracy, along with the trained parameter values. |
| `best.csv` | For each participant, records the learning rate and parameter set that achieved the highest interpretability (i.e., best explanatory power). |
|strategy_plot.ipynb|Clustering, statistical analysis and visualization modules, including spider charts for average strategy consistency, and line charts for performance presentation.|
|cluster_perf.ipynb|Supplementary statistical analysis for user performance.|
|multi_strategy_model.ipynb|Multi-strategy integration model using XGBoost and Random Forest, aiming to predict user decision and evaluate contributions of strategy features with SHAP analysis.|
