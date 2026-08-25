# 比較候補のローカル配置

このディレクトリには、採用前のUdonarium派生版をそれぞれ独立したGitリポジトリとして配置します。

- `axe/`: Udonarium Axe
- `hktrpg/`: Udonarium @ HKTRPG
- 必要になった場合だけ、ほかの候補を小文字の短い名前で追加します。

候補本体は親リポジトリの`.gitignore`対象です。候補側の履歴、ブランチ、依存関係を維持し、親のLycorisリポジトリへソースをコピーしたり`git add`したりしません。

一時的なfork調査や数分で削除するクローンは、ここではなくルートの`.work/`を使います。

詳細は[`doc/WORKSPACE_LAYOUT.html`](../doc/WORKSPACE_LAYOUT.html)を参照してください。
