# ベースイメージの設定
FROM golang:1.19-alpine
# アップデートとGitインストール
RUN apk update && apk add git
# appディレクトリの作成
RUN mkdir -p /go/src/github.com/kenji-otomo/SNS-RECORD-API/api
# 作業ディレクトリの設定
WORKDIR /go/src/github.com/kenji-otomo/SNS-RECORD-API/api
# ホストのファイルをコンテナ内の作業ディレクトリに移行
ADD . /go/src/github.com/kenji-otomo/SNS-RECORD-API/api

# COPY go.mod go.sum ./
# RUN go mod download

