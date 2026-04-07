---
name: travel-smart
description: 自驾出行决策助手 - 高速出口推荐、途中住宿、打车点推荐三大场景。开箱即用，高德地图+评分算法，无需配置直接体验。
---

# TravelSmart - 智能出行决策助手

自驾途中的「第二大脑」——不只告诉你哪里近，而是告诉你**综合最优的决策点在哪里**。

## 核心能力

- 🚗 **高速出口推荐**：堵车时推荐最佳下高速出口，综合考虑餐饮评分+绕行距离
- 🏨 **途中住宿推荐**：找停车场充足+次日行程顺路的酒店
- 🚕 **景点打车点推荐**：告知最佳停车候车位置

## 快速开始

### 方式一：Python CLI（推荐，无需 API Key）

```bash
cd D:\project\travel-smart
python src/main.py --scene highway --highway G4 --lng 116.397 --lat 39.909 --destination 北京
```

### 方式二：Web 演示页面

```bash
pip install -r requirements.txt
python server.py
# 访问 http://localhost:5188
```

### 方式三：飞书对话集成

集成到大管家，通过自然语言使用。

## 三大场景详解

见 `references/` 目录下的详细文档：
- `scoring-algorithm.md` - 多因子评分算法
- `api-reference.md` - API 接口文档
- `PRD.md` - 产品需求文档
