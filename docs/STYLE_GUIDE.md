# Style Guide

This guide ensures consistent formatting across all resource files.

## 📋 Table Format

Use this standard table format for all resource listings:

```markdown
| Name | Description | License | Notes |
|------|-------------|---------|-------|
| [Tool Name](https://example.com) | Brief description | Free/Paid | Additional info |
```

### Column Guidelines

- **Name**: Link format with descriptive text
- **Description**: 1-2 sentences max, focus on primary use case
- **License**: Free, Paid, Freemium, or specific license (MIT, CC0, etc.)
- **Notes**: Optional features, requirements, or caveats

## 🏷️ File Naming

- Use lowercase with hyphens: `color-generators.md`
- Be descriptive: `font-pairing.md` not `fonts2.md`
- Group similar resources: `free-illustrations.md`, `premium-illustrations.md`

## 📂 Category Structure

Each category folder should have:

```
category-name/
├─ README.md              # Overview + links to subcategories
├─ subcategory1.md        # Specific resource type
├─ subcategory2.md        # Another resource type
└─ tools.md              # Supporting tools (if applicable)
```

## ✍️ Writing Style

- **Concise**: Keep descriptions under 15 words
- **Actionable**: Focus on what the resource does, not what it is
- **Consistent**: Use similar phrasing for similar resource types
- **Accurate**: Verify all claims and links

## 🔗 Link Guidelines

- Always use markdown link format: `[Text](URL)`
- Use HTTPS when available
- Link directly to the main product/tool page
- Avoid referral links or tracking parameters

## 📊 Examples

### Good Examples

```markdown
| [Tailwind CSS](https://tailwindcss.com) | Utility-first CSS framework | MIT | Highly customizable |
| [Coolors](https://coolors.co) | Color palette generator | Free | Export in multiple formats |
```

### Bad Examples

```markdown
| Tailwind CSS - https://tailwindcss.com | This is a really great utility-first CSS framework that helps you build modern websites | Free and open source | It's super customizable and has tons of features |
```

## 🎯 Quality Checklist

Before adding any resource:

- [ ] Link works and loads quickly
- [ ] Description is accurate and concise
- [ ] License/pricing information is current
- [ ] Resource adds unique value
- [ ] Follows table format exactly
- [ ] No typos or formatting errors 