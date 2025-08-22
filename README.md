# Claude Rails Agents

Specialized Claude Code agents for Ruby on Rails development workflows. These agents provide focused expertise for different aspects of Rails development including code review, security analysis, performance optimization, testing, and documentation.

## Available Agents

| Agent | Purpose | Focus Area |
|-------|---------|------------|
| [`rails-code-reviewer`](./rails-code-reviewer.md) | Comprehensive code review | Code quality, architecture, maintainability |
| [`rails-security-review`](./rails-security-review.md) | Security analysis | Vulnerability detection, security best practices |
| [`rails-performance-review`](./rails-performance-review.md) | Performance optimization | Database queries, caching, scalability |
| [`rails-test-writer`](./rails-test-writer.md) | Test creation and improvement | Unit tests, integration tests, test strategy |
| [`rails-yardoc-expert`](./rails-yardoc-expert.md) | Documentation generation | YARD documentation, type annotations |

## Usage

These agents are designed to work with [Claude Code](https://claude.ai/code) and provide specialized expertise for Rails development tasks. Each agent can be invoked automatically by Claude Code when specific development scenarios are detected.

### Example Workflows

- **Code Review**: `rails-code-reviewer` analyzes code structure, identifies code smells, and suggests architectural improvements
- **Security Audit**: `rails-security-review` scans for vulnerabilities and security anti-patterns
- **Performance Issues**: `rails-performance-review` identifies bottlenecks and optimization opportunities
- **Test Coverage**: `rails-test-writer` creates comprehensive test suites following smoke test principles
- **Documentation**: `rails-yardoc-expert` adds proper YARD documentation for IDE tooling

## Documentation

For more information about Claude Code agents and configuration:

- [Claude Code Documentation](https://docs.anthropic.com/claude/docs/claude-code)
- [Claude Code - Sub Agents Documentation](https://docs.anthropic.com/en/docs/claude-code/sub-agents)

## Agent Configuration Format

Each agent file follows the standard Claude Code agent format:

```yaml
---
name: agent-name
description: Agent description with usage examples
model: sonnet
---

Agent prompt and instructions...
```
