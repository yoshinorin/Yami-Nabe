#### 全テーブルにFGAを張るサンプル

##### このサンプルを作った背景
--------------------
* どのテーブルがどのようなSQLで更新されたか横着して確認したい。

##### ちなみに
--------------------
* 全テーブルに張るだけなら、[標準監査]で対応できる。(今回のようにFGAはつかわなくても使わなくてもよい・・・・)
* 本番環境での使用厳禁 !!
* 今回のサンプルの場合、監査ポリシーはテーブル名で作成される。

##### 実際のサンプル
--------------------
* [テーブル名で全テーブルの監査ポリシーを作成する](CreatePolicy.md)
* [監査結果の確認](Confirmation.md)
* [監査の有効化と無効化](PolicyEnableDisEnable.md)
* [監査の削除](DropPolicy.md)
* [監査ログの削除](TrancateAuditTable.md)