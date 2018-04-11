# `management.azure.com.advisor.recommendations.get`

## `summary`
キャッシュされた推奨事項の詳細を取得します。

## `uriParameters[name="resourceUri"]/description`
推奨設定を適用するリソースの完全修飾の Azure リソース マネージャー識別子です。

## `uriParameters[name="recommendationId"]/description`
推奨設定の id。

## `uriParameters[name="api-version"]/description`
クライアント要求で使用する API のバージョンです。

## `responses[name="200 OK"]/description`
OK です。 推奨設定の詳細が正常に取得しました。

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


