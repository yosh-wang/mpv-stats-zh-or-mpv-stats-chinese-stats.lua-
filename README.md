# mpv 中文统计信息脚本 (stats.lua)

本仓库是 mpv 播放器内置统计脚本 `stats.lua` 的中文翻译版本。  
原版文件：[mpv-player/mpv/player/lua/stats.lua](https://github.com/mpv-player/mpv/blob/master/player/lua/stats.lua)

## 特性
- 完全中文化的统计信息显示
- 支持所有原版功能（性能数据、视频/音频信息、帧率、缓存等）
- 兼容 mpv 所有版本（v0.35+）

## 安装使用

### 1. 禁用原版英文脚本
在 mpv 配置文件 `mpv.conf` 中添加：
load-stats-overlay=no



### 2. 放置脚本
将 `stats.lua` 放入 mpv 的脚本目录：
- **便携版**：`mpv.exe` 同级目录下 `portable_config/scripts/`
- **安装版**：`%APPDATA%\mpv\scripts\`

### 3. 快捷键
| 按键 | 功能 |
|------|------|
| `i` | 临时显示统计信息 |
| `I` (大写) | 持续显示统计信息 |
| `Shift+I` | 同 `I` |
| `1`~`5` / `0` | 切换不同信息页面 |

## 文件说明
- `stats.lua` — 主脚本（中文版）
- `LICENSE` — MIT 许可证
- `README.md` — 本文件
- `CHANGELOG.md` — 更新日志

## 贡献
欢迎提交翻译改进或功能增强。详见 [CONTRIBUTING.md](CONTRIBUTING.md)

## 许可证
本项目采用 MIT 许可证。原 mpv 项目采用 GPLv2+，本翻译脚本作为独立作品不继承其许可证。