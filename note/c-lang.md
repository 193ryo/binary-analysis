# C言語の実行

## mac環境での実行
- vscodeの右上実行マークで実行
- gccを使用した実行

## gccでの実行
1. gcc cファイル名（例：gcc hello.c）
2. コンパイルが成功するとa.outという実行ファイルができる。
3. ./ コンパイル後ファイル名（例：./ a.out）

#### オーバーフローを許容するコンパイル
- gcc -fno-stack-protector cファイル名