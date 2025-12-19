# dll-maker
"跨平台动态链接库生成工具 | Vue3 + Django | 让小白也能制作DLL/SO | 作者：衡度人生"
"跨平台动态链接库生成工具 | Vue3 + Django | 让小白也能制作DLL/SO | 作者：衡度人生"
<p align="center">
  <a href="https://github.com/hengdulife/dll-maker">
    <img src="https://img.shields.io/github/stars/hengdulife/dll-maker?style=for-the-badge&logo=github&color=blue" alt="GitHub星标">
  </a>
  <a href="https://github.com/hengdulife/dll-maker/fork">
    <img src="https://img.shields.io/github/forks/hengdulife/dll-maker?style=for-the-badge&logo=github&color=green" alt="GitHub复刻">
  </a>
  <a href="https://github.com/hengdulife/dll-maker/issues">
    <img src="https://img.shields.io/github/issues/hengdulife/dll-maker?style=for-the-badge&logo=github&color=yellow" alt="GitHub问题">
  </a>
  <a href="https://github.com/hengdulife/dll-maker/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/hengdulife/dll-maker?style=for-the-badge&logo=opensourceinitiative&color=orange" alt="许可证">
  </a>
  <a href="https://github.com/hengdulife/dll-maker/actions">
    <img src="https://img.shields.io/github/actions/workflow/status/hengdulife/dll-maker/ci.yml?style=for-the-badge&logo=githubactions&color=brightgreen" alt="CI状态">
  </a>
  <a href="https://discord.gg/your-invite-link">
    <img src="https://img.shields.io/discord/your-server-id?style=for-the-badge&logo=discord&color=7289da" alt="Discord">
  </a>
</p>

<h1 align="center">
  🚀 DLL Maker
</h1>

<h3 align="center">
  可视化跨平台动态库生成器 | 打破编程语言壁垒的革命性工具
</h3>

<p align="center">
  <strong>"让编程语言不再设限，让每个人都能创造价值"</strong>
</p>

<p align="center">
  <a href="https://www.hengdu.life/dll/">🌐 在线演示</a> •
  <a href="#vision">🔮 项目愿景</a> •
  <a href="#features">✨ 核心功能</a> •
  <a href="#quick-start">🚀 快速开始</a> •
  <a href="#contribute">🤝 贡献指南</a> •
  <a href="#sponsor">💖 支持项目</a> •
  <a href="#license">📄 许可证</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/hengdulife/dll-maker/main/public/images/screenshot.png" alt="DLL Maker 界面截图" width="800">
  <br>
  <em>可视化DLL配置界面 - 拖拽式函数定义，一键跨平台编译</em>
</p>

## 🌟 在线演示

体验完整功能：**[https://www.hengdu.life/dll/](https://www.hengdu.life/dll/)**

### 🎯 演示功能包括：
- ✅ 可视化函数配置（拖拽式参数定义）
- ✅ 多语言编译器选择（C++、Rust、Go、Python、Zig）
- ✅ 实时代码生成与预览
- ✅ 跨平台编译（Windows .dll / Linux .so / macOS .dylib）
- ✅ 编译状态实时监控
- ✅ 安全沙箱隔离编译

## 🔮 <span id="vision">项目愿景</span>
🤝 <span id="contribute">贡献指南</span>
我们热烈欢迎所有形式的贡献！无论你是开发者、设计师、文档作者还是普通用户。
### 我们正在解决的问题
1. **跨语言调用难题**：不同编程语言间的函数调用复杂且易错
2. **编译门槛过高**：DLL/SO编译需要专业知识，新手难以入门
3. **平台差异巨大**：Windows、Linux、macOS编译环境差异大
4. **代码复用困难**：现有代码难以跨语言、跨平台复用

### 我们的解决方案
- **可视化配置**：无需编写代码，拖拽式完成函数定义
- **智能代码生成**：自动生成C++/Rust/Go/Python包装层
- **云编译服务**：浏览器中完成一切，无需本地环境
- **多平台支持**：一键生成各平台动态库

### 🚀 未来展望：DLL制作智能体
我们相信：**未来的编程不是单一语言竞争，而是多语言协作共赢的时代**

**阶段规划**：
- **短期**（0-6个月）：基础可视化编辑器 + 多语言支持
- **中期**（6-18个月）：AI代码生成助手 + 企业级API服务
- **长期**（18-36个月）：编程语言融合平台 + 智能DLL生成器

## ✨ <span id="features">核心功能</span>

### 🎯 **可视化编辑器**
- 拖拽式函数参数配置
- 实时代码预览
- 模板库与代码片段
- 可视化调用关系图

### ⚡ **多语言支持**
- **系统语言**：C++、Rust、Go、Zig（高性能编译）
- **脚本语言**：Python、JavaScript、Lua（快速原型）
- **目标语言**：支持生成调用各种语言的动态库

### 🌐 **跨平台编译**
- **Windows**：生成 `.dll` 文件（x86/x64）
- **Linux**：生成 `.so` 文件（多种架构）
- **macOS**：生成 `.dylib` 文件
- **交叉编译**：在单一平台编译多平台库

### 🔒 **企业级特性**
- 安全沙箱隔离编译
- 代码审计与安全检查
- 多租户支持
- API访问控制与限流
- 编译历史与版本管理

### 🏗️ **现代化架构**
- **前端**：Vue 3 + TypeScript + Vite
- **后端**：Django + Go + Rust 微服务架构
- **数据库**：PostgreSQL + Redis
- **部署**：Docker + Kubernetes
- **监控**：Prometheus + Grafana
# 💖 资助与支持

## 🌟 为什么需要资助？
DLL Maker是一个有远大愿景的开源项目，旨在**打破编程语言壁垒**。您的资助将直接帮助：

### 🚀 技术研发
- 多语言编译器集成
- AI代码生成技术
- 高并发云编译服务

### 🌍 社区建设
- 多语言文档翻译
- 教程视频制作
- 社区活动举办

### 📚 生态完善
- 插件系统开发
- API市场建设
- 企业级功能开发

## 💰 资助方式

### 个人支持者
| 等级 | 月捐 | 权益 |
|------|------|------|
| ☕️ 咖啡支持者 | ¥15 | 名字出现在感谢列表 |
| 🌟 星星支持者 | ¥30 | 名字+链接，优先技术支持 |
| 🚀 火箭支持者 | ¥99 | 专属徽章，功能优先权 |

### 企业赞助商
| 等级 | 月捐 | 权益 |
|------|------|------|
| 🥈 银牌赞助 | ¥500 | 企业Logo展示，技术支持 |
| 🥇 金牌赞助 | ¥2000 | 首页展示，定制功能 |
| 💎 钻石赞助 | ¥5000 | 专属服务，联合品牌 |

### 一次性捐赠
- 支付宝/微信扫码捐赠
- 企业大额赞助（单独联系）

## 🤝 企业合作
### 技术合作
- 编译器技术合作
- 云服务资源支持
- 联合研发项目

### 生态合作
- 插件开发合作
- 教育培训合作
- 市场推广合作
- 
### 为什么需要支持？
我们正在构建一个可能需要3-5年完成的大项目。您的支持将：
- 支付服务器和编译集群费用
- 支持全职开发者的生活
- 制作高质量的教程和文档
- 举办技术分享和社区活动
## 📞 联系资助
- **GitHub Sponsors**: 审核通过后开启
### 资金支持（直接捐赠）：
- **支付宝/微信**：扫描下方二维码
**支付宝**：
<img src="https://hengdu.life/zhifubao.jpg" alt="支付宝收款码" width="200" height="200">

**微信支付**：
<img src="https://hengdu.life/shoukuan.jpg" alt="微信收款码" width="200" height="200">
- **企业合作**: hengdulife@163.com
- **技术咨询**: 微信 hengdulife

## 📊 资金使用透明
每季度发布资金使用报告：
1. 研发投入（占比60%）
2. 社区建设（占比20%）
3. 基础设施（占比15%）
4. 运营推广（占比5%）

## 资金使用承诺
- 服务器费用（编译集群）
- 开发者激励
- 文档和教程制作
- 社区活动组织

## 🚀 <span id="quick-start">快速开始</span>

### 方式一：Docker一键部署（推荐）
```bash
# 1. 克隆项目
git clone https://github.com/hengdulife/dll-maker.git
cd dll-maker

# 2. 启动所有服务
docker-compose up -d

# 3. 访问应用
# 前端界面: http://localhost:3000
# API文档: http://localhost:8000/api/docs
# 监控面板: http://localhost:9090
