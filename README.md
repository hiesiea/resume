# resume

[職務経歴書](https://hiesiea.github.io/resume/)

## バージョニングについて

[セマンティック バージョニング](https://semver.org/lang/ja/)に基づく。

- メジャーバージョンアップ：修正後、新しく転職活動を始める際に上げる
- マイナーバージョンアップ：誤字脱字等の修正完了時に上げる
- パッチバージョンアップ：誤字脱字等の修正中、PDF で確認したいときに上げる

## コミットメッセージのフォーマットについて

[Semantic Commit Messages](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716) に基づく。

## リリースノートを作成する

`v**` tag をつけて push すると GitHub Actions でビルドが走り、PDF の生成、Release の作成、Assets へ PDF の登録が実行されます。

```shell
git tag v1.0
git push origin --tags
```
