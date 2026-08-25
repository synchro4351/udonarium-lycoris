# ローカル検証領域

採用候補を同じ条件で比較するための、候補に依存しない検証資産を置きます。

- `plans/`: 人間が実施する手順、チェックリスト、合格基準
- `scripts/`: 複数候補で再利用する検証補助スクリプト
- `fixtures/public/`: Gitへ登録してよい、小さく無害な共通テストデータ
- `fixtures/private/`: 実卓データや公開できない素材。Git管理外
- `artifacts/`: ログ、スクリーンショット、計測結果、ビルド成果物。Git管理外
- `runtime/`: PID、ポート情報、一時設定、キャッシュ。Git管理外

候補固有のテストコードは各候補リポジトリに置きます。ここには、同じ試験をAxe、Lycoris、HKTRPGへ適用するための共通物だけを置きます。

詳細は[`doc/WORKSPACE_LAYOUT.html`](../doc/WORKSPACE_LAYOUT.html)を参照してください。
