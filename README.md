[English](README.en.md) · **中文**

# COM Tool

> 算 802.3 链路余量，不用装 MATLAB 完整版

把 IEEE 802.3 官方 COM 脚本包成了带界面的工具。丢进 .s4p 通道文件，选好标准和数据率，出 COM / ERL 数值和 PDF 报告。109 个 IEEE 参数可以在界面里直接改，多个 case 并行跑。装 MATLAB Runtime 就行，不需要 MATLAB 完整版。

## 📥 下载

**本仓库不含软件本体。** 这是商业软件，源码不公开，仓库只作说明与下载入口。

### ⬇️ [COM_dist_v1_7_8.zip](http://106.14.76.130/COM/1.7.8/COM_dist_v1_7_8.zip)

| 版本 | 大小 | 发布日期 |
|---|---|---|
| v1.7.8 | 245.9 MB | 2026-08-20 |

下载站首页（全部工具）：http://106.14.76.130

下载站支持断点续传（HTTP Range）。

## 🔑 授权

**商业授权 · 免费试用**

本软件不开源，源码不公开。

**试用 key 在[下载站](http://106.14.76.130)直接要**：页面右下角的咨询窗口里报一下 Host ID，当场就能拿到。也可以找微信公众号「**高速通信杂谈**」的作者。

## ✨ 功能

`IEEE 802.3` · `COM / ERL` · `SCPI 远程` · `VNA 联机`

## 📋 技术规格

| | |
|---|---|
| 授权 | 商业授权；提供免费试用，试用 key 在页面右下角的咨询窗口报 Host ID 即时领取 |
| 计算引擎 | com_ieee8023_4p14p0.m v4.14.0 (MATLAB) |
| 标准支持 | Annex 93A / 162A / 178A · 802.3ck · 802.3dj 草案 |
| 数据率 | 25G / 50G / 100G / 200G per lane（含 1.6T = 8 × 200G） |
| 输入格式 | Touchstone .s4p · 端口序 [1,3,2,4] |
| VNA 集成 | Keysight PNA / PNA-X / ENA · R&S ZNB / ZNA · Anritsu ShockLine / VectorStar |
| 远程控制 | SCPI over TCP/IP :5026 · 247 条命令 |
| 并行 | 1–16 个 case 同时跑 |
| 报告输出 | PDF · CSV · 信道 PNG · JSON 配置 |
| 测试覆盖 | 619 项单元测试 |
| 系统 | Windows 10 / 11 (x64) · 简体中文 / English |

## 📮 联系

微信公众号：**高速通信杂谈**
