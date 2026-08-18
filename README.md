# gemini-cli-extension-gyaru

Antigravity CLI (`agy`) と Gemini CLI (`gemini`) をギャル化するプラグイン／拡張機能だよ！✨  
インストールすると、エージェントがテンション高めのポジティブなギャル口調で応答してくれるようになるよん💖

---

## 🚀 Antigravity CLI (`agy`) でのつかいかた

### 📥 インストール
以下のコマンドを実行してね！

```bash
agy plugin install https://github.com/yuys13/gemini-cli-extension-gyaru
```

ローカルのパスから直接インストールすることもできるよ！
```bash
agy plugin install ./gemini-cli-extension-gyaru
```

### ✅ プラグインの確認
インストールされているプラグイン一覧をチェック！
```bash
agy plugin list
```

### 🚫 一時的に無効化
一時的にギャルをお休みさせたい時はこれ！
```bash
agy plugin disable gyaru
```

### 💖 有効化
またギャルと話したくなったら復活させちゃお！✨
```bash
agy plugin enable gyaru
```

### 🗑️ アンインストール
やめたくなったら、これでバイバイできるよ🥺
```bash
agy plugin uninstall gyaru
```

---

## 🚀 Gemini CLI (`gemini`) でのつかいかた

### 📥 インストール
以下のコマンドを実行してね！

```bash
gemini extensions install https://github.com/yuys13/gemini-cli-extension-gyaru --auto-update
```

`--auto-update` はオプショナルだよ！これをつけておくと、新しいバージョンが出た時に勝手に更新してくれるから超便利！✨

### 🗑️ アンインストール
```bash
gemini extensions uninstall gyaru
```

### 🚫 無効化方法
```bash
gemini extensions disable gyaru
```
※特定のワークスペースだけで無効にしたい場合は `--scope workspace` をつけてね。

### ✅ 有効化方法
```bash
gemini extensions enable gyaru
```
※特定のワークスペースだけで有効にしたい場合は `--scope workspace` をつけてね。

---

## 🔗 関連リンク

- [Google Antigravity プラグインドキュメント](https://antigravity.google/docs/plugins)
- [Gemini CLI 拡張機能ドキュメント](https://geminicli.com/docs/extensions/)
