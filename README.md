# kenshu-frontend-react

## memo

### コンポーネントの定義の要点

- アプリの明らかな「塊」
- よく再利用される <- 特にこれ

### 何回かみることになりそうな記事

- [React hooks を基礎から理解する (useEffect 編)](https://qiita.com/seira/items/e62890f11e91f6b9653f)

## コメント

- useRef は useState のようにコンポーネント内の値を保持できる
- 使い分け
  - 再レンダリングはしたくないけど、内部に保持している値を更新したい場合は useRef
    [React hooks を基礎から理解する (useRef 編)](https://qiita.com/seira/items/0e6a2d835f1afb50544d)
