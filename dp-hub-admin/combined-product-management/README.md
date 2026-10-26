# DP Hub Admin · Product Listing Revamp

打开 `index.html` 即可预览整合后的交互页面。`vendor/` 中包含页面运行所需的 React、Ant Design 5、图标和 Day.js 文件。

这是根据 Figma 页面整理的静态原型，包含 Item Pool、Mass Add、Mass Edit 和 Edit Item。列表与批量校验使用示例数据，操作不会连接后台服务。

## Recent changes

- 按 DP Hub Admin 设计稿整理 Item Basic、Linked Hub Product、Bind Partner 和 Clearing Rule 模块。
- 增加核心字段影响开关、发布前提醒，以及发布成功后返回列表页的交互。
- 列表页 Module Status 与编辑页当前模块状态保持对应；首条示例记录为完整状态，其他记录按模块完成情况控制 Publish。
- 编辑页 Clearing Rule 表格使用 Partner、Clearing Type、Supply Price、Valid Period 字段。
