# Travel Map App

Travel Map App は、Next.js と Leaflet を使って作成された、旅行のルートをインタラクティブな地図上で可視化し、アニメーションとして再生できるWebアプリケーションです。位置情報を追加したり、移動手段を選択したり、ラベルや写真を各ポイントに添付することができます。また、作成したルートのスクリーンショットを保存する機能も備えています。

## 主な機能

- **インタラクティブルートマップ:** Leaflet を使用した様々なタイルレイヤーの切り替えが可能なマップ。
- **ルートアニメーション:** 追加した地点間の移動をアニメーションで滑らかに表現。
- **Geocoding (住所検索):** OpenStreetMap (Nominatim API) を利用して、地名から自動で緯度経度を取得。
- **カスタムピンと写真の追加:** 訪れた場所に独自のラベルや思いでの画像を添付可能。
- **スクリーンショット撮影:** 作成した旅行ルートを html2canvas で画像としてローカルに保存。

## 技術スタック

- **Framework:** [Next.js 15](https://nextjs.org/) (App Router)
- **Library:** [React 19](https://react.dev/)
- **Styling:** [Tailwind CSS 4](https://tailwindcss.com/)
- **Map Library:** [Leaflet](https://leafletjs.com/), [Leaflet Routing Machine](https://www.liedman.net/leaflet-routing-machine/)
- **Icons:** [Lucide React](https://lucide.dev/)
- **Utilities:** html2canvas, file-saver

## ローカルでの実行方法

リポジトリをクローンした後、以下の手順で開発サーバーを立ち上げてください。

1. 依存関係のインストール

```bash
npm install
```

2. 開発サーバーの起動

```bash
npm run dev
```

ブラウザで [http://localhost:3000](http://localhost:3000) を開き、アプリの動作を確認してください。

## 注意事項

- このアプリケーションはGitHub上で公開コード（Public）として管理・閲覧されることを前提としていますが、実際のアプリとしてのデプロイは現在想定していません。
- 外部API (Nominatim) を利用しているため、APIの利用規約に従い、短時間での大量リクエスト等の負荷をかける行為はお控えください。

## 著作権およびライセンス (License)

このプロジェクトは **MIT License** のもとで公開しています。
以下の条件を守れば、個人・商用問わず、誰でも無償で自由にご利用いただけます。

- **自由な利用:** 複製、改変、再配布、フォーク（派生リポジトリの作成）が可能です。
- **商用利用:** 個人開発だけでなく、商用プロダクトへの組み込み等も問題ありません。
- **必須条件:** ご利用の際は、ソフトウェアのコピーや重要な部分に、「著作権表示」および「MITライセンスの全文」を含める必要があります（本リポジトリ内の `LICENSE` ファイルをご参照ください）。

※ 詳細については [MIT License の解説](https://opensource.org/licenses/MIT) をご参照ください。

---

## 著作権 (Copyright)

Copyright (c) 2025 Lchiki_nl

- **Twitter (X):** [@Lchiki_nl](https://twitter.com/Lchiki_nl)
