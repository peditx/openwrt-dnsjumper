## Language Selection:

[**English**](README.md) | [**فارسی**](README_fa.md) | [**中文**](README_zh.md) | [**Русский**](README_ru.md) | [**Türkçe**](README_tr.md) | [**العربية**](README_ar.md)

![PeDitX Banner](https://raw.githubusercontent.com/peditx/luci-theme-peditx/refs/heads/main/luasrc/brand.png)  

---

# DNS Jumper for OpenWrt

这是一款适用于 OpenWrt 的 LuCI 面板的简单高效工具，让您可以轻松快速地管理和更改路由器的 DNS 服务器。



## 🚀 功能特性

* **快速切换 DNS:** 只需单击一下，即可从流行服务器列表（如 Shecan、Electro、Cloudflare、Google 等）或您自己的自定义服务器中更改路由器的 DNS。
* **速度测试 (Ping):** 直接从您的路由器测试每个 DNS 服务器的响应时间，为您的网络找到最佳、最快的选项。
* **智能排序:** 根据最低的 ping 值（最快的服务器）自动对 DNS 列表进行排序。
* **完整的列表管理:**
    * 轻松添加新的 DNS 服务器。
    * 删除您不需要的服务器。
    * 为您喜欢的服务器加星 ⭐，以便更快地访问。
    * 使用拖放（Drag & Drop）手动更改显示顺序。
* **备份与恢复:** 为您的自定义 DNS 列表创建备份文件，并在需要时恢复它。
* **在线更新:** 通过从互联网获取最新列表来更新 DNS 服务器列表。
* **网络诊断工具:** 一个内置工具，可通过您选择的 DNS ping 自定义域名或 IP。
* **实时监控:** 实时查看网络流量（与 Passwall 兼容）。

## ⚙️ 安装方法

有两种方法可以安装此工具：

### 1. 通过命令直接安装（推荐）
只需使用 SSH 客户端（如 PuTTY 或终端）连接到您的路由器，然后运行以下命令：

```sh
sh -c "$(curl -sL https://peditx.ir/projects/DNSJumper/DNSJumper)"
```
该脚本将自动安装所有依赖项，并将必要的文件复制到正确的位置。

### 2. 通过 PeDitXOS 应用商店
如果您正在使用 **PeDitXOS** 操作系统，您可以直接从其内置的应用商店下载并安装此软件包。

**重要提示：** 安装完成后，请强制刷新您的浏览器页面（**Ctrl+Shift+R**），以确保面板正确显示。

## 🖥️ 如何使用

1.  安装后，登录到您的路由器的 LuCI 管理面板。
2.  从主菜单中，导航至 **PeditXOS** 部分，然后点击 **DNS Jumper**。
3.  在此页面上，您可以查看 DNS 列表，测试它们的 ping 值，并通过单击 **Apply** 按钮激活您想要的 DNS 服务器。

---

## 特别感谢

- [PeDitX](https://github.com/peditx)  
- [PeDitXRT](https://github.com/peditx/peditxrt)  
- [OpenWrt](https://github.com/openwrt)  
- [Bootstrap Theme](https://github.com/twbs/bootstrap)
- [Mohamadreza Broujerdi](https://t.me/MR13_B)
- [Sia7ash](https://github.com/Sia7ash)


---

© 2018–2025 PeDitX. All rights reserved.  
For support or inquiries, join us on [Telegram](https://t.me/peditx).
