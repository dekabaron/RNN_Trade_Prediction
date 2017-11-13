# RNN_Trade_Prediction 
LSTM_nikkei225.pyはLSTMを使って日経平均株価の予測を目指したコードです。 このコードではLSTMを使って、日経平均を学習後に予測を行いますが、予測した株価を元にさらに次の日の株価の予測をするを繰り返しおこなっています。 しかし実際に実行してみればわかりますが、最終的に予測した株価が収束してしまい、学習がうまく行っていないません。 
LSTM_nikkei225andGDP.pyは株価だけでなく、GDPを入力に加えて翌日の株価の予測を目指しています。しかし株価が上がるか下がるかの予測の精度が50%程度と、ランダムに予測した時の精度と変わらないため、実用性にはほどと遠いです。計算の全ての行程から見直す必要あると考えています。

