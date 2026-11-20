# Classical Poetry Wiki (古典詩歌知識庫)

這是一個以 LLM 驅動、結構化的古典詩歌知識庫專案。

## 目錄架構

```text
classical-poetry-wiki/
├── raw_pdfs/                  # 來源教材／講義 PDF（請放置 6 份原始文檔）
├── wiki/                      # 結構化 Markdown 知識庫節點
│   ├── index.md               # 總目錄、時代時間軸與跨維度導航
│   ├── works/                 # 12 篇作品賞析節點
│   ├── authors/               # 作家檔案節點
│   ├── genres/                # 6 大文體流變節點
│   └── techniques/            # 核心表現手法節點
└── web/                       # 最終產出的互動式 HTML 網頁簡報
```

## 使用指引

1. **資料來源**：將 6 份 PDF 文件置於 `raw_pdfs/` 中，或由 Agent 自動擷取生成經典知識庫。
2. **知識庫節點**：包含作品（Works）、作者（Authors）、文體（Genres）、表現手法（Techniques）等雙向連結 Markdown。
3. **網頁簡報**：於 `web/` 生成具備時代軸線、雙向關聯檢索與互動圖表的單頁應用 (SPA)。
