---
title: "RealDiffusion：面向多角色绘本生成的物理先验注意力方法"

# 作者列表
authors:
  - Qi Zhao
  - Jun Chen 陈军
  - Ivor W Tsang
  - Guang Dai

# 作者备注（*为通讯作者）
author_notes:
- ""
- "通讯作者"

date: '2026-02-27'
doi: ''

# 网页发布日期（非论文录用日期）
publishingDate: '2026-02-27'

# 论文分类：会议论文
publication_types: ['paper-conference']

# 会议全称与简称
publication: IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2026), pp.4698-4707
publication_short: CVPR 2026

# 中文摘要
abstract: 当前扩散模型单图生成效果优异，但在连续多帧绘本动画生成中难以平衡角色一致性与叙事动态性，普遍出现人物特征错乱、身份互换、动作僵化、剧情断裂等问题。本文提出免训练框架RealDiffusion，在预训练扩散模型推理阶段嵌入物理感知注意力模块。依托热传导耗散先验平滑帧内人物特征，抑制角色跨帧漂移；搭配区域可控随机扰动保留画面动作变化，借助动态掩码约束物理正则仅作用于角色区域。框架内置全局平衡参数α，可灵活调节一致性与动态效果，全程无需微调模型权重，无缝对接SDXL等预训练生成模型。在大量多角色故事prompt上开展对比实验，本文方法在角色身份保留、故事流畅度等指标全面优于现有SOTA方案，可落地自闭症儿童康复动画、特殊教育社交绘本生成场景，项目代码已开源。

# 精简小结
summary: RealDiffusion是一款免训练多角色序列生成框架，融合热传导物理先验与区域随机扰动，通过可调参数平衡角色一致性与画面动态，多角色绘本生成效果领先主流算法。

# 标签
tags: [CVPR2026,扩散模型,物理先验注意力,多角色生成,故事绘本,自闭症康复,免训练生成]

# 是否首页精选
featured: true

# 各类链接
url_pdf: 'https://arxiv.org/abs/2605.11927'
url_code: 'https://github.com/ShmilyQiCN/RealDiffusion'
url_dataset: ''
url_poster: ''
url_project: 'https://github.com/ShmilyQiCN/RealDiffusion'
url_slides: ''
url_source: ''
url_video: ''

# 封面配图说明
image:
  caption: '效果图：多风格多角色故事绘本生成样例（美式漫画、吉卜力动画、中式国风）'
  focal_point: ''
  preview_only: false

# 关联项目
projects:
  - example

# 关联幻灯片
slides: example
---