# Qianyan_Sentence_Pair_Classification

千言文本相似度比赛

# tricks and tips

删除`bp_corpus.train.tsv`中的`"`，否则读取时少行。

# in the end

- erlangshen 永远的神仙！

- 其它一些方式效果不好也可能是使用不当造成的。比如bert微调使，dev的accuracy达到80，最后的test才50，原因除了他的代码不好，就是我的使用姿势不对。
- 很多方法由于算力或时间精力限制，没有详尽完善地测试。

- lcqmc最亲民，pawx-s虽然看着奇怪但是居然被二郎神一览无余，bq_corpus专业领域词汇仍有待商榷（用一个该领域的模型做出的结果居然还不及二郎神，但是其不是专门做sim的，有情可原）。
- （Known something about bert as a whole, but didn't get the point of transformer and bert and finetune, almost using third-party lib all the time）



