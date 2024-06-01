# [Cursor](https://cursor.sh/)
コード生成AIについて調べたときによく名前が出てきていたエディタ

## 導入
1. [Cursor](https://cursor.sh/) > Download for Free からダウンロード
2. DLしたファイルを実行
    - Cusor Setup 0.34.3 - x64 だった
3. Cursor が開いて以下の設定画面が出る。下記を選択/実行後、Continue
    - ![image](https://github.com/kkt0116/til/assets/97575675/cd420892-5012-4fdc-9739-5300d0dbe7f7)
    - Keyboard: ショートカットキーの設定。既存含む。デフォルトの VS Code のままとする
    - Language: AIでサポートする言語。日本語にする
    - Codebase-wide: コードベース全体にわたる質問に答えるための計算をする機能を有効にするか、無効にするか。有効にする
      - Cursor 内でプロジェクト全体のシンボルにインデックスを作成したり、コードの意味やコンテキストの情報を保持(埋め込み)して、プロジェクト全体を加味してAIが回答してくれるようになる
        - e.g.) ファイルをまたがった定義で正確な場所を特定して回答
        - e.g.) プロジェクト全体の依存関係や構造を理解した上で、コードの最適化やバグ修正をアドバイス
        - e.g.) 質問の文脈に基づいて、関連するコードスニペットやドキュメントを提示
    - Command Line: コマンドラインを使用して Cursor を開けるようにする登録。cursor を登録
      - e.g.) cursor登録 → `cursor .` で現在のディレクトリを Cursor で開けて便利
      - ![image](https://github.com/kkt0116/til/assets/97575675/d7f5c77f-a824-4d0d-90b8-2a647e57dabe)
        - PCに変更を加えている。システム環境変数の Path に以下が登録されていた
          - C:\Users\{User}\AppData\Local\Programs\cursor\resources\app\bin
4. VS Codeの拡張機能、設定、ショートカットキーをインポートするかどうか。インポートしておく
    - ![image](https://github.com/kkt0116/til/assets/97575675/8bb1dc4f-07b0-4ece-a1e6-b4654f83f14d)
5. Cursor のためのデータの収集に協力するか。プライベートでいろいろ試してみるようなのでする
    - ![image](https://github.com/kkt0116/til/assets/97575675/d95d012f-2caf-4170-a503-469df33c10d6)
6. ログイン/サインアップ/スキップ。ログインして完了！
    - ![image](https://github.com/kkt0116/til/assets/97575675/7976c8f2-d85e-49f2-a732-9268de5554be)
      - Google や Github のアカウントも使える。
      - バックエンドの不正利用を防ぐため、AI機能を使用する際にはログインをお願いしています。今はスキップすることもできます。とのこと
      
## Welcome
閉じちゃったら Cursor 起動しなおすと出てくる  
![image](https://github.com/kkt0116/til/assets/97575675/8d05ecc1-43a9-43b4-bc4a-2a671a468269)

1. Finish onboarding: なんか終わってた。初期設定？
2. Accept an autocomplete
3. Prompt an edit
4. Ask a question
5. Chat with your codebase

## 設定
### Git
1. 入れてなかったのでPCに導入 > [Git](./Git.md) 参照
     - Cursor をエディタとして設定
2. reload をクリック
     - ![image](https://github.com/kkt0116/til/assets/97575675/e48be964-8167-4230-a3b6-b944ee156890)
3. Folder を開いている場合は閉じて、`Gtrl + Shift + G' or ツールバーの View > Source Control
4. Clone Repository から、Github と連携させて、このリポジトリをクローン。完了！

