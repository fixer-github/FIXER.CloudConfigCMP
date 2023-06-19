# ARMTemplate - Bastion

- 参考：https://learn.microsoft.com/ja-jp/azure/bastion/bastion-overview
## 概要

- Azure Bastion Host、仮想ネットワーク、サブネット、パブリック IP、ネットワークセキュリティグループをデプロイする

## デプロイ方法

1. 以下の[Deploy to Azure]ボタンを押下
2. 以下の各パラメータを指定
   - `サブスクリプション`：リソースのデプロイ先のサブスクリプションを指定
   - `リソースグループ`：リソースのデプロイ先のリソースグループを指定
   - `リージョン`：リソースのデプロイ先のリージョンを指定
   - `Vnet Name`：デプロイする仮想ネットワークのリソース名を指定
   - `Vnet Ip Prefix`：デプロイする仮想ネットワークの IP 範囲を指定
   - `Vnet New or Existing`：仮想ネットワークを新規デプロイするか、既存のものを利用するか指定
   - `Bastion Subnet Ip Prefix`：Bastion をデプロイするサブネットの IP 範囲を指定
   - `Bastion Host Name`：Bastion のリソース名を指定
   - `Location`：リソースのデプロイ先のリージョンを指定
3. 内容に問題がなければ、[確認と作成]からデプロイを実行

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Ffixer-github%2FFIXER.CloudConfigCMP%2Fdevelop%2FARMTemplate%2FNetwork%2FBastion%2FBastion_template.json)