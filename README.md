# Welcome to your CDK TypeScript project

This is a blank project for CDK development with TypeScript.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

* `npm run build`   compile typescript to js
* `npm run watch`   watch for changes and compile
* `npm run test`    perform the jest unit tests
* `npx cdk deploy`  deploy this stack to your default AWS account/region
* `npx cdk diff`    compare deployed stack with current state
* `npx cdk synth`   emits the synthesized CloudFormation template

# 前提条件
- Ubuntu 22.04
- Docker 27

# 開発時の注意点
- Nodeのバージョンを揃えるため、コンテナを使用します。
- cdkコマンドの実行方法
    1. コンテナに入る。  
        `sh start-cdk-container.sh`
    2. cdkコマンドを実行する。  
        `npx cdk 〇〇`