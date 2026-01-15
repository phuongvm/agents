# Task Completion Workflow for Agents Project

## Before Completing a Task

### 1. Plugin Development Validation
If creating/modifying plugins:
- [ ] Plugin follows single-responsibility principle
- [ ] Agents, commands, and skills properly organized
- [ ] Naming conventions followed (lowercase, hyphen-separated)
- [ ] Documentation updated in `docs/` directory

### 2. Documentation Updates
- [ ] `docs/plugins.md` updated if adding new plugin
- [ ] `docs/agents.md` updated if adding new agent
- [ ] `docs/agent-skills.md` updated if adding new skill
- [ ] `docs/usage.md` updated if adding new workflow

### 3. Marketplace Configuration
- [ ] `.claude-plugin/marketplace.json` updated with new plugin entry
- [ ] Plugin metadata correct (name, description, category)

## Verification Checklist
- [ ] Plugin structure is correct (agents/, commands/, skills/)
- [ ] All markdown files properly formatted
- [ ] Model tier assignments appropriate
- [ ] Progressive disclosure pattern followed for skills
- [ ] No errors in plugin definitions

## Final Steps
1. Review `git status` and `git diff` to verify changes
2. Ensure plugin follows architecture guidelines
3. Test plugin installation in Claude Code (if applicable)
4. Ask user: "Is this complete from your perspective? Any adjustments needed?"

## Important Reminders
- Plugins are for Claude Code marketplace
- Follow granular design principles (single purpose per plugin)
- Optimize for minimal token usage
- Use progressive disclosure for skills
- Maintain clear boundaries between plugins
- Update all relevant documentation files