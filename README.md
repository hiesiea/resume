# hiesiea

職務経歴書用のリポジトリです。

## リリースノートを作成する

`v**` tag をつけて push すると GitHub Actions でビルドが走り、PDF の生成、Release の作成、Assets へ PDF の登録が実行されます。

```shell
git tag v1.0
git push origin --tags
```
