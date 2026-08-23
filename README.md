<p align="center">
  <img src="./assets/banner.svg" alt="XXD Panel 022 项目横幅" width="1200">
</p>

<div align="center">

# 🦁 XXD Panel 022

### 用流畅线稿与唯一彩色点，让照片主体从纯黑矩形中越界而出

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Four Modes](https://img.shields.io/badge/Modes-4-d75d32?style=flat-square)](#四种输出共享同一种黑色域越界逻辑)
[![Raster Output](https://img.shields.io/badge/Output-PNG-3c6f67?style=flat-square)](#边界与信任)

<strong>简体中文</strong> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

> 纯黑矩形 · 主体大部入场 · 一个特征越界 · 流畅稳定线 · 唯一单点彩色

XXD Panel 022 是一个面向 Codex 与兼容 Agent 的图像生成 Skill。它先从照片中锁定身份、轮廓、姿态、动作、功能与关系，再用一个横向或纵向的纯黑矩形建立主场：主体的大部分留在黑色域内，只有一个最具识别度的结构自然穿出边界。

主体以简洁、顺滑、稳定且带自然手绘弹性的黑线出现；白色负形承担主要识别，极少灰面只用于辅助结构。再从原图提取一个代表色，只点亮一个最关键的小局部。大面积白纸、不对称位置、局部裁切与小型编辑文字，让越界动作轻巧、幽默而克制。

## 为什么需要 022

普通“黑色块＋线稿”很容易退化成主体贴在矩形上的海报模板：边界没有事件，线条过于顺滑，主体、黑色域和文字彼此无关。

022 的顺序完全相反：

```text
锁定源图事实 → 选择横向或纵向纯黑矩形 → 让主体大部分进入黑色域 → 只让一个决定性特征越界 → 用流畅、稳定、有弹性的黑线与白色负形重建主体 → 从原图提取一个代表色并只点亮一个小局部 → 让微文字沿边界、负形或越界方向完成构图
```

如果换成一张无关照片，矩形方向、主体位置、越界特征、轮廓、白色负形与文字关系仍然成立，这张图就不属于 022。

## 022 的视觉契约

- **一个纯黑主场：** 只用一个横向或纵向纯黑矩形，不拆成多个色块，也不把它当装饰背景。
- **主体大部入场：** 至少三个源图专属线索保住身份、轮廓、姿态、动作、功能与关系；主体的大部分必须位于矩形内。
- **恰好一个越界特征：** 头顶、枝条、屋顶、肢体或物件边缘等最具识别度的结构自然穿出、长出或突破边界。
- **流畅稳定手绘线：** 黑线简洁、顺滑、稳定并带自然弹性；允许轻微手工变化，但拒绝抖动、重复描边、毛躁噪点和机械等粗矢量。
- **白负形＋微灰面：** 白色负形建立识别，灰色只占极小面积；主体绝不能变成纯黑剪影。
- **恰好一个彩色点：** 从原图提取一个代表性亮点色，适度提纯后只落在一个最关键、最有叙事性的小局部；禁止第二种颜色、大片彩色或全局染色。
- **不对称与局部裁切：** 大面积白纸和偏置构图制造张力，辅助线面保持极少，不发展成复杂场景。
- **编辑文字参与越界：** 一个短标题＋1–3 组微文字进入矩形边缘、白色负形、越界方向或主体轮廓，而不是另贴标签。

## 样张 · 来自 X

> [小小东（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2090277026066546845) · 2026-08-20<br>
> GPT2 x 越界 x 黑白 x 局部彩色 x 美学提示词 x VOL.022

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090277026066546845"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 022 样张 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090277026066546845"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 022 样张 2"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2090277026066546845">查看原推文与完整提示词 →</a></p>

这些样张用于展示 022 的美学动机，不会把样张中的主体、构图、配色、文案或旧画幅变成生成参考或当前默认值。

## 四种输出共享同一种黑色域越界逻辑

四种模式支持单选或多选。可回复 `1`、`1+3`、`1、2、4` 或 `全部`；Skill 去重后按 1→4 执行。每种模式独立输出并进入独立子文件夹，不制作总图；`全部` 每张原图得到 7 个 PNG（前三种各 1 张＋壁纸 4 张）。尺寸可在同一回复中按模式标注，未标注普通模式按源图适配；文案默认跨所选模式共用，也可按模式单独指定。

| 模式 | 尺寸逻辑 | 成品 |
| --- | --- | --- |
| `top-bottom` | 源图自适应 | 上方完整原图，下方 022 黑色域越界线稿设计；两块都保持原图完整尺寸，严格 50/50 |
| `left-right` | 源图自适应 | 左侧完整原图，右侧 022 黑色域越界线稿设计；两块都保持原图完整尺寸，严格 50/50 |
| `design-only` | 源图自适应 | 只显示变化设计，不显示原照片；沿用原图比例和尺寸 |
| `wallpaper-pack` | 四种设备尺寸 | 分别输出手机、iPad、电脑、儿童手表四张 PNG |

用户精确尺寸 > 指定比例或用途 > 普通模式源图自适应。原始 `022.md` 里的 3:4 只是一开始的创作画幅，不会被写成当前 Skill 的静默默认值。

双联模式的摄影区域保持真实，只允许克制调色和必要的环境扩展。纯设计版与壁纸仍以照片为事实依据，但不显示原片。

### 四端壁纸：连贯或独立

壁纸没有静默尺寸默认。可选择常用预设——手机 `1440×3200`、iPad `2048×2732`、电脑 `3840×2160`、儿童手表 `1024×1024`——也可逐设备自定义。

- **连贯套装（推荐）：** 先生成并验收 iPad 定调图，另外三张都直接参考原照片＋同一张定调图，分别为设备重新构图。
- **四张独立：** 每张只参考原照片，可以分别探索不同的矩形方向、主体入场比例、越界特征、流畅线节奏、单点彩色与文字关系。

连贯不等于裁切。四张壁纸始终分别生成、分别构图、分别验收，也不会按 iPad→手机→电脑→手表顺序垫图造成漂移。

## 文字必须成为黑色域与越界动作的一部分

正式生图前，先选择自动文案、自定义文案或无文字。有文字时还要指定目标语言或地区。

自动文案从源图可见或有依据的情绪、动作、关系、时间或微小故事中提炼一个简短标题。它可以温软、克制、安静、幽默或孤独，但必须与当前画面高度绑定。

再按需增加一至两组极小辅助文字、金句式短句、编号或章节号。日期、地点、出处与编号必须由用户提供或可靠确认，绝不会为了显得高级而伪造。文案仍需通过换图测试。

用户提供最终成稿时逐字保留。用户提供的是方向或可编辑草稿时，才会在保留受众、目的、必备词、语气和潜台词的前提下专业深化。

语言遵循目标受众，而不是用户下指令时使用的语言：

```text
目标市场或受众 > 指定成品语言 > 用户方向语言；都不明确时生图前询问
```

日本版使用自然日语，韩国受众使用自然韩语与正确空格，英国版使用英式英语，阿拉伯语版默认使用自然的现代标准阿拉伯语和真正的从右到左排版。字体会在当地文字系统中寻找克制的艺术出版物小字与流畅手绘线相匹配的自然等价物，不会把拉丁排版规则生硬套过去。

## 精确拼版交给代码，作品交给图像生成

图像模型负责源图绑定的黑色域、主体入场、恰好一个越界特征、流畅稳定手绘线、白色负形、微灰面、唯一单点彩色和编辑文字。`scripts/compose_panel.py` 只负责画布规划、精确 50/50 位图拼合、最终尺寸和审计，不会用程序绘图伪造成品。

```bash
python3 scripts/compose_panel.py --plan --layout top-bottom --source photo.png
python3 scripts/compose_panel.py --plan --layout left-right --size 2560x1440
python3 scripts/compose_panel.py --audit result.png --layout design-only --size 2048x2048
```

精确上下画布的总高度必须为偶数，精确左右画布的总宽度必须为偶数。Skill 不会静默修改用户指定的像素。

## 开始使用

```bash
git clone https://github.com/nevertoday/xxd-panel-022.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-022" ~/.codex/skills/xxd-panel-022
```

Claude Code 用户可以把同一目录链接到 `~/.claude/skills/xxd-panel-022`。安装后重新启动 Agent 会话。

```text
$xxd-panel-022
把这张照片做成左右双联，文案由你根据照片内涵创作，使用自然韩语。
```

只上传照片也可以调用。Skill 会先用分行编号菜单询问一个或多个模式，再询问文字设置；选择壁纸时还会确认连贯或独立以及设备尺寸。

完整规范：

- [Skill 工作流](SKILL.md)
- [中文完整提示词](references/xxd-panel-022-prompt.zh-CN.md)
- [英文完整提示词](references/xxd-panel-022-prompt.en.md)
- [原始风格提示词](references/022-source.md)

## 边界与信任

- 每张照片只在自己的任务中使用，不借用其他输入、旧成品或样张里的主体、颜色、文案和构图。
- 每次调用都创建新的任务子文件夹；相同原图和参数也要重新生成，旧成品不能冒充当前任务。
- 最终交付为 PNG 位图，不是 SVG、HTML、Canvas 或程序绘图替代品。
- 已配置位图桥接只返回脱敏状态，不显示供应商、端点、请求头、凭据、提示词或服务器响应正文。
- 每个所选普通模式各返回一张；若选择 `wallpaper-pack`，再返回四张独立壁纸。选择 `全部` 时每张原图共返回 7 个 PNG，分处四个同级模式文件夹，绝不生成拼贴总览。

本地拼版需要 Python 3 和 Pillow。安全位图桥接使用 Python 3.11+ 的 `tomllib`。图像生成仍需要主机 Agent 的内置位图能力或已经配置好的兼容位图路径。

## 项目结构

```text
xxd-panel-022/
├── SKILL.md
├── README.md / README.en.md / README.ja.md / README.ko.md / README.ar.md
├── agents/openai.yaml
├── assets/
│   ├── banner.svg
│   └── examples/（未来本地样张占位）
├── scripts/
│   ├── compose_panel.py
│   └── configured_imagegen.py
└── references/
    ├── xxd-panel-022-prompt.zh-CN.md
    ├── xxd-panel-022-prompt.en.md
    └── 022-source.md
```

## 关于 XXD

XXD 是小小东的品牌名称缩写。项目由 [@xiaoxiaodong01](https://x.com/xiaoxiaodong01) 创建并维护。

## 服务与会员

### 深度咨询 · 299 元/小时

Skills 使用的一对一深度咨询按 299 元/小时收费。请通过下方微信二维码联系小小东预约。

### 小小东 Skills 用户交流群 · 入群 99 元

一次支付 99 元加入用户交流群，用于交流工作流、作品与互助；不包含按小时的一对一深度咨询。扫码后请备注“Skills 用户交流群”。

### 知识星球＋成员提示词库 · 699 元/年

[知识星球](https://wx.zsxq.com/group/15554814142882)与[小小东成员提示词库](https://vip.xiaoxiaodong.ai/)是同一份会员权益：**一次年费同时开通两边，无需重复付费。**

1. 在[知识星球](https://wx.zsxq.com/group/15554814142882)开通后，微信联系小小东领取成员提示词库兑换码。
2. 在[成员提示词库](https://vip.xiaoxiaodong.ai/)自助开通后，微信联系小小东邀请进入知识星球。

<p align="center">
  <a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="小小东付费服务微信二维码" width="320"></a>
</p>

<div align="center">

**让主体只用一个特征越界，也只让一个颜色被点亮。**

</div>

---

<div align="center">
  <h2>☕ 为开源项目赞助算力</h2>
  <p>如果这个项目为你节省了时间，可以通过微信或支付宝赞助后续测试与生成算力。</p>
  <table>
    <tr>
      <td align="center" width="240">
        <a href="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png" alt="小小东微信算力赞助二维码" width="180"></a><br>
        <strong>微信算力赞助</strong>
      </td>
      <td align="center" width="240">
        <a href="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png" alt="小小东支付宝算力赞助二维码" width="180"></a><br>
        <strong>支付宝算力赞助</strong>
      </td>
    </tr>
  </table>
  <p><sub>赞助完全自愿，不会改变这个开源项目的使用权限。</sub></p>
</div>
