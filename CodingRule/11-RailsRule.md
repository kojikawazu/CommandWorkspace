# コーディング規約(Rails)

Ruby on Railsのコーディング規約に関するベストプラクティスを日本語でまとめます。

## 1. スペースインデント

- Ruby on Railsでは、インデントにはスペース2つを使用します。これはRailsコミュニティで広く受け入れられている慣習で、コードの読みやすさと一貫性を保つための基本です​ (RubyStyle Guide)​。

## 2. ファットモデル、スキニーコントローラー

- ビジネスロジックはモデルに記述し（ファットモデル）、コントローラーはユーザーの入力を扱い、レスポンスを返すことに集中させます（スキニーコントローラー）。これにより、メンテナンス性が向上し、Railsの「設定より規約」の原則に沿った開発が可能になります​ (SitePoint)​。

## 3. DRY（Don't Repeat Yourself）

- コードの重複を避けるために、共通の機能をメソッド、モジュール、またはクラスに抽出します。これにより、コードベースを整理し、アプリケーションのスケールに伴う修正や更新が容易になります​ (SitePoint)​。

## 4. サービスオブジェクトの利用

- モデルやコントローラーに適さないビジネスロジックは、サービスオブジェクトを使ってカプセル化します。これにより、MVCコンポーネントがそれぞれの責任に集中できるようになります​ (SitePoint)​。

## 5. RESTfulリソース

- ルーティングにおいてRESTfulな原則に従うことで、アプリケーションが整理され予測しやすい構造を保つことができます。これにはリソースベースのルートを使用し、クリーンでリソース指向のコントローラーを維持することが含まれます​ (SitePoint)​。

## 6. テストの重視

- 開発の初期段階からテストの作成に注力します。Railsはテスト駆動開発（TDD）に適しており、モデル、コントローラー、統合のための堅牢なテストスイートを維持することで、アプリケーションが進化しても安定性とバグのない状態を保つことができます​ (SitePoint)​。

## 7. 質問マークを使った述語メソッドの定義

- 述語メソッド（真偽値を返すメソッド）の名前には疑問符を使用します。これによりメソッドの目的が明確になり、コードがより直感的に読めるようになります。例えば、invoice.paid? のように使用します​ (RubyStyle Guide)​。

これらのベストプラクティスを適用することで、Ruby on Railsアプリケーションの品質、メンテナンス性、拡張性が向上します。