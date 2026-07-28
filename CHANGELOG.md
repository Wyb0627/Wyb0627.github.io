## [2026-07-28] Match AGRAG badge spacing
- **变更**：提高 CMI-Mem 资源徽章归零外边距规则的 CSS 优先级，使四个按钮实际采用统一的 4px 间距；同时清理 Hugging Face 徽章外层元数据中的平台文案。
- **原因**：旧规则的 `margin-left: 10px` 优先级更高，导致截图中的按钮间距仍比 AGRAG 的两个按钮更宽。

## [2026-07-28] Normalize CMI-Mem resource badge spacing
- **变更**：将 CMI-Mem 的 arXiv、GitHub、Hugging Face Papers 与 ModelScope 徽章放入统一间距容器，并将 Hugging Face 文案改为 `2607.20553`，同步缩短徽章宽度。
- **原因**：消除四个资源入口之间不一致的间距，并让按钮尺寸适配新的论文编号文案。

## [2026-07-28] Add Hugging Face Papers badge
- **变更**：在 CMI-Mem 论文的 GitHub 与 ModelScope 徽章之间加入 Hugging Face Papers 入口，链接至论文页面并使用 Hugging Face 黄色与品牌图标。
- **原因**：补充论文在 Hugging Face Papers 上的访问入口，同时保持现有 publication 徽章样式统一。
