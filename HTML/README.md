# HTML
  
### [基本的なタグ一覧](https://web-designer.cman.jp/html_ref/function_list/) 　（ [別サイト](https://www.tagindex.com/html_tag/elements/) ）
  
#### 補足  
* meta　head内に記述する。文字コードや説明文を閉じタブなしで記述する　[参考サイト](https://style.potepan.com/articles/21185.html#metameta)
  * ①charset="utf-8"　文字コードを指定する（基本はUTF-8）
  * ②name="description" content="概要"　検索時の下部（補足）にあたる
  * ③name="viewport" content="width=, initial-scale=, user-scalable=, minimum-scale=, maximum-scale="　[各種要素（外部サイト）](https://pecopla.net/web-column/viewport)
  * ④name="keywords" content="キーワード1, キーワード2"　メタキーワードの設定は非推奨・不要（サポートされていない）
  * ⑤http-equiv="X-UA-Compatible" content="IE=edge"　IE使用者に指定したバージョンで表示　例）IE=11
  * ⑥property="〇〇" content="▲▲▲▲"　[SNSとWebページの情報を連携（外部サイト）](https://seolaboratory.jp/64252/)
  * ⑦name="format-detection" content="email=no,telephone=no,address=no"　各種自動リンクの無効化
  * その他は[参考サイト](https://style.potepan.com/articles/21185.html#metameta)から
  
* style　HTML内にCSSを直接記述できる　デメリット）量が多いと見づらい
  
* nav　各種リンク（ナビゲーション）をまとめる　[sectionとは？](https://webukatu.com/wordpress/blog/11267/)
  
* p　段落をつくる　brは改行　pで区切ってからbrで改行（デバイスの仕様があるのでbrの多用は厳禁）
  
* li　箇条書き（ulとセットで用いる）
  
* ul　順序なしのリスト 
