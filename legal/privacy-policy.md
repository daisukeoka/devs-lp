# プライバシーポリシー

最終更新日: 2026年2月28日

DeVS（以下「本アプリ」）をご利用いただきありがとうございます。本プライバシーポリシーは、本アプリにおける情報の取り扱いについて説明するものです。

## 1. 収集する情報

### 1.1 ユーザーが入力する情報
- ディスカッションのテーマ（トピック）
- カスタムエージェントの設定情報（名前、専門分野、ペルソナ）

これらの情報は**端末内（ローカルストレージ）にのみ保存**されます。当社のサーバーにユーザーデータを保存することはありません。

### 1.2 AI応答の生成に使用する情報
ディスカッション機能を利用する際、入力されたテーマとエージェント設定は、AI応答を生成するために Anthropic 社の Claude API に送信されます。この通信は当社の Supabase Edge Function を経由して行われます。

- 送信される情報: ディスカッションのテーマ、エージェントのペルソナ設定、会話履歴
- 送信先: Anthropic 社 Claude API（Supabase Edge Function 経由）
- Anthropic 社のプライバシーポリシー: https://www.anthropic.com/privacy

### 1.3 広告に関する情報
本アプリは Google AdMob を使用して広告を表示します。AdMob は広告配信のために以下の情報を収集する場合があります。

- 広告識別子（IDFA / GAID）
- デバイス情報（機種、OS バージョン等）
- おおよその位置情報

本アプリでは**非パーソナライズ広告のみ**を配信しています。

- Google のプライバシーポリシー: https://policies.google.com/privacy
- Google の広告に関するポリシー: https://policies.google.com/technologies/ads

## 2. 情報の保存場所

| 情報 | 保存場所 |
|------|----------|
| ディスカッション履歴 | 端末内のみ（AsyncStorage） |
| アプリ設定 | 端末内のみ（AsyncStorage） |
| カスタムエージェント | 端末内のみ（AsyncStorage） |
| 利用回数 | 端末内のみ（AsyncStorage） |

当社は独自のサーバーにユーザーの個人データを保存しません。

## 3. 第三者サービス

本アプリは以下の第三者サービスを利用しています。各サービスの利用規約・プライバシーポリシーもあわせてご確認ください。

| サービス | 用途 | プライバシーポリシー |
|----------|------|----------------------|
| Anthropic Claude API | AI応答の生成 | https://www.anthropic.com/privacy |
| Google AdMob | 広告の表示 | https://policies.google.com/privacy |
| Supabase | API通信の中継 | https://supabase.com/privacy |

## 4. 子どものプライバシー

本アプリは13歳未満のお子様を対象としておらず、13歳未満のお子様から意図的に個人情報を収集することはありません。

## 5. データの削除

アプリ内のデータはすべて端末内に保存されています。アプリをアンインストールすることで、すべてのデータが削除されます。

## 6. 地域別の権利

### 6.1 欧州経済領域（EEA）のユーザー — GDPR
EU一般データ保護規則（GDPR）に基づき、EEA にお住まいのユーザーには以下の権利があります。

- **アクセス権**: ご自身のデータへのアクセスを求める権利
- **訂正権**: 不正確なデータの訂正を求める権利
- **削除権**: データの削除を求める権利
- **処理の制限権**: データ処理の制限を求める権利
- **データポータビリティ権**: データを移転可能な形式で受け取る権利
- **異議申立権**: データ処理に異議を申し立てる権利

本アプリのデータは端末内にのみ保存されるため、上記の権利はアプリのアンインストールにより行使できます。広告に関するデータについては、端末の設定から広告識別子をリセットすることで対応可能です。

処理の法的根拠: 本アプリのデータ処理は、サービス提供に必要な処理（GDPR第6条1項(b)）および正当な利益（GDPR第6条1項(f)）に基づきます。

### 6.2 カリフォルニア州のユーザー — CCPA
カリフォルニア州消費者プライバシー法（CCPA）に基づき、カリフォルニア州にお住まいのユーザーには以下の権利があります。

- 収集される個人情報のカテゴリを知る権利
- 個人情報の削除を求める権利
- 個人情報の販売をオプトアウトする権利

当社はユーザーの個人情報を第三者に販売しません。権利の行使に関するお問い合わせは、下記の連絡先までご連絡ください。

## 7. プライバシーポリシーの変更

本プライバシーポリシーは、必要に応じて更新されることがあります。変更があった場合は、本ページの最終更新日を更新します。

## 8. お問い合わせ

プライバシーに関するご質問やご要望（データの削除・アクセス要求を含む）がございましたら、以下までご連絡ください。

メール: devate.vs.app@gmail.com

---

# Privacy Policy

Last Updated: February 28, 2026

Thank you for using DeVS (the "App"). This Privacy Policy explains how information is handled in the App.

## 1. Information We Collect

### 1.1 Information You Provide
- Discussion topics
- Custom agent settings (name, specialty, persona)

This information is stored **only on your device (local storage)**. We do not store user data on our servers.

### 1.2 Information Used for AI Responses
When using the discussion feature, the topic and agent settings are sent to Anthropic's Claude API to generate AI responses. This communication is routed through our Supabase Edge Function.

- Information sent: Discussion topic, agent persona settings, conversation history
- Destination: Anthropic Claude API (via Supabase Edge Function)
- Anthropic's Privacy Policy: https://www.anthropic.com/privacy

### 1.3 Advertising Information
The App uses Google AdMob to display advertisements. AdMob may collect the following information for ad delivery:

- Advertising identifiers (IDFA / GAID)
- Device information (model, OS version, etc.)
- Approximate location

The App serves **non-personalized ads only**.

- Google Privacy Policy: https://policies.google.com/privacy
- Google Ads Policy: https://policies.google.com/technologies/ads

## 2. Where Information Is Stored

| Information | Storage Location |
|-------------|-----------------|
| Discussion history | Device only (AsyncStorage) |
| App settings | Device only (AsyncStorage) |
| Custom agents | Device only (AsyncStorage) |
| Usage counts | Device only (AsyncStorage) |

We do not store personal user data on our own servers.

## 3. Third-Party Services

The App uses the following third-party services. Please review their respective privacy policies.

| Service | Purpose | Privacy Policy |
|---------|---------|---------------|
| Anthropic Claude API | AI response generation | https://www.anthropic.com/privacy |
| Google AdMob | Ad delivery | https://policies.google.com/privacy |
| Supabase | API communication relay | https://supabase.com/privacy |

## 4. Children's Privacy

The App is not intended for children under 13 years of age, and we do not knowingly collect personal information from children under 13.

## 5. Data Deletion

All app data is stored on your device. Uninstalling the App will delete all data.

## 6. Regional Rights

### 6.1 Users in the European Economic Area (EEA) — GDPR
Under the General Data Protection Regulation (GDPR), users residing in the EEA have the following rights:

- **Right of access**: Request access to your data
- **Right to rectification**: Request correction of inaccurate data
- **Right to erasure**: Request deletion of your data
- **Right to restriction**: Request restriction of data processing
- **Right to data portability**: Receive your data in a transferable format
- **Right to object**: Object to data processing

Since the App stores data only on your device, these rights can be exercised by uninstalling the App. For advertising-related data, you can reset your advertising identifier in your device settings.

Legal basis for processing: Data processing in the App is based on the necessity for service provision (GDPR Article 6(1)(b)) and legitimate interests (GDPR Article 6(1)(f)).

### 6.2 California Users — CCPA
Under the California Consumer Privacy Act (CCPA), California residents have the following rights:

- The right to know what categories of personal information are collected
- The right to request deletion of personal information
- The right to opt out of the sale of personal information

We do not sell users' personal information to third parties. For inquiries regarding the exercise of these rights, please contact us using the information below.

## 7. Changes to This Policy

This Privacy Policy may be updated as needed. Any changes will be reflected by updating the "Last Updated" date on this page.

## 8. Contact Us

If you have any questions or concerns about privacy (including data deletion or access requests), please contact us at:

Email: devate.vs.app@gmail.com
