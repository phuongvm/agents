# Code Style and Conventions for Agents Project

## Plugin Structure
Each plugin is a self-contained directory with:
- `agents/` - Specialized agent definitions (`.md` files)
- `commands/` - Tools and workflows (`.md` files)
- `skills/` - Modular knowledge packages (`.md` files)

## Naming Conventions
- Plugin names: lowercase, hyphen-separated (e.g., `python-development`)
- Agent names: lowercase, hyphen-separated (e.g., `python-pro`)
- File names: lowercase, hyphen-separated, match component name
- Directory structure: mirrors plugin organization

## Agent Skills Architecture
Three-tier progressive disclosure for token efficiency:
1. **Metadata** - Name and activation criteria (always loaded)
2. **Instructions** - Core guidance (loaded when activated)
3. **Resources** - Examples and templates (loaded on demand)

## Model Configuration
Three-tier model strategy:
- **Tier 1 (Opus 4.5)**: 42 agents for critical architecture, security, code review
- **Tier 2 (Inherit)**: 42 agents - user chooses model (AI/ML, backend, frontend)
- **Tier 3 (Sonnet 4.5)**: 51 agents for support tasks
- **Tier 4 (Haiku 4.5)**: 18 agents for fast operational tasks

## Documentation Standards
- Clear activation criteria for agents and skills
- Comprehensive content with examples
- Progressive disclosure pattern
- Well-organized by category

## Best Practices
- Single responsibility per plugin
- Minimal token usage (average 3.4 components per plugin)
- Composable design (mix and match plugins)
- Clear boundaries between plugins
- Focused, single-purpose plugins