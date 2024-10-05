# AWSコース第11回講義の受講

## ServerSpecでインフラ環境のテスト実行
* SeverSpecのインストール
- $ gem install serverspec
- $ mkdir serverspec  
- $ cd serverspec 

* ServerSpec初期セットアップ
- $ serverspec-init
.
├── Rakefile
└── spec
    ├── localhost
    │   └── sample_spec.rb
    └── spec_helper.rb

![tree](images11/tree.png)

* sample_spec.rbの編集

require 'spec_helper'

describe package('nginx') do
  it { should be_installed }
end

describe service('nginx') do
  it { should be_running }
end

describe port(80) do
  it { should be_listening }
end

describe command('ruby -v') do
  its(:stdout) { should match /ruby 3\.2\.3/ }
end

describe command('bundler --version') do
  its(:stdout){ should match /Bundler version 2\.3\.14/ }
end

![sample_spec.rb](images11/lecture11-testcode.png)

* テスト結果
![テスト](images11/serverspec-test.png)