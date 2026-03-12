<think>1.  **分析 AGENTS.md**：
    *   專案名稱：`aeo-demo-insurance`
    *   用途：保險業模板，包含 Schema.org, llms.txt, FAQ, AI-friendly markup。
    *   語言：HTML
    *    Topics: aeo, ai-friendly, demo, schema-org, template
    *   原文是英文。

2.  **按照 GEMINI.md 格式要求生成內容**：
    *   標題：# aeo-demo-insurance
    *   Overview：描述這是一個保險行业的 AEO (AI Engine Optimization) 演示模板，使用 HTML 構建，強調結構化數據和 AI 友好性。
    *   Tech Stack：HTML, Schema.org, JSON-LD。
    *   Architecture：基於單頁或簡單多頁結構，包含 FAQ, llms.txt 等優化檔案。
    *   Commands：由於是純 HTML 專案，沒有複雜的 build commands，通常是 "Open index.html in browser" 或 "Deploy to static hosting"。
    *   Coding Style：语义化 HTML，結構化數據 (Schema.org)。
    *   Important Rules：確保 Schema.org 數據有效，頁面需對 LLM 友好 (llms.txt)。

3.  **組織語言**：根據要求，如果是英文專案則用英文。

4.  **Drafting GEMINI.md**:

    *   **# aeo-demo-insurance**
    *   **## Overview**: A demo template for the insurance industry focused on AI Engine Optimization (AEO). It uses semantic HTML and Schema.org to make content easily readable for LLMs and AI agents.
    *   **## Tech Stack**: HTML5, JSON-LD (Schema.org), CSS (minimal/responsive).
    *   **## Architecture**:
        *   `index.html`: Main entry point.
        *   `llms.txt`: Text file designed for AI/LLMs to parse site content.
        *   `faq.html` or section: Contains structured Q&A.
    *   **## Commands**: No build process required. Simply open `index.html` in a browser or deploy to a static host (GitHub Pages, Netlify, Vercel).
    *   **## Coding Style**: Use semantic tags (`<article>`, `<section>`, `<h1>` to `<h6>`). Include valid JSON-LD structured data. Keep content clear and concise.
    *   **## Important Rules**: Do not remove or break Schema.org JSON-LD blocks. Ensure `llms.txt` remains accessible.

5.  **檢查行數**：需保持簡潔，不超過 80 行。目前預估約 30-40 行，符合要求。

6.  **最終輸出**：移除 Markdown 代碼塊包裹，直接輸出內容。</think>

# aeo-demo-insurance

## Overview
A demo template for the insurance industry designed for AI Engine Optimization (AEO). It leverages semantic HTML, Schema.org structured data, and AI-friendly files like `llms.txt` to ensure compatibility with LLMs and AI agents.

## Tech Stack
- **Language**: HTML5
- **Data**: JSON-LD (Schema.org)
- **Optimization**: llms.txt

## Architecture
- `index.html`: Main landing page with semantic structure.
- `llms.txt`: A text file providing a simplified, AI-readable version of the site content.
- `faq.html`: Structured FAQ section to improve search visibility and AI context.
- **Schema**: JSON-LD scripts embedded in HTML for insurance-specific entities (e.g., Product, FAQPage).

## Commands
- **Preview**: Open `index.html` directly in any web browser.
- **Deploy**: Push to any static hosting provider (GitHub Pages, Netlify, Vercel).

## Coding Style
- **HTML**: Semantic, accessible, and clean.
- **SEO/AEO**: Prioritize clear headings, short paragraphs, and accurate Schema.org markup.
- **Formatting**: 2-space indentation for HTML attributes if needed.

## Important Rules
- Do not remove or corrupt the JSON-LD `<script>` tags.
- Ensure `llms.txt` is generated/present and accessible at the root level.
- Avoid heavy JavaScript frameworks that obscure the semantic content.