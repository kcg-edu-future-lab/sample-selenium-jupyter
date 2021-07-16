# sample-selenium-jupyter

seleniumをJupyter Notebookから使うサンプルです。

このサンプルを動かすには，dockerとdocker-compose，VNC Viewer(https://www.realvnc.com/en/connect/download/viewer/ )が入っている必要があります。

このリポジトリをcloneし，cloneしたディレクトリに移動して下記コマンドを実行してください。

```
docker-compose up
```

正常に起動すると，以下のアドレスでJupyter Notebookが利用できます。

```
http://localhost:8888/
```

VNC Viewerで以下のアドレスに接続すると，Jupyterから起動したChromeを表示できます。

```
localhost:5900
```
