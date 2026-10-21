# Arknights Operator Picker · 明日方舟干员随机抽选

一个纯前端的明日方舟干员随机抽选小工具，打开 `index.html` 即可使用，无需安装或联网。

## 功能

- 收录 432 名可获得干员（一至六星），默认只抽六星
- 按 **星级**、**职业** 筛选卡池（Ctrl / Shift + 点击只选该项）
- 自定义抽取数量，可选是否允许重复
- **重抽**：整组重新抽取；点卡片左上角的 ↻ 只重抽这一位
- **锁定**：点击卡片锁定，重抽时保留该干员，再点一次解锁
- **删除**：点卡片右上角的 × 删除这位干员，6 秒内可撤销
- **指定干员**：搜索干员名（支持拼音、首字母），设为「必出」（每次必定抽到）或「排除」（永远不会抽到），设置保存在本浏览器；也可点「选择必出 / 选择排除」打开头像面板，按星级、职业筛选后点选
- **小窗展示**：右上角按钮打开一个小窗口，以圆形或方形头像同步显示当前抽出的干员，默认显示 6 位，窗口拉长可显示更多，放不下时循环滚动；可切换横向/竖向、滚动速度、背景（含绿幕），适合用 OBS「窗口采集」放进直播画面
- 每张卡片附精英化立绘，并可跳转到 PRTS 查看详情
- 快捷键：空格 / 回车 抽取

## 使用

本地：下载后双击 `index.html`（`img` 文件夹需与其放在同一目录）。

在线：在仓库 Settings → Pages 中选择从 `main` 分支部署，即可通过 GitHub Pages 访问。

## 作者

紫竽学姐

- Bilibili：[space.bilibili.com/225198974](https://space.bilibili.com/225198974)
- GitHub：[@tonyshtark](https://github.com/tonyshtark)

## 数据来源

- 干员数据：[Kengxxiao/ArknightsGameData](https://github.com/Kengxxiao/ArknightsGameData)（2026-10-16）
- 立绘：[yuanyan3060/ArknightsGameResource](https://github.com/yuanyan3060/ArknightsGameResource)
- 干员详情链接：[PRTS](https://prts.wiki)

## 声明

本项目为非官方粉丝作品。游戏数据与美术素材版权归 上海鹰角网络科技有限公司（Hypergryph）所有，仅供学习与交流使用。
