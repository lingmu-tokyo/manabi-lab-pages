# manabi-lab-pages

まなびラボシリーズ（えいごラボ／かんじラボ・かなカナラボ）の公式サポートサイト（GitHub Pages）。
公開URL：https://lingmu-tokyo.github.io/manabi-lab-pages/

## フォルダ構成

```
index.html              まなびラボの入口（各アプリのサイトへのリンク）
style.css               全アプリ共通のスタイル
img/                    全アプリ共通の画像（アプリアイコン・ロゴ・favicon）
eigo-lab/               えいごラボ（入門・初級・中級）
  index.html / privacy-policy.html / terms.html / support.html
kanji-kana-lab/         かんじラボ・かなカナラボ
  index.html / privacy-policy.html / support.html
```

## App Store Connect / Play Console に登録するURL

| アプリ | 項目 | URL |
|---|---|---|
| えいごラボ | プライバシーポリシー | https://lingmu-tokyo.github.io/manabi-lab-pages/eigo-lab/privacy-policy.html |
| えいごラボ | サポート | https://lingmu-tokyo.github.io/manabi-lab-pages/eigo-lab/support.html |
| えいごラボ | マーケティング | https://lingmu-tokyo.github.io/manabi-lab-pages/eigo-lab/ |
| かんじラボ・かなカナラボ | プライバシーポリシー | https://lingmu-tokyo.github.io/manabi-lab-pages/kanji-kana-lab/privacy-policy.html |
| かんじラボ・かなカナラボ | サポート | https://lingmu-tokyo.github.io/manabi-lab-pages/kanji-kana-lab/support.html |

## 運用上の注意

- ストアに登録済みのURLになるため、各アプリのフォルダ名・ファイル名は変更しない（変更するとストアのリンクが切れる）。
- ページ内のリンクはすべて相対パス。リポジトリ名を変えてもページ内は壊れないが、GitHub Pagesの公開URLは
  リポジトリ名に連動して変わる（旧URLは自動転送されない）ため、ストアの登録URLを必ず更新すること。
- アプリ内の文面（えいごラボ：`eigo-native`の`PrivacyPolicyScreen.tsx`等）と同期させる。
- 新しいアプリを追加するときは、アプリごとにフォルダを作り、このREADMEのURL表と入口ページ（`index.html`）にも追記する。
