# AWSコース第11回講義の受講

## ServerSpecでインフラ環境のテスト実行
* SeverSpecのインストール<br>
  $ gem install serverspec<br>
  $ mkdir serverspec<br>  
  $ cd serverspec<br><br>

* ServerSpec初期セットアップ<br>
  $ serverspec-init<br><br>
![tree](images11/tree.png)

* sample_spec.rbの編集<br><br>
![sample_spec.rb](images11/lecture11-testcode.png)

* テスト結果<br><br>
![テスト](images11/serverspec-test.png)