本次探究尝试在原论文基础上进行改进，使用gru.py替换rnn.py，对应的，ModelG需要替换为newModelG，在进行Ablation时，将taskada.py中的loss = F.cross_entropy(pred, YQ) + 0.5 * discriminative_loss替换为loss = F.cross_entropy(pred, YQ)
