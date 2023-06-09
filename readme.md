# Pycharm のショートカットキーについて

- ショートカットキーで操作できるようになると学習速度が加速し、プログラミングも上達します。
- ショートカットキーの組み合わせはメニュー名の右側に書いてあることが多いので、それを見て覚えましょう。
- また、プラグイン [Key Promoter X](https://plugins.jetbrains.com/plugin/9792-key-promoter-x) を使えばショートカットキーを覚えやすくなります。
- 環境設定 > キーマップ からショートカットキーをカスタムできます。
- [キーマップリファレンス(公式)|](https://pleiades.io/help/pycharm/keymap-reference.html?keymap=primary_windows)



## Pycharm でよく使うショートカットキー



| 分類           | 動作                               | 備考                                                         | Windows        | Mac            | 必修 |
| -------------- | ---------------------------------- | ------------------------------------------------------------ | -------------- | -------------- | ---- |
| 全般           | 環境設定                           |                                                              | Ctrl+Alt+S     | Cmd+,          |      |
| 全般           | どこでも検索                       | メニューを呼び出せる                                         | Shift2回押し   | Shift2回押し   | ★    |
| コーディング   | コードの整形                       | PEP8をふまえたものに修正される                               | Ctrl+Alt+L     | Cmd+Opt+L      | ★    |
| コーディング   | コメントのオンオフ                 | 複数行も可能                                                 | Ctrl+/         | Cmd+/          | ★    |
| コーディング   | 関数・変数・モジュールの名前変更   | 使用箇所を一気に変更。文字列内で使われている名前は変更されないことも。 | Shift+F6       | Shift+F6       | ★    |
| コーディング   | コードの改善提案の表示             | 提案がある場合は💡が表示                                      | Alt+Enter      | Opt+Enter      |      |
| コーディング   | 警告、エラーに移動                 |                                                              | F2             | F2             |      |
| コーディング   | クリップボード履歴の表示           |                                                              | Ctrl+Shift+V   | Cmd+Shift+V    |      |
| コーディング   | インポート最適化                   | 未使用モジュールの記述削除や並び順修正                       | Ctrl+Alt+O     | Cmd+Opt+O      | ★    |
| コーディング   | クイックドキュメント               | オブジェクトのドックストリングを表示                         | Ctrl+Q         | F1             |      |
| コーディング   | 宣言または使用箇所に移動           | オブジェクトが宣言されている箇所、及び使用箇所にジャンプする | Ctrl+B         | Cmd+B          |      |
| コーディング   | 元の場所に戻る                     | ジャンプ先から戻る                                           | Ctrl+Alt+左キー     | Cmd+Opt+左キー |      |
| コーディング   | 新規ファイル・ディレクトリ作成     | プロジェクトウィンドウにフォーカスして                       | Alt+Insert     | Cmd+N          |      |
| コーディング   | 行の先頭に移動                     |                                                              | Home           | Ctrl+A<br>Home         | ★    |
| コーディング | 行ジャンプ | マウスを使わずに指定した行に飛ぶ | Ctrl+G | Cmd+L |  |
| コーディング   | 行全体を選択                       |                                                              | Shift+下キー   | Shift+下キー   | ★    |
| コーディング   | 選択範囲のコピー                   |                                                              | Ctrl+C         | Cmd+C          | ★    |
| コーディング   | 選択範囲の切り取り                 |                                                              | Ctrl+X         | Cmd+X          | ★    |
| コーディング   | 元に戻す                           |                                                              | Ctrl+Z         | Cmd+Z          | ★    |
| コーディング   | 複数範囲選択                       |                                                              | Shift+矢印キー | Shift+矢印キー | ★    |
| コーディング   | 選択範囲を広げる                   |                                                              | Ctrl+W         | Opt+上キー | ★    |
| コーディング   | メソッド間の移動                   |                                                              | Alt+上下キー   | Alt+上下キー   |      |
| コーディング   | 現在のファイル内で検索             |                                                              | Ctrl+F         | Cmd+F |      |
| コーディング   | 複数ファイル内で検索               |                                                              | Ctrl+Shift+F   | Cmd+Shift+F |      |
| コーディング | 同じ単語を選択 | ショートカットキーを押すたびに選択数が増える | Alt+J | Ctrl+G | |
| コーディング | 同じ単語を一気に選択 |  | Alt+Ctrl+Shift+J | Cmd+Ctrl+G | |
| 実行系         | スクリプト実行                     | 現在選択中の実行構成を実行する                               | Shift+F10      | Ctrl+R         | ★    |
| 実行系         | 構成を選択してスクリプト実行       | どの構成を実行するか選択して実行                             | Shift+Alt+F10  | Ctrl+Opt+R |      |
| 実行系         | デバッグ開始                       | ブレークポイントを置いたところまで一気に実行し、その後は一行ずつ可能 | Shift+F9       | Ctrl+D         | ★    |
| 実行系         | 構成を選択してデバッグ開始         | どの構成をデバッグするか選択して開始                         | Shift+Alt+F9   | Ctrl+Shift+D |      |
| 実行系         | ブレークポイントの設定と解除       | デバッグ中に止まるところを設定する                           | Ctrl+F8        | Cmd+F8         |      |
| 実行系         | ステップイン実行                   | 1行ずつ実行するが、関数などの中に入る                        | F7             | F7             | ★    |
| 実行系         | ステップオーバー実行               | 1行ずつ実行するが、関数などの中に入らない                    | F8             | F8             | ★    |
| 実行系         | 式の評価                           | デバッグ中にオブジェクトの値を確認できるウィンドウを表示<br>式=何らかの演算を行うこと<br>評価=式を実行して値を得ること | Alt+F8         | Opt+F8         | ★    |
| 実行系         | 実行停止                           | プログラムの途中でも停止させる                               | Ctrl+F2        | Cmd+F2 |      |
| フォーカス切替 | 最近開使用したファイル             | 移動先を選べる。コンソールなども。                           | Ctrl+E         | Cmd+E          | ★      |
| フォーカス切替 | タブ移動 (左)                      |                                                              | Alt+左キー     | Cmd+Shift+[    |      |
| フォーカス切替 | タブ移動 (右)                      |                                                              | Alt+右キー     | Cmd+Shift+]    |      |
| フォーカス切替 | タブを閉じる                       |                                                              | Ctrl+F4        | Cmd+W          |      |
| フォーカス切替 | エディタにフォーカス               | コードエディタにフォーカス                                   | Esc            | Esc            |      |
| フォーカス切替 | プロジェクトウィンドウにフォーカス | 左側ペインにフォーカス                                       | Alt+1          | Cmd+1          |      |
