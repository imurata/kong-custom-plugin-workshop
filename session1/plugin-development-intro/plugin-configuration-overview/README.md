## 検証の内容

1. Kong plugin templateを更新し、Upstreamに送信する前にAPIリクエストからリクエストヘッダを削除するプラグインの設定フィールドを追加する。
2. プラグインの設定には、削除するヘッダのリストを指定する。
3. 追加した設定フィールドを使用するようにプラグインのコードを更新し、プラグインの動作を検証する。