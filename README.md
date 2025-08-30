# 30天运动记录本（GitHub Pages 版 + 慢骑｜修正）

此版本修复：
- 输入框“无法填写”的潜在问题（事件从 `change` 改为同时监听 `input`/`change`，即时更新）。
- 生成/解析分享链接改用 `TextEncoder/TextDecoder`，避免 `escape/unescape` 相关兼容性问题。
- 图表增加容错（Chart.js 未加载不会阻断页面）。
- 全局错误捕获并在页面顶部显示红色错误条，便于定位问题。

慢骑按标准 **MET=4.0** 计算：`千卡 = MET × 3.5 × 体重(kg) ÷ 200 × 时长(分钟)`。

MIT License © 2025
