# PRML-with-Python
[Bishop(2006).Pattern Recognition and Machine Learning.Springer](https://www.microsoft.com/en-us/research/publication/pattern-recognition-machine-learning/)（訳本：[元田浩,栗田多喜夫訳．パターン認識と機械学習 上下．丸善出版](https://www.amazon.co.jp/%E3%83%91%E3%82%BF%E3%83%BC%E3%83%B3%E8%AA%8D%E8%AD%98%E3%81%A8%E6%A9%9F%E6%A2%B0%E5%AD%A6%E7%BF%92-%E4%B8%8A-C-M-%E3%83%93%E3%82%B7%E3%83%A7%E3%83%83%E3%83%97/dp/4621061224/ref=sr_1_1?adgrpid=127345571705&hvadid=655072144057&hvdev=c&hvqmt=b&hvtargid=kwd-308831990579&hydadcr=4073_13322143&jp-ad-ap=0&keywords=%E3%83%91%E3%82%BF%E3%83%BC%E3%83%B3%E8%AA%8D%E8%AD%98%E3%81%A8%E6%A9%9F%E6%A2%B0%E5%AD%A6%E7%BF%92&qid=1681890471&s=books&sr=1-1)）に対応するpythonコードとグラフをいくつか載せます．また，対応づけた補足資料や他プログラム言語のコードも載せることがあります．コードの詳細はコメントとして追加しており，READMEにも注意や説明があります．

# 目的
参考書にある図の意図を読み取ることや，設定されたパラメータで遊ぶことを目的としています．

# Files
## [graph2-24.ipynb](/graph2-24.ipynb)
参考書の本文では密度推定とあるものの，
参考書にある図ではおそらくヒストグラムと曲線がサンプル数倍に拡大されています．
多峰性が潰れることを強調するためかと思いますが，
コードでは本文に合わせてヒストグラムと曲線が密度となるようにしています．

## [graph2-25.ipynb](/graph2-25.ipynb)
説明や注意事項は[graph2-24.ipynb](graph2-24.ipynb)とほとんど同様です．
ガウシアンカーネル密度推定法を用いた確率密度の推定を行っています．

## [graph2-26.ipynb](/graph2-26.ipynb)
説明や注意事項は[graph2-24.ipynb](graph2-24.ipynb)とほとんど同様．
参考書でカーネルは指定されていませんが，図は連続なので
何かしら連続なカーネルとしてガウスを仮定しています．
平滑化パラメータを指定していますが，これが本文のデータ点に依存していると考えれば良いと思います．

## [graph2-27,28.ipynb](/graph2-27,28.ipynb)
K最近傍法を用いたクラス分けです．
本文とは異なりirisデータを用いていますが，行っていることや伝わることは同じです．
