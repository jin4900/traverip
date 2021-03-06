# Application name
### Traverip
# 概要
旅行記事の閲覧、観光スポット写真の投稿と共有  
・アドレス <http://54.92.40.20/>  
・テスト用アカウント  
　email: "test2@gmail.com"  
　password: "1234567"  
# 機能一覧
・ユーザー登録、編集  
・記事の閲覧(管理者のみ記事の作成、削除)   
・記事のキーワード検索(複数キーワードの絞り込み可)  
・各エリア(例：関東)毎の絞り込み  
・記事のお気に入り登録  
・観光スポット(記事)に対する写真の投稿  
・写真とユーザーのリンクにより、他ユーザーの詳細ページ(投稿一覧)閲覧  
# 制作環境
・Ruby 2.5.1  
・Ruby on Rails 5.2.4  
・HAML, SCSS, JavaScript(ライブラリ：jQuery)  
・AWS(EC2, S3)  
※サーバーはEC2インスタンスを使用しており、画像はCarrierWaveを使用し、S3へ保管
# 制作背景
本アプリは旅行をテーマとして「traverip（travel & trip）」と題しています。
自分の目標である"１からWebサービスを立ち上げる"のと、趣味の旅行を掛け合わせました。
今まで学んだ知識、応用、新しい技術を取り入れることで、スキルアップを目指し、目標達成への一歩として作成しました。
# 工夫したこと
ユーザーの興味を惹くように、動的な要素を多く取り入れました。
サービスはユーザーがいてこそ成り立つものなので、一人でも多くの人の目に止まることを考えました。  
以下、一部抜粋
![動的サンプル](https://github.com/anomeme/traverip/blob/master/%E5%8B%95%E7%9A%84%E3%82%B5%E3%83%B3%E3%83%95%E3%82%9A%E3%83%AB.gif)
他にもボタンの動きなどの細かい部分も気を配りました。
# DB設計
![ER図](https://github.com/anomeme/traverip/blob/master/ER%E5%9B%B3.png)
