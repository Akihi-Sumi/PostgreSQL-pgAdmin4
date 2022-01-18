# PostgreSQL
Docker-Composeを使ってPostgreSQLとPgadmin4を入れる

## 構築手順
①　docker-compose.ymlファイルを作成・記述<br>
②　ターミナルで「docker volume create postgres_volume」「docker volume create pgadmin4_volume」を実行
③　「docker-copmose up -d」を実行<br>
④　ブラウザで「localhost:8000」を確認<br>
⑤　pgadmin4の欄に記述したメールアドレスとパスワードでログイン
