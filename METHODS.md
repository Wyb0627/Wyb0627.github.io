## Publication 扁平徽章
- **用途**：为论文资源链接生成统一的紧凑双区 SVG 徽章。
- **核心逻辑**：左侧固定 24px 深灰区域承载平台图标，右侧使用平台品牌色与兼容字体显示入口名称；徽章固定高度 20px，并通过 `publication-badge` 类统一间距与对齐。
- **关键代码**：
  ```html
  <a class="publication-badge" href="https://huggingface.co/papers/2607.20553" target="_blank" rel="noopener noreferrer">
      <img src="./HuggingFace-Papers.svg" alt="Hugging Face Papers" width="112" height="20"/>
  </a>
  ```
- **注意事项**：修改 SVG 宽度时需同步修改 HTML 中的 `width`，否则浏览器会按旧宽度缩放徽章。
