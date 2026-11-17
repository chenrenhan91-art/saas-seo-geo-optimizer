# SaaS SEO & GEO Optimizer

An AI agent skill for planning, auditing, and improving organic search and AI-search visibility for SaaS products, AI tools, and independent web apps. The skill combines product-led SEO, technical audits, content planning, and generative engine optimization (GEO) in one reusable workflow.

[中文说明](#中文说明) · [Skill instructions](SKILL.md)

## What it covers

- **Strategy and research:** search personas, competitor research, keyword clusters, and a five-dimension opportunity score.
- **Site and content architecture:** topic maps, page ownership, URL structures, internal links, and briefs for tools, tutorials, comparisons, and alternatives.
- **Technical SEO:** indexing, canonicals, sitemaps, structured data, internationalization, and Core Web Vitals.
- **GEO and entity clarity:** answer-first content, verifiable facts, machine-readable discovery, and consistent entity references.
- **Execution and measurement:** prioritized audit findings, implementation receipts, and Search Console and conversion reviews.

The complete instructions are in [SKILL.md](SKILL.md). This repository contains agent guidance, not an application or an automated SEO scanner. The agent's ability to inspect sites, run commands, or access search and analytics data depends on its tools and permissions.

## Get started

1. Clone the repository:

   ```bash
   git clone https://github.com/chenrenhan91-art/saas-seo-geo-optimizer.git
   ```

2. Add the `saas-seo-geo-optimizer` folder to your agent's skills directory or upload it through your agent's skill manager. Follow your agent's installation instructions; supported locations and automatic discovery vary by product. Alternatively, reference `SKILL.md` directly in a workspace conversation.
3. Provide the site URL or codebase, target markets, business goals, and any available Search Console or analytics exports. Ask the agent to distinguish verified findings from assumptions.
4. Review proposed changes and validate them against the live site and current search-engine guidance before deployment.

### Example prompts

```text
Use the SaaS SEO & GEO Optimizer skill to audit this repository. Identify indexing,
metadata, internal linking, and structured-data issues. Prioritize fixes and cite
file paths and evidence; do not invent search volume or rankings.
```

```text
Build a topic map and page-owner table for our AI transcription SaaS targeting
English-speaking product teams. Label unverified demand and scoring assumptions.
```

```text
Review this comparison page for search intent, useful first-hand evidence, and
AI-readable answers. Suggest improvements without making unsupported claims.
```

## Evidence and limitations

The skill labels findings as **CONFIRMED**, **SYNTHESIS**, or **HEURISTIC**. Its opportunity scores are internal prioritization aids, not measured keyword difficulty or search volume. Real rankings, crawlability, traffic, and conversions require appropriate data and verification.

Recommendations and thresholds in the skill are starting points, not guarantees or universal search-engine rules. Search products and crawler policies change; verify current official guidance and choose crawler access, structured data, and discovery files to fit the site's goals and privacy requirements. Files such as `llms.txt` do not guarantee indexing, citation, or ranking.

## Sources and attribution

The skill was prepared with Gemini and synthesizes the [SaaS SEO Playbook by JeffLi1993](https://github.com/JeffLi1993/saas-seo-playbook), a five-dimension keyword opportunity model, and SEO/GEO audit guidance. Refer to the source project for its original material and terms. Rule identifiers such as `SEO-001` are labels used by this skill; the referenced knowledge base is not included as a separate file in this repository.

## Contributing

Issues and pull requests are welcome for corrections, clearer evidence, and practical examples. For a proposed change, include the problem, supporting sources or reproduction steps, and any limitations. Avoid submitting private analytics, credentials, or customer data.

## License

No license has been specified for this repository. Public visibility alone does not grant a license to reuse or redistribute its contents; please contact the repository owner for permission. Third-party sources retain their own terms.

## 中文说明

这是一个面向 SaaS、AI 工具和独立开发者网站的 AI Agent 技能，覆盖关键词与搜索意图研究、网站结构、技术 SEO、GEO、内容规划和审计执行。核心指令见 [SKILL.md](SKILL.md)。它不是独立运行的软件，实际联网、代码审查和数据分析能力取决于所用 Agent 的工具和权限。

克隆仓库后，将整个目录添加到所用 Agent 的技能目录，或在支持的技能管理器中导入；也可以在工作区对话中直接引用 `SKILL.md`。使用时提供网站地址或代码库、目标市场和业务目标，并要求区分已验证事实与推测。关键词评分仅用于内部排序，不能替代真实的搜索量、排名或难度数据；AI 搜索收录与引用也不受保证。

欢迎通过 Issue 或 Pull Request 提交带有证据的修正。仓库目前尚未指定许可证，公开可见不等于允许再利用或再分发。
