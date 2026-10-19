# 课序 · 磨课计时

面向教师备课、公开课磨课与授课节奏演练的响应式网页工具。用环节进度、全课进度和正向累计时间感知节奏，记录真实环节用时，并在模拟授课中直接复用。

## 在线访问

| 渠道 | 地址 |
| --- | --- |
| GitHub Pages（主用） | https://cdmccnu.github.io/classroom-timer/ |
| WorkBuddy 托管（备用） | https://classroom-timer-09119.app.workbuddy.host/ |

手机、电脑浏览器均可直接打开。微信内置浏览器如无法打开，请复制链接到系统浏览器。

## 文件说明

| 文件 | 作用 |
| --- | --- |
| `index.html` | 入口跳转页，自动进入首页 |
| `classroom-timer-demo.html` | 首页（选课时、我的课程），含全部界面代码 |
| `classroom-timer-settings.html` | 课程设置入口；与首页代码相同，仅默认打开的视图不同 |
| `使用说明.txt` | 使用说明 |

> 注意：两个 HTML 文件除 `<title>` 和 `data-entry` 外完全相同，均包含六个界面（首页 / 课程设置 / 模式选择 / 磨课计时 / 模拟授课 / 结果复盘）。**修改样式或逻辑时必须同步修改两个文件。** 手机端样式以追加覆盖块写在样式表末尾（标记注释「手机端竖屏优化」）。

## 部署更新

```bash
git add -A && git commit -m "说明" && git push   # GitHub Pages 约 1 分钟自动更新
```

备用链接（WorkBuddy 托管）需在 WorkBuddy 中对本目录重新执行发布，链接地址不变。

设计文档见项目上层目录 `docs/`（01-最终设计文档、02-页面设计说明）。
