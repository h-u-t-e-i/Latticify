# Latticify
全てあなたの所為です。様の『表』、『裏』をイメージしたMIDIヴィジュアライザーです。どっちかっていうとLatticefyが正しいのかもしれないです。

## 概要
MIDIファイルを読み込み、マッピングに従ってグリッド状にノートを配置し、映像と音声を合成してビジュアライズします。  
  
## **`latticify_omote.exe`**
表をイメージしています。〇がひかるよ。

## **`latticify_ura.exe`**
表をイメージしています。□がひかるよ

## **`mapping.txt`**
格子の点滅する位置と音階を紐付けています。行数、列数もここで決まります。

例えば


<img width="238" height="399" alt="スクリーンショット 2025-08-30 002141" src="https://github.com/user-attachments/assets/f7ac43ab-2367-4b0d-967f-ae63fe2cc646" />


と書いて保存すると、最後の行は最後の二枠が補完され、4*10の格子になります。フラットは小文字のbを使ってください。

## **`onkai.exe`**
必要か分かりませんが、そのMIDIファイルに登場する音階を教えてくれます。

##使い方
1. 上の画像に倣って、**`mapping.txt`**を作成してください。
2. **`latticify_omote.exe`**や**`latticify_ura.exe`**の隣に、格子にしたいMIDIファイルを**`input.mid`**という名前で設置してください。
3. **`latticify_omote.exe`**や**`latticify_ura.exe`**の隣に、**`mapping.txt`**を設置してください。
4. **`latticify_omote.exe`**または**`latticify_ura.exe`**をダブルクリックしてください。コマンドプロンプトが出てきますが、放置でいいです。
5. 
