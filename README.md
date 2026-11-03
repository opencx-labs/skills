# OpenCX skills

Skills that help AI coding assistants such as Claude Code, Codex, and Cursor work with OpenCX products. Each folder holds one product's skills and installs on its own.

## Widget

Add, configure, or upgrade the OpenCX chat widget. Guide: [OpenCX widget AI coding skills](https://docs.open.cx/widget/agent-skills).

```bash
# All widget skills
npx skills add https://github.com/opencx-labs/skills/tree/main/widget --skill "*"

# One skill
npx skills add https://github.com/opencx-labs/skills/tree/main/widget --skill opencx-widget-integration
```

| Skill | Use it to |
| --- | --- |
| `opencx-widget-integration` | Install and configure the widget with the HTML embed, React components, or headless React hooks, including branding, page context, and Companion mode. |
| `opencx-widget-migration` | Upgrade a widget integration from v4 to v5: package versions, self-hosted embed assets, custom rendering, streaming, Companion layouts, and page context. |

## Updates

OpenCX publishes the files listed in `.skills-mirror/generated.txt`, this README included, and replaces them on every update. Other files can be added alongside them.
