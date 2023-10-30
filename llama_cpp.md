## llama.cpp
MacBookとかでLlama系のLLMを動かそうというもの。
ggmlやggufはこれに当たる。
- https://github.com/ggerganov/llama.cpp

## GPUオフロード
元々CPU推論だったが、GPUで推論するともっと高速化できる。
- [Llama.cpp + cuBLAS による Llama 2 の高速実行を試す](https://note.com/npaka/n/n9eda56d3a463)
- [【個人メモ】RTX4090+llama.cppでGPUオフロードできなかったので解決した](https://zenn.dev/saldra/articles/26288e2f03f2ae)

## 量子化
ggufモデルを選定する時のメモ。q4K_Mとか色々ある。
[【ローカルLLM】llama.cppの量子化バリエーションを整理する](https://note.com/bakushu/n/n1badaf7a91a0)

