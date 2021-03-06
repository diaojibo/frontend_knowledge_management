### html语义化的理解
1. 去掉或者丢失样式的时候能够让页面呈现出清晰的结构
2. 有利于SEO：和搜索引擎建立良好沟通，有助于爬虫抓取更多的有效信息：爬虫依赖于标签来确定上下文和各个关键字的权重；
3. 方便其他设备解析（如屏幕阅读器、盲人阅读器、移动设备）以意义的方式来渲染网页；
4. 便于团队开发和维护，语义化更具可读性，是下一步吧网页的重要动向，遵循W3C标准的团队都遵循这个标准，可以减少差异化。

### doctype的作用
1. <!DOCTYPE> 声明位于文档中的最前面，处于 <html> 标签之前。告知浏览器以何种模式来渲染文档。

2. 严格模式的排版和 JS 运作模式是  以该浏览器支持的最高标准运行。

3. 在混杂模式中，页面以宽松的向后兼容的方式显示。模拟老式浏览器的行为以防止站点无法工作。

4. DOCTYPE不存在或格式不正确会导致文档以混杂模式呈现。

### 你如何对网站的文件和资源进行优化？
期待的解决方案包括：
- 文件合并
- 文件最小化/文件压缩
- 使用 CDN 托管
- 缓存的使用（多个域名来提供缓存）
- 其他
