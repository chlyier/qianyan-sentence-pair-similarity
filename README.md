# 代码目录

bert：bert+finetune方式训练

bq_corpus_sbert_extend_model：针对银行数据使用特定的针对金融领域预训练模型DMetaSoul/sbert-chinese-qmc-finance-v1进行训练

erlangshen：使用Fengshenbang的二郎神系列进行预测

sbert_unsupervised：使用SBERT提供的模型编码句向量进行预测

simple_transformer：使用该框架进行训练、评估和预测

# 关于数据

实验时，目录中的数据都删去了`bp_corpus/train.tsv`中的`"`，否则读取时少行。

# 运行说明

这里对效果最好的erlangshen模型实现运行环境加以说明：

Python 3.9

Google Colab GPU

Pytorch: 1.11.0+cu113

使用模型：IDEA-CCNL/Erlangshen-Roberta-110M-Similarity



- ~~erlangshen 永远的神仙！~~
- ~~其它一些方式效果不好也可能是使用不当造成的。比如bert微调使，dev的accuracy达到80，最后的test才50，原因除了他的代码不好，就是我的使用姿势不对。~~
- ~~很多方法由于算力或时间精力限制，没有详尽完善地测试。~~
- ~~lcqmc最亲民，pawx-s虽然看着奇怪但是居然被二郎神一览无余，bq_corpus专业领域词汇仍有待商榷（用一个该领域的模型做出的结果居然还不及二郎神，但是其不是专门做sim的，有情可原）。~~
- ~~（Known something about bert as a whole, but didn't get the point of transformer and bert and finetune, almost using third-party lib all the time）~~

