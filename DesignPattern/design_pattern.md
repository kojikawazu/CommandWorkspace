# デザインパターン

## 1. 作成(Creational)パターン

これらのパターンはオブジェクトのインスタンス化に関連しており、オブジェクトの作成方法を柔軟にするためのものです。

- Singleton（シングルトン）: クラスに対してインスタンスが一つだけ存在することを保証するパターン。
- Factory Method（ファクトリーメソッド）: インスタンスの作成をサブクラスに任せるパターン。
- Abstract Factory（抽象ファクトリ）: 関連する一連のインスタンスを作成するためのインタフェースを提供するパターン。
- Builder（ビルダー）: 複雑なオブジェクトの構築とその表現を分離するパターン。
- Prototype（プロトタイプ）: 既存のオブジェクトをコピーして新しいオブジェクトを作成するパターン。

## 2. 構造(Structural)パターン

これらのパターンは、クラスやオブジェクトを組み合わせてより大きな構造を形成する方法に焦点を当てています。

- Adapter（アダプタ）: インターフェースの不一致を解消するためにクラスのインターフェースを変更するパターン。
- Composite（コンポジット）: オブジェクトを木構造で表し、個々のオブジェクトと組み合わせたオブジェクトを同一視できるようにするパターン。
- Proxy（プロキシ）: アクセス制御やコストの高いオペレーションの遅延実行など、他のオブジェクトへのアクセスを制御するオブジェクトを提供するパターン。
- Flyweight（フライウェイト）: 多数存在する細かいインスタンスを効率的に共有するためのパターン。
- Facade（ファサード）: 複雑なサブシステムに対する統一されたインターフェースを提供するパターン。
- Bridge（ブリッジ）: 抽象化と実装を分離し、それぞれを独立して変更できるようにするパターン。
- Decorator（デコレータ）: オブジェクトに動的に新しい責任を追加するパターン。

## 3. 振る舞い(Behavioral)パターン

これらのパターンはオブジェクト間の通信の効率を高め、責任の分散を助けます。

- Observer（オブザーバー）: オブジェクト間の依存関係を最小限にしながら、一つのオブジェクトの状態変化を他の依存オブジェクトに通知するパターン。
- Strategy（ストラテジー）: 実行時にアルゴリズムを選択するパターン。
- Command（コマンド）: 要求をオブジェクトの形でカプセル化し、パラメータを用いてメソッドを実行するパターン。
- State（ステート）: オブジェクトの状態変化に応じてオブジェクトの振る舞いを変更するパターン。
- Visitor（ビジター）: 操作をオブジェクト構造の要素に加えるパターン。要素のクラスを変更せずに新しい操作を簡単に追加できる。
- Mediator（メディエータ）: オブジェクト間の直接的な通信を避け、代わりに通信を仲介するオブジェクトを介して行うパターン。
- Iterator（イテレータ）: コレクションの要素に順にアクセスする方法を提供するパターン。
- Memento（メメント）: オブジェクトの状態を保存して後で取り出せるようにするパターン。
- Template Method（テンプレートメソッド）: アルゴリズムの構造をメソッドに定義し、一部をサブクラスでオーバーライドするパターン。
Chain of Responsibility（チェーンオブレスポンシビリティ）: 複数のオブジェクトに処理の機会を提供するパターン。