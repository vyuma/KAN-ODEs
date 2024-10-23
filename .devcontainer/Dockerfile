# ベースイメージ
FROM pytorch/pytorch:2.4.1-cuda12.4-cudnn9-runtime

# 必要なパッケージをインストール
RUN apt-get update && apt-get install -y \
    git 


# 作業ディレクトリの設定
WORKDIR /workspace


# コンテナ起動時に実行するコマンド（必要に応じて変更）
CMD [ "bash" ]