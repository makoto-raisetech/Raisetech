# AWSコース第11回講義の受講

## ServerSpecでインフラ環境のテスト実行
* SeverSpecのインストール
- $ gem install serverspec
- $ mkdir serverspec  
- $ cd serverspec 

* ServerSpec初期セットアップ
- $ serverspec-init
![tree](images11/tree.png)

* sample_spec.rbの編集
![sample_spec.rb](images11/lecture11-testcode.png)

* テスト結果
！[テスト実行結果](images11/serverspec-test.png)