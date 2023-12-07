# # DockerHubのベースとなるイメージを指定
# FROM python:3.10

# # 作業ディレクトリを変更
# WORKDIR /workspace

# # ローカルPCのファイルをコンテナのカレントディレクトリにコピー
# COPY requirements.txt ${pwd}

# # pipのアップデート
# RUN pip install --upgrade pip

# # pythonパッケージをインストール
# RUN pip install -r requirements.txt

# # コンテナ起動時に実行するコマンドを指定
# CMD ["/bin/bash"]


FROM nvcr.io/nvidia/pytorch:21.12-py3
WORKDIR /workspace/src
CMD ["/bin/bash"]
# CMD ["jupyter", "lab", "--ip=0.0.0.0", "--allow-root", "--LabApp.token=''"]