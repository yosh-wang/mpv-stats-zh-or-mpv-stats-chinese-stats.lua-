# 🤝 Contributing Guide

Thank you for helping to improve this Chinese translation script!

---

## 📝 How to Contribute

### 🐛 Report Issues

If you find translation errors, layout issues, or missing features, please open an **Issue** and include:
- The mpv version you are using
- Steps to reproduce the problem

### ✏️ Submit Translation Improvements

1. **Fork** this repository
2. Make changes to `stats.lua` – look for `_("...")` or modify the translated strings directly
3. Test to ensure there are no syntax errors
4. Open a **Pull Request** and describe your changes

### 🔄 Sync with Upstream

When the official mpv project updates `stats.lua`, check for new strings that need translation. You can compare differences using tools like `diff`.

---

## 📖 Translation Guidelines

- Maintain **terminology consistency** (e.g., 缓存, 解码器, 帧率)
- Keep original English punctuation style where possible
- Technical terms may remain in English (e.g., HDR, VSync) as long as the context is clear

---

## 🛠️ Development Environment

No special environment required. Any text editor works.  
To test, place `stats.lua` in mpv’s `scripts` folder, play any video, and press `i` to verify the translation.

---

## ⚖️ License

All contributions will be licensed under the same **MIT License** as this project.


# 贡献指南

感谢你愿意帮助改进这个中文翻译脚本！

## 如何贡献

1. **报告问题**  
   如果发现翻译错误、界面错位或功能缺失，请在 [Issues](https://github.com/yosh-wang/mpv-stats-zh-or-mpv-stats-chinese-stats.lua/issues) 中提出，并附上 mpv 版本和重现步骤。

2. **提交翻译改进**  
   - Fork 本仓库  
   - 在 `stats.lua` 中修改翻译文本（搜索 `_("...")` 或直接修改字符串）  
   - 测试确保没有语法错误  
   - 发起 Pull Request，并说明修改内容

3. **同步上游更新**  
   当 mpv 官方更新 `stats.lua` 时，请留意是否新增了需要翻译的字符串。你可以通过对比工具（如 `diff`）查看差异。

## 翻译规范
- 保持术语一致性（如“缓存”“解码器”“帧率”）
- 尽量保留原英文标点格式
- 技术术语可保留英文（如 HDR、VSync），但需确保上下文清晰

## 开发环境
无需特殊环境，任意文本编辑器即可。测试时可将 `stats.lua` 放入 mpv 的 `scripts` 目录，用任意视频播放并按下 `i` 验证。

## 许可证
贡献的代码将采用与项目相同的 MIT 许可证。
