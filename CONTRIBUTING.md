# Contributing to The Playbook

## Development Workflow

### Branch Strategy
- `main` - Stable, reviewed content
- `development` - Active development
- `feature/[name]` - Specific features or episodes
- `research/[topic]` - Research and fact-checking

### Commit Guidelines

Use conventional commit format:
- **script**: Episode script changes
- **docs**: Documentation updates
- **research**: New research or fact-checking
- **structure**: Project organization changes
- **fix**: Bug fixes or corrections
- **feat**: New features or content

Example: `script: add Episode 2 opening sequence`

### Episode Development Process

1. Create feature branch: `git checkout -b feature/tv-S01E02-revelation`
2. Develop outline in appropriate outlines directory
3. Write script in appropriate episodes directory
4. Update character arcs in character-arcs directory
5. Update status tracker: `docs/project-management/status-tracker.md`
6. Commit changes with descriptive message
7. Push and create pull request to `development`
8. Review and merge to `main`

### Quality Control Checklist

- [ ] Consistency with series bible
- [ ] Historical accuracy verified
- [ ] Character voice consistency maintained
- [ ] Technical details researched
- [ ] Timeline continuity checked
- [ ] Status tracker updated

### File Naming Conventions

- TV Episodes: `S[XX]E[XX]-[title-slug].md`
- Podcast Episodes: `S[XX]E[XX]-[title-slug].md`
- Characters: `[character-name-slug].md`
- Research: `[topic-slug].md`
- Documents: `[document-name-slug].md`

### Content Guidelines

- Use markdown format for all text files
- Include metadata at top of episode scripts
- Link to related documents where relevant
- Maintain consistent formatting
- Include sources for research materials
