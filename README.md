#スケジュール
- https://docs.google.com/spreadsheets/d/1fw-3M0BXq9cxP8XOKsJc_xqgRHQ4fdld5zsvbIJWGF0/edit?usp=sharing

------------------------------------------------------------------------------------
# 5/19,20
## やったこと  
- 申し訳ありません、風邪が悪化してしまった為、作業ができておりません。
  
------------------------------------------------------------------------------------

# 5/21
## やったこと  
- パーツ洗い出し
- スケジュール作成
- css設計

## 学んだこと   

## 時間    
- 2:00  

------------------------------------------------------------------------------------
  
# 5/22
## やったこと  
- ヘッダー
- グローバルナビ
- ボタン
- ラベル
- h2見出し
- 記事のアウトライン

## 学んだこと   
- text-align: justifyで文字の両端揃えができる
  - ※現在labrlのunreadが「未□読」とスペースで調整されているが、こちらを使えば解決である。
- flexの「justify-content」は横並びにする要素の元々の横幅を全て合算した上で、余った部分の余白に対して「どの要素がどれだけ使うのか」計算される

## 時間    
- 3:00  

------------------------------------------------------------------------------------
  
# 5/23
## やったこと  
- ボタンモジュール全パターン作成
- アンカーテキスト全パターン作成

## 学んだこと・疑問に思ったこと 
- labelやbtnmoduleの切り方に悩んだ。（あとで質問したいです）
  
##林さんアドバイス
- anchor-outsideはテキスト+アイコン部分のみそれを角丸のbtn moduleでラップするのが自然。
- 役割で括ったのはOKだが、見た目がかけ離れ過ぎているのもよくない。（anchor-outsideが今はどう見てもbtn module）
- 丸いボタンと、四角いボタンを共有のmoduleで実装しようとすると、デザインが違い過ぎてクラスが作りにくいので、別々に分ける
- 要素の無駄を取っ払った最小単位（全てに共通しているものは何か）を考える。（最小単位が全くマッチしない要素は別moduleにすると考えるのが無難そう）
  
## 時間    
- 0:45  

------------------------------------------------------------------------------------
  
# 5/24
## やったこと  
- ボタンモジュール修正
- アンカーテキスト修正
- font-familyの設定
- h3,h4の作成

## 学んだこと・疑問に思ったこと 
- fontをダウンロードして設定する方法が複雑でわからなかった。（今はwebからimportしている）  
  
## 時間   
- 1:30
  
------------------------------------------------------------------------------------
  
# 5/25
## やったこと  
- @font-faceの設定
- utillityのmargin設定
- [wip]記事内の文字組み設定

## 学んだこと・疑問に思ったこと 
- fontには様々な形式がある。
- true type：レガシーな形式。数が多く様々なソフトウェアに使われているが容量が小さい。
- open type：true typeに比べて容量が増えた
- woff 上記二つに比べて軽い
- woff2 woffとの違いは圧縮アルゴリズム
- サブセット化してからwoffへ変換することで軽くすることができる。

## 時間   
- 2:00
  
------------------------------------------------------------------------------------
  
# 5/26,27
## やったこと  
- 申し訳ありません、作業ができておりません。
  
------------------------------------------------------------------------------------
  
# 5/28
## やったこと  
- マイルストーン作成
- [wip]section部分のmodule作成

## 学んだこと・疑問に思ったこと 
- 平日は「起床→出社前にやる」という制約の中でやっているが、土日は何も決めていないので逆にうまくできない
- 土日も平日と同じ様に行動を制限してやった方が迷わず勧められるので良い
  
##マイルストーン
- 水曜日に「記事部分」「フッター」「本紹介」が完了している
- 今週の土曜日で一通り作成が終わり、日曜、月曜で微調整する


## 時間   
- 1:00

------------------------------------------------------------------------------------
  
# 5/29
## やったこと  
- [wip]book module作成途中

## 学んだこと・疑問に思ったこと 
- display flexのプロパティを使いこなせていない
- flex-basis:フレックスアイテムの基準の幅を指定する。
- flex-grow：フレックスコンテナの余白を個々のフレックスアイテムに分配する比率。0だと変わらない
- flex-shrink：フレックスアイテムの横幅がフレックスコンテナを上回る時、個々のサイズを縮小する比率。0だと変わらない。
- flex: grow→shrink→basisの順番で一括指定ができる。
- とりあえず手を動かすが意外と重要。頭だけで考えても時間が過ぎるだけだった。
  
## 時間   
- 1:00
  
------------------------------------------------------------------------------------
  
# 5/30
## やったこと[wip]  
- 本紹介
- 本の詳細情報
- 本の評価
- アコーディオン（今回jsメインじゃないのでjQuelyでパパッと）
- 記事部分のテキストレイアウト
- お店のロゴ
- コピーライト

## 学んだこと・疑問に思ったこと 
- flex-grouはフレックスコンテンツの余白なので、フレックスアイテムの幅が狭くなると（今回だと文字数）横幅が変わってしまう
- icotto模写で学んだ方法（snsやlabel,btn）の考え方がこのタイプのサイトではかなり汎用的に流用できる。構造は同じなので迷わず作成ができる事が分かった。
  
## 時間   
- 4:30

------------------------------------------------------------------------------------
  
# 5/31
## やったこと[wip]  
- raking
- footer

## 学んだこと・疑問に思ったこと 
- 本の紹介moduleとランキングmoduleは似ているようで微妙に違う。book moduleをと大きく括って作成していたが、もっと細かいパーツに分けて　layoutで2つを再現する必要がありそう。設計を考え直す。
  
## 時間   
- 1:00
  
------------------------------------------------------------------------------------
  
# 6/1
## やったこと
- mediaパーツ
- l-bottomの値を再調整

## 学んだこと・疑問に思ったこと 
- 迷ってる時間がとても長い。flierのおすすめ本も、mediaパーツもmoduleに関しては文字のサイズ調整のみで実装が可能なので汎用パーツで作るべきか、moduleをどのように切り出すかで迷った。
- labelが２種類あり、命名をどう分けるかで迷った。
  
## 時間   
- 2:00
  
------------------------------------------------------------------------------------
  
# 6/2,3,4
## やったこと
- 画像素材切り出し
- sns module
- ranking module
- ３種類あるlabelの差別化
- fooer module（アコーディオンが残ってる）
- ページトップに戻るボタン
- panel module
- l-container（汎用的なコンテナパーツ）
- ライター紹介
- thumbnailのフレーム

## 学んだこと・疑問に思ったこと 
- 四角形を４５度回転させる。隣接する２辺にborderをつける事でで「>」「<」これらの記号を表現する事ができる。
- ユニバーサルセレクタでデフォルトを指定してしまうと画像にもline-heightが付いてしまい意図しない結果になるのでmodule毎に指定していたが、記述箇所が多くて管理できていない。
- border-radiusで [コンテナの高さpx コンテナの高さpx 0 0]指定で半円が描写できる
- calcはcalc(xx%□-□10px)という風に半角スペースを付けないと指定できない
- l-flexとl-bottom-xxxでそこそこのパーツが再現できる
- 改行に全角スペースが紛れ込んでいると、謎の高さができてしまう
  
## 時間   
- 9:00
  
------------------------------------------------------------------------------------
  
# 6/5
## やったこと
- 残りパーツ全て
- スタイル見直し

## 学んだこと・疑問に思ったこと 
- box-sizingはmarginは含まない。border、paddingのみ
  
## 時間   
- 5:00
