CATLOCK / PRIVACY

# Privacy Policy

Provider: SEAL
Contact: [sealluo81@gmail.com](mailto:sealluo81@gmail.com)
Effective date: November 3, 2026
Last updated: November 20, 2026

## Scope

This policy describes information handled by the CatLock macOS app and through support requests sent to the contact email above.

## Information processed on your Mac

CatLock does not require an app account. It includes no advertising, tracking, or third-party analytics SDKs, and has no feature that sends usage data to a developer server.

Your cat name, selected appearance, interface preferences, lock mode, auto-unlock settings, and onboarding status are stored in local macOS preferences. A custom unlock phrase is stored in macOS Keychain and is also used in memory while the app runs. CatLock provides no cloud sync service. System backup, device migration, and other services you use may process local data under their own settings.

## Lock modes, permissions, and keyboard events

Starting with version 1.0 Build 3, default locking requires neither Accessibility nor Input Monitoring permission. A transparent overlay handles keyboard and mouse events sent to CatLock’s own windows so ordinary input does not reach underlying apps. This mode does not create a global keyboard event tap.

“Allow mouse use while locked”, under Settings → Protection & Unlock → Additional options, is off by default. It is available only after the user enables it and grants Accessibility permission. While locked, this mode blocks keyboard input in other apps while allowing mouse interaction. Its keyboard event listener is created only when locking in this mode and removed on unlock. Earlier Build 2 used this permission-based approach for keyboard protection.

During protection, the app temporarily processes key input in memory to detect your unlock phrase. It does not create or save a keystroke log or upload key input to the developer. The matching buffer is cleared on unlock, input reset, or matching timeout. Text entered directly into CatLock, such as a cat name or unlock phrase, is processed for that feature.

You can revoke permission in System Settings → Privacy & Security → Accessibility. Without permission, the optional mouse mode is unavailable, but default locking remains available. You can stop protection by typing your unlock phrase or holding the cat for 3 seconds.

## Support email

When you contact us, we receive your email address, message, and any diagnostic information or screenshots you choose to attach. We use this information to respond and provide support. Do not send Apple Account passwords, verification codes, or unnecessary sensitive information.

Support information is retained for handling your request, necessary follow-up, and any legally required retention. Contact us to request access, correction, or deletion, subject to required legal retention. Our email provider processes information to deliver and store messages and may process it in other regions under its service arrangements. We do not sell support information or use it for advertising.

## Apple services and beta testing

Apple handles App Store purchases, downloads, and refunds. The CatLock app does not read your payment card details.

CatLock has no integrated automatic diagnostic upload service. Apple system diagnostics and App Store services may process information under Apple's terms and your settings. During TestFlight testing, Apple collects and shares test usage, crash information, and submitted feedback with the developer, potentially including names and email addresses. We use this information for testing support and improving the app and do not share it with third parties. See [Apple's TestFlight & Privacy information](https://www.apple.com/legal/privacy/data/en/test-flight/).

## Managing local data

You can change your cat name, appearance, and preferences in Settings. Restoring the default unlock phrase deletes the custom phrase stored by the app. Deleting the app alone may leave preferences and Keychain items on your Mac. Contact support for complete removal instructions. The developer cannot remotely read or delete local data on your Mac.

## Changes

If our information practices change, we will update this policy and its effective date and provide notice or request permission where required.

## Visiting this website

These support documents and the privacy policy are provided through GitHub, with the website version hosted on GitHub Pages. GitHub may process technical information such as IP addresses, browser information, and requests to deliver content and keep the service secure, under its applicable service and privacy policies. We have not added advertising, analytics scripts, third-party fonts, or contact forms to these pages. Email links open your own email service. Website access is separate from the app's local data processing.

---

CATLOCK / PRIVACY

# 隐私政策

服务提供者：SEAL
联系邮箱：[sealluo81@gmail.com](mailto:sealluo81@gmail.com)
生效日期：2026 年 11 月 3 日
更新日期：2026 年 11 月 20 日

## 适用范围

本政策说明 CatLock macOS 应用如何处理信息，以及通过上方邮箱提供支持时的信息处理方式。

## 应用在本机处理的信息

CatLock 无需注册应用账号。应用未集成广告、跟踪或第三方分析 SDK，也没有向开发者服务器发送使用数据的功能。

猫咪名字、所选外观、界面偏好、锁定模式、自动解除保护设置及新手引导状态，保存在本机 macOS 偏好设置中。自定义解锁口令保存在本机 macOS 钥匙串中；应用运行期间也会在内存中使用该口令完成匹配。CatLock 不提供自己的云同步功能。你使用的系统备份、设备迁移或其他系统服务可能按各自设置处理本机数据。

## 锁定模式、权限与键盘事件

从 1.0 Build 3 起，默认锁定无需辅助功能或输入监控权限。应用通过透明覆盖窗口处理发送给 CatLock 自己的按键和鼠标事件，使普通输入不会传到下方应用；默认模式不创建全局键盘拦截监听。

“设置 → 保护与解锁 → 附加选项”中的“锁定时允许使用鼠标”默认关闭。只有用户主动开启并授予辅助功能权限后，此模式才可在锁定期间拦截其他应用的键盘输入，同时保留鼠标操作。用于拦截的键盘事件监听只在该模式锁定时创建，解锁时移除。此前的 Build 2 使用这一授权方式进行键盘保护。

保护期间，应用在内存中临时处理按键，以判断是否输入了解锁口令。它不会建立或保存按键日志，也不会把按键内容上传给开发者。匹配缓冲区会在解锁、输入重置或匹配超时后清空。猫咪取名、设置口令等应用内输入会按对应功能正常处理。

你可在“系统设置 → 隐私与安全性 → 辅助功能”撤销 CatLock 的授权。撤销后，可选鼠标模式将无法使用，默认免权限锁定仍可用。也可通过输入解锁口令或按住猫咪 3 秒停止保护。

## 客服邮件

当你主动发送邮件，我们会收到你的邮箱地址、邮件内容及自行附上的诊断信息或截图，用于回复问题和提供支持。请不要发送 Apple 账户密码、验证码或其他不必要的敏感信息。

客服资料仅在处理请求、必要后续沟通及依法必须保存的期间保留。你可以通过上方邮箱请求查询、更正或删除客服资料；依法必须保留的部分除外。邮件服务提供商会为收发和存储邮件处理相应信息，邮件可能根据该服务的安排在其他地区处理。我们不将客服内容用于广告或出售给他人。

## Apple 平台服务与测试版本

App Store 的购买、下载和退款由 Apple 平台处理，CatLock 应用不会读取你的银行卡资料。

CatLock 本身没有集成自动诊断上传服务。Apple 的系统诊断与 App Store 服务可能按其条款及你的设置处理信息。通过 TestFlight 测试时，Apple 会收集并向开发者提供测试使用情况、崩溃信息及你提交的反馈，可能包括姓名和邮箱；开发者仅将其用于测试支持和改善应用，不向第三方分享这些测试资料。详见 [Apple TestFlight 与隐私](https://www.apple.com/legal/privacy/data/en/test-flight/)。

## 管理与删除本机数据

你可以在 CatLock 设置中修改猫咪名字、外观及偏好，也可以将解锁口令恢复为默认值，以删除应用保存的自定义口令。单独删除应用不一定会清除系统保留的偏好设置和钥匙串项目。如需完整清理指引，请联系支持；开发者不能远程读取或删除你的本机数据。

## 政策更新

当应用的信息处理方式变化时，我们会更新此政策及生效日期，并在需要时提供通知或取得授权。

## 本网站的访问

本支持文档及隐私政策通过 GitHub 提供，网页版本使用 GitHub Pages。为传送内容和保障服务安全，GitHub 可能处理 IP 地址、浏览器信息及访问请求等技术数据，其处理同时受 GitHub 的相关服务及隐私政策约束。我们未在页面中添加广告、分析脚本、第三方字体或联系表单；点击邮箱链接会打开你自行使用的邮件服务。应用本身的数据处理方式与访问本网站不同。
