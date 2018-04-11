# `management.azure.com.advisor.suppressions.create`

## `summary`
推奨設定の再または消去された属性を有効にします。 再または消去された属性は、"抑制"と呼ばれます。 この API を使用して作成または、推奨設定の再または却下のステータスを更新します。

## `uriParameters[name="resourceUri"]/description`
推奨設定を適用するリソースの完全修飾の Azure リソース マネージャー識別子です。

## `uriParameters[name="recommendationId"]/description`
推奨設定の id。

## `uriParameters[name="name"]/description`
抑制の名前。

## `uriParameters[name="api-version"]/description`
クライアント要求で使用する API のバージョンです。

## `responses[name="200 OK"]/description`
OK です。 抑制が正常に作成します。

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


