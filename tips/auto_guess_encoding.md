# ファイルを開いた時にエンコーディングを自動判別したい

[//]: # (Image References)

[image1]: ./images/autoguessencoding.png

既定では UTF-8 でファイルを開きますが、`files.autoGuessEncoding` を true にすると自動でエンコーディングを判定してくれます。

1. [Code] - [Preferences] - [Settings] と選択 (macOS の場合)
2. 右ペインのユーザー設定のところに次の設定を書く
```
{
    "files.autoGuessEncoding": true
}
```

![alt text][image1]