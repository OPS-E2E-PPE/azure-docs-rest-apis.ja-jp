# `management.azure.com.advisor.recommendations.getgeneratestatus`

## `summary`
推奨設定の計算などの生成プロセスの状態を取得します。 この API を呼び出し、生成推奨設定を呼び出した後。 この API の URI は、応答ヘッダーの [場所] フィールドで返されます。

## `uriParameters[name="subscriptionId"]/description`
Azure サブスクリプション ID です。

## `uriParameters[name="operationId"]/description`
操作 ID、生成する推奨設定の応答ヘッダーに Location フィールドから確認できます。

## `uriParameters[name="api-version"]/description`
クライアント要求で使用する API のバージョンです。

## `responses[name="202 Accepted"]/description`
受け入れられます。 推奨設定の生成が進行中です。

## `responses[name="204 No Content"]/description`
NoContent です。 推奨設定の生成が完了しました。


