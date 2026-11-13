# 素材与许可说明（NOTICE）

本目录（及 `app/web/static/img/`）内用于「竞品猫 PriceCat」落地页与产品的全部图形素材，均为**本项目原创手工绘制的矢量 SVG**，未直接复制任何第三方图形文件。以下逐项说明来源与许可。

## 1. 原创矢量图形（本项目自制，可自由商用）

以下文件均为本次从零手工绘制的 SVG 矢量图，著作权归本项目所有，可随产品自由使用：

| 文件 | 说明 |
|---|---|
| `app/web/static/img/logo.svg` | 主 Logo（图形 + 字标，浅色背景版） |
| `app/web/static/img/logo-light.svg` | 主 Logo 深色背景版（白字） |
| `app/web/static/img/logo-mark.svg` | 仅图形标（猫耳 + 雷达/十字眼），`currentColor` 可继承颜色 |
| `app/web/static/img/favicon.svg` | favicon（teal 圆角底 + 白色图形标） |
| `app/web/static/img/empty-state.svg` | 空状态插画（猫 + 放大镜，扁平风） |
| `app/web/static/img/icon-*.svg` | 功能/通道线性图标（link / clock / send / trending-down / chart / shield / bell） |
| `landing/assets/push-sample.svg` | 多通道推送卡片样例（企微/钉钉/飞书/Server酱） |
| `landing/assets/console-mock.svg` | 移动端控制台样例 |
| `landing/assets/og-image.svg` | 社交分享图底图 |

由上述 SVG 栅格化导出的 PNG（`logo-192.png`、`logo-512.png`、`favicon-32.png`、`app-icon.png`、`og-image.png`）版权同源，可自由使用。

## 2. 风格参考（仅借鉴风格，未拷贝文件，无需署名）

- **unDraw / Storyset 扁平插画风格**：`empty-state.svg` 在视觉语言上借鉴了 unDraw（MIT License）与 Storyset 的扁平几何风格，但**未使用其任何原始矢量文件**，所有形状均为重新绘制，配色改为本项目 teal 品牌色。因此不构成衍生作品，无需署名；如对外发布仍建议保留本说明以表明风格出处。
- **Tabler Icons / Iconify 线性图标风格**：`icon-*.svg` 借鉴了 Tabler Icons（MIT License，https://tabler.io/icons）的 24×24、2px 描边、圆角端点线性规范，但路径为重新手写，未拷贝其 SVG 代码。

> 说明：以上两者均为 MIT 许可，即便完全拷贝也可商用并需保留版权声明；本项目采取「重新绘制」方式，进一步规避侵权风险。

## 3. 字体

落地页与图形中文字使用**系统字体栈**（-apple-system / PingFang SC / Microsoft YaHei / Segoe UI 等），未嵌入任何 webfont，无字体许可问题。

## 4. 外部资源

落地页 `landing/index.html` 为**纯离线静态页**：
- 不引用任何 CDN、外部 CSS/JS/字体/图片；
- 所有资源均为相对路径（`assets/...`）；
- 双击 `file://` 可直接打开，无需联网、无 fetch 请求。

## 5. 商标与第三方名称

页面中出现的「拼多多」「抖店」「鱼多多」「YINKTECH」等名称仅为对标说明与平台指代，归各自权利人所有；定价数据来自其官网公开标价（见 `调研文档.md`）。
