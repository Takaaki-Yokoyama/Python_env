# DockerHubのベースとなるイメージを指定
FROM python:3.10-slim

# 作業ディレクトリを変更
WORKDIR /workspace

# ローカルPCのファイルをコンテナのカレントディレクトリにコピー
COPY requirements.txt ${pwd}

# pipのアップデート
RUN pip install --upgrade pip

# pythonパッケージをインストール
RUN pip install -r requirements.txt

# コンテナ起動時に実行するコマンドを指定
CMD ["/bin/bash"]
