# SOZO App - Privacy Policy & Terms of Service

## 📚 概要

このリポジトリは、SOZO App（美容業界向け英語学習アプリ）のプライバシーポリシーと利用規約を管理しています。

**公開URL**: https://hey-show123.github.io/sozo-app-policies/

---

## 📋 ドキュメント一覧

### 必須ドキュメント
- [プライバシーポリシー](https://hey-show123.github.io/sozo-app-policies/privacy_policy.html)
- [利用規約](https://hey-show123.github.io/sozo-app-policies/terms_of_service.html)

### 審査用ガイド
- [App Store データプライバシー設定ガイド](./APP_STORE_DATA_PRIVACY.md)
- [Google Play データセーフティ設定ガイド](./GOOGLE_PLAY_DATA_SAFETY.md)
- [App Store 提出ガイド](./APP_STORE_SUBMISSION_GUIDE.md)
- [Google Play 提出ガイド](./GOOGLE_PLAY_SUBMISSION_GUIDE.md)
- [事前提出チェックリスト](./PRE_SUBMISSION_CHECKLIST.md)

### 記入用チェックリスト
- [プライバシーポリシー記入チェックリスト](./PRIVACY_POLICY_CHECKLIST.md)

---

## ⚠️ 重要：審査前に必要な情報の記入

プライバシーポリシーには以下のプレースホルダーがあり、**必ず実際の情報に置き換える必要があります**：

### 1. 運営者情報
```html
[会社名または個人名] → 実際の運営者名
[住所] → 実際の住所
[代表者名] → 代表者の名前
[法人番号]（法人の場合） → 法人番号
```

### 2. 連絡先
```html
[サポートメールアドレス] → support@example.com
[プライバシー担当メールアドレス] → privacy@example.com
```

### 3. その他
```html
[使用リージョン] → Azure Speech Servicesのリージョン（例：Japan East）
```

---

## 🚀 更新手順

### 1. ローカルで編集
```bash
# リポジトリをクローン
git clone https://github.com/hey-show123/sozo-app-policies.git
cd sozo-app-policies

# プライバシーポリシーを編集
nano privacy_policy.html

# プレースホルダーを実際の情報に置換
# [会社名または個人名] → あなたの情報
# [住所] → あなたの住所
# [サポートメールアドレス] → support@example.com
```

### 2. 変更をコミット
```bash
git add .
git commit -m "Update privacy policy with actual information"
git push
```

### 3. GitHub Pagesで確認
```bash
# 数分待ってからアクセス
open https://hey-show123.github.io/sozo-app-policies/privacy_policy.html
```

---

## 📱 アプリ内での実装

### Flutter アプリでの URL 設定

**ファイル**: `/lib/presentation/screens/profile/profile_screen.dart`

```dart
// プライバシーポリシー
onTap: () => _launchUrl('https://hey-show123.github.io/sozo-app-policies/privacy_policy.html'),

// 利用規約
onTap: () => _launchUrl('https://hey-show123.github.io/sozo-app-policies/terms_of_service.html'),
```

---

## 📊 データ収集の概要

### 収集するデータ
- **アカウント情報**: メールアドレス、表示名、プロフィール画像
- **学習データ**: レッスン進捗、スコア、学習時間
- **音声データ**: 発音練習の一時録音（24時間で自動削除）
- **AI会話**: レッスン中の会話履歴

### 使用するサードパーティサービス
| サービス | 用途 | データ |
|---------|------|--------|
| Supabase | データベース、認証 | すべてのユーザーデータ |
| OpenAI | AI会話、音声合成・認識 | 会話内容、音声 |
| Azure Speech | 発音評価 | 音声録音 |
| Firebase | アプリ配信（Core機能のみ） | 基本的な使用状況 |

---

## ✅ 審査提出チェックリスト

### App Store
- [ ] プライバシーポリシーのプレースホルダーをすべて置換
- [ ] App Store Connectでデータプライバシーを設定
- [ ] プライバシーポリシーURLが有効
- [ ] 年齢制限（13+）を設定
- [ ] スクリーンショットを準備

### Google Play
- [ ] データセーフティセクションを記入
- [ ] プライバシーポリシーとの整合性を確認
- [ ] コンテンツレーティングを設定
- [ ] ストア掲載情報を完成
- [ ] APK/AABファイルをアップロード

---

## 📝 よくある質問

### Q: バーチャルオフィスの住所でも大丈夫？
A: はい、問題ありません。実在する住所であれば受理されます。

### Q: 個人開発者の場合、会社名はどうする？
A: 「個人事業主」として個人名を記載するか、屋号がある場合は屋号を使用できます。

### Q: メールアドレスはGmailでも大丈夫？
A: はい。ただし、専用のアドレス（support@、privacy@）を作成することを推奨します。

### Q: データ保護責任者（DPO）は必要？
A: 小規模アプリでは通常不要です。EU市民を対象とする大規模サービスの場合に検討してください。

---

## 🔄 更新履歴

| 日付 | 内容 |
|------|------|
| 2025-01-11 | 完全版プライバシーポリシー作成 |
| 2025-01-11 | App Store/Google Play審査ガイド追加 |
| 2025-01-11 | 実装に基づいた正確な内容に更新 |

---

## 📧 サポート

審査で問題が発生した場合や質問がある場合は、以下にお問い合わせください：

- **技術的な質問**: [GitHubのIssues](https://github.com/hey-show123/sozo-app-policies/issues)
- **プライバシーに関する質問**: [プライバシーポリシー記載のメールアドレス]

---

## 📄 ライセンス

このドキュメントは SOZO App 専用です。無断転載・流用は禁止されています。

© 2025 SOZO App. All rights reserved.
