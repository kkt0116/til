# Git
1. 入手
    - [git --local-branching-on-the-cheap](https://git-scm.com/download/win) > Click here to download で 2.45.1 64bit(Git-2.45.1-64-bit-exe) を取得
2. 取得したファイルを実行してインストール。基本的にデフォルト。変更したものなどは以下。完了！
    - Component。デフォルト。記録しておく
      - ![image](https://github.com/kkt0116/til/assets/97575675/703a1e7c-bc6c-4ec7-a9d1-b9b3e06ce8bd)
    - デフォルトエディタ。Cursor にする
      - 「Select other editor as Git's default editor」 を選択
      - Location は [Cursor > 導入](./Cursor.md#導入) > 3. > Command Line のパス内の cursor.cmd を選択し、` --wait` を追記
        - テストに通ることも確認
    - inital branch in new repositories。main にする
    - Configuring the line ending conversions。Checkout も commit も as-is
