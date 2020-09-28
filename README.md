# Abstractive-Summarization-with-pointer-generator-Networks



Neural sequence-to-sequence models have provided a viable new approach for abstractive text summarization (meaning they are not restricted to simply selecting and rearranging passages from the original text). However, these models have two shortcomings: they are liable to reproduce factual details inaccurately, and they tend to repeat themselves. In this work we propose a novel architecture that augments the standard sequence-to-sequence attentional model in two orthogonal ways. First, we use a hybrid pointer-generator network that can copy words from the source text via pointing, which aids accurate reproduction of information, while retaining the ability to produce novel words through the
generator. Second, we use coverage to keep track of what has been summarized,which discourages repetition. We apply our model to the Telugu articles which are preprocessed before.outperforming the current abstractive state-of-the-art by at least 2 ROUGE points.

Models that we use to implement Abstractive summarization:
1.Sequence-to-sequence Attention model.
2.Pointer-Generator.
3.Attention mechanisms.
