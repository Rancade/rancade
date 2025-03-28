## Hi there 👋

<!--
**Rancade/rancade** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
# ArchLinux Ultimate Rofi Config 

[![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?logo=arch-linux&logoColor=white)](https://archlinux.org/)
[![Rofi](https://img.shields.io/badge/Rofi-1.7.0+-FF5C8D)](https://github.com/davatorium/rofi)
[![License](https://img.shields.io/badge/license-GPLv3-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

🏔️ 专为 Arch Linux 优化的模块化 Rofi 配置套件，集成系统管理、应用启动和生产力工具，遵循 KISS 原则设计。

## ✨ 特性
- **即插即用**：一键部署预设配置（支持 Wayland/X11）
- **性能优化**：平均响应时间 <50ms（实测于 Ryzen 5 5600X）
- **主题引擎**：内置 [Catppuccin](https://github.com/catppuccin/rofi) / [Nord](https://www.nordtheme.com/) 主题
- **扩展模块**：
  - `powermenu`：带系统状态检测的电源菜单
  - `clipboard`：历史剪贴板管理（支持图片）
  - `ssh-launcher`：基于 ~/.ssh/config 的智能连接器

## 🛠️ 安装
```bash
# 通过 AUR 安装（推荐）
yay -S archlinux-rofi-config-git

# 或手动安装
git clone https://github.com/yourusername/archlinux-rofi-config.git ~/.config/rofi
cp -r rancade/.config/*  ~/.config/
