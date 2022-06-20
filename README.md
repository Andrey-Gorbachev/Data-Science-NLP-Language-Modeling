# Language Modeling 
variants

1. Statistical N-Gram LM 
- Sampling with temperature

2. Bi-LSTM LM (TensorFlow/Keraas)
- experiments with word & subword (SentencePiece) tokenization

3. Char RNN LM (Tensorflow)
- original very fast version

4. Transformer LM (PyTorch)
- Decoding: BeamSeach

5. SpeechBrain CRDNN & Transformer LM (PyTorch)
- Decoding: GreedySearch, BeamSeach

6. GPT2 HuggingFace LM
- embedded Decoding: GreedySearch, BeamSeach
- embedded Sampling: Temperature, Top-K, Top-P, mix