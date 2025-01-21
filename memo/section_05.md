# 学習メモ

### Indexes
- 文書をベクトル化して、Vector Storeに保存しておき、入力と近いベクトルの文書をVector Storeから検索してcontextに含めることができる
- ベクトル化には、OpenAIのEmbeddingsなどを使用

## Memory
- 過去の対話の保持

# Agents
- モチベーション：IndexsによるVector Storeなどの検索以外にも、LLMが必要に応じていろいろなことをしてくれたら嬉しい　
- MRKL, ReActという仕組みのプロンプトで動いている
