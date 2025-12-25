# GitHub Profiles

This repository contains the **organization profile page** for [Lumen Analytica LLC](https://github.com/lumen-analytica) on GitHub.

## 📋 What This Repository Does

GitHub automatically displays the content from [`profile/README.md`](profile/README.md) on our organization's landing page at:  
**https://github.com/lumen-analytica**

This special `.github` repository serves as the "front door" to our organization, providing visitors with:

- An overview of what Lumen Analytica does
- Our philosophy and approach to data analytics
- What types of projects and tools they'll find here
- Who we serve and how to engage with our work

## 📂 Repository Structure

```bash
.github/
├── README.md          # This file (documentation about the repo itself)
└── profile/
    └── README.md      # The organization landing page content
```

## ✏️ Making Changes

### Updating the Organization Profile

To update what appears on the Lumen Analytica organization page:

1. **Edit the profile README:**

   ```bash
   # Navigate to the repository
   cd .github
   
   # Edit the organization profile
   open profile/README.md
   # or use your preferred editor:
   # code profile/README.md
   # vim profile/README.md
   ```

2. **Make your changes:**

   - Update company information, services, or philosophy
   - Add or remove sections as needed
   - Keep the tone professional and informative
   - Use clear markdown formatting

3. **Preview locally** (optional):

   - Use a markdown preview tool
   - Or check the rendered view in your editor

4. **Commit and push:**

   ```bash
   git add profile/README.md
   git commit -m "Update organization profile"
   git push origin main
   ```

5. **Verify:**
   - Visit https://github.com/lumen-analytica
   - Changes should appear within a few seconds

### Style Guidelines

When editing the profile:

- **Keep it concise** – visitors scan quickly
- **Use clear headings** – make content scannable
- **Include emojis sparingly** – for visual breaks only
- **Focus on value** – what we do, not just who we are
- **Link to key repositories** – when relevant
- **Maintain professional tone** – authoritative but approachable

### Other Organization-Wide Settings

This repository can also contain:

- **`.github/workflows/`** – Organization-level GitHub Actions
- **`.github/ISSUE_TEMPLATE/`** – Default issue templates
- **`.github/PULL_REQUEST_TEMPLATE.md`** – Default PR template
- **`.github/FUNDING.yml`** – Sponsorship configuration

These are not currently in use but can be added as needed.

## 🔍 Additional Resources

- [GitHub Docs: About organization profiles](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile)
- [Markdown Guide](https://www.markdownguide.org/basic-syntax/)
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)

## 🤝 Contributing

This repository is maintained by Lumen Analytica team members. If you're on the team:

- Feel free to propose updates via pull request
- Or edit directly if you have write access
- Keep changes aligned with our brand and messaging

**Questions?** Contact the Lumen Analytica team.
