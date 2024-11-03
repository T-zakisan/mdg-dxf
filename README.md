# mdg-dxf
M-Draf(*.mdg)をテキストベースのdxfファイルに変換する方法。

これを使用することにより、CADデータをgitで管理すれは、共同編集が可能となる。

リストもExcel(*.xlsx)からCSVファイルにすることで、同様にgitで管理することで、共同編集か可能となる。

また、共同編集だけでなく、
* いつ
* だれが（ユーザ設定必要）
* どこを
* なぜ（コメントを残した場合のみ）
編集したのかを残すことができる。

さらに、同時編集後のマージも


## 方法
1. M-Drafでmdgファイルを開く.
2. ファイル > 保存 > 保存対象の窓をクリック
3. ファイル名：任意
4. ファイルの種類：DXFファイル(*.dxf)
5. [DXFパラメータ]をクリックし、以下画像を参考に変更（M-Draf Lite体験版での実績より）
![image](https://github.com/user-attachments/assets/1a270091-b538-4b5b-b6d1-86f80d213db7)
6.[パラメータの保存] を押す ※dxf → mdgファイルに変換する場合は、これを読み込む！
7. [ok] を押す　※[DXFパラメータ]を閉じる
8. [保存]　を押す
9. 保存したdxfファイルを開き、属性が保たれているか確認する



## 少なくとも分かっているmdgとdxfの違い
|   | mdg | dxf | 備考 |
|:----|:----:|:----:|:---- |
| クリップ | ◯ | ✕ | テキスト周囲を非表示 |
| |  |  |
