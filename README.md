# makemore
I re-create Andrej Karpathy's ```makemore``` series, along with my own notes, anecdotes, additions, and changes.

Makemore is an autoregressive character-level language model, possessing a range of models (bigrams to Transformers (like GPT)). It basically predicts the next character. 

Makemore accepts one text file as input and generates more of what it is given, line by line. In this repo, we'll give it a list of name in a database, and it will generate new, non-existing name ideas. We'll apply this function across multiple arenas.

PyTorch is the only requirement.

This series uses these papers:

- Bigram (one character predicts the next one with a lookup table of counts)
- MLP, following Bengio et al. 2003
- CNN, following DeepMind WaveNet 2016 (in progress...)
- RNN, following Mikolov et al. 2010
- LSTM, following Graves et al. 2014
- GRU, following Kyunghyun Cho et al. 2014
- Transformer, following Vaswani et al. 2017
- Usage
