# Mahua Chinese Heritage Poster

面向 Codex 的中国文化遗产海报艺术指导 Skill。它将传统建筑、历史场所、古城、博物馆主题和文化叙事转化为具有宣纸、矿物颜料、水墨氛围与当代编辑设计感的高端海报。

## 特点

- 优先保持真实建筑的屋顶、比例、材质和标志性轮廓
- 使用大面积留白、层叠山水、雾气和微小人物建立尺度
- 支持完整海报、无字主视觉、商业海报与统一系列
- 内置“裂境”“洞天”“山河建筑卷”“古建切片”等构图方法
- 避免廉价国潮模板、错误建筑类型、塑料 CGI 与过度装饰

## 仓库结构

```text
mahua-chinese-heritage-poster/
├── LICENSE
├── README.md
└── skills/
    └── mahua-chinese-heritage-poster/
        ├── SKILL.md
        ├── agents/
        │   └── openai.yaml
        └── references/
            ├── composition-and-style.md
            └── prompt-template.md
```

## 安装

将 Skill 子目录复制到 Codex Skills 目录：

```bash
cp -R skills/mahua-chinese-heritage-poster ~/.codex/skills/
```

重新启动或刷新 Codex 后即可使用。

## 使用示例

- `用 $mahua-chinese-heritage-poster 制作一张故宫文化海报`
- `把颐和园做成“裂境”构图的展览主视觉`
- `根据我上传的照片制作一套统一的中国古建筑海报`
- `为敦煌主题生成一张保留标题留白的文化主视觉`

## 默认输出方向

- 2:3 竖版
- 单一主建筑或文化主体
- 大面积受控留白
- 宣纸、壁画、岩石和矿物颜料质感
- 墨黑、赭石、朱砂、青绿、黛青与旧金等克制色彩

## 版权与使用边界

- 本仓库不包含示例照片、字体、品牌 Logo 或第三方视觉资产。
- 使用者应确保输入图片、建筑照片、商标和文案具有合法使用权限。
- Skill 要求提取参考图的高层视觉语法，不复制特定作品的完整构图或受保护表达。
- 生成结果可能出现建筑、人物、文字或历史事实错误，公开或商业使用前必须人工审核。
- 地名、建筑名和文化主题仅用于描述创作对象，不代表任何机构的授权、认可或合作关系。

## License

MIT License。详见 [LICENSE](LICENSE)。
