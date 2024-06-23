<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Facette

[![集成程度](https://dash.yunohost.org/integration/facette.svg)](https://dash.yunohost.org/appci/app/facette) ![工作状态](https://ci-apps.yunohost.org/ci/badges/facette.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/facette.maintain.svg)

[![使用 YunoHost 安装 Facette](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=facette)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Facette。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Facette is a web application to display time series data from various sources — such as collectd, Graphite, InfluxDB or KairosDB — on graphs, designed to be easy to setup and to use.

**分发版本：** 0.5.1~ynh4

**演示：** <https://play.facette.io/browse/>

## 截图

![Facette 的截图](./doc/screenshots/screenshot.png)

## :red_circle: 负面特征

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## 文档与资源

- 官方应用网站： <https://facette.io/>
- 官方管理文档： <https://docs.facette.io/>
- 上游应用代码库： <https://github.com/facette/facette>
- YunoHost 商店： <https://apps.yunohost.org/app/facette>
- 报告 bug： <https://github.com/YunoHost-Apps/facette_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/facette_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/facette_ynh/tree/testing --debug
或
sudo yunohost app upgrade facette -u https://github.com/YunoHost-Apps/facette_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
