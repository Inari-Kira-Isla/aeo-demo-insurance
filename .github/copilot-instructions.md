<think>用户要求我根据 AGENTS.md 内容生成 copilot-instructions.md。让我分析一下 AGENTS.md 的内容：

1. 项目名称：aeo-demo-insurance
2. 项目描述：AEO Demo — insurance industry template with Schema.org, llms.txt, FAQ, AI-friendly markup
3. 语言：HTML
4. Topics: aeo, ai-friendly, demo, schema-org, template

根据用户的要求格式：
1. 用 # 标题开头，写专案名称
2. ## Project — 一句话描述专案和技术栈
3. ## Conventions — 程式码风格规范（用简短的 bullet points）
4. ## Naming — 命名规范
5. ## Architecture — 关键架构决策
6. ## Commands — 常用指令
7. ## Do Not — 禁止事项列表
8. 保持非常简洁，用 imperative 语气（"Use X", "Prefer Y over Z"）
9. 不超过 60 行（GitHub Copilot 建议不超过 2 页）
10. 如果原文有中文内容，保留中文；如果是英文专案则用英文
11. 不要包含 YAML frontmatter

这是一个英文项目，所以使用英文。

让我生成内容：

# aeo-demo-insurance

## Project
Insurance industry template demonstrating AEO (AI-Engineered Optimization) with Schema.org structured data, llms.txt, FAQ schema, and AI-friendly HTML markup.

## Conventions
- Use semantic HTML5 elements
- Include Schema.org structured data in JSON-LD format
- Generate llms.txt for AI crawler compatibility


- Implement FAQ schema for common insurance queries
- Add meta tags for AI visibility

## Naming
- Use kebab-case for file names
- Name schema files with descriptive purpose (e.g., schema-product.json)
- Use clear, descriptive class names for semantic sections

## Architecture
- Single-page HTML template with modular components
- JSON-LD schema blocks in `<script type="application/ld+json">`
- Separate files for different schema types (product, FAQ, organization)
- No external dependencies—self-contained static files

## Commands
- No build commands needed
- Deploy via git push to hosting provider
- Validate using schema.org validator and AI crawler testing tools

## Do Not
- Avoid dynamic content requiring JavaScript frameworks
- Skip unnecessary CSS or JS libraries
- Don't hardcode sensitive or customer-specific data in templates
- Refrain from omitting structured data—it's essential for AI visibility</think>

# aeo-demo-insurance

## Project
Insurance industry template demonstrating AEO (AI-Engineered Optimization) with Schema.org structured data, llms.txt, FAQ schema, and AI-friendly HTML markup. Language: HTML.

## Conventions
- Use semantic HTML5 elements throughout
- Include Schema.org structured data in JSON-LD format inside `<script type="application/ld+json">` tags
- Generate llms.txt for AI crawler compatibility
- Add FAQ schema for common insurance queries
- Include meta tags for AI visibility (description, keywords, robots)
- Keep all markup self-contained with no external dependencies

## Naming
- Use kebab-case for file names (e.g., insurance-policy.html, schema-product.json)
- Name schema files with descriptive purpose (e.g., schema-product.json, schema-faq.json)
- Use clear, descriptive class and id names reflecting content purpose

## Architecture
- Single-page HTML template with modular semantic sections
- JSON-LD schema blocks embedded in document head
- Separate files for different schema types (product, FAQ, organization, breadcrumb)
- Self-contained static files — no build process required

## Commands
- No build commands needed
- Deploy via git push to hosting provider
- Validate using schema.org validator and AI crawler testing tools

## Do Not
- Use client-side JavaScript frameworks unnecessarily
- Add external CSS or JS libraries when not essential
- Hardcode sensitive or customer-specific data in templates
- Omit structured data — it is critical for AI visibility
- Create complex build pipelines for static HTML files