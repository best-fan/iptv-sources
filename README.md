
<div align="center">

# 📺 iptv-sources

**IPTV 直播数据分享 | 每天自动采集更新**

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![Channels](https://img.shields.io/badge/Channels-46+-orange)
![Auto Update](https://img.shields.io/badge/Auto_Update-每日-brightgreen)
![License](https://img.shields.io/badge/License-MIT-green)

</div>

## 🚀 项目简介

这是一个功能强大的 IPTV 直播数据采集和汇总地址的仓库。项目可以从多个来源获取直播源数据，进行有效性验证，并生成标准的 M3U8 播放列表文件。

**✨ 核心特点：**
- 🔄 **每日自动更新** - 确保直播源的有效性
- ✅ **智能验证** - 自动检测可播放性
- 📊 **数据分类** - 按频道类型整理

## 📁 项目结构

```bash
iptv-sources/
├── 📋 cn_all.m3u8          # 完整播放列表（46+个频道）
├── 📡 cn_cctv.m3u8         # 央视频道列表
├── 🏢 cn_province.m3u8     # 卫视频道列表  
├── 💎 cn_pay.m3u8          # 付费频道列表
└── 📖 README.md            # 项目说明文档
```

## ✨ 功能特性

<div align="center">

| 功能 | 状态 | 图标 | 描述 |
|------|------|------|------|
| **多源数据采集** | ✅ | 🔍 | 支持从多个网站和 API 获取直播源数据 |
| **有效性验证** | ✅ | ✅ | 自动检测直播源的可播放性和响应时间 |
| **频道分类** | ✅ | 📺 | 支持央视、卫视、付费频道等多种分类 |
| **智能去重** | ✅ | 🎯 | 自动去除重复的直播源 |
| **清晰度排序** | ❌ | 📊 | 按视频清晰度自动排序 |
| **跨域检测** | ❌ | 🌐 | 检测直播源是否支持跨域访问 |
| **M3U8 生成** | ✅ | 📝 | 生成标准格式的 M3U8 播放列表 |

</div>

## 📺 支持频道类型

### 🇨🇳 央视频道
- **包含**:📡 CCTV-1 到 CCTV-17，CCTV-4K 等
- **文件**: `cn_cctv.m3u8`

### 🏢 卫视频道  
- **包含**:🏙️ 北京卫视、湖南卫视、东方卫视等 37 个省级卫视
- **文件**: `cn_province.m3u8`

### 💎 付费频道
- **包含**:💰 凤凰中文、金鹰纪实、茶友频道等 45 个付费频道
- **文件**: `cn_pay.m3u8`

### 📋 完整列表
- **包含**: 📺所有 46+ 个频道
- **文件**: `cn_all.m3u8`

## ⚠️ 注意事项

<div align="center">

| 注意事项 | 图标 | 说明 |
|----------|------|------|
| **遵守条款** | 📜 | 请遵守相关网站的使用条款 |
| **定期更新** | 🔄 | 直播源可能会随时失效，需要定期更新 |
| **学习用途** | 🎓 | 仅供学习和研究使用 |
| **法律责任** | ⚖️ | 用户需自行承担使用责任 |

</div>

## 📄 许可证

本项目采用 **MIT 许可证**，仅供学习和研究使用。

---

## 🙏 数据源致谢

本项目的数据源部分数据于以下优秀的开源项目，感谢这些项目的贡献者：

- **mzky/checklist** - https://github.com/mzky/checklist
- **ssili126/tv** - https://github.com/ssili126/tv
- **hujingguang/ChinaIPTV** - https://github.com/hujingguang/ChinaIPTV
- **kaige-cai/live** - https://github.com/kaige-cai/live
- **BurningC4/Chinese-IPTV** - https://github.com/BurningC4/Chinese-IPTV
- **iptv-org/iptv** - https://iptv-org.github.io
- **ibert.me** - https://m3u.ibert.me

<div align="center">

**🌟 如果这个项目对你有帮助，请给个 Star！**

</div>





