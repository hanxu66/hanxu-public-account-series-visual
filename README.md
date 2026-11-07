# 公众号封面 Skill

版本：0.1.0 独立用户版。按本项任务单独使用，不要求安装合集或作者的经营系统。

## 适用和材料写法

需要：已定标题、模板选择、自己的品牌/署名、需要的封面/双图和输出目录。标题保持原文；模板二只需主题短句与可选品牌，模板一双图需要期数/署名/系列名。素材须有权使用，无头像不借作者头像。材料可粘贴或放自己的工作目录，明确已确认内容与待定事项；缺项只补会改变本次结果的部分。

完整合成练习（不代表真实客户或传播效果）：

> 用 $hanxu-public-account-series-visual：合成练习标题：先问清修改范围，再答应客户。使用模板二，只做封面；品牌填设计练习，方图主题为修改范围／先问再接。不要头像、期数或头图，输出到指定目录。检查实际图片、两个裁切图和缩略主题，不上传微信。

## 安装与使用

取得完整 hanxu-public-account-series-visual 文件夹后交给能读取Skill的AI助手安装，保留配套文件。旧版先备份到技能发现目录外，用户素材与结果单独保存；让助手读回名称、0.1.0版本及实际位置，未识别时按宿主说明恢复。

需要Python 3.9以上、Node.js、Sharp和可显示中文的本机字体。先在技能目录运行 npm install；不附字体，不默认购买服务。

在技能目录运行：

    python3 scripts/render_public_account_series_visual.py --title "先问清修改范围，再答应客户" --title-line "先问清" --title-line "修改范围，再答应客户" --cover-style 2 --cover-only --square-line "修改范围" --square-line "先问再接" --brand-label "设计练习" --delivery-dir "./demo-output"

模板一用 --cover-style 1 --issue 1 --author "自己的名字" --series-name "自己的系列"，要求双图才去掉 --cover-only。1283×383母图包括900×383横向区及383×383方形区，双图头图1080×120；本地裁切检查不等于微信后台真实裁切已通过。

## 安装包与结果

包内包括：SKILL.md、references/发布准备执行标准.md、scripts/render_public_account_series_visual.py、assets/series-template/render-series-visuals.mjs、package.json、agents/openai.yaml及版本/校验文件。SKILL.md和配套方法通常不用修改；示例复制到自己的工作目录后换真实材料，安装依赖不等于素材已授权。

得到：上传母图、两个内部裁切检查图、同版本SVG/配置；按请求交封面或双图。图片成品要打开最终文件检查，返修后重查同版本，不混交旧图。未具备渲染工具时说明真实阶段，不把文案或结构当成图片。

## 费用、资料与限制

模型、渲染及外部工具费用按自己的账号实际承担；不自动购买、发送、上传或发布。使用选择的AI服务处理材料，文件存自己的目录，包内不带作者私人照片、声音或客户资料。

本版实际验证范围见 VALIDATION.md；不保证真人采用、点击率、阅读量或商业效果。模型图的具体工具与产出须逐任务核对。反馈用版本、去敏材料及具体问题，不交凭据或完整私人库。

未设正式开源许可证；公开可下载不自动授予再分发或转售权利。

## 本版验证

见[验证范围与已知限制](VALIDATION.md)。技术和合成演练不代表真实用户采用或经营效果。

## 下载与源码

[GitHub源码](https://github.com/hanxu66/hanxu-public-account-series-visual) · [本版ZIP](https://github.com/hanxu66/hanxu-public-account-series-visual/releases/download/v0.1.0/hanxu-public-account-series-visual-v0.1.0.zip)。下载后解压完整目录，按上面的输入示例开始。

## 练习得到的实际结果

以下结果来自本轮明确合成材料，不是客户效果或外部用户认可。

合成标题“先问清修改范围，再答应客户”的模板二实际封面如下。横向区保留完整题意，方形区以“修改范围／先问再接”呈现缩略主题；已回看两种本地裁切。

![合成练习封面](examples/rendered-cover.png)

本轮未验证模板一完整双图和微信后台真实裁切。
