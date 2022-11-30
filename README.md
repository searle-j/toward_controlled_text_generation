# toward_controlled_text_generation

## 목적
- 이 [페이퍼](http://proceedings.mlr.press/v70/hu17e/hu17e.pdf)의 한국어 구현.
- NSMC dataset에서 긍부정이 바뀐 텍스트를 생성하는 것이 목적.

## 결과는?
- ~~좋지 않았다...ㅠㅡㅠ~~
- Gaussian prior에서 생성되는 문장은 어느 정도 fluent.
- LSTM-VAE의 reconstruction은 좋은 성능을 보였다.
- 그러나 sentiment flipping을 하면 fluency가 너무 떨어짐 (sentiment는 바뀌기는 하는 듯).

## references
- [official_code](https://github.com/asyml/texar/tree/master/examples/text_style_transfer)
- [unofficial_code_1](https://github.com/GBLin5566/toward-controlled-generation-of-text-pytorch)
- [unofficial_code_2](https://github.com/wiseodd/controlled-text-generation)
- [NSMC_dataset](https://github.com/e9t/nsmc)
- [Word_vector_model](https://github.com/Kyubyong/wordvectors)
