# HelloTalk VIP 权益中心 Demo

这是一个 HelloTalk VIP 权益中心的高保真前端交互 Demo，用于展示会员权益量化、权益列表展开、续费升级入口和业务功能跳转等核心体验。

项目是单文件实现，直接上传到 GitHub 后即可通过 GitHub Pages 预览。

## 在线/本地预览

### 直接打开

双击 `index.html`，或用浏览器打开该文件。

### 本地服务

```bash
python3 -m http.server 8080
```

然后访问 <http://localhost:8080>。

## 核心功能

- iPhone 风格移动端容器
- VIP 用户信息与会员有效期展示
- 「本周 / 本月」权益使用周期切换
- 动态刷新倒计时
- 权益使用数据看板：已用次数、累计节省、专属特权数量
- 文字翻译、AI 助手、每天新聊天、附近语伴四个额度卡片
- 推荐权益模块：搜索城市语伴
- 全部 VIP 特权列表
- 默认展示前 6 项权益
- 点击「查看更多权益」展开剩余 13 项
- 点击「收起」恢复折叠状态
- 底部固定操作栏：立即续费、升级 PLUS
- 权益模块和底部按钮跳转到 HelloTalk 官网或 Web 入口
- 键盘辅助滚动：方向键、PageUp、PageDown、Home、End

## 权益列表

默认展示：

- 筛选任意语言帖文
- 直播语聊实时字幕
- 直播语聊无限时长
- 附近语伴
- 搜索城市语伴
- 性别搜索

展开后补充展示：

- 搜索任意语言语伴
- 隐身访问
- 学/教多门语言
- 装扮个人主页
- 装扮聊天背景
- 专属 Q 萌表情
- 每月会员福利
- 查看访客
- 无限次文字翻译
- 每天新聊天
- 身份标识
- 增加曝光机会
- 无广告

## 项目结构

```text
.
├── index.html          # Demo 主页面，包含 HTML、CSS、SVG 图标和 JavaScript
├── README.md           # GitHub 仓库首页说明
├── LICENSE             # MIT License
├── .gitignore          # Git 忽略规则
└── docs/
    └── product-doc.md  # 产品与交互说明文档
```

## 技术说明

- 原生 HTML、CSS、JavaScript
- 不依赖 npm、构建工具或后端服务
- SVG 图标内嵌在页面中
- 当前页面状态仅存在于浏览器会话中
- Demo 中的跳转地址指向 HelloTalk 官网、VIP 页面或 Web 入口

## 上传到 GitHub

在本目录执行：

```bash
git init
git add .
git commit -m "Add HelloTalk VIP demo"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repository>.git
git push -u origin main
```

把 `<your-username>` 和 `<your-repository>` 替换成你的 GitHub 用户名和仓库名。

## 部署到 GitHub Pages

1. 打开 GitHub 仓库的 **Settings**。
2. 进入 **Pages**。
3. 在 **Build and deployment** 中选择 **Deploy from a branch**。
4. 分支选择 `main`，目录选择 `/ (root)`。
5. 点击 **Save**。

部署完成后即可通过 GitHub Pages 地址访问 Demo。

## 免责声明

本项目仅用于产品原型、交互演示和设计评审，不包含真实会员服务、支付能力、用户账号系统或后端接口。

## License

MIT License. See [LICENSE](LICENSE).
