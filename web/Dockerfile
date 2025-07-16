FROM openjdk:17

# 作業ディレクトリを設定
WORKDIR /app

# jarファイルをコンテナにコピー（ファイル名そのままでもOK）
COPY DailyReportSystemApplication-0.0.1-SNAPSHOT.jar DailyReportSystemApplication-0.0.1-SNAPSHOT.jar

# 起動スクリプトをコピーして実行権限を付与
COPY startup.sh startup.sh
RUN chmod +x startup.sh

# アプリケーションを起動
CMD ["./startup.sh"]
