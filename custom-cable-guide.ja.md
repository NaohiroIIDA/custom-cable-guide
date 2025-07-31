# LCSC カスタムケーブル発注ガイド（OpenArm実例）

このドキュメントでは、OpenArm プロジェクトで実際に使用した LCSC のカスタムケーブル発注手順について紹介します。

LCSC のカスタムケーブルサービスでは、簡単な配線図（PDFやPNG）をアップロードすることで、メニューを使わずに柔軟な仕様のケーブルを注文できます。

---

## 対象プロジェクト

- OpenArm（オープンソースロボットアーム）  
  https://openarm.dev/
- 配線仕様  
  https://docs.openarm.dev/hardware/electronics-guide/arm-wiring-and-casing
- 電子部品表（BOM）  
  https://docs.openarm.dev/hardware/bill-of-materials/electrical

---

## 発注手順

### 1. 図面を用意する

以下の項目を記載した図面（PDFまたはPNG）を用意します：

- コネクタの種類（例：JST PH-2P オス／メス）
- ケーブルの長さ（例：300mm）
- ピン配列（例：GND, VCC）
- 本数（例：10本）
- 収縮チューブ・被覆・スリーブ等の特記事項（任意）

---

### 2. LCSCにアップロードして注文

1. https://lcsc.com/custom-cable.html にアクセス
2. 「詳細図面のアップロード」からPDF/PNGをアップロード
3. 数量などを入力し、「Order」をクリック

---

### 3. 見積もりと支払い

- 約1営業日後、「注文管理」画面に見積もりが表示されます
- 問題なければPayPalなどで支払いを行います

---

### 4. 製造図面の確認

- さらに1営業日後、LCSCから製造用の図面（PDF）が届きます
- 以下の点を**必ず慎重に確認してください**：
  - コネクタの型番
  - ピン配列
  - ケーブルの長さ、色、スリーブ指定など

- 問題がなければ「Confirm」をクリックします

---

### 5. 製造と出荷

- Confirm後、5〜10営業日で製造が完了し、出荷されます
- 数日後、日本国内に到着します

---

## 注意点・コツ

- コネクタの型番（例：JST SXH-001T-P0.6）をできるだけ明記する  
- 図面は手書きでも可。ただし誤解のない明確な表記にする  
- 接続するコネクタのピン番号・長さ・ケーブルの色／太さを正確に！
- 英語のメールはシンプルな表現でOK（Google翻訳で十分）

---

## 図面・資料（サンプル）

- [example-cable-diagram.png](./example-cable-diagram.png)
- [lcsc-confirmed.pdf](./lcsc-confirmed.pdf)

---

## このドキュメントの他言語版

- English version: [custom-cable-guide.en.md](./custom-cable-guide.en.md)
