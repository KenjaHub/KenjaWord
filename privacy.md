# Privacy Policy — KenjaWord

**Effective date: November 1, 2026**

**The short version: KenjaWord collects nothing.** There are no accounts, no analytics, no ads, and no tracking. Your documents never leave your device — opening, editing, saving and printing all happen locally. The only network traffic the app can make is when **you** use the AI pane, whose requests go directly to the model endpoint **you** configured.

KenjaWord is a word processor for macOS, Windows, Linux and the web, developed by KenjaHub ("we", "us"). This policy explains what happens to your data when you use the app.

## 1. Data we collect

None. KenjaWord does not transmit any personal data to us, and does not share data with any third party on our behalf.

In particular, KenjaWord does **not** include:

- user accounts or sign-in
- analytics, telemetry, or crash-reporting SDKs
- advertising or ad tracking of any kind
- third-party trackers

This matches our App Store privacy declaration: *Data Not Collected*.

## 2. Documents stay on your device

Everything KenjaWord does with your documents happens locally on your device:

- **Opening, editing, saving, printing and exporting all run on device.** There is no server, no sync, no cloud — files are read from and written to wherever you choose on your disk.
- **On macOS (App Store version)** the app runs in the sandbox and can touch only the files and folders you explicitly open or grant access to.
- **On the web** the app runs entirely in your browser; documents you open there stay in your browser unless you export or save them yourself.

## 3. AI features — you choose the endpoint

KenjaWord's AI pane (chat, writing help) is a **bring-your-own-model** feature. It has no built-in AI service of ours:

- **You configure the connection** — the endpoint (any OpenAI-compatible API, such as a hosted provider or a local model server like Ollama), the model, and your own API key.
- **When you use AI, your request goes directly from your device to that endpoint.** The message you type, plus the document context the feature includes (such as text you selected for the AI to work on), is sent to the provider you configured. That transfer is covered by **that provider's** privacy policy, not this one — pick a provider you trust.
- **We never see it.** AI traffic does not pass through any KenjaHub server; there is no middleman to route it through.
- **Chat sessions are memory-only.** Closing the app discards them. The only thing that persists is your model configuration (endpoint, model name, API key), stored in the app's local settings on your device.

If you never use the AI pane, the app makes no network requests at all beyond the local Zotero connection described below.

## 4. Zotero integration (optional, local only)

If you connect Zotero for citations, KenjaWord talks **only to the Zotero app running on your own machine** (over your computer's loopback interface). No citation data is sent to us or anywhere online by KenjaWord.

## 5. Data stored on your device

The following data is stored only on your device, under your full control:

- **Your documents** — the files you open and create stay wherever you saved them; KenjaWord keeps no copy
- **App settings** — including your AI model profiles (endpoint, model name, API key), kept in the app's local settings

Uninstalling the app removes the app and its local settings. Your documents are yours and remain untouched.

## 6. Network access

KenjaWord itself initiates no network traffic — no account check, no update ping, no telemetry. The only connections it can make are the ones described above: AI requests to the endpoint you configured, and the optional local Zotero connection. App updates are delivered by the App Store (or your platform's package channel), not by us.

## 7. Children

KenjaWord is a general-purpose productivity app and is not directed at children. Since the app collects no data at all, no data of children is collected either.

## 8. Your control

Because everything lives on your device, you are in full control at all times: open, copy, export or delete your documents whenever you like, in the Finder (or your file manager) like any other file. You can change or remove your AI model profiles in the app's settings at any time.

## 9. Changes to this policy

If we change this policy, we will post the updated version on this page with a new effective date.

## 10. Contact

- Email: [kenjasoft@kofukuai.com](mailto:kenjasoft@kofukuai.com)
- GitHub: <https://github.com/KenjaHub>

---

# 隐私政策 — KenjaWord(简体中文)

**生效日期：2026 年 11 月 1 日**

**简而言之：KenjaWord 不收集任何数据。**没有账号、没有统计、没有广告，也没有追踪。你的文档从不出你的设备——打开、编辑、保存、打印全部在本地完成。应用唯一可能发起的网络请求，是**你**使用 AI 面板时直接发往**你自己配置**的模型端点。

KenjaWord 是一款运行于 macOS、Windows、Linux 和网页端的文字处理器，由 KenjaHub（下称「我们」）开发。本政策说明你使用本应用时，你的数据会发生什么。

## 1. 我们收集的数据

无。KenjaWord 不会向我们传输任何个人数据，也不会代表我们与任何第三方共享数据。

具体而言，KenjaWord **不包含**：

- 用户账号或登录
- 统计分析、遥测或崩溃报告 SDK
- 任何形式的广告与广告追踪
- 第三方追踪器

这与我们在 App Store 的隐私申报一致：*不收集数据（Data Not Collected）*。

## 2. 文档留在你的设备上

KenjaWord 对你的文档所做的一切，都在你的设备本地完成：

- **打开、编辑、保存、打印与导出全部在设备上运行。**没有服务器、没有同步、没有云端——文件只从你选择的位置读入、写回。
- **macOS（App Store 版）**在沙盒中运行，只能访问你明确打开或授权的文件与文件夹。
- **网页版**完全在你的浏览器中运行；除非你自行导出或保存，文档始终留在浏览器里。

## 3. AI 功能——端点由你选择

KenjaWord 的 AI 面板（对话、写作辅助）是**自带模型（bring-your-own-model）**功能，我们不提供任何内置 AI 服务：

- **连接由你配置**——端点（任何 OpenAI 兼容 API，例如托管服务商或 Ollama 等本地模型服务）、模型与你的 API Key。
- **使用 AI 时，请求从你的设备直接发往该端点。**你输入的消息，以及该功能附带的文档上下文（例如你选中、交给 AI 处理的文字），会发送给你配置的服务商。该传输受**该服务商**的隐私政策约束，而非本政策——请选择你信任的服务商。
- **我们看不到。**AI 流量不经过任何 KenjaHub 服务器，没有中间环节。
- **对话仅在内存中。**关闭应用即丢弃。唯一持久保存的是你的模型配置（端点、模型名、API Key），存放在设备的本地应用设置中。

如果你从不使用 AI 面板，除下述本地 Zotero 连接外，应用不会发起任何网络请求。

## 4. Zotero 集成（可选，仅限本机）

如果你连接 Zotero 插入引文，KenjaWord **只与你本机上运行的 Zotero 应用通信**（走本机回环接口）。KenjaWord 不会把任何引文数据发给我们或任何在线服务。

## 5. 存储在你设备上的数据

以下数据仅存储在你的设备上，完全由你掌控：

- **你的文档**——你打开和创建的文件留在你保存它们的位置；KenjaWord 不保留任何副本
- **应用设置**——包括你的 AI 模型配置（端点、模型名、API Key），保存在设备的本地应用设置中

卸载应用会移除应用及其本地设置。你的文档属于你，不会被触碰。

## 6. 网络访问

KenjaWord 自身不发起任何网络流量——没有账号验证、没有更新探测、没有遥测。它唯一可能建立的连接就是上文所述：发往你配置端点的 AI 请求，以及可选的本机 Zotero 连接。应用更新由 App Store（或你所在平台的发布渠道）提供，而非我们。

## 7. 儿童

KenjaWord 是一款通用效率应用，不面向儿童。由于应用完全不收集数据，自然也不会收集任何儿童数据。

## 8. 你的掌控

因为一切都保存在你的设备上，你始终拥有完全的掌控：随时在访达（或你的文件管理器）中打开、复制、导出或删除你的文档，与任何普通文件一样。你也可以随时在应用设置中修改或删除 AI 模型配置。

## 9. 政策变更

如果我们修改本政策，会在本页发布更新版本，并注明新的生效日期。

## 10. 联系方式

- 邮箱：[kenjasoft@kofukuai.com](mailto:kenjasoft@kofukuai.com)
- GitHub：<https://github.com/KenjaHub>

---

# プライバシーポリシー — KenjaWord（日本語）

**発効日：2026 年 11 月 1 日**

**要点：KenjaWord は何も収集しません。**アカウントも、分析も、広告も、トラッキングもありません。お客様の書類が端末の外へ出ることはありません——開く・編集・保存・印刷はすべてローカルで実行されます。アプリが発信しうる唯一のネットワーク通信は、**お客様ご自身**が AI パネルを使う際に、**お客様が設定した**モデルエンドポイントへ直接送信されるものです。

KenjaWord は macOS・Windows・Linux・ウェブで動作するワードプロセッサーで、KenjaHub（以下「当社」）が開発しました。本ポリシーは、アプリご利用の際にお客様のデータがどう扱われるかを説明するものです。

## 1. 収集するデータ

なし。KenjaWord は当社へいかなる個人データも送信せず、当社のために第三者へデータを共有することもありません。

とくに、KenjaWord には以下のものは**含まれません**：

- ユーザーアカウントやサインイン
- アナリティクス、テレメトリー、クラッシュレポート SDK
- いかなる形態の広告および広告トラッキング
- サードパーティのトラッカー

これは App Store のプライバシー申告「*Data Not Collected（データ収集なし）*」と一致します。

## 2. 書類はお客様の端末に残ります

KenjaWord が書類に対して行うすべての処理は、お客様の端末上でローカルに実行されます：

- **開く・編集・保存・印刷・書き出しはすべて端末上で動作します。**サーバーも、同期も、クラウドもなく、ファイルはお客様が選んだ場所から読み込まれ、そこへ書き戻されます。
- **macOS（App Store 版）**はサンドボックスで動作し、お客様が明示的に開くか許可したファイルやフォルダーにしかアクセスできません。
- **ウェブ版**は完全にブラウザー内で動作します。お客様が書き出しや保存をしない限り、書類はブラウザーの中に留まります。

## 3. AI 機能——エンドポイントはお客様が選択します

KenjaWord の AI パネル（チャット、文章支援）は**モデル持ち込み（bring-your-own-model）**方式で、当社が AI サービスを内蔵することはありません：

- **接続はお客様が設定します**——エンドポイント（OpenAI 互換 API 全般。ホスト型プロバイダーでも、Ollama などのローカルモデルサーバーでも可）、モデル、お客様自身の API キー。
- **AI を使うと、リクエストはお客様の端末からそのエンドポイントへ直接送信されます。**入力されたメッセージと、機能が添付する書類の文脈（AI に処理させるため選択したテキストなど）は、お客様が設定したプロバイダーに送られます。この通信には**そのプロバイダー**のプライバシーポリシーが適用され、本ポリシーは適用されません——信頼できるプロバイダーをお選びください。
- **当社には見えません。**AI 通信が KenjaHub のサーバーを経由することはなく、仲介サーバーも存在しません。
- **チャットセッションはメモリー上のみ。**アプリを閉じると破棄されます。永続化されるのはモデル設定（エンドポイント、モデル名、API キー）だけで、端末のアプリローカル設定に保存されます。

AI パネルを一切使わない場合、後述のローカル Zotero 接続を除き、アプリはネットワーク通信を一切行いません。

## 4. Zotero 連携（任意・ローカルのみ）

引用のために Zotero を接続した場合、KenjaWord は**お客様のマシン上で動作している Zotero アプリとのみ**通信します（ループバックインターフェース経由）。KenjaWord が引用データを当社やオンラインのサービスへ送ることはありません。

## 5. 端末に保存されるデータ

以下のデータはお客様の端末にのみ保存され、完全にお客様の管理下にあります：

- **お客様の書類**——開いた作成したファイルは保存した場所にそのまま残り、KenjaWord はコピーを保持しません
- **アプリ設定**——モデル設定（エンドポイント、モデル名、API キー）を含むアプリのローカル設定

アプリをアンインストールすると、アプリとそのローカル設定は削除されます。書類はお客様のものであり、手つかずのまま残ります。

## 6. ネットワークアクセス

KenjaWord 自身は、ネットワーク通信を一切開始しません。アカウント確認も、更新確認も、テレメトリーもありません。確立されうる接続は、上記のとおり、お客様が設定したエンドポイントへの AI リクエストと、任意のローカル Zotero 接続だけです。アプリの更新は当社ではなく App Store（または各プラットフォームの配布チャネル）から配信されます。

## 7. 児童

KenjaWord は汎用的な生産性アプリであり、児童向けに作られたアプリではありません。アプリはまったくデータを収集しないため、児童のデータも収集されません。

## 8. お客様の管理

すべてが端末内に存在するため、データの管理権限は常に完全にお客様側にあります。書類はほかのファイルと同じように、いつでも開く・コピー・書き出し・削除ができます。AI モデル設定も、アプリの設定からいつでも変更・削除できます。

## 9. 本ポリシーの変更

本ポリシーを変更する場合は、このページに新しい発効日付きの更新版を掲載します。

## 10. お問い合わせ

- メール：[kenjasoft@kofukuai.com](mailto:kenjasoft@kofukuai.com)
- GitHub：<https://github.com/KenjaHub>

---

© 2026 KenjaHub
