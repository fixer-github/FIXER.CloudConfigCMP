# ARMTemplate - Azure Policy

- 参考：https://learn.microsoft.com/ja-jp/azure/governance/policy/samples/built-in-policies#general

## テンプレート一覧

- [AllowedLocations.json](./AllowedLocations.json)

## テンプレート詳細

### AllowedLocations.json

#### 概要

- Azure リソースをデプロイするリージョンを制限する Azure ポリシーを設定する

#### デプロイ方法

1. 以下の[Deploy to Azure]ボタンを押下
2. `サブスクリプション` で Azure ポリシーを適用するサブスクリプションを指定
3. `listOfAllowedLocations` でリソースのデプロイ先として許可する Azure リージョンを指定
4. 内容に問題がなければ、[確認と作成]からデプロイを実行

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Ffixer-github%2FFIXER.CloudConfigCMP%2Fdevelop%2FARMTemplate%2FBasicTemplate%2FAzurePolicy%2FGeneral%2FAllowedLocations.json)