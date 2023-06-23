# ARMTemplate - DNS

- 参考：https://learn.microsoft.com/ja-JP/azure/dns/dns-overview
- 
## 概要

- Azure DNS、A レコードをデプロイする

## デプロイ方法

1. 以下の[Deploy to Azure]ボタンを押下
2. 以下の各パラメータを指定
   - `サブスクリプション`：リソースのデプロイ先のサブスクリプションを指定
   - `リソースグループ`：リソースのデプロイ先のリソースグループを指定
   - `リージョン`：リソースのデプロイ先のリージョンを指定
   - `Zone Name`：デプロイする DNS ゾーンのドメイン名を指定
   - `Record Name`：デプロイする A レコードのレコード名を指定
3. 内容に問題がなければ、[確認と作成]からデプロイを実行

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Ffixer-github%2FFIXER.CloudConfigCMP%2Fdevelop%2FARMTemplate%2FBasicTemplate%2FNetwork%2FDNS%2FAzureDNS_template.json)