# WP Update Manager Companion

WordPress プラグイン「WP Update Manager Companion」の配布元です。

このリポジトリにソースコードは置いていません。配布物は [Releases](../../releases) にあります。

- 最新版の情報: [`releases/latest/download/manifest.json`](../../releases/latest/download/manifest.json)
- 配布物: 各 Release の `wp-update-manager-companion-<version>.zip`

zip の完全性は `manifest.json` の `sha256` で確認できます。

## manifest.json

```json
{
  "version": "0.0.0",
  "package": "https://github.com/sx-inc/wp-update-manager-companion/releases/download/v0.0.0/wp-update-manager-companion-0.0.0.zip",
  "sha256": "…",
  "requires": "5.8",
  "requires_php": "7.4"
}
```

プラグインは自身の `Update URI` ヘッダを通じてこのファイルを参照し、
zip の SHA-256 が一致した場合にのみ更新を適用します。
