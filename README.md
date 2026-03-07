# Deep_Learning_assignment_1
[Wandb Report Link](https://wandb.ai/ma24m006-indian-institute-of-technology-madras/ASSIGNMENT_1/reports/-DA6401_Assignment_1--VmlldzoxNjExNzI4OA?accessToken=4gq97o3kmtw99i0r43c40d5oe2vv1lt0xpksovqrr2q68threualbyrsbkv1v1ye)


```
      ├── data/
│   ├── dakshina_dataset_v1.0.zip               # Original dataset archive
│   ├── vocab_input.json                        # Character-to-index mapping for input (Latin)
│   ├── vocab_output.json                       # Character-to-index mapping for output (Devanagari)
│   └── dakshina_dataset_v1.0/hi/lexicons/      # Hindi lexicons used for training/testing
│
├── font/
│   ├── NotoSansDevanagari-VariableFont_wdth,wght.ttf
|
├── models/                                     # Model architectures
│   ├── encoder.py                              # Encoder for vanilla model
│   ├── decoder.py                              # Decoder for vanilla model
│   ├── seq2seq.py                              # Seq2seq class integrating encoder and decoder
│   ├── attention.py                            # Attention mechanism
│   ├── attention_encoder.py                    # Encoder for attention model
│   ├── attention_decoder.py                    # Decoder for attention model
│   └── attention_seq2seq.py

```
