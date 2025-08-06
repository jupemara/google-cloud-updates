# Cloud Run Updates - May & June 2025

## 2025-06

### 2025-06-16
- Cloud Run job で GPU を設定できるようになりました (プレビュー)。
  - [Configure GPU in your Cloud Run job](https://cloud.google.com/run/docs/configuring/jobs/gpu)

### 2025-06-09
- Cloud Run service を呼び出す際のアクセス制御を定義する際に、IAM Condition でリクエストホストとリクエストパスを使用できるようになりました。
  - [Use request host and request path in IAM Conditions](https://cloud.google.com/run/docs/securing/managing-access#conditions)

## 2025-05

### 2025-05-30
- functions-framework バージョン 1.4.0 以降を使用する Java Cloud Run function で、`java.util.logging.Logger` クラスを使用してログ出力に一意の実行 ID を追加できるようになりました。
  - [Unique execution ID to log outputs for Java functions](https://cloud.google.com/run/docs/runtimes/java#execution_id)

### 2025-05-28
- 複数のリージョンで、Cloud Run service URL のレイテンシの影響を受けやすいアプリケーションの応答性が向上しました。
  - [Enhanced responsiveness for Cloud Run service URLs](https://cloud.google.com/run/docs/triggering/https-request#url)

### 2025-05-15
- Google Cloud Console から service または job を作成する際のリージョンセレクタが、デフォルトで `europe-west1` になりました。

### 2025-05-13
- gcloud functions コマンドまたは Cloud Functions v2 API を使用して以前に Cloud Run function に設定したラベルが、Cloud Run に function をデプロイする際に伝播されるようになりました。Cloud Run でのラベル作成の詳細については、[Configure labels for services](https://cloud.google.com/run/docs/configuring/services/labels#set-labels) を参照してください。
  - [Labels propagation from Cloud Functions](https://cloud.google.com/run/docs/deploy-functions)

### 2025-05-06
- Direct VPC egress が Private NAT をサポートしました (プレビュー)。
  - [Direct VPC egress supports Private NAT](https://cloud.google.com/run/docs/configuring/vpc-direct-vpc)
  - [Private NAT](https://cloud.google.com/nat/docs/private-nat)
- 第2世代実行環境を使用するほとんどの service で、Cloud Monitoring のメモリ使用量メトリックがより低いメモリ使用率を示すようになりました。これらのメトリックには、以前はオペレーティングシステムのページキャッシュによって使用されるメモリが含まれていました。
  - [Lower memory utilization in Cloud Monitoring metrics](https://cloud.google.com/monitoring/api/metrics_gcp#gcp-run)

### 2025-05-05
- Python 3.13 ランタイムのサポートが一般提供 (GA) となりました。
  - [Python 3.13 runtime GA](https://cloud.google.com/run/docs/runtime-support#python)
- Ruby 3.4 ランタイムのサポートがプレビューとなりました。
  - [Ruby 3.4 runtime Preview](https://cloud.google.com/run/docs/runtime-support#ruby)
- PHP 8.4 ランタイムのサポートがプレビューとなりました。
  - [PHP 8.4 runtime Preview](https://cloud.google.com/run/docs/runtime-support#php)
