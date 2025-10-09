# AIC8800 Linux Driver

AIC8800 WiFi 驱动程序,适用于 Arch Linux 平台。

## 概述

本驱动修复了 AIC8800 芯片在较新 Linux 内核版本下的编译错误问题。

## 测试环境

- **平台**: Arch Linux
- **内核版本**: Linux 6.17.1-arch1-1

## 致谢

本项目参考了以下资源:

- [绿联官方 AX300 驱动](https://www.ugreen.com/)
- [sqlwwx/aic8800](https://github.com/sqlwwx/aic8800) 项目中的修改
- 使用 Claude Code 辅助进行代码修改

## 编译安装

```bash
# 克隆仓库
git clone https://github.com/yourusername/aic8800.git
cd aic8800

# 编译
make

# 安装
sudo make install
```

## 问题修复

本版本主要修复了 AIC8800 驱动在 Linux 6.17.1 内核下的编译错误。

## 许可证

请参考原始驱动的许可证条款。

## 贡献

欢迎提交 Issue 和 Pull Request。
