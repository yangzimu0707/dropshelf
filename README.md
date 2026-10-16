# DropShelf · 拾放时

> Drop a file in now, drag it out when you need it.
> 把文件先拖进来，需要时再拖出去。

A Windows desktop utility — a drop shelf for files · clipboard history

---

## Download

### ✅ Recommended: Microsoft Store (no security warnings)

https://apps.microsoft.com/detail/9MXV6M967R4T

Signed and distributed by Microsoft. No warnings during installation, and updates are handled automatically by the Store.

### Or: download the EXE directly

👉 **[Download the latest version](https://github.com/yangzimu0707/dropshelf/releases/latest)**

---

## ⚠️ About security warnings when installing (please read first)

This app is **not code-signed** (a signing certificate is costly for an individual developer), so your system may block it.

**Depending on your system there are two different blocks, and whether you can click through differs completely.** Figure out which one you have first.

### First: SmartScreen (most people, you can click through)

When you run an installer downloaded from a browser, Windows shows a blue prompt:

**"Windows protected your PC"**

This is how Windows treats **every program that is unsigned and not yet widely downloaded**. It does **not** mean the file is unsafe. To install:

1. Click **"More info"** in the prompt
2. Click **"Run anyway"** that appears below
3. Continue with the normal installation

> Note: **auto-updates will not show this prompt again.** Update packages are downloaded by the app itself (not through a browser), so they carry no "downloaded from the Internet" mark. You only face this prompt once.

### Second: Smart App Control (some Windows 11 devices, **no way through**)

If your Windows 11 was **cleanly installed** (not upgraded from an older version), Smart App Control may be enabled. It blocks unsigned programs outright, and **there is no "Run anyway" option**:

- The message looks like "Smart App Control blocked this app"
- **There is no per-app exception** — the feature simply does not work that way, and there is no allow list
- The only way around it is to turn Smart App Control off entirely — and once off, it **can only be re-enabled by resetting or reinstalling Windows**

**If you hit this block, please do not turn it off — use the Microsoft Store version above instead.** Store apps are signed and distributed by Microsoft and are treated as trusted, so they are not affected.

> Note: while Smart App Control is on, the installer delivered by auto-update may be blocked as well. In that case, the Store version is the recommended path.

### Which one are you seeing?

| What you see | Which block | What to do |
|---|---|---|
| Blue "Windows protected your PC" with a clickable "More info" | SmartScreen | Click "More info" → "Run anyway" |
| "Smart App Control blocked this app" with **no button to proceed** | Smart App Control | Use the Microsoft Store version |

---

## Features

**📥 File drop shelf** — Park a file now, pick it up later

No copying, no renaming, no folders. Only a path reference is stored, so even huge files are added instantly.

**📋 Clipboard history** — Text and images you copied stay within reach. Text that looks like a password is skipped by default.

**🖥️ Two desktop forms** — Keep it as a floating ball, or as a bar docked to the top edge of your screen (it expands when you drag a file near it). A global hotkey can summon it anytime.

**🌐 Bilingual UI** — Choose Chinese or English on first launch; switch anytime in Settings.

---

## Privacy

**Everything stays on your machine. Nothing is uploaded to any server.**

- No account required
- No usage data collected
- The shelf only stores path references, never file contents
- Clipboard images are saved in the app data folder (D: by default, and you can move it anywhere)

---

## Requirements

- Windows 10 / 11 (64-bit)
- ~300 MB of disk space

---

## About updates

The EXE build has a built-in auto-updater: it checks once per launch and downloads new versions quietly in the background. When the download finishes, click "Restart to update" — the app installs and reopens automatically.

If it has already checked that day and found nothing new, it won't make another request.

---

## Feedback

Found a bug or have a feature request? Please open an issue:

https://github.com/yangzimu0707/dropshelf/issues

---
---

# 拾放时 · DropShelf

> 把文件先拖进来，需要时再拖出去。

Windows 桌面工具 · 文件中转站 · 剪贴板历史

---

## 下载

### ✅ 推荐：微软商店（不会弹任何安全提示）

https://apps.microsoft.com/detail/9MXV6M967R4T

由微软签名和分发，安装时不弹任何警告，后续更新也由商店自动完成。

### 或者：直接下载 EXE

👉 **[下载最新版](https://github.com/yangzimu0707/dropshelf/releases/latest)**

---

## ⚠️ 安装时的安全提示（请先看一眼）

本应用**没有购买代码签名证书**（个人开发者购买证书的成本较高），所以安装时可能被系统拦下。

**根据你的系统情况有两道拦截，能不能点过去完全不同** —— 请先分清自己是哪一种。

### 第一道：SmartScreen（大部分人遇到，可以点过去）

从浏览器下载的安装包首次运行时，Windows 会弹出蓝色提示：

**「Windows 已保护你的电脑」**（英文系统为 *Windows protected your PC*）

这是 Windows 对**所有「没有签名、下载量还不高」的程序**的统一处理方式，**不代表文件有问题**。安装时这样做：

1. 点击提示框里的 **「更多信息」**
2. 点击随后出现的 **「仍要运行」**
3. 正常走安装流程即可

> 说明：应用**装好之后的自动更新不会再弹这个提示**。更新包是应用自己下载的、不经过浏览器，不带「来自 Internet」的标记。这个提示你只需要面对一次。

### 第二道：智能应用控制（部分 Windows 11 遇到，**点不过去**）

如果你用的是**全新安装的** Windows 11（不是从旧系统升级上来的），系统可能开着「智能应用控制」（Smart App Control）。它会直接拦下未签名的程序，而且**没有「仍要运行」这个选项**：

- 提示内容类似「智能应用控制已阻止此应用」
- **不支持针对单个应用放行** —— 系统层面就没有这个功能，也没有例外名单
- 唯一的办法是把「智能应用控制」整个关掉，但它**一旦关闭，必须重置或重装 Windows 才能再打开**

**所以遇到这道拦截，请不要去关它，直接改用上面的微软商店版本。** 商店里的应用由微软签名和分发、被系统视为可信，不受这道限制影响。

> 补充：智能应用控制处于开启状态时，自动更新下载的安装包同样可能被阻止。这种情况也请改用商店版本。

### 怎么判断自己遇到的是哪一道

| 你看到的 | 是哪一道 | 怎么办 |
|---|---|---|
| 蓝底「Windows 已保护你的电脑」，有「更多信息」可点 | SmartScreen | 点「更多信息」→「仍要运行」 |
| 「智能应用控制已阻止此应用」，**没有任何可以点过去的按钮** | 智能应用控制 | 改用微软商店版本 |

---

## 功能

**📥 文件中转站** —— 拖进去先放着，要用时再拖出来

不用复制文件、不用起名字、不用建文件夹。中转只记录路径引用，所以再大的文件也是瞬间加入。

**📋 剪贴板历史** —— 复制的文字和图片都留得住，随时翻回去。疑似密码的内容默认跳过，不会记录。

**🖥️ 两种桌面形态** —— 悬浮球，或贴在屏幕顶部的长方形栏（拖动文件靠近会自动展开）。还可以设置全局快捷键随时唤起。

**🌐 中英双语** —— 首次启动自己选，之后也能在设置里随时切换。

---

## 隐私

**所有数据只存在你自己的电脑上，不会上传到任何服务器。**

- 不需要注册账号
- 不收集任何使用数据
- 中转站只记录文件的路径引用，不复制文件内容
- 剪贴板历史里的图片保存在应用数据目录（默认 D 盘，位置可自行更改）

---

## 系统要求

- Windows 10 / 11（64 位）
- 约 300 MB 磁盘空间

---

## 关于更新

EXE 版内置自动更新：每次启动会检查一次新版本，发现后**在后台静默下载**，不打断你的使用。下载完成后点一下「重启更新」即可完成安装，装完会自动重新打开。

如果当天已经检查过且没有新版本，就不会重复请求。

---

## 问题反馈

遇到问题或有功能建议，欢迎在这里提 Issue：

https://github.com/yangzimu0707/dropshelf/issues
