# 【バSPユーザ】機能設計書_エリア検索(新ASP)

## 目次

## 1-2-6-1. 都道府県配下の市区町村リストからチェックを付けるべき対象にフラグを立てる

※単一エリアフラグが1のエリア1は表示対象ではないが、下記のチェック対象とし最終的な表示の制御箇所でこれを除外する  

![エリア検索(新ASP)_1-2-6-1](Markdown挿入フロー図(draw.io)\【バSPユーザ】機能設計書_エリア検索(新ASP)\エリア検索(新ASP)_1-2-6-1.svg)

## 1-2-6-2. フラグを付けたリストをチェック済状態にして表示処理を行う

※チェックフラグはそれぞれのリストで固有  

![エリア検索(新ASP)_1-2-6-2](Markdown挿入フロー図(draw.io)\【バSPユーザ】機能設計書_エリア検索(新ASP)\エリア検索(新ASP)_1-2-6-2.svg)
