# ZhangxixiLauncher

[![Kotlin Version](https://img.shields.io/badge/Kotlin-1.9.20-blue.svg)](https://kotlinlang.org)
[![License](https://img.shields.io/badge/License-MPL%202.0-orange.svg)](https://opensource.org/licenses/MPL-2.0)

非官方的Minecraft Java版安卓启动器（🚧 实验性项目）

## 许可协议

本项目采用 **Mozilla Public License 2.0** 授权，核心条款包括：

- 允许自由使用、修改和分发
- **修改后的源代码必须保持MPL-2.0协议**
- 修改文件必须包含变更说明
- 专利授权不可撤销

完整协议内容请查看 [LICENSE](LICENSE) 文件

## 开发者义务

根据MPL-2.0要求，如果您修改代码并分发，必须：

1. 在文件头保留原始版权声明
2. 新增文件需包含MPL-2.0声明
3. 在显著位置说明修改内容


非官方的Minecraft Java版安卓启动器，支持基础游戏启动和版本管理



## 功能特性

✅ 正在实现功能  
- 多版本选择（1.12.2/1.16.5/1.18.2）
- 自定义内存分配
- 基础账户配置
- 游戏日志输出
- 安全存储访问

🛠 计划功能  
- [ ] 游戏文件自动下载
- [ ] 正版账户登录
- [ ] Forge/Fabric支持
- [ ] 控制器映射

## 运行要求

- Android 7.0+ (API 24)
- 至少2GB可用存储空间
- ARMv8/AArch64设备（推荐骁龙835以上）
- 已安装OpenJDK 17（或集成JRE环境）

## 安装指南

### 直接安装（APK）
1. 从 [Releases](https://github.com/zhangxixi2012/ZhangxixiLauncher/releases) 下载最新APK
2. 允许安装未知来源应用
3. 安装后授予存储权限

### 从源码构建
```bash
git clone https://github.com/zhangxixi2012/ZhangxixiLauncher.git
cd ZhangxixiLauncher

# 使用 Android Studio 打开项目
# 配置 local.properties 文件
# 构建 -> 生成 Signed Bundle/APK
