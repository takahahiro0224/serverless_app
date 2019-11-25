# serverless todo app
railsで作成したtodoアプリとそれをAWS lambdaでサーバレス化したサンプル

# 環境
ruby 2.5
npm
ServerlessFramework
aws lambda
DynamoDB

# コマンド
ruby設定
```
brew install ruby-build
brew install rbenv
rbenv install 2.5.0
rbenv global 2.5.0
ruby -v
```
ServerlessFramework設定
```
npm install serverless -g
sls -v
```
デプロイ設定
```
sls config credentials --provider aws --key <ACCESS_KEY> --secret <SECRET_KEY>
```

デプロイ
```
sls deploy
```
