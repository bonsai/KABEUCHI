# Intent設計

KABEUCHIでは、発話を単純な質問として処理せず、「今ユーザーが何をしたいのか」をIntentとして扱う。

## 初期Intent

- start: 壁打ちを始める
- explain: 考えを話す
- deepen: もっと掘る
- challenge: 別の角度から問い直す
- research: 調べる
- summarize: 整理する
- save: 成果物として保存する
- finish: 今回の壁打ちを終了する

## 重要な考え方

Intentは固定順序ではない。

ユーザーの回答によって、
deepen → research → deepen
のように遷移できる。

出版企画では7問を基本フレームとするが、回答が弱い場合は質問を追加する。

## Hidden complexity

ユーザーにはIntentを見せない。

ユーザーが意識する操作は基本的に、

「話す」
「調べる」
「保存する」

だけにする。
