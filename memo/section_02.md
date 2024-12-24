# 学習メモ


- "https://api.openai.com/v1/chat/completions"にgpt-4など最新のモデルがある
- `role`の`user`とは`ユーザー`で、`assitant`とは`AI`のことだと思えばよい
- 会話は`system`のメッセージの後に、`user`と`assitant`のメッセージが交互に続く
- apiではchat-gptのように過去の会話の記憶を保持する機能はないので、過去の履歴を全てメッセージに含める必要がある。
- token数削減のため、英語でやり取りした方が良い
- apiの料金は、
モデルの種類とトークン数（入力と出力の合計）で決まる。