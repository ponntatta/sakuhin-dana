# みんなの作品棚

友だちと作ったサイトやアプリを並べておく、招待制のページです。

- 公開アドレス: https://ponntatta.github.io/sakuhin-dana/
- ログイン: 各自の Google アカウント（Firebase Authentication）
- データ: Firebase Firestore（シフトボードと同じプロジェクト。コレクション名は `hub_` で始まる）
- 参加: 管理者が作った招待リンク `#invite=<合言葉>` を開いてログイン
- メンバーはだれでも作品を見る・追加・編集できる。消せるのは追加した本人と管理者だけ
- `firestore.rules` はシフトボードと共通。変えたら Firebase コンソールのルールに貼り付けて公開する
