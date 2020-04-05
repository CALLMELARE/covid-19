# 新型冠状病毒 (COVID-19) 仪表盘

📈 [**新型冠状病毒 (COVID-19) 仪表盘**](https://trekhleb.github.io/covid-19/) 以曲线图的形式展示每个国家/地区的疫情动态

## 缘由

开发此项目是为了补充完善[JHU Dashboard](https://www.arcgis.com/apps/ops仪表盘/index.html#/bda7594740fd40299423467b48e9ecf6) (约翰霍普金斯大学系统科学与工程中心开发) ，实现了展示（确诊/康复/死亡）病例的功能。

### 主要功能

仪表板仍然处于开发阶段，但它实现了显示全球和各个国家/地区数据图表的基本功能。

## 数据源和技术栈

此项目以[仓库：COVID-19](https://github.com/CSSEGISandData/COVID-19)作为数据源.

为保证前端代码尽可能简洁，项目使用了纯[React.js](https://reactjs.org/) (不包含 `JSX` 文件及 `CreateReactApp` 脚手架)。绘制图表使用[Charts.js](https://www.chartjs.org/)实现。

## 使用条款

此 [仓库](https://github.com/trekhleb/covid-19) 以及 [仪表盘](https://trekhleb.github.io/covid-19/) 基于 [仓库：COVID-19](https://github.com/CSSEGISandData/COVID-19) 的公开数据。 本网站的作者特此声明否认与 [此网站](https://trekhleb.github.io/covid-19/)有关的任何和所有陈述和保证，包括准确性、使用性和可商业性。严禁依据 [此网站](https://trekhleb.github.io/covid-19/) 此网站作为提供医学建议的依据或商用。