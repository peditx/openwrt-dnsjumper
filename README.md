## Language Selection:

[**English**](README.md) | [**فارسی**](README_fa.md) | [**中文**](README_zh.md) | [**Русский**](README_ru.md) | [**Türkçe**](README_tr.md) | [**العربية**](README_ar.md)

![PeDitX Banner](https://raw.githubusercontent.com/peditx/luci-theme-peditx/refs/heads/main/luasrc/brand.png)  

---

# DNS Jumper for OpenWrt

This is a simple and efficient tool for the LuCI panel on OpenWrt, allowing you to easily and quickly manage and change your router's DNS servers.



## 🚀 Features

* **Quick DNS Change:** With a single click, change your router's DNS from a list of popular servers (like Shecan, Electro, Cloudflare, Google, etc.) or your own custom servers.
* **Speed Test (Ping):** Test the response time of each DNS server directly from your router to find the best and fastest option for your network.
* **Smart Sorting:** Automatically sort the DNS list based on the lowest ping (the fastest server).
* **Full List Management:**
    * Easily add new DNS servers.
    * Delete servers you don't need.
    * Mark your favorite servers with a star ⭐ for quicker access.
    * Manually change the display order using Drag & Drop.
* **Backup and Restore:** Create a backup file of your custom DNS list and restore it when needed.
* **Online Update:** Update the DNS server list by fetching the latest list from the internet.
* **Network Diagnostic Tool:** A built-in tool to ping custom domains or IPs through your selected DNS.
* **Live Monitor:** View network traffic in real-time (compatible with Passwall).

## ⚙️ Installation

There are two ways to install this tool:

### 1. Direct Installation via Command (Recommended)
Simply connect to your router using an SSH client (like PuTTY or Terminal) and run the following command:

```sh
sh -c "$(curl -sL https://peditx.ir/projects/DNSJumper/DNSJumper)"
```
The script will automatically install all prerequisites and copy the necessary files to the correct location.

### 2. Via the PeDitXOS Store
If you are using the **PeDitXOS** operating system, you can download and install this package directly from its internal store.

**Important Note:** After the installation is complete, hard-refresh your browser page (**Ctrl+Shift+R**) for the panel to display correctly.

## 🖥️ How to Use

1.  After installation, log in to your router's LuCI management panel.
2.  From the main menu, navigate to the **PeditXOS** section and then click on **DNS Jumper**.
3.  On this page, you can view the DNS list, test their ping, and activate your desired DNS server by clicking the **Apply** button.

---

## Special Thanks

- [PeDitX](https://github.com/peditx)  
- [PeDitXRT](https://github.com/peditx/peditxrt)  
- [OpenWrt](https://github.com/openwrt)  
- [Bootstrap Theme](https://github.com/twbs/bootstrap)
- [Mohamadreza Broujerdi](https://t.me/MR13_B)
- [Sia7ash](https://github.com/Sia7ash)


---

© 2018–2025 PeDitX. All rights reserved.  
For support or inquiries, join us on [Telegram](https://t.me/peditx).
