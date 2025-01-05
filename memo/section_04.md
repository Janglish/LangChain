# 学習メモ

## LangChainのモジュール（全部で6つ）
- Models: LangChainで使用する機械学習のモデル(LLMs, Chat Models, Text Embedding Models)
- Prompts: モデルへの入力を組み立てるためのモジュール(Prompt Templates, Chat Prompt Templates, Example Selectors, Output Parsers)
- Chains: モジュール（Modelse, Templates, Chainsなど）を連結する 
- Indexes: 
- Memory: 
- Agents: 

### Chains
- SimpleSequentialChainを使うと、ChainとChainを直列に連結できる

### Output Parsers
- JSONなどの出力形式を指定するプロンプトの作成と、Pythonのオブジェクトとのマッピングを提供する機能
- 形式が不正でうまく解析できなかった場合に、LLMに形式を整えてもらうような機能もある
- Few-shotプロンプティングの例を埋め込むための「Example Selectors」という機能もある