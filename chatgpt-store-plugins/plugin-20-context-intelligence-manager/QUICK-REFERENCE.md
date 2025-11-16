# Context Intelligence Manager - Quick Reference

## Essential Commands

### Context Management
```
Create context:          "Create a context for [project/topic]"
List contexts:           "Show all my contexts"
View context:            "Show context [name/id]"
Update context:          "Update context [name] with [new info]"
Delete context:          "Delete context [name]"
```

### Notes
```
Add note:                "Add a [type] note to [context]: [content]"
View notes:              "Show all notes in [context]"
Filter notes:            "Show [note_type] notes in [context]"
```

### Decisions
```
Create decision:         "Create a decision matrix for [decision]"
Compare options:         "Compare [option1] vs [option2] for [decision]"
Get recommendation:      "What's the best option for [decision]?"
Document decision:       "Document our decision to [decision]"
```

### Research
```
Add research:            "Add research on [topic]: [URL/source]"
Find research:           "Show research on [topic]"
Summarize findings:      "Summarize key findings on [topic]"
```

### Search & Export
```
Search all:              "Search for [keyword]"
Export context:          "Export [context] as [format]"
Get analytics:           "Show my activity summary"
```

## Note Types Reference

| Type | Usage | Example |
|------|-------|---------|
| Research | External findings, data | "Competitor launched feature X" |
| Action Item | Tasks to complete | "Schedule customer interviews" |
| Decision | Decision points | "Chose React over Vue" |
| Insight | Key learnings | "Users prefer simplicity over features" |
| Reference | Links & citations | "See Gartner report on page 15" |

## Decision Criteria Guide

### Business Decisions
- Revenue potential
- Market impact
- Implementation cost
- Time to market
- Strategic alignment

### Technical Decisions
- Performance
- Scalability
- Maintainability
- Security
- Team expertise

### Strategic Decisions
- Market differentiation
- Competitive advantage
- Resource alignment
- Risk mitigation
- Long-term value

## Common Workflows

### 30-Second Workflow
```
1. "Create context for [topic]"
2. "Add research on [topic]"
3. "Create decision matrix: [options]"
4. "Get recommendation"
```

### Quick Decision Making
```
1. "What are the pros and cons of [option1]?"
2. "What are the pros and cons of [option2]?"
3. "Create a decision matrix to compare"
4. "What's the recommendation?"
```

### Document Decision
```
1. "We decided to go with [option]"
2. "Document decision: [rationale]"
3. "Add research: [supporting evidence]"
4. "Export as PDF"
```

### Research Project
```
1. "Create context for [research topic]"
2. "Add research: [source 1]"
3. "Add research: [source 2]"
4. "Find insights on [subtopic]"
5. "Export as markdown"
```

## Priority Levels

```
CRITICAL  - Requires immediate attention
HIGH      - Important, schedule soon
MEDIUM    - Important, can wait
LOW       - Nice to have, defer
```

## Tag Recommendations

### By Category
- **Business**: strategy, planning, market, product, sales, finance
- **Technical**: architecture, performance, infrastructure, security, data
- **Project**: roadmap, milestone, release, q1/q2/q3/q4, 2024/2025
- **Function**: product, engineering, marketing, sales, ops

### By Context
- **Urgency**: urgent, planning, backlog, research
- **Status**: active, archived, blocked, completed
- **Audience**: executive, technical, team, public

## Export Formats

| Format | Best For | Includes |
|--------|----------|----------|
| PDF | Executive reports | All formatted content |
| Markdown | Technical docs | Code-friendly format |
| JSON | Data import | Raw data structure |
| HTML | Web sharing | Interactive format |
| DOCX | Word editing | Editable document |

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `/context` | Quick context creation |
| `/note` | Quick note addition |
| `/decision` | Quick decision creation |
| `/search` | Quick search |
| `/export` | Quick export |

## Tips & Tricks

### 1. Template Reuse
Save decision templates for recurring decisions:
```
"Use template: [template_name]"
```

### 2. Batch Operations
Add multiple notes at once:
```
"Add these notes to [context]:
- Note 1
- Note 2
- Note 3"
```

### 3. Context Cloning
Start similar context from existing:
```
"Clone context [existing] as [new_name]"
```

### 4. Smart Search
Find across all contexts:
```
"Find all notes about [topic]"
"Find decisions from [date range]"
```

### 5. Auto-Tagging
Bulk tag operations:
```
"Tag all notes in [context] with [tag]"
```

## Decision Quality Checklist

Before finalizing a decision, verify:
- ✓ All options documented
- ✓ Criteria defined with weights
- ✓ Supporting research added
- ✓ Trade-offs documented
- ✓ Risks identified
- ✓ Implementation plan noted
- ✓ Owner assigned
- ✓ Timeline established

## API Rate Limits

```
Standard User:    1,000 requests/minute
Pro User:         5,000 requests/minute
Enterprise:       Unlimited
```

## Storage Limits

```
Free Plan:        10 contexts, 1GB
Pro Plan:         Unlimited contexts, 100GB
Enterprise:       Custom limits
```

## Troubleshooting Quick Answers

**Q: How do I find a past decision?**
A: Use search feature - search for decision name or tags

**Q: Can I merge contexts?**
A: Export both as JSON, combine manually, re-import

**Q: How do I share a decision?**
A: Export as PDF/HTML and share the file or link

**Q: Can I create custom templates?**
A: Pro users can save decisions as templates

**Q: How do I backup my data?**
A: Export regularly or enable auto-backup in settings

## Integration Quick Links

- **Slack**: Install bot for notifications
- **Email**: Subscribe to digest summaries
- **Calendar**: Link decisions to calendar events
- **Zapier**: Automate workflows

## Support

- **Help**: https://help.contextintelligence.example.com
- **Docs**: https://docs.contextintelligence.example.com
- **Chat**: Chat with support (24/7)
- **Email**: support@contextintelligence.example.com

---

**Plugin Version**: 2.0.0
**Last Updated**: November 2024
