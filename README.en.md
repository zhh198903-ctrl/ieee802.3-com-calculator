**English** · [中文](README.md)

# COM Calculator

> IEEE 802.3 link margin, without a full MATLAB license

An IEEE 802.3 Channel Operating Margin (COM) and ERL calculator with a PyQt6 GUI, SCPI remote control and multi-vendor VNA integration. It wraps the official IEEE 802.3 COM MATLAB script: drop in a .s4p channel file, pick the standard and data rate, and get COM / ERL figures plus a PDF report. 109 IEEE parameters are editable in the GUI and cases run in parallel. Runs on MATLAB Runtime — a full MATLAB license is not required.

## 📥 Download

**This repository does not ship the software itself.** It is a commercial product with closed source; this repo is only a description and download entry.

### ⬇️ [COM_dist_v1_7_8.zip](http://106.14.76.130/COM/1.7.8/COM_dist_v1_7_8.zip)

| Version | Size | Released |
|---|---|---|
| v1.7.8 | 245.9 MB | 2026-08-20 |

All tools: http://106.14.76.130

The download site supports resumable downloads (HTTP Range).

## 🔑 License

**Commercial · free trial**

This software is proprietary; the source code is not published.

**Get a trial key straight from the [download site](http://106.14.76.130).** Send your Host ID in the chat box at the bottom right and you will get one on the spot. You can also reach the author through the WeChat official account **高速通信杂谈** (High-Speed Comms Notes).

## ✨ Features

`IEEE 802.3` · `COM / ERL` · `SCPI remote` · `VNA integration`

## 📋 Specifications

| | |
|---|---|
| License | Commercial; free trial available, send your Host ID in the chat box at the bottom right to get a trial key instantly |
| Compute engine | com_ieee8023_4p14p0.m v4.14.0 (MATLAB) |
| Standards | Annex 93A / 162A / 178A · 802.3ck · 802.3dj draft |
| Data rates | 25G / 50G / 100G / 200G per lane (incl. 1.6T = 8 × 200G) |
| Input format | Touchstone .s4p · port order [1,3,2,4] |
| VNA support | Keysight PNA / PNA-X / ENA · R&S ZNB / ZNA · Anritsu ShockLine / VectorStar |
| Remote control | SCPI over TCP/IP :5026 · 247 commands |
| Parallelism | 1–16 cases at once |
| Report output | PDF · CSV · channel PNG · JSON config |
| Test coverage | 619 unit tests |
| Platform | Windows 10 / 11 (x64) · Simplified Chinese / English |

## 📮 Contact

WeChat official account: **高速通信杂谈** (High-Speed Comms Notes)
