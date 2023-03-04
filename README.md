# first-wasm-contract
AstarをWASMで作ってみた（最初のサンプル）

## 主要コマンド
コントラクトのデプロイ
```
swanky contract compile {コントラクト名(ex. flipper)} -v
```

コントラクトのテスト
```
cd contracts/flipper/
cargo +nightly test
```

***
## 参考文献
* [Zenn - Astar入門　WASMを使って、「Shibuya」テストネット上にコントラクトをデプロイしてみよう！](https://zenn.dev/yuki2020/articles/605b2d31d085dd)