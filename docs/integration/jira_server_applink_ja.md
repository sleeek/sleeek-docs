---
id: jira-server-applink-ja
title: Jira Software Serverでの事前設定
sidebar_label: Linking with Jira Software Server (ja)
---

SleeekはJIRA Software Serverから情報を取得するために、REST APIを利用します。
[このREST APIの利用には、OAuth 1.0aプロトコルを利用した、ユーザによるAPI使用の認可が必要です。](https://developer.atlassian.com/server/jira/platform/oauth/)
この認可処理を開始するためには、JIRA Software Server側での事前設定が必要です。
SleeekでJIRA Serverへの連携を設定する際に、「JIRA Server側での登録が必要です」とエラーメッセージが表示された場合は、本手順書に従って、登録処理を進めましょう。

なお、本作業はJIRA Software Serverごとに１回だけ必要です。あるJIRA Software ServerとSleeekの間に複数の連携を設定する場合でも、複数回設定する必要はありません。
例えば、`https://jira.example.com/`で運用されているJIRA Software Serverがあり、Taro, Jiro, SaburoがSleeekに接続する場合、
本手順書に記載された作業を１回実施すれば、全員がSleeek側から認可処理を開始することができます。（つまり、３回実施する必要はありません。）

本作業にはJIRA Software Serverにおける管理者権限が必要です。もし作業者に管理者権限を持っていない場合、管理者権限を持つユーザへ設定を依頼してください。


## 手順

1. JIRAにログインし、右上の設定メニューから「JIRA管理」-「アプリケーション」をクリックします
（本メニューに設定画面のへの遷移が存在しない場合、作業者の権限が不足しています。
JIRAの管理者に問い合わせて権限の付与を依頼するか、管理者に設定を依頼する必要があります）

![Step 1](../../img/docs/integration/jira-server-applink-ja/step1.png)


2. 管理者画面が表示されたら、「統合」-「アプロケーションリンク」をクリックします。

![Step 2](../../img/docs/integration/jira-server-applink-ja/step2.png)


3. 「アプリケーションリンクの設定」が表示されたら、テキストボックスに`https://app.sleeek.io`と入力して
「新しいリンクを作成」をクリックします。

![Step 3](../../img/docs/integration/jira-server-applink-ja/step3.png)


4. エラー画面が表示されますが、本手順書のでの操作には無関係です。そのまま「続行」をクリックしてください

![Step 4](../../img/docs/integration/jira-server-applink-ja/step4.png)


5. 表示されるダイアログに以下の内容を設定して、「続行」をクリックします。

* 「アプリケーション名」には任意の名前を入力する
* 「アプリケーションタイプ」は「汎用アプリケーション」を選択する
* 「被リンクを作成」のチェックボックスをチェック状態にする

![Step 5](../../img/docs/integration/jira-server-applink-ja/step5.png)


6. 以下の内容を設定して、「続行」ボタンをクリックします。
* 「コンシューマーキー」には`SleeekJiraLink`を入力する
* 「コンシューマー名」に`Sleeek`を入力する
* 「公開キー」には以下の文字列を入力する
```text
-----BEGIN PUBLIC KEY-----
MIGfMA0GCSqGSIb3DQEBAQUAA4GNADCBiQKBgQCbqUf0AjETHMyskzpc3fq/i3VR
kEzfc9rh/FHoiyDAhNArQUW+a/07tB0M7F0X90BI6XvVkixaPDoEquAw6VMlhteH
J0DBuDjNC+mIaGjXw6woUta+wS2dV6BNx3DPH29BkdKSNkXmvkYoj+fwy3+dviQC
lghtzKE3/zcuxsVc7QIDAQAB
-----END PUBLIC KEY-----
```

![Step 6](../../img/docs/integration/jira-server-applink-ja/step6.png)


7. アプリケーションリンクの一覧に登録した設定項目が表示されれば完了です。

![Step 6](../../img/docs/integration/jira-server-applink-ja/step7.png)
