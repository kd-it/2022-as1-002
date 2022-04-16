# 課題内容

Dockerがちゃんと入ったかを検証してみましょう。

## `docker` コマンドが動くかを検証しましょう

```
$ docker run --rm hello-world
```

を実行し、いわゆるHello Worldが動くことを確認して下さい。

## 確認できたら、ファイルに保存しましょう。

リダイレクトを使って出力内容を保存して下さい。
保存先ファイル名は `result.txt` としてください。

```
$ docker run --rm hello-world > result.txt
```

結果ファイル `result.txt` をこのワークツリーにadd,commitして提出(push)してください。
提出先ではこのファイル名固定で内容をチェックして判定するので、ファイル名のミスに注意してください。

