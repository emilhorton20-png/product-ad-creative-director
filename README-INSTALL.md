# Product Ad Creative Director — Codex Skill

A reusable Codex skill for product-ad strategy, creative direction, cinematic production, AI image/video generation, editing, and evaluation.

## Global install (recommended)

Extract this folder into:

- Windows: `%USERPROFILE%\.agents\skills\product-ad-creative-director\`
- macOS/Linux: `~/.agents/skills/product-ad-creative-director/`

The final structure should be:

```text
.agents/
└── skills/
    └── product-ad-creative-director/
        ├── SKILL.md
        └── references/
            ├── workflow-and-gates.md
            ├── visual-bible-11-dimensions.md
            ├── ai-shot-production-template.md
            ├── creative-review-rubric.md
            └── brief-and-deliverable-templates.md
```

For project-only use, put the `product-ad-creative-director` folder under `<project-root>/.agents/skills/` instead.

## Activate

Start a new Codex session. Type `$product-ad-creative-director` or use `/skills` to find it. Codex may also select it automatically when a task matches the description.

Example:

> Use $product-ad-creative-director. I want to create an Amazon conversion-focused video ad for my wooden vinyl-record storage rack. Start with Product Intelligence. Review the product images and don't write video prompts until we approve the creative direction.

Codex detects skill changes automatically; if it does not appear, restart Codex.

## Notes

This is an instruction-led skill. It does not install external AI video tools. Prompts should be tailored to the user's actual generation model/version. Keep product images and specifications in the project so Codex can inspect them.
