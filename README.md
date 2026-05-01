from pathlib import Path

readme_md = """# スポットライトプラグイン ver1.0.0

ゆっくりMovieMaker4に、矩形スポットライトの映像エフェクトを追加するプラグインです。

画面全体を暗くし、指定した四角形の範囲だけを明るく表示できます。  
資料解説、ニュース風動画、注目範囲の強調などに使用できます。

---

## 製作者

**破綻国家研究所**

- X: <https://x.com/InsHatanCountry>
- YouTube: <https://www.youtube.com/@%E7%A0%B4%E7%B6%BB%E5%9B%BD%E5%AE%B6%E7%A0%94%E7%A9%B6%E6%89%80>
- GitHub: <https://github.com/hatankokka>

---

## 主な機能

- スポットライト範囲の中心X/Yをpx単位で指定
- スポットライト範囲の幅/高さをpx単位で指定
- 周囲を暗くする強度を調整
- 境界ぼかしをpx単位で調整
- 画像および動画アイテムへの適用に対応

---

## 導入方法

### 方法1：`.ymme` で導入する

`SpotlightEffect.ymme` をダブルクリックして導入してください。

この方法を利用するには、YMM4のバージョンが **4.29.0.0以降** であり、YMM4用拡張子が関連付けされている必要があります。

導入後、YMM4を再起動してください。

### 方法2：手動で導入する

`SpotlightEffect.dll` を、YMM4フォルダ内の `user\\plugin` フォルダへ配置してください。

環境によっては `plugin` フォルダが存在しない場合があります。  
その場合は、自分で `plugin` フォルダを作成してください。

yummeで導入できない場合は下記をお試しください。
https://github.com/hatankokka/YMM4-SpotlightEffect

配置例：

```text
YukkuriMovieMaker4\\user\\plugin\\SpotlightEffect\\SpotlightEffect.dll
