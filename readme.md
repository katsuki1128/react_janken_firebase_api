# じゃんけん+firebase+chatGPT

## 紹介と使い方

  - じゃんけんの勝率をfirebaseに保存
  - コンピューターが出す手はランダム、勝ち負けを判断
  - 勝率はfirebaseから引っ張ってきている
  - 勝率を見て次に出す手をchatGPTに答えさせている

## 工夫した点

  - firebaseに勝敗を保存して呼び出している点
  - 勝敗についてChatGPTに答えさせている点

## 苦戦した点

  - firebaseとの連携がなかなかできず、結果updateDocはtype="module"のスコープの問題だったことが判明した

## 参考にした web サイトなど

  - https://firebase.google.com/docs?hl=ja