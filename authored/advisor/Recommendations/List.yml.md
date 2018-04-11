# `management.azure.com.advisor.recommendations.list`

## `summary`
サブスクリプションのキャッシュされた推奨事項を取得します。 推奨事項が生成されるか、generateRecommendations を呼び出すことによって計算します。

## `uriParameters[name="subscriptionId"]/description`
Azure サブスクリプション ID です。

## `uriParameters[name="api-version"]/description`
クライアント要求で使用する API のバージョンです。

## `uriParameters[name="$filter"]/description`
推奨事項を適用するフィルター。

## `uriParameters[name="$top"]/description`
この API のページングされたバージョンが使用されている場合は、ページあたりの推奨事項の数。

## `uriParameters[name="$skipToken"]/description`
この API のページングのバージョンで使用するページ継続トークンです。

## `responses[name="200 OK"]/description`
OK です。 キャッシュされた推奨事項が正常に取得されます。

## `definitions[name="ResourceRecommendationBaseListResult"]/description`
アドバイザーの推奨設定の一覧。

## `definitions[name="ResourceRecommendationBaseListResult"]/properties[name="nextLink"]/description`
  
推奨設定の次のページを取得するために使用されるリンク。

## `definitions[name="ResourceRecommendationBaseListResult"]/properties[name="value"]/description`
  
アドバイザーの推奨設定です。

## `definitions[name="ResourceRecommendationBase"]/description`
推奨事項の一覧。

## `definitions[name="ResourceRecommendationBase"]/properties[name="properties.category"]/description`
  
推奨設定のカテゴリ。

## `definitions[name="ResourceRecommendationBase"]/properties[name="properties.impact"]/description`
  
推奨設定のビジネスへの影響。

## `definitions[name="ResourceRecommendationBase"]/properties[name="properties.impactedField"]/description`
  
Advisor によって識別されるリソースの種類。

## `definitions[name="ResourceRecommendationBase"]/properties[name="properties.impactedValue"]/description`
  
Advisor によって識別されるリソースです。

## `definitions[name="ResourceRecommendationBase"]/properties[name="properties.lastUpdated"]/description`
  
Advisor に推奨設定の有効性がチェックされている最新の時間。

## `definitions[name="ResourceRecommendationBase"]/properties[name="properties.metadata"]/description`
  
推奨設定のメタデータ。

## `definitions[name="ResourceRecommendationBase"]/properties[name="properties.recommendationTypeId"]/description`
  
推奨設定の種類の GUID。

## `definitions[name="ResourceRecommendationBase"]/properties[name="properties.risk"]/description`
  
推奨設定を実装しなかった場合の潜在的なリスクです。

## `definitions[name="ResourceRecommendationBase"]/properties[name="properties.shortDescription"]/description`
  
推奨設定の概要です。

## `definitions[name="ResourceRecommendationBase"]/properties[name="properties.suppressionIds"]/description`


## `definitions[name="ResourceRecommendationBase"]/properties[name="id"]/description`
  
リソース id です。

## `definitions[name="ResourceRecommendationBase"]/properties[name="name"]/description`
  
リソースの名前。

## `definitions[name="ResourceRecommendationBase"]/properties[name="type"]/description`
  
リソースの種類。

## `definitions[name="category"]/description`
推奨設定のカテゴリ。

## `definitions[name="impact"]/description`
推奨設定のビジネスへの影響。

## `definitions[name="risk"]/description`
推奨設定を実装しなかった場合の潜在的なリスクです。

## `definitions[name="ShortDescription"]/description`
推奨設定の概要です。

## `definitions[name="ShortDescription"]/properties[name="problem"]/description`
  
懸案事項または営業案件の推奨設定で識別されます。

## `definitions[name="ShortDescription"]/properties[name="solution"]/description`
  
推奨設定で推奨修復アクション。


