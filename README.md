# TF2_BERTJapanese

TensorFlow 2系とHuggingfaceから落とした東北大の日本語BERTで、いろいろなタスクについて学習させる。

# 参考文献

* BERTによる自然言語処理入門 Transformersを使った実践プログラミング

## classifiy_sentences

文章を読んで、複数のラベルから適切なラベルを一つ選んで文章につけるタスク

* データセット：Livedoor News Corpus

* TPUで学習させるとGPUほど正解率が上がらないのは何故だろうか?

## multi-labeling

文章を読んで、ラベルをつける。必要であれば複数のラベルをつける。今回は、ポジティブ、ネガティブ、ニュートラルのラベルをつける。

* データセット：chABSAデータセット
