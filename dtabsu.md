# データベース

データベースでは、ユーザーがアプリの使用時に作成するデータを管理します。ここでは、アプリのデータベース内のデータを構成、および表示することができます。

### プライベート

Privacy rulesタブに遷移することができます。

### 新しいテーブルを作成する

テーブルの名前を入力することであたらしいテーブルを作成することができます。

### 編集

ペンのアイコンから、テーブル名を変更することができます。

### 削除

ゴミ箱のアイコンからテーブルを削除することができます。

## テーブル

アプリのデータベース内のデータが一覧表示されます。データをデータ型別に表示します。データベース内の特定のフィールドを作成、編集、削除することができます。

## カスタムタイプ

これらのフィールドは、テーブルを作成した際に自動で定義されます。これらはユーザーのテーブルにも適用されています。

### id

フィールドの一意のIDです。データ型は、を検索するです。

### created\_at

フィールドが作成された日付を格納します。データ型は、dateです。

### updated\_at

フィールドが最後に編集された日付を格納します。データ型は、dateです。

## カスタムフィールド

テーブルの新しいフィールドを定義します。

### フィールド

フィールドにはデータ型が必要です。ナンバー、テキスト、はい / いいえ、日付、ファイルなどがあります。リレーションを作成するためにすでに存在しているテーブルの名前を選択することもできます。

### フィールドを追加

フィールド名、データ型、ユニークな値、デフォルト値を設定し、新たなフィールドを作成することができます。

### ユニークな値

ユニークな値を選択すると、フィールドの一意のIDを表示します。

## ユーザー

ユーザーテーブルでは、カスタムフィールドに加え初期設定として以下の特定のフィールドが表示されています。

### email

登録しているユーザーのEmailを格納します。データ型は、stringです。

### phone

登録しているユーザーの電話番号を格納します。データ型は、stringです。

### role

利用者のグループあるいは雛形です。利用者の種類（管理者、開発者、一般利用者など）に応じて作られ、各利用者それぞれにrole の値がつけられます。データ型は、stringです。

### is\_super\_admin

ユーザーがアプリ管理者であるかどうかを「はい / いいえ」のどちらかを格納します。データ型はbooleanです。

### email\_confirmed

ユーザー登録の際に使用する確認用のEmailの使用を「はい / いいえ」のどちらかで格納します。データ型はbooleanです。

### phone\_confirmed

ユーザー登録の際に使用する確認用の電話番号の使用を「はい / いいえ」のどちらかで格納します。データ型はbooleanです。

## アプリデータ

アプリのデータベース内のデータが表示されています。データをデータ型別に表示し、特定のフィールドを列に表示します。データベース内の特定のフィールドを作成、変更、削除したり、一括でアップロードすることもできます、

### 検索

フィールドを検索することができます。

### フィルター

一覧で表示させたいデータを絞り込むことができます。

### 新しく入力

新しいフィールドを作成することができます。

### インポート

データベースの情報をインポートします。

### バルク

データの一括管理を行います。

## Privacy rules

プライバシーでは、ユーザーがさまざまな種類のデータの表示に関するルールを決めることができます。























###
