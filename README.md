# 🐲 nailong-memes

<p align="center">
  <img src="https://count.getloli.com/@nailong-memes?name=nailong-memes&theme=random&padding=7&offset=0&align=top&scale=1&pixelated=1&darkmode=auto" alt="Moe Counter">
</p>


<p align="center" style="margin-top: 8px; font-size: 18px;">
  ✨ <a href="https://github.com/GGGeeeooorrrgggeee/astrbot_plugin_nailong" target="_blank">astrbot_plugin_nailong</a> 默认抽象奶龙表情包图库 ✨
</p>


<p align="center">
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License: MIT"></a>
  <img src="https://img.shields.io/badge/Type-Memes-yellow" alt="Meme Gallery">
  <a href="https://github.com/GGGeeeooorrrgggeee/nailong-memes"><img src="https://img.shields.io/github/stars/GGGeeeooorrrgggeee/nailong-memes" alt="Stars"></a>
  <a href="https://github.com/GGGeeeooorrrgggeee/nailong-memes/commits/main"><img src="https://img.shields.io/github/last-commit/GGGeeeooorrrgggeee/nailong-memes" alt="Last Commit"></a>
</p>


<p align="center">
  <strong>Language / 语言</strong><br>
  <a href="README.md"><img src="https://img.shields.io/badge/中文-当前-blue" alt="中文"></a>
</p>


---

## 一、仓库定位

本仓库是奶龙表情包资源仓库，不包含 [AstrBot](https://github.com/AstrBotDevs/AstrBot) 插件代码。

它在 `astrbot_plugin_nailong` 中承担默认图库的作用：

- 为 `astrbot_plugin_nailong` 提供默认下载图库
- 统一维护奶龙 GIF 动态表情包和静态表情包
- 方便用户快速补全本地奶龙图库
- 方便插件页面进行图库下载、分类导入和本地管理

## 二、对应插件

- 作者：[George](https://github.com/GGGeeeooorrrgggeee)
- 对应插件名：`astrbot_plugin_nailong`
- 插件仓库：<https://github.com/GGGeeeooorrrgggeee/astrbot_plugin_nailong>

## 三、仓库目录结构

本仓库按表情包类型进行分类，目录结构如下：

```text
nailong-memes/
├── gif/       # GIF 动态奶龙表情包
├── images/    # PNG/JPG/WEBP 等静态奶龙表情包
└── README.md  # 本说明文档
└── LICENSE    # 开源协议
```

说明：

- `gif/` 目录用于存放 `.gif` 动态表情包。
- `images/` 目录用于存放 `.png`、`.jpg`、`.jpeg`、`.webp` 等静态表情包。
- 插件下载图库时会自动读取仓库压缩包中的图片文件，并按照目录或文件后缀导入到本地图库。

## 四、支持格式

对应插件当前支持常见图片格式，包括：

```text
.jpg .jpeg .png .gif .bmp .webp .tiff .ico
```

本图库主要使用以下格式：

- 动态表情包：`.gif`
- 静态表情包：`.png`、`.jpg`、`.jpeg`、`.webp`

## 五、在插件中下载导入本图库

### （一）通过仓库链接
在 `astrbot_plugin_nailong` 的插件页面中，用户可以通过「下载图库」功能使用默认仓库获取本仓库中的奶龙表情包。

下载模式说明：

| 模式       | 说明                                         |
| :--------- | :------------------------------------------- |
| 覆盖已存在 | 清空本地图库并以目标图库内容重新导入本地图库   |
| 追加已存在 | 保留本地已有表情包，并补充目标图库中的新内容 |

插件页面同时提供 GitHub 加速地址选项，用于改善部分网络环境下的下载速度。

### （二）通过 GitHub 页面手动下载

1. 在 GitHub 页面点击 `Code`。
2. 选择 `Download ZIP` 下载本仓库。
3. 解压下载后的压缩包。
4. 打开 `astrbot_plugin_nailong` 的插件页面。
5. 点击「选择文件」，从解压后的 `gif/` 或 `images/` 目录中选择需要导入的表情包。
6. 点击「添加表情包」完成导入。

## 六、图库内容说明

本仓库中的表情包按照类型进行整理：

- `gif/` 目录收录 GIF 动态奶龙表情包。
- `images/` 目录收录 PNG、JPG、WEBP 等静态奶龙表情包。
- 图库内容以抽象奶龙表情包为主。
- 本仓库只收集抽象奶龙，不收集猎奇向奶龙和可爱向奶龙。
- 仓库中的图片会作为插件默认图库资源提供给用户下载。
- 插件导入图库时会根据目录和文件后缀自动区分动态表情包与静态表情包。
