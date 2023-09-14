# docker-win-netbox

Docker で NetBox を構築

## 環境

- OS：Windows 10 Pro 21H2
- Rancher Desktop 1.9.1
- Docker version 24.0.2-rd, build e63f5fa

## 実行コマンド

```bash
# netboxリポジトリを取得
$ git clone -b release https://github.com/netbox-community/netbox-docker.git

# ファイル名を変更して有効にする
$ cd netbox-docker
$ mv docker-compose.override.yml.example docker-compose.override.yml
# ビルド
$ docker-compose up -d
```

## 接続 URL

```bash
http://127.0.0.1:8000/
```

## 参考リンク

- [netbox-community/netbox-docker](https://github.com/netbox-community/netbox-docker)
- [Odocker compose で netbox をインストールする手順](https://mebee.info/2020/08/19/post-14474/)
- [Docker 版 NetBox を導入して IP アドレス管理台帳.xlsx に別れを告げる](https://zaki-hmkc.hatenablog.com/entry/2021/01/11/171626)
