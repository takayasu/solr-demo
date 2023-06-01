# solr-demo

## 概要
6月25日に実施したBTC主催のSolr勉強会のデモ（空間検索）を公開します。

## 勉強会資料
https://speakerdeck.com/takayasu/solrmian-qiang-hui-2015

## 構成

Javascript - Apache - Apache Solr

##　利用方法
* コアの準備
confフォルダの設定ファイルをSolrのコアとして設定します。コア名は「station」としてください。

* データ読み込み
dataフォルダのCSVをコアにロードしてください

* HTMLリソースの配置
Apacheにstationフォルダを配置、あるいは中身を配置してください。



# 謝辞
駅のデータは、

駅データ.jp様（http://www.ekidata.jp/）

のデータを加工しています。

利用させていただいており、ありがとうございます。


## 注意
品質については、デモなので確認がゆるいため、何か問題がおこっても責任を取ることができませんので了承ください。

Javascriptはプロトタイプとして書いているので、書き方が汚いので、きれいに書き直していただけたらうれしいです。（プルリクください）
