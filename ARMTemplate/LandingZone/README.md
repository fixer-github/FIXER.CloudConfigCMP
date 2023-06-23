# ARMTemplate - LandingZone

## 概要

- 以下の Azure ポリシーとリソースグループをデプロイする
  - Azure ポリシー
    - Azure リソースをデプロイするリージョンを制限する Azure ポリシー
    - 指定したテナント ID の Azure テナントにのみ、Azure Lighthouse の権限委任を許可する Azure ポリシー
  - リソースグループ
    - グローバルリージョンのリソースを配置するリソースグループ
    - プライマリリージョンのリソースを配置するリソースグループ
    - セカンダリリージョンのリソースを配置するリソースグループ

## デプロイ方法

1. 以下の[Deploy to Azure]ボタンを押下
2. 以下の各パラメータを指定
   - `サブスクリプション`：リソースのデプロイ先のサブスクリプションを指定
   - `リソースグループ`：リソースのデプロイ先のリソースグループを指定
   - `リージョン`：リソースのデプロイ先のリージョンを指定
   - `Environment`：環境名(本番：`pr`、ステージング：`st`、開発：`dv` 、検証：`ve` )
   - `Project Prefix`：プロジェクト名
   - `Primary Location Name`：プライマリリージョンの名前（東日本：japaneast、西日本：japanwest）
   - `Secondary Location Name`：セカンダリリージョンの名前（東日本：japaneast、西日本：japanwest）
   - `Primary Location Code`：プライマリリージョンの略称（東日本：je、西日本：jw）
   - `Secondary Location Code`：セカンダリリージョンの略称（東日本：je、西日本：jw）
   - `List Of Allowed Locations Parameter`：リソースのデプロイ先として許可する Azure リージョン
   - `List Of Allowed Tenants Parameter`：Lighthouse の権限委任を許可する Azure テナントのテナント ID
3. 内容に問題がなければ、[確認と作成]からデプロイを実行

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Ffixer-github%2FFIXER.CloudConfigCMP%2Fdevelop%2FARMTemplate%2FLandingZone%2FLandingZone_template.json)