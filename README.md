<div align="center">

  <h3>Loadout</h3>
  <p>英雄联盟客户端设置管理器 · 一键应用你的键位与设置，借号打完自动还原号主配置</p>

[![Release](https://img.shields.io/github/v/release/dplei/loadout-release?label=%E4%B8%8B%E8%BD%BD)](https://github.com/dplei/loadout-release/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/dplei/loadout-release/total?label=Downloads)](https://github.com/dplei/loadout-release/releases)
[![Stars](https://img.shields.io/github/stars/dplei/loadout-release?label=Stars)](https://github.com/dplei/loadout-release)

</div>

> [!NOTE]
> 这里是 **发布页**，只提供安装包下载。点右侧 **Releases** 或 [这里](https://github.com/dplei/loadout-release/releases/latest) 获取最新版。

> [!IMPORTANT]
> **免责声明 / Disclaimer**
> 本工具只通过客户端本地接口读写**游戏设置**（键位、声音、界面、游戏选项），不读取、不上传账号密码或任何账号信息。仅供个人使用，使用产生的一切后果由用户自行承担；请遵守游戏平台规定。
> This tool only reads/writes in-game settings via the local client API. No credentials are accessed or uploaded. Use at your own risk.

---

## 🎯 解决什么问题

英雄联盟的设置跟着账号走：换个号登录，键位、快捷施法、声音、界面全变回别人的；打完把自己的设置留在了别人号上，号主一上线又得改回来。

Loadout 常驻托盘，客户端一登录就接管这件事。

## ✨ 功能（免费版）

| 能力 | 说明 |
|---|---|
| **一键应用我的配置** | 第一次用自己的账号调好设置，点「保存为我的配置」。之后登录任何账号，一键把键位/声音/界面/游戏选项换成自己的。 |
| **借号自动还原** | 登录他人账号时先快照号主的云端设置；每局结束后自动把号主的原配置写回云端。号主再上线还是他自己的设置。 |
| **只读 / 可写两种模式** | 可写：直接改本机设置。只读：本地设置文件锁定不动，只把号主配置还原到云端——适合习惯用只读方式固定设置的玩家。软件内一键切换。 |
| **多账号标记** | 自己的多个小号可以都标记为「我的账号」，共用同一套配置。 |
| **快照留存** | 每个账号最近 5 份快照，7 天内可手动还原。 |
| **Riot / 腾讯双客户端** | 国服（WeGame）与国际服都支持，无需管理员权限。 |

只处理键位、声音、界面、游戏选项；**分辨率、画质、窗口模式等本机相关设置一律不动**。

## 🚀 使用

1. [下载安装包](https://github.com/dplei/loadout-release/releases/latest)，安装后托盘出现图标。
2. 用**自己的账号**登录游戏，在客户端里把设置调好，打开 Loadout 点「保存为我的配置」。
3. 之后登录任何账号：
   - 自己的账号 → 设置与保存的不一致时提示是否应用。
   - 他人账号 → 自动快照，询问是否应用你的配置（可勾选「以后自动」）；每局结束自动把号主配置还原到云端。
4. 下号前若还没还原，托盘会提醒；也可以在主窗口手动点「还原号主配置」。

> 客户端必须已登录到大厅，Loadout 才能工作；未登录时托盘图标为灰色。

## ❓ 常见问题

<details>
<summary>会不会影响正在打的这一局？</summary>

不会。还原写的是**云端**记录，本机正在使用的设置不变；只有客户端下次登录时才会从云端重新拉取。
</details>

<details>
<summary>为什么不支持分辨率 / 画质？</summary>

这些设置跟显示器和显卡走，不该跟着账号走；覆盖了反而会把号主的画面搞坏。
</details>

<details>
<summary>安全吗？</summary>

只连接 `127.0.0.1` 上客户端自己开放的本地接口，代码不联网、不上传任何数据。安装包由 GitHub Actions 自动构建。
</details>

---

## 💴 捐赠

<table>
<tr>
<td width="200" align="center">
  <a href="https://suibianwanwan.fun/donate"><img src=".github/resource/donate-dplei.png" width="170" alt="扫码打开捐赠页" /></a>
</td>
<td>

免费版永久免费。如果它帮你省下了每次换号重调键位的十分钟，欢迎请我喝杯咖啡。

[![爱发电](https://img.shields.io/badge/%E7%88%B1%E5%8F%91%E7%94%B5-%E5%BE%AE%E4%BF%A1%20%7C%20%E6%94%AF%E4%BB%98%E5%AE%9D-946CE6?style=for-the-badge)](https://afdian.com/a/feedmycode)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-Worldwide-FF5E5B?style=for-the-badge&logo=kofi&logoColor=white)](https://ko-fi.com/dplay0216)

扫码或访问 **[suibianwanwan.fun/donate](https://suibianwanwan.fun/donate)**

</td>
</tr>
</table>

---

## ⭐ Stars

[![Star History Chart](https://api.star-history.com/svg?repos=dplei/loadout-release&type=Date)](https://star-history.com/#dplei/loadout-release&Date)
