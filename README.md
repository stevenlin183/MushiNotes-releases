# MushiNotes — 下载

这里只放 **MushiNotes** 的安装包和发布说明（代码不在这里）。

👉 **[最新版本](../../releases/latest)**

| 文件 | 是什么 |
|---|---|
| `MushiNotes-Setup-<版本>.exe` | Windows 装机版。装过的会自己提示更新。 |
| `MushiNotes.html` | 网页版，一个文件，双击用 Chrome / Edge 打开。 |
| `SHA256SUMS.txt` | 校验和 |
| `latest.yml` / `*.blockmap` | 装机版自动更新用的，不用管 |

⚠️ 安装包暂时没有代码签名，Windows 第一次会拦一下：点「更多信息 → 仍要运行」。


## 网页版（手机 / 平板）

👉 **https://stevenlin183.github.io/MushiNotes-releases/**

- 内容就是最新 Release 里的 `MushiNotes.html`；每次 Release 点 **Publish** 后自动更新（`.github/workflows/pages.yml`）。
- iPhone / iPad：Safari 打开 → 分享 → **添加到主屏幕**，之后**只用那个图标**打开。主屏幕版和 Safari 标签页里的数据**不共享**（各存一份），第一次打开先登录云同步把笔记拉下来。
