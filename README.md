# Language Modeling 
variants

1. Statistical N-Gram LM 
- + Sampling with temperature

2. Statistical N-Gram LM v02 
- + K-Smoothing
- + Perplexity

3. Bi-LSTM LM (TensorFlow/Keraas)
- experiments with word & subword (SentencePiece) tokenization

4. Char RNN LM (Tensorflow)
- original very fast version

5. Transformer LM (PyTorch)
- Decoding: BeamSeach

6. SpeechBrain CRDNN & Transformer LM (PyTorch)
- Decoding: GreedySearch, BeamSeach

7. GPT2 HuggingFace LM
- embedded Decoding: GreedySearch, BeamSeach
- embedded Sampling: Temperature, Top-K, Top-P, mix