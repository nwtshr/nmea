# nmea
NMEAで書かれた緯度経度の情報を10進数に変換し、Google Mapにポジショニングする。

##制約条件
・NMEAファイルから緯度経度データを自身で読み取らなければならない
・HTML５では整数型がないため緯度経度の整数部分、少数部分を分けて入力する必要がある
・連続データやNMEAファイルそのものを入力要素とすることができない

##フロー
1.NMEAで書かれた60進数の緯度経度を手入力
2.10進数に変換
3.２の結果をgooglemapに代入
4.表示