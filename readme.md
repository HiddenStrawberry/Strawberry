# Strawberry

致力于构建中国特色社会主义的基于Scrapy的特色版爬虫Framework

## Strawberry 的目标

### 分布式

- 实现爬虫云上工作，将所有网络请求中转至多台云主机分发以实现快速的分布式抓取。
- 便捷的一键部署，直接运行Server端程序即可部署至一台机器。结合自定义镜像与各云平台API可实现快速的机器增减

### 代理池
- 直接集成付费代理与免费代理，并可提供一键转发功能。
- 支持SSH-Tunnel、HTTP/HTTPS代理等多种代理方式

### 支持JS渲染
- 云端集成Splash、puppeteer等多种抓取方式，可直接通过客户端yield Request()指定客户端参数即可，无需额外设置。

### 众包解析
- 支持Python代码在线编译，可通过Panel直接在线上编辑Python代码并运行。
- 支持选择爬虫项目直接测试，大大降低人工成本。

### 成本可见
- 只需设定各组件（机器、代理、网络等参数）单位时间成本，即可快速核算单一项目所消耗的爬虫成本。

### 非侵入
- 无需大量修改原有Scrapy项目代码就可将Strawberry低侵入地挂载到原有项目中，直接将爬虫请求转移到云上。

### 用户友好
- Web Panel管理，可直接预览所爬取页面。

### 失效报警、数据质量控制
- 当单一项目出现大量报错可灵活接入多种报警方式实现实时报警。

### 在线抓取测试
- 当Scrapy某个请求出现错误时，可直接线上测试单一请求返回情况，以快速完成调试。

## Strawberry的开发进度

## Contact me

### Wechat:hiddenstrawberry
