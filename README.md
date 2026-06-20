# 🚀 本项目固件仅作为作者本人自用，若有需要请点击下方进入原作者主页

OpenWrt / AX6600 / IPQ6010 / JDCloud RE-CS-02 / NSS / Router Firmware / Cloud Build
> 基于 OpenWrt / ImmortalWrt 的定制固件，适配 JDCloud RE-CS-02（京东云雅典娜 AX6600），集成 NSS 硬件加速优化与 GitHub Actions 自动云编译

[👉 进入原作者项目主页](https://github.com/VIKINGYFY/OpenWRT-CI)
---

## 📋 固件说明

| 说明 | 详情 |
|------|------|
| **编译时间** | 显示的时间为编译开始时间，用于对应上游源码版本 |
| **硬件平台** | 基于 QUALCOMMAX（IPQ6010）架构 |
---

## 📂 项目结构

| 目录/文件 | 用途 | 说明 |
|----------|------|------|
| `.github/workflows/` | CI/CD 自动编译 | 定义 GitHub Actions 工作流，实现云端自动构建 |
| `scripts/` | 编译脚本 | 包含编译前置处理、自定义配置等辅助脚本 |
| `config/` | 编译配置 | 存放 ImmortalWrt 配置文件 |

---

## 🔗 上游源码与依赖

### 📦 OpenWrt 源码仓库

| 版本 | 仓库地址 | 说明 |
|------|---------|------|
| **官方版** | [immortalwrt/immortalwrt](https://github.com/immortalwrt/immortalwrt.git) | ImmortalWrt 官方仓库 |
| **高通专用版** | [VIKINGYFY/immortalwrt](https://github.com/VIKINGYFY/immortalwrt.git) | IPQ 平台优化版本 |

---

## ⚠️ 免责声明

刷机有风险，操作需谨慎。

本项目固件仅供作者本人自定义使用，所有插件均在Releases详情中写出，若要刷写请确认设备型号匹配并提前备份数据。
因刷机造成的设备损坏或数据丢失，作者不承担任何责任。