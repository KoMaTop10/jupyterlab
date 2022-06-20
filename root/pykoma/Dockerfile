FROM python:3.8-buster
#ARG DEBIAN_FRONTEND=noninteractive

# パッケージの追加とタイムゾーンの設定
# 必要に応じてインストールするパッケージを追加してください
#RUN apt-get update && apt-get install -y \
#    tzdata \
#&&  ln -sf /usr/share/zoneinfo/Asia/Tokyo /etc/localtime \
#&&  apt-get clean \
#&&  rm -rf /var/lib/apt/lists/*

ENV TZ=Asia/Tokyo
RUN python3 -m pip install --upgrade pip\
&&  pip install --no-cache-dir \
    numpy \
    pandas \
    matplotlib \
    jupyterlab \
    scikit-learn \
    networkx \
    PuLP \
    ortoolpy \
    opencv-python \
    # dlib \
    mecab-python