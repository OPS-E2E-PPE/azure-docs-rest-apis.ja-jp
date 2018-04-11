# `management.azure.com.advisor.operations.list`

## `summary`
使用可能なすべてのアドバイザー REST API 操作を一覧表示します。

## `uriParameters[name="api-version"]/description`
クライアント要求で使用する API のバージョンです。

## `responses[name="200 OK"]/description`
OK です。 正常に取得された操作の一覧です。

## `definitions[name="OperationEntityListResult"]/description`
アドバイザーの操作の一覧。

## `definitions[name="OperationEntityListResult"]/properties[name="nextLink"]/description`
  
操作の次のページを取得するために使用されるリンク。

## `definitions[name="OperationEntityListResult"]/properties[name="value"]/description`
  
Advisor でサポートされる操作です。

## `definitions[name="OperationEntity"]/description`
操作の一覧。

## `definitions[name="OperationEntity"]/properties[name="name"]/description`
  
操作名: {プロバイダー}/{リソース}/{操作}。

## `definitions[name="OperationEntity"]/properties[name="display"]/description`
  
Advisor でサポートされる操作です。

## `definitions[name="OperationDisplayInfo"]/description`
Advisor でサポートされる操作です。

## `definitions[name="OperationDisplayInfo"]/properties[name="description"]/description`
  
操作の説明。

## `definitions[name="OperationDisplayInfo"]/properties[name="operation"]/description`
  
ユーザーが実行できるアクションは、それぞれの権限レベルに基づいています。

## `definitions[name="OperationDisplayInfo"]/properties[name="provider"]/description`
  
サービス プロバイダー: Microsoft アドバイザー。

## `definitions[name="OperationDisplayInfo"]/properties[name="resource"]/description`
  
操作を実行するリソースです。


