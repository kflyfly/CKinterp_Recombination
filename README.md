# CKinterp_Recombination
### 必要ファイル
|ファイル名|内容|
|:---|:---|
|chem_Recombination.inp|反応機構（KUCRSで作成されたi-オクタンの）|
|thermdat|熱力学データベースファイル|
|ckinterp.f|Fortran77コード，反応機構と熱力学データベースの読み込み|
|compl.sh|コンパイル用シェルスクリプト|
### 出力ファイル
|ファイル名|内容|
|:---|:---|
|ckout|結果確認用アウトプットファイル|
|cklink|次の反応解析で使用されるバイナリファイル|
### 使用方法
必要ファイルを準備してターミナルで以下を実行
```
$ sh compl.sh
```
生成されるckoutでエラーの有無を確認．  
cklinkを反応解析（SENKIN, PREMIXなど）を行うフォルダにコピーして使用# CKinterp_Recombination
