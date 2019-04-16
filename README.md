
# C# SSH.Net の使用例です。

やっていることは以下になります。
1. sftpへの接続
1. ファイルリスト取得
1. ファイル内容取得(download)
1. ファイルアップロード(upload)

ファイル構成は

```
└─[projectroot]
　　└─[docker]
　　　　├─[remote]
　　　　│　└─test.txt
　　　　│　　　└─id_rsa
　　　　└─[ssh]
```

となっており、Dockerでsftpサーバを立ててテストを行いました。
