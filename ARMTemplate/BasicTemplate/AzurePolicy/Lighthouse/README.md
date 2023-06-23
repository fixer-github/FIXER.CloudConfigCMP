# ARMTemplate - Lighthouse

- 参考：https://learn.microsoft.com/ja-jp/azure/governance/policy/samples/built-in-policies#lighthouse

## テンプレート一覧

- [AllowCertainManagingTenantIds.json](./AllowCertainManagingTenantIds.json)

## テンプレート詳細

### AllowCertainManagingTenantIds.json

#### 概要

- 指定したテナント ID の Azure テナントにのみ、Azure Lighthouse の権限委任を許可する Azure ポリシーを設定する

#### デプロイ方法

1. 以下の[Deploy to Azure]ボタンを押下
2. `サブスクリプション` で Azure ポリシーを適用するサブスクリプションを指定
3. `listOfAllowedTenantsParameter` で Lighthouse の権限委任を許可する Azure テナントのテナント ID を指定
4. 内容に問題がなければ、[確認と作成]からデプロイを実行

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Ffixer-github%2FFIXER.CloudConfigCMP%2Fdevelop%2FARMTemplate%2FBasicTemplate%2FAzurePolicy%2FLighthouse%2FAllowCertainManagingTenantIds.json)