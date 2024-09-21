# Legal-Judgment-Prediction
1 GAT_GCN_code.ipynb —— 基于GAT和GCN模型的司法判决预测算法

model文件保存GAT和GCN的best_model_path

aux_files文件定义停用词文件的路径STOPWORDS_PATH

1.1 基于GAT模型的司法判决预测算法

F1 in test: 0.828065190694157

precision in test: 0.8405425486020889

recall in test: 0.834963701242771

accuracy in test: 0.834963701242771


1.2 基于GCN模型的司法判决预测算法

F1 in test: 0.7988395395765523

precision in test: 0.8130721153032072

recall in test: 0.8079242032730405

accuracy in test: 0.8079242032730405

2 RoBERTa+DPR_code.ipynb —— 基于RoBERTa和DPR模型的司法判决预测算法

验证集评估结果: {'eval_loss': 12.467425346374512, 'eval_runtime': 200.9035, 'eval_samples_per_second': 85.27, 'eval_steps_per_second': 5.331, 'epoch': 10.0}

预测准确率：0.8871662360034454

Macro F1: 0.8271501624283938

Micro F1: 0.8871662360034454

3 数据集data

详见 https://github.com/china-ai-law-challenge/CAIL2018
