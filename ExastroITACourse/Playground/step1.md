# Exastro ITA Playground
本コースは、オープンソースソフトウェアであるExastro ITAを自由に使用できるPlaygroundです。

誤りや修正箇所を見つけた場合、以下へご連絡ください。
- https://github.com/yassy225/katacoda-scenarios/issues

# 準備作業
## Exastro ITAの起動
以下のコマンドを実行することで、環境の準備を行います。  
この作業は1,2分ほどかかる場合があります。  
docker run --privileged --add-host=exastro-it-automation:127.0.0.1 -d -p 8080:80 -p 10443:443 --name
 exastro01 exastro/it-automation:1.7.2-ja{{execute}}

## 画面の表示
Terminal横の`+`ボタンをクリックし、`View HTTP port 80 on Host 1`をクリックします。  
※エラーが発生した場合は、時間をおいてから再度クリックしてください。

## ログイン
ログイン画面が表示されたら、以下のログインID、パスワードを入力し、`ログイン`ボタンでログインします。  
- ログインID：`administrator`
- 初期パスワード：`password`
※初期パスワードはログイン後に変更する必要があります。

# リンク
[Exastro ITA](https://exastro-suite.github.io/it-automation-docs/index_ja.html)
