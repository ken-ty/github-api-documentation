# github-api-documentation
自動生成したGithubAPI のドキュメンテーション

## 開発者向け

### 開発準備

```
# このリポジトリのクローン
git clone git@github.com:ken-ty/github-api-documentation.git
# npm パッケージ化
npm init
# global に comittizen　をインストール
npm install
# 開発用パッケージのインストール
npm install -g commitizen
npm install -g cz-conventional-changelog-ja
```

### 開発の流れ

1. develop から feature ブランチを切る
1. 実装する. コミットは `npm run commit` を使用する
1. PRを作成する. wipでも早めに作成することを推奨
1. 承認もらったら develop にマージ
1. develop を定期的に リリース
1. リリース確定したら main に反映