# `management.azure.com.advisor.recommendations`

## `operations[uid="management.azure.com.advisor.recommendations.generate"]/summary`
サブスクリプションの推奨設定の生成または計算プロセスを開始します。 この操作は非同期です。 生成された推奨事項は、Advisor サービス内のキャッシュに格納されます。

## `operations[uid="management.azure.com.advisor.recommendations.get"]/summary`
キャッシュされた推奨事項の詳細を取得します。

## `operations[uid="management.azure.com.advisor.recommendations.getgeneratestatus"]/summary`
推奨設定の計算などの生成プロセスの状態を取得します。 この API を呼び出し、生成推奨設定を呼び出した後。 この API の URI は、応答ヘッダーの [場所] フィールドで返されます。

## `operations[uid="management.azure.com.advisor.recommendations.list"]/summary`
サブスクリプションのキャッシュされた推奨事項を取得します。 推奨事項が生成されるか、generateRecommendations を呼び出すことによって計算します。


