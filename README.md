# サバ活 — 公開ドキュメント (Legal & Support)

サバイバルゲーム戦績記録アプリ **「サバ活」** のプライバシーポリシー・特定商取引法に基づく表示・サポートページを GitHub Pages で公開するためのリポジトリです。
アプリ内（「このアプリについて」「購入画面」）と App Store / Google Play のストア掲載情報（プライバシーポリシーURL・サポートURL）から参照されます。

## 公開ページ

| ドキュメント | URL |
|---|---|
| プライバシーポリシー | https://sabakatsuapp.github.io/63works.github.io/privacy-policy.html |
| 特定商取引法に基づく表示 | https://sabakatsuapp.github.io/63works.github.io/tokusho.html |
| サポート（お問い合わせ・FAQ） | https://sabakatsuapp.github.io/63works.github.io/support.html |

## ファイル構成

\```
.
├── privacy-policy.html   # プライバシーポリシー
├── tokusho.html          # 特定商取引法に基づく表示
├── support.html          # サポートページ（お問い合わせ先・FAQ）
└── README.md
\```

## ホスティング

GitHub Pages で配信（リポジトリ `sabakatsuapp/63works.github.io`、
Settings → Pages の設定ブランチのルート）。HTML を編集して push すると数分で自動反映されます。

## 更新手順

1. 各 HTML を編集
2. commit して push
3. GitHub Pages が自動デプロイ（反映まで数分）
4. 上記 URL で表示を確認

> アプリ側の参照 URL は サバ活本体リポジトリの `src/lib/links.ts`
> （`PRIVACY_POLICY_URL` / `TOKUSHO_URL`）で一元管理しています。
> サポートURLは App Store Connect / Google Play Console のストア情報にも登録済み。
> URL を変える場合は、アプリ・ストア両方を必ず合わせて更新してください。

## アプリについて

- **サバ活** … サバゲーの戦績・出撃・フィールド・写真を記録する個人向けアプリ
- 記録データは端末内にローカル保存（外部送信なし）
- お問い合わせ: sabakatsu.app@gmail.com
- 運営：**63works**

## 注意

本リポジトリのファイルはサバ活の法的告知・サポート文書です。転用・再配布は想定していません。
