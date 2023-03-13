# Text-Translation-Machine

# Sequence-to-sequence introduction
- The most common seq2seq model is the encoder-decoder model, which consists of two main parts: the encoder and decoder. These two parts can be implemented using recurrent neural networks (RNNs) or transformers and are mainly used to solve the problem of inputs and outputs having different lengths.
- **Encoder** takes a sequence of inputs, such as text, video, or audio signals, and encodes them into a single vector. This vector can be thought of as an abstract representation of the entire input, containing all of its information.
- **Decoder** decodes the single vector output by the encoder step by step, producing one output at a time until the final target output is generated. Each output affects the next output, and "< BOS >" is generally added at the beginning to indicate the start of decoding, while "< EOS >" is output at the end to indicate the end of the output.
