# Suggested Commands for Agents Project

## Claude Code Plugin Commands

### Add Marketplace
```bash
/plugin marketplace add wshobson/agents
```

### Browse and Install Plugins
```bash
/plugin
```

### Install Specific Plugins
```bash
# Essential development
/plugin install python-development
/plugin install javascript-typescript
/plugin install backend-development

# Infrastructure
/plugin install kubernetes-operations
/plugin install cloud-infrastructure

# Security & quality
/plugin install security-scanning
/plugin install code-review-ai

# Full-stack orchestration
/plugin install full-stack-orchestration
```

## Multi-Agent Workflow Commands

### Full-Stack Feature Development
```bash
/full-stack-orchestration:full-stack-feature "user authentication with OAuth2"
```

### Security Hardening
```bash
/security-scanning:security-hardening --level comprehensive
```

### Python Development
```bash
/python-development:python-scaffold fastapi-microservice
```

### Kubernetes Deployment
```bash
# Activates k8s skills automatically
"Create production Kubernetes deployment with Helm chart and GitOps"
```

## Git Commands
```bash
git status                # Check repository status
git diff                  # Review changes
git log -n 5              # Review recent commits
```

## Windows-Specific Commands
- Use `dir` instead of `ls`
- Use `cd` for directory navigation
- Use PowerShell or Git Bash
- Paths use backslashes: `O:\workspaces\oss\agents`

## File Operations
- Browse plugins: `dir plugins\`
- View plugin structure: `dir plugins\<plugin-name>\`
- Read documentation: `type docs\<doc-name>.md`

## Troubleshooting
```bash
# Clear cache and reinstall
rm -rf ~/.claude/plugins/cache/claude-code-workflows
rm ~/.claude/plugins/installed_plugins.json
```