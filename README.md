# カウントアプリ発展

## なにをするか

このレポジトリは，カウントアプリのプラス/マイナス機能を実装したものになります．
このレポジトリを clone してからスタートしてください！

## 注意事項

- データベースは作成されていませんが，マイグレーションファイルは含まれています．各自マイグレートしてください．

## 仕様

https://ld13-count.herokuapp.com/ <br>
このアプリケーションを実装してください

### 背景 / ボタン

#### 全体背景色

- ![#00b5de](https://via.placeholder.com/15/00b5de/000000?text=+) #00b5de

#### プラスボタン

- 背景色: ![#e94c4d](https://via.placeholder.com/15/e94c4d/000000?text=+) #e94c4d
- 文字色: ![#d8d8d8](https://via.placeholder.com/15/d8d8d8/000000?text=+) #d8d8d8

#### マイナスボタン

- 背景色: ![#c2ca2e](https://via.placeholder.com/15/c2ca2e</000000?text=+) #c2ca2e
- 文字色: ![#d8d8d8](https://via.placeholder.com/15/d8d8d8/000000?text=+) #d8d8d8

#### クリアボタン

- 元のファイルにはないので実装してください！
- 背景色: ![#f8b516](https://via.placeholder.com/15/f8b516</000000?text=+) #f8b516
- 文字色: ![#d8d8d8](https://via.placeholder.com/15/d8d8d8/000000?text=+) #d8d8d8

### リングの色

現在のカウントの数によってリングの色が変わります.

- 通常時
  - ![#d8d8d8](https://via.placeholder.com/15/d8d8d8/000000?text=+) #d8d8d
- 3 の倍数または、3 がつく数字の時
  - ![#f8b516](https://via.placeholder.com/15/f8b516/000000?text=+) #f8b516
- 0 は通常時として扱います！

### カウント文字色

現在のカウントの数によって文字色が変わります.

- 通常時
  - ![#edda15](https://via.placeholder.com/15/edda15</000000?text=+) #edda15
- 3 の倍数の時
  - ![#d01026](https://via.placeholder.com/15/d01026</000000?text=+) #d01026 
- 5 の倍数の時
  - ![#ec6c1f](https://via.placeholder.com/15/ec6c1f</000000?text=+) #ec6c1f
- 15 の倍数の時
  - ![#2a6d39](https://via.placeholder.com/15/2a6d39</000000?text=+) #2a6d39
- 0 は通常時として扱います！