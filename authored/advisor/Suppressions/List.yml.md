# `management.azure.com.advisor.suppressions.list`

## `summary`
サブスクリプションの再または消去された抑制の一覧を取得します。 推奨設定の再または消去された属性は、"抑制"と呼ばれます。

## `uriParameters[name="subscriptionId"]/description`
Azure サブスクリプション ID です。

## `uriParameters[name="api-version"]/description`
クライアント要求で使用する API のバージョンです。

## `responses[name="200 OK"]/description`
OK です。 サブスクリプションのすべての抑制を正常に取得しました。

## `definitions[name="SuppressionContract"]/description`
ルールの詳細、再または消去されました。たとえば、期間、名、およびルールに関連付けられている GUID。

## `definitions[name="SuppressionContract"]/properties[name="properties.suppressionId"]/description`
  
抑制の GUID です。

## `definitions[name="SuppressionContract"]/properties[name="properties.ttl"]/description`
  
抑制が有効な期間です。

## `definitions[name="SuppressionContract"]/properties[name="id"]/description`
  
リソース id です。

## `definitions[name="SuppressionContract"]/properties[name="name"]/description`
  
リソースの名前。

## `definitions[name="SuppressionContract"]/properties[name="type"]/description`
  
リソースの種類。


