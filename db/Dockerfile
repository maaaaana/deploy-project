FROM mysql:8.0

# 初期化用SQLファイルをコピー
COPY mysql_setup.sql /docker-entrypoint-initdb.d/

# 起動スクリプト（必要に応じて）
COPY startup.sh /usr/local/bin/
RUN chmod +x /usr/local/bin/startup.sh
