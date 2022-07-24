# the_best_routes(仮)
---
■ サービス概要  
営業職をはじめとした、外回りが多くルート検索を面倒に感じている人に、  
複数の訪問先への行き方を一括で、かつ時間を指定して1日の予定に則した検索ができ、  
ルート検索を効率化できるサービスです。  

■ メインのターゲットユーザー  
外回りの多い営業職  
1日に複数の訪問予定があり、都度ルート検索を行うのに手間がかかってしまう。  

■ 解決方法  
1日の予定の訪問先や時間を入力することで、  
それぞれの訪問先への行き方をまとめて提示することによって、  
都度ルート検索を行う手間を省く。  

■ 実装予定の機能  
- ルート検索機能
  - 複数の訪問先への行き方をまとめて検索し、出発時間、公共交通機関の時間を提示する
- ルート出力機能
  - その日に利用した公共交通機関の区間、運賃を出力して経費精算を効率化する
- ユーザー登録機能
  - ユーザー登録を行うことにより、上記のルート出力機能を一定期間保存できるようにする
- 通知機能
  - 次の予定に向け、公共交通機関の出発時間・乗換案内を通知
  - 利用予定機関の遅延・運休など非常事態の通知
- ランチタイム確保
  - 入力された予定から空き時間を見つけ、ランチタイムを確保する
  - 近くのランチをやっているお店を表示
  - PC作業をしたい人向けに電源のあるお店を探す
- ニュース表示
  - 訪問予定の会社の最新ニュース、時事・業界ニュースを表示する

■ なぜこのサービスを作りたいのか？  
自身の営業職としての経験を通じて、  
事前に訪問予定先へのルートを調べるのに時間がかかり、  
商談終了後に次のアポイントに向けて都度ルートを検索することが手間だと感じておりました。  
また、中途半端な時間に移動してしまい昼食を食べそこなる日も多々ありました。  
このサービスを通して、事前準備を効率よく行い、  
ランチもしっかりと食べて営業活動に集中できるようサポートができればと思います。  

■ スケジュール  
企画〜技術調査:7/31〆  
README〜ER図作成:8/6〆  
メイン機能実装:8/6 - 8/31  
β版をRUNTEQ内リリース（MVP）:9/1〆  
本番リリース:9/15  