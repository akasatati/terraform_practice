## 概要
terraformの練習用

### 環境構築
```shell
brew install tfenv
tfenv install

# 鍵の流出防止
brew install git-secrets
git secrets --register-aws --global
git secrets --install ~/.git-templetes/git-secrets
git config --global init.templatedir '~/.git-templates/git-secrets'
```
