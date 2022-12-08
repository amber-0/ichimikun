# 課題　 --
辛いものを登録していくアプリ一味くん

## ①課題内容（どんな作品か）
- 辛いものを登録すれば、登録したデータをデータベースにぶち込める

## ②工夫した点・こだわった点
- プルダウンで選択肢を選べるようにした
- 登録した内容をデータベースにぶち込める
- 以下の通りデータベースを設計（設計というのか？）
DB名　　：ichimi_db
Table名 ：ichimi_data_table
項目名　：
1.id（int12,PrimaryKey,Autoincrement）
2.name（varcher64）
3.eval(int12)
4.container(varcher64)
5.seller(varcher64)
6.quantity(varcher64)
7.review(text)

## ③難しかった点・次回トライしたいこと(又は機能)
- 今回はINSERTでデータベースにぶち込むだけなので、次回はSELECTでデータを取り出し、CSSを適用した状態で適宜画面に表示していきたい。
- 次回、待ってろよLaravel（実際そこまでは無理かも）

## ④質問・疑問・感想、シェアしたいこと等なんでも
- DBは友達、iLtyの動画通りにやればできる。プログラミングを始めてから初めてエラーも出ず、すんなりできたので、とても感動した。
![image](https://user-images.githubusercontent.com/105370349/206443382-8abeaa2e-6f5e-40cc-aa3c-2bb81185fc64.png)
