# Hi, I'm Burning-Lyu 👋

## Featured Project

### Disaster Tweet Classification with PyTorch

使用 PyTorch 全量微调预训练 DistilBERT，判断英文推文是否描述真实灾害。建立 TF-IDF＋逻辑回归基线，比较正文、关键词和地点输入，并处理重复文本与标签冲突。

- **效果：**相同验证划分、正文输入下，验证集 F1 从 **0.7257** 提升至 **0.8087**；Kaggle **Public Score 为 0.81121**。
- **技术：**PyTorch、Hugging Face Transformers、scikit-learn、pandas。
- **实现：**Dataset/DataLoader、全量微调、梯度裁剪、最佳模型保存、错误样本分析与比赛提交。
- **验证：**去重后采用一次 80/20 分层随机划分；DistilBERT 验证指标与最终提交均采用 0.5 阈值。
- **作品：**[Kaggle Notebook](https://www.kaggle.com/code/eliburninglyu/disaster-tweets-261105) · [Competition](https://www.kaggle.com/competitions/nlp-getting-started)。

上述结果依据 Kaggle Notebook 第 2 版代码与输出。Public Score 与验证集 F1 来自不同评估数据。
