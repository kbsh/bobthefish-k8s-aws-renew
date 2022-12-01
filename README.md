## 概要
- bobthefishのAWS-VAULTを利用したプロファイル名表示が（私の環境では）動作しなかったので`AWS_PROFILE`環境変数を参照するよう修正
- bobthefishのk8s context名表示が、AWS EKSの場合ARN全ての表示となり長ったらしいので、アカウントIDやリージョンなどを省略して表示するよう修正
  - これをやらずとも`~/.kube/config`のnameで変名を付けることができました・・

![結果](readmeimg/result.png)
