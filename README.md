# OpenGov Africa - Hacktoberfest 2025 🌍

[![Hacktoberfest 2025](https://img.shields.io/badge/Hacktoberfest-2025-blueviolet)](https://hacktoberfest.com)
[![Open Source](https://img.shields.io/badge/Open%20Source-❤-green)](https://github.com/OpenGovAfrica)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/OpenGovAfrica/hacktoberfest/pulls)

Welcome to the **OpenGov Africa Hacktoberfest Repository**! This is your central hub for discovering and contributing to meaningful open-source projects that advance **transparency**, **accountability**, and **civic engagement** across Africa.

---

## 📋 Table of Contents

- [About OpenGov Africa](#about-opengov-africa)
- [Why Contribute?](#why-contribute)
- [Quick Start Guide](#quick-start-guide)
- [How to Contribute](#how-to-contribute)
- [Repository Structure](#repository-structure)
- [Contribution Workflow](#contribution-workflow)
- [Team Repositories](#team-repositories)
- [Creating Your Own Issues](#creating-your-own-issues)
- [Common Mistakes to Avoid](#common-mistakes-to-avoid)
- [Getting Help](#getting-help)
- [Recognition](#recognition)
- [Resources](#resources)
- [Code of Conduct](#code-of-conduct)

---

## 🌟 About OpenGov Africa

OpenGov Africa is a community-driven, open-source organization building Africa's first civic-tech STEM startup. We focus on:

- **Transparency** - Making government data accessible
- **Accountability** - Building tools for citizen oversight  
- **Digital Inclusion** - Empowering communities with technology
- **Governance Innovation** - Reimagining how democracy works

Our work spans **civic tech tools**, **open data**, **community organizing**, and **sustainable digital transformation** in Africa—with a global community of contributors.

---

## 🎯 Why Contribute?

- **Make Real Impact** - Your code, designs, and content directly improve governance across Africa
- **Learn & Grow** - Work with experienced mentors in civic tech, data science, and open source
- **Build Your Portfolio** - Showcase meaningful contributions to employers and communities
- **Join a Movement** - Connect with passionate changemakers across the continent and beyond
- **Earn Recognition** - Get featured, receive certificates, and grow into leadership roles

**Hacktoberfest Bonus**: Earn your Hacktoberfest rewards while building tools that matter!

---

## 🚀 Quick Start Guide

### New to Open Source? Start Here!

1. **Create a GitHub account** (if you don't have one): https://github.com/join
2. **Join our Discord community**: https://discord.gg/Eswe4cvvMM
3. **Introduce yourself** in the `#general` channel
4. **Browse open issues** in this repo: [Issues](https://github.com/OpenGovAfrica/hacktoberfest/issues)
5. **Pick an issue** that matches your skills (look for `good-first-issue` label)
6. **Comment to express interest** and wait for assignment
7. **Start contributing!** Follow the workflow below

### Prerequisites

- GitHub account
- Git installed on your computer ([Download Git](https://git-scm.com/downloads))
- Basic understanding of Git commands (we'll guide you!)
- Enthusiasm for civic tech and open governance

---

## 📖 How to Contribute

### Step 1: Pick or Get Assigned an Issue

1. Browse open issues: [OpenGovAfrica/hacktoberfest/issues](https://github.com/OpenGovAfrica/hacktoberfest/issues)
2. Find an issue matching your skills:
   - `good-first-issue` - Perfect for beginners
   - `design` - Visual design tasks
   - `documentation` - Writing and editing
   - `marketing` - Content and campaigns
   - `data` - Data collection and analysis
   - `tech` - Development tasks
3. Comment: "I'd like to work on this issue"
4. **Wait for a maintainer to assign you** before starting work
5. Verify the issue has the `hacktoberfest` or `hacktoberfest-accepted` label

### Step 2: Set Up Your Workspace

Once assigned, work in the appropriate team repository (not this one):

**Fork and clone the team repository:**

```bash
# Example for marketing repo
git clone https://github.com/YOUR-USERNAME/marketing.git
cd marketing
git checkout -b issue-10-social-calendar
```

### Step 3: Make Your Changes

- Create a new branch for your work
- Make your changes following the issue requirements
- Test your changes thoroughly
- Commit with clear, descriptive messages

```bash
git add .
git commit -m "Add: Social media calendar for Q4 2025 (Issue #10)"
git push origin issue-10-social-calendar
```

### Step 4: Submit a Pull Request

1. Go to the team repository on GitHub
2. Click "New Pull Request"
3. Fill out the PR template (see example below)
4. **Add the `hacktoberfest-accepted` label**
5. Request review from your team lead

**PR Title Format:**
```
[Area]: Brief description (Fixes OpenGovAfrica/hacktoberfest#XX)
```

**Example:**
```
Marketing: Social Media Calendar Q4 2025 (Fixes OpenGovAfrica/hacktoberfest#10)
```

### Step 5: Respond to Feedback

- Maintainers will review your PR
- Make requested changes promptly
- Once approved and merged, the issue will be closed
- Your contribution counts toward Hacktoberfest! 🎉

---

## 📁 Repository Structure

This repository (`hacktoberfest`) is for **issues only**. Actual work happens in team repositories:

```
OpenGovAfrica/
├── hacktoberfest/          ← You are here (Issues tracking)
├── marketing/              ← Marketing & communications work
├── design/                 ← Design assets and branding
├── tech/                   ← Development and tools
├── research/               ← Data and research
├── open-data/              ← Open datasets
├── docs/                   ← Documentation
├── hr/                     ← HR and volunteer coordination
└── [other team repos]
```

---

## 🔄 Contribution Workflow

```
1. Browse Issues (hacktoberfest repo)
   ↓
2. Comment & Get Assigned
   ↓
3. Fork Team Repository
   ↓
4. Create Branch & Make Changes
   ↓
5. Test Your Work
   ↓
6. Push & Create PR (in team repo)
   ↓
7. Add hacktoberfest-accepted Label
   ↓
8. Request Review
   ↓
9. Address Feedback
   ↓
10. Get Merged & Celebrated! 🎉
```

---

## 🗂️ Team Repositories

| Team | Repository | Focus Area | Contact |
|------|------------|------------|---------|
| **Marketing** | [marketing](https://github.com/OpenGovAfrica/marketing) | Content, campaigns, social media | events@opengovafrica.org |
| **Design** | [design](https://github.com/OpenGovAfrica/design) | Visual assets, branding, UX | - |
| **Tech/Dev** | [tech](https://github.com/OpenGovAfrica/tech) | Tools, platforms, automation | tech@opengovafrica.org |
| **Research & Data** | [research](https://github.com/OpenGovAfrica/research) | Datasets, analysis, insights | research@opengovafrica.org |
| **Open Data** | [open-data](https://github.com/OpenGovAfrica/open-data) | Public datasets | - |
| **HR** | [hr](https://github.com/OpenGovAfrica/hr) | Volunteer coordination | hr@opengovafrica.org |
| **Documentation** | [docs](https://github.com/OpenGovAfrica/docs) | Technical writing | - |

**Reference format in PRs:**
```
Related to OpenGovAfrica/hacktoberfest#XX
```

---

## 💡 Creating Your Own Issues

You can propose new issues if:

- ✅ It directly improves an OpenGov Africa project
- ✅ It's meaningful and has clear value
- ✅ You can articulate the problem and proposed solution
- ✅ It aligns with our mission

**How to create an issue:**

1. Choose the appropriate team repository
2. Click "New Issue"
3. Provide detailed description:
   - What problem does this solve?
   - What's the expected outcome?
   - Any technical requirements?
4. Reference related work if applicable
5. Add appropriate labels
6. Submit and wait for maintainer approval

**Note:** Self-created issues still need maintainer approval before you can work on them.

---

## ⚠️ Common Mistakes to Avoid

❌ **Don't** open PRs in the `hacktoberfest` repo - only issues go here  
❌ **Don't** start work before being assigned  
❌ **Don't** forget to reference the issue number in your PR  
❌ **Don't** forget the `hacktoberfest-accepted` label  
❌ **Don't** submit trivial or spammy contributions  
❌ **Don't** copy-paste without understanding the context  
❌ **Don't** submit work to the wrong repository

✅ **Do** read the issue description carefully  
✅ **Do** ask questions if anything is unclear  
✅ **Do** test your work before submitting  
✅ **Do** write clear commit messages  
✅ **Do** respond to feedback promptly  
✅ **Do** celebrate your merged contributions!

---

## 🆘 Getting Help

### Stuck? We're here for you!

**Discord Support:**
- Join: https://discord.gg/Eswe4cvvMM
- Ask in `#help` or team-specific channels
- Tag mentors with `@maintainer` or `@team-lead`

**GitHub Discussions:**
- Visit: https://github.com/OpenGovAfrica/OpenGovAfrica/discussions
- Search existing questions
- Post your question with context

**Documentation:**
- [90-Day Roadmap](https://docs.google.com/document/d/13ELP1Azq7UFlbLQ0nIKrirszMJaRBs9qhlVLIlMij1s/edit?usp=drivesdk)
- [Community Drive](https://drive.google.com/drive/folders/1EF5yA7_0STfUdrRYWvRItOtY95bhVVQS)

**Email:**
- General inquiries: [Contact through GitHub issues]
- Team-specific: See team repository READMEs

---

## 🏆 Recognition

We celebrate every contribution!

- **Contributor Spotlights** on social media
- **Monthly Recognition** in community calls
- **Growth Pathways** to leadership roles
- **Certificates** for significant contributions
- **Maintainer Opportunities** for consistent contributors

Learn more about growth pathways: [Governance Model](https://github.com/OpenGovAfrica/.github/blob/main/governance.md)

---

## 📚 Resources

### For Contributors
- [How to Contribute Guide](https://github.com/OpenGovAfrica/hacktoberfest#how-to-contribute)
- [General Contributor Form](https://forms.gle/63BwMW3r7MxuJGYE6)
- [Git & GitHub Tutorial](https://docs.github.com/en/get-started)
- [Markdown Guide](https://www.markdownguide.org/)

### For Maintainers
- [Maintainer Guide](https://github.com/OpenGovAfrica/.github/blob/main/MAINTAINERS.md)
- [Issue Triage Process](https://github.com/OpenGovAfrica/.github/wiki)

### About Hacktoberfest
- [Official Hacktoberfest Site](https://hacktoberfest.com)
- [Hacktoberfest Rules](https://hacktoberfest.com/participation/)
- [Quality Standards](https://hacktoberfest.com/participation/#quality-standards)

---

## 🤝 Code of Conduct

OpenGov Africa is committed to providing a welcoming and inclusive environment for all contributors.

We expect:
- Respectful communication
- Constructive feedback
- Collaboration over competition
- Recognition of diverse perspectives
- Zero tolerance for harassment

Read our full [Code of Conduct](https://github.com/OpenGovAfrica/.github/blob/main/CODE_OF_CONDUCT.md).

---

## 📢 Announcements

**Hacktoberfest 2025 is live!**
- GitHub: [Announcement Discussion](https://github.com/OpenGovAfrica/.github/discussions/2)
- LinkedIn: [Announcement Post](https://www.linkedin.com/feed/update/urn:li:activity:7379756527324286976)

**Stay Connected:**
- Instagram: [@opengovafrica](https://instagram.com/OpenGovAfrica)
- Twitter/X: [@opengovafrica](https://twitter.com/OpenGovAfrica)
- LinkedIn: [OpenGov Africa](https://www.linkedin.com/company/104341081)
- Facebook: [@OpenGov Africa](https://facebook.com/OpenGovAfrica)
- YouTube: [@OpenGov Africa](https://www.youtube.com/@OpenGovAfrica?sub_confirmation=1)

**Hashtags:**
`#Hacktoberfest2025` `#OpenGovAfrica` `#OpenSource` `#CivicTech`

---

## ❓ FAQ

**Q: I'm new to open source. Where do I start?**  
A: Look for issues labeled `good-first-issue` and join our Discord for guidance!

**Q: Do I need to know how to code?**  
A: No! We have opportunities in design, writing, research, marketing, and more.

**Q: How long does PR review take?**  
A: Usually 2-5 days. Maintainers are volunteers, so please be patient.

**Q: Can I work on multiple issues?**  
A: Yes, but complete one before starting another to ensure quality.

**Q: What if I can't finish an issue?**  
A: That's okay! Let the maintainer know so they can reassign it.

**Q: How do I become a maintainer?**  
A: Contribute consistently, help others, and express interest. See our [Growth Pathways](https://github.com/OpenGovAfrica/.github/blob/main/governance.md).

---

## 💬 Thank You

Hacktoberfest is about **community**, **mentorship**, and **open collaboration**.

By contributing to OpenGov Africa, you're helping build a more **transparent**, **accountable**, and **inclusive** future for Africa—and the world.

Every line of code, every design, every dataset matters. **Thank you for being part of this movement!**

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Ready to make an impact? [Browse Open Issues →](https://github.com/OpenGovAfrica/hacktoberfest/issues)**

*Built with ❤️ by contributors across Africa and beyond*