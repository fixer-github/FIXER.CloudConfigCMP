# ARMTemplate - Virtual WAN

## 概要

- Virtual WAN、Virtual WAN ハブをデプロイする

## デプロイ方法

1. 以下の[Deploy to Azure]ボタンを押下
2. 以下の各パラメータを指定
   - `サブスクリプション`：リソースのデプロイ先のサブスクリプションを指定
   - `リソースグループ`：リソースのデプロイ先のリソースグループを指定
   - `リージョン`：リソースのデプロイ先のリージョンを指定
   - `Location`：デプロイする DNS ゾーンのドメイン名を指定
   - `V Wan Name`：デプロイする Virtual WAN のリソース名を指定
   - `V Wan Sku`：デプロイする Virtuwal WAN の SKU(Basic or Standard)を指定
   - `Hub Name`：デプロイする Virtual WAN ハブのリソース名を指定
   - `Hub Address Prefix`：デプロイする Virtual WAN ハブの IP 範囲を指定
3. 内容に問題がなければ、[確認と作成]からデプロイを実行

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Ffixer-github%2FFIXER.CloudConfigCMP%2Fdevelop%2FARMTemplate%2FNetwork%2FVirtualWAN%2FVirtualWAN_template.json)