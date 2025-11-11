# SOZO App - 審査提出ガイド

## 🎯 必要なドキュメントは2つだけ！

### 📱 iOS (App Store)
→ **[iOS_COMPLETE_GUIDE.md](./iOS_COMPLETE_GUIDE.md)**

### 🤖 Android (Google Play)
→ **[Android_COMPLETE_GUIDE.md](./Android_COMPLETE_GUIDE.md)**

上記のガイドに従えば審査提出に必要なすべてが分かります。

---

## ⚠️ 最重要：プライバシーポリシーの記入

プライバシーポリシーの以下を**必ず**実際の情報に置き換えてください：

```
[会社名または個人名] → あなたの名前/会社名
[住所] → 実際の住所
[代表者名] → 代表者の名前
[サポートメールアドレス] → support@example.com
[プライバシー担当メールアドレス] → privacy@example.com
[使用リージョン] → Azure Speech Servicesのリージョン
```

### 編集方法
```bash
cd /Users/yamazakishohei/Documents/SOZO/sozo-app-policies
nano privacy_policy.html
# 上記のプレースホルダーを置換
git add privacy_policy.html
git commit -m "Update with actual information"
git push
```

---

## 📄 公開URL

- **プライバシーポリシー**: https://hey-show123.github.io/sozo-app-policies/privacy_policy.html
- **利用規約**: https://hey-show123.github.io/sozo-app-policies/terms_of_service.html

---

© 2025 SOZO App. All rights reserved.