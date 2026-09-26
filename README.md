# 藏见 CANGJIAN · Case Study

围绕收藏整理、偏好理解与选择支持的 AI 产品设计案例。作者：**Ruiying (Rain) Liu**。

- [在线案例](https://rainliu0309.github.io/cangjian-case-study/)
- [可运行产品原型](https://cangjian-ai-design.onrender.com/)
- [产品原型源码](https://github.com/rainliu0309/cangjian-ai-design)

## 内容

1. 项目概述：问题定义、目标用户与场景、价值主张。
2. 方案取舍：产品范围、痛点拆解、产品方案与关键取舍。
3. AI 交互流程：用户操作、AI 处理与保存回看的协作过程。
4. 用户流程：信息架构、任务流程与嵌入式可运行原型。
5. 价值验证：测试计划、验收目标与对照设计。
6. 落地迭代：体验风险、AI 边界设计、AI Coding 协作与迭代记录。

案例中的测试目标属于待验证计划，不代表已完成的用户测试结果。

## 本地预览

这是原生 HTML、CSS 和 JavaScript 静态站点，无需安装依赖或构建。

```sh
git clone https://github.com/rainliu0309/cangjian-case-study.git
cd cangjian-case-study
python3 -m http.server 8000 --bind 127.0.0.1
```

打开 `http://127.0.0.1:8000/`。章节深链接使用 `#cangjian-chapter-01` 至 `#cangjian-chapter-06`。

## 维护与部署

- `index.html`：六章内容与页面结构。
- `assets/cangjian.css`：布局、响应式及明暗主题样式。
- `assets/cangjian.js`：章节导航与交互逻辑。
- `assets/case-study.js`、`assets/fluid-cursor.js`：页面效果与指针交互。
- `media/`：品牌标识及概念视频。

GitHub Pages 从 `main` 分支根目录发布，推送后自动更新。页面右上角可切换明暗主题，偏好保存在当前浏览器。

第4章嵌入独立部署的线上产品，加载依赖其服务及网络状态；本仓库维护案例页面，不包含产品后端或模型密钥。
