# 草榴社区 · 代码资料目录

[返回项目记录](../草榴社区.md) · [返回首页](../../README.md)

先看：[五个页面的关系与联动现状](页面关系说明.md)。五页目前相互独立，未接入旧破解项目，不是完整自动化系统。

**类型：源码归档｜状态：未运行、未部署，未进行完整安全或功能测试**

## 两组资料

- **五个空间代码包**：本目录中的 5 个 HTML 页面，见下方文件索引。
- **1024RegisterTool 历史项目**：[归档说明](1024RegisterTool/归档说明.md) · [原始文件](1024RegisterTool/)。从用户已有公开仓库合并，保留原 README、源码和 BSD-3-Clause 许可证。包含枚举尝试功能，与 HTML 页面规则不同，仅单独归档，不联动执行。

## 五个空间代码包

来源：`t66y五个空间代码包.zip`。原包内 5 个 HTML 文件和 1 份文本说明原样解压，未修改代码。

## 文件索引

| 原文件标题 | 源码 |
| --- | --- |
| 监控手册（分享版） | [HTML](t66y-yao-qing-ma-jian-kong-shou-ce-fen-xiang-ban.html) |
| 带掩码的码只原样通知 | [HTML](dai-yan-ma-de-ma-zhi-yuan-yang-tong-zhi.html) |
| 收到码发邮箱或网盘 | [HTML](shou-dao-ma-fa-you-xiang-huo-wang-pan.html) |
| 单独测试邀请码 | [HTML](dan-du-ce-shi-yao-qing-ma.html) |
| 测试完能用再去注册（分享版） | [HTML](ce-shi-wan-neng-yong-zai-qu-zhu-ce-fen-xiang-ban.html) |
| 原包说明 | [TXT](t66y-5-spaces-README.txt) |

GitHub 上的 HTML 链接用于查看源文件，不是已部署的网站入口。本次仅归档，不启用 GitHub Pages，不连接 Muse 或第三方账号。

## 阅读代码时注意

- 页面标题描述的是预期流程，不代表相关自动化已经实现。检查到的交互主要是本地格式检查、复制、记录及导出；“发邮箱”包含调用本机邮件客户端的 `mailto:` 链接，不代表服务器已代发邮件。
- 没有发现这些页面通过 `fetch` 或 `XMLHttpRequest` 实际请求注册接口；页面上的状态标记不能作为远端验证成功的证据。
- 不同页面对字符、长度及掩码的判断规则不完全一致。保留原代码不代表确认这些规则正确。
- 两个页面引用 Google Fonts，因此不能将“单文件”理解为完全无外部资源。
- 未发现本地持久化 API；不要假定刷新或关闭页面后记录仍会保留。
- 初步敏感信息检查只发现示例邮箱，未发现实际密码或密钥；这不是完整安全审计。请勿把真实账号、私人记录或凭据提交到公开仓库。

## English

Unmodified archive of five user-supplied HTML files and their original text README. No deployment, execution or complete security/functional validation has been performed. UI labels describe intended workflows rather than verified integrations. Local checks and manually selected statuses do not prove remote validity; email handling includes a `mailto:` action. Some pages load external fonts, and validation rules differ between pages.
