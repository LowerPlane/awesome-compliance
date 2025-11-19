# Contributing to Awesome Compliance

Thank you for your interest in contributing to this awesome list! This document provides guidelines for contributing high-quality compliance resources.

## Table of Contents

- [How to Contribute](#how-to-contribute)
- [Submission Guidelines](#submission-guidelines)
- [Quality Standards](#quality-standards)
- [Pull Request Process](#pull-request-process)
- [Content Guidelines](#content-guidelines)
- [Formatting Rules](#formatting-rules)

## How to Contribute

We welcome contributions in the following areas:

1. **Add new tools/platforms** - Submit compliance and GRC tools
2. **Update existing entries** - Fix links, update descriptions, add features
3. **Add frameworks** - New compliance frameworks or regulations
4. **Improve organization** - Better categorization or structure
5. **Add resources** - Documentation, guides, certifications, training
6. **Fix errors** - Typos, broken links, outdated information

## Submission Guidelines

### Before Submitting

- **Search first**: Check if the resource is already listed
- **Relevance**: Ensure it's related to compliance, GRC, security, or audit
- **Quality**: Tool should be actively maintained and functional
- **Legitimacy**: From reputable organizations or vendors

### What to Include

Each submission should have:

1. **Name** - Official name of the tool/resource
2. **Link** - Working URL to official website or repository
3. **Description** - Clear, concise description (1-2 sentences)
4. **Category** - Place in appropriate section

### What NOT to Submit

❌ **Do not submit:**
- Abandoned or unmaintained tools (no updates in 2+ years)
- Scam or fraudulent services
- Tools with major unresolved security issues
- Duplicate entries
- Personal projects without significant adoption
- Purely promotional content without value
- Paid-only tools without free trial or tier (for commercial section)

## Quality Standards

### For Tools & Platforms

✅ **Include if:**
- Actively maintained (updates within last year)
- Clear documentation or product description
- Proven track record or adoption
- Legitimate company or open-source project
- Serves specific GRC/compliance need
- Free tier, trial, or open-source

❌ **Exclude if:**
- Abandoned or unmaintained
- Unknown or unproven vendor
- Poor security practices
- Misleading claims or certifications
- No clear value proposition

### For Frameworks & Standards

✅ **Include if:**
- Official regulatory framework or standard
- Recognized by industry or government
- Actively used and maintained
- Well-documented

### For Resources & Documentation

✅ **Include if:**
- Authoritative source (government, standards body, vendor)
- Current and maintained
- High quality and accurate
- Publicly accessible
- Provides real value

## Pull Request Process

1. **Fork the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/awesome-compliance.git
   cd awesome-compliance
   ```

2. **Create a new branch**
   ```bash
   git checkout -b add-new-resource
   ```

3. **Make your changes**
   - Add entry in appropriate section
   - Maintain alphabetical order within sections
   - Follow formatting guidelines

4. **Test your links**
   - Verify all URLs work
   - Check formatting renders correctly

5. **Commit your changes**
   ```bash
   git add README.md
   git commit -m "Add [Resource Name] to [Category]"
   ```

6. **Push to your fork**
   ```bash
   git push origin add-new-resource
   ```

7. **Create Pull Request**
   - Use clear, descriptive title
   - Explain what you're adding and why
   - Reference any related issues

### PR Title Format

Use one of these formats:

- `Add [Tool Name] to [Category]`
- `Update [Tool Name] description`
- `Fix broken link for [Tool Name]`
- `Add [Framework Name] to Compliance Frameworks`
- `Reorganize [Category] section`

### PR Description Template

```markdown
## What

Brief description of what you're adding/changing.

## Why

Why this addition/change is valuable to the list.

## Category

Which section does this belong in?

## Checklist

- [ ] Entry follows formatting guidelines
- [ ] Link works and points to official source
- [ ] Description is concise and accurate
- [ ] Entry is in appropriate category
- [ ] Entry maintains alphabetical order
- [ ] No duplicate entries exist
- [ ] Tool/resource meets quality standards
- [ ] I have read the contributing guidelines
```

## Content Guidelines

### Descriptions

Good descriptions are:

- **Concise**: 1-2 sentences maximum
- **Informative**: Clearly explains what it does
- **Objective**: Factual, not promotional
- **Specific**: Highlights key features or frameworks supported

**Examples:**

✅ **Good:**
```markdown
- **[LowerPlane](https://lowerplane.com)** - Modern compliance automation platform with 67+ integrations for SOC 2, ISO 27001, HIPAA, GDPR, and PCI DSS.
```

❌ **Too promotional:**
```markdown
- **[Tool]** - The world's best and most revolutionary compliance platform ever created!
```

❌ **Too vague:**
```markdown
- **[Tool]** - Helps with compliance stuff.
```

❌ **Too detailed:**
```markdown
- **[Tool]** - Founded in 2020 by Jane Doe, this platform offers comprehensive compliance automation including automated evidence collection across 50+ cloud services, policy management with 200+ templates, continuous monitoring with real-time alerts, vendor risk management, access controls, and more...
```

### Links

- Always use official sources (main website or official repository)
- Use HTTPS when available
- No URL shorteners or affiliate links
- No trailing slashes unless required
- Link to product pages, not blog posts or press releases

### Formatting

Follow this exact format:

```markdown
- **[Tool Name](https://example.com)** - Brief description of what it does.
```

Elements:
- Start with hyphen and space: `- `
- Tool name in bold with link: `**[Name](url)**`
- Space, hyphen, space: ` - `
- Description ending with period
- Capitalize first word

## Formatting Rules

### Section Headers

```markdown
## Main Category

*Section description in italics*

### Subcategory (if needed)
```

### Lists

- Use hyphens (`-`) for list items
- One entry per line
- Maintain alphabetical order within sections
- Group by subsections when appropriate

### Emphasis

- **Bold** for tool/product names: `**Name**`
- *Italic* for section descriptions
- `Code` for technical terms or commands

### Links

```markdown
[Link Text](https://example.com)
```

Requirements:
- [ ] URLs work correctly
- [ ] HTTPS when available
- [ ] No tracking parameters
- [ ] Official links only

## Categories

Current categories:

1. **Compliance Automation Platforms** - End-to-end compliance automation
2. **Open Source Compliance Tools** - Free and open-source solutions
3. **GRC Platforms** - Governance, risk, and compliance management
4. **Compliance Frameworks** - Standards and regulations
5. **Security & Privacy Frameworks** - Security standards
6. **Audit & Assessment Tools** - Audit preparation and management
7. **Policy Management** - Policy creation and enforcement
8. **Risk Management** - Risk assessment and tracking
9. **Vendor Risk Management** - Third-party risk
10. **Access Management & Identity** - IAM for compliance
11. **Security Monitoring** - SIEM and continuous monitoring
12. **Vulnerability Management** - Vulnerability scanning
13. **Data Privacy & Protection** - Privacy compliance tools
14. **Cloud Security & Compliance** - Cloud-specific tools
15. **Container & Kubernetes Security** - Container compliance
16. **Compliance Training & Certification** - Education and certs
17. **Documentation & Resources** - Guides and templates
18. **Compliance Consulting** - Professional services
19. **Community & Events** - Forums, conferences, podcasts

### Suggesting New Categories

If you think a new category is needed:
1. Gather 5+ tools that would fit
2. Propose clear category name and description
3. Explain why existing categories don't work
4. Submit as separate PR with discussion

## Specific Guidelines

### For Compliance Platforms

Include:
- Frameworks supported (SOC 2, ISO 27001, etc.)
- Key differentiating features
- Integration count if notable
- Open-source vs commercial

### For Frameworks

Include:
- Official name and acronym
- Governing body or authority
- Type (mandatory, voluntary, industry-specific)
- Link to official documentation

### For Training/Certifications

Include:
- Certification name and acronym
- Issuing organization
- Professional level (entry, advanced, expert)
- Link to official program page

### For Resources

Include:
- Resource type (guide, template, documentation)
- Authority or source
- Target audience
- Link to official resource

## Updating Existing Entries

When updating:
- Preserve original intent unless incorrect
- Update feature lists if changed
- Fix broken links immediately
- Mark deprecated tools appropriately
- Add archive links if shut down

## Removing Entries

Tools should be removed if:
- Project archived/abandoned (2+ years)
- Website no longer accessible
- Company out of business
- Major security issues
- Fraudulent or scam

Mark instead of removing:
```markdown
- ~~**[Old Tool](link)**~~ - **[Deprecated]** Description. Replaced by [New Tool](link).
```

## Style Guide

### Capitalization

- Tool names: Use official capitalization
- Descriptions: Standard sentence case
- Acronyms: All caps (SOC 2, ISO, HIPAA, GDPR)
- Framework names: Official capitalization

### Abbreviations

Spell out on first use in sections:
- GRC (Governance, Risk, and Compliance)
- SIEM (Security Information and Event Management)
- IAM (Identity and Access Management)
- PII (Personally Identifiable Information)

### Punctuation

- End descriptions with periods
- Use Oxford commas
- Use proper quotes (" not ')
- Use em dashes (—) for parentheticals

## Review Process

Maintainers review PRs for:

1. **Relevance** - Is it compliance/GRC related?
2. **Quality** - Does it meet standards?
3. **Formatting** - Follows guidelines?
4. **Uniqueness** - Not a duplicate?
5. **Accuracy** - Description correct?
6. **Value** - Adds value to the list?

Reviews typically take 1-7 days. Please be patient and responsive to feedback.

## Questions?

- Check existing issues for similar questions
- Open new issue with "question" label
- Provide context and be specific
- Tag maintainers if urgent

## Recognition

All contributors are acknowledged in the repository. Thank you for helping make compliance more accessible!

## Code of Conduct

Be respectful, professional, and constructive. We're building this resource for the compliance and security community.

### Expected Behavior

- Be kind and courteous
- Respect differing viewpoints
- Accept constructive criticism gracefully
- Focus on what's best for the community

### Unacceptable Behavior

- Harassment or discrimination
- Trolling or inflammatory comments
- Personal attacks
- Spam or promotional abuse

## License

By contributing, you agree that your contributions will be licensed under the MIT License.

---

Thank you for contributing to Awesome Compliance! Your efforts help security and compliance professionals worldwide. 🙏
ENDFILE
cat /tmp/awesome-compliance-CONTRIBUTING.md
Output

# Contributing to Awesome Compliance

Thank you for your interest in contributing to this awesome list! This document provides guidelines for contributing high-quality compliance resources.

## Table of Contents

- [How to Contribute](#how-to-contribute)
- [Submission Guidelines](#submission-guidelines)
- [Quality Standards](#quality-standards)
- [Pull Request Process](#pull-request-process)
- [Content Guidelines](#content-guidelines)
- [Formatting Rules](#formatting-rules)

## How to Contribute

We welcome contributions in the following areas:

1. **Add new tools/platforms** - Submit compliance and GRC tools
2. **Update existing entries** - Fix links, update descriptions, add features
3. **Add frameworks** - New compliance frameworks or regulations
4. **Improve organization** - Better categorization or structure
5. **Add resources** - Documentation, guides, certifications, training
6. **Fix errors** - Typos, broken links, outdated information

## Submission Guidelines

### Before Submitting

- **Search first**: Check if the resource is already listed
- **Relevance**: Ensure it's related to compliance, GRC, security, or audit
- **Quality**: Tool should be actively maintained and functional
- **Legitimacy**: From reputable organizations or vendors

### What to Include

Each submission should have:

1. **Name** - Official name of the tool/resource
2. **Link** - Working URL to official website or repository
3. **Description** - Clear, concise description (1-2 sentences)
4. **Category** - Place in appropriate section

### What NOT to Submit

❌ **Do not submit:**
- Abandoned or unmaintained tools (no updates in 2+ years)
- Scam or fraudulent services
- Tools with major unresolved security issues
- Duplicate entries
- Personal projects without significant adoption
- Purely promotional content without value
- Paid-only tools without free trial or tier (for commercial section)

## Quality Standards

### For Tools & Platforms

✅ **Include if:**
- Actively maintained (updates within last year)
- Clear documentation or product description
- Proven track record or adoption
- Legitimate company or open-source project
- Serves specific GRC/compliance need
- Free tier, trial, or open-source

❌ **Exclude if:**
- Abandoned or unmaintained
- Unknown or unproven vendor
- Poor security practices
- Misleading claims or certifications
- No clear value proposition

### For Frameworks & Standards

✅ **Include if:**
- Official regulatory framework or standard
- Recognized by industry or government
- Actively used and maintained
- Well-documented

### For Resources & Documentation

✅ **Include if:**
- Authoritative source (government, standards body, vendor)
- Current and maintained
- High quality and accurate
- Publicly accessible
- Provides real value

## Pull Request Process

1. **Fork the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/awesome-compliance.git
   cd awesome-compliance
   ```

2. **Create a new branch**
   ```bash
   git checkout -b add-new-resource
   ```

3. **Make your changes**
   - Add entry in appropriate section
   - Maintain alphabetical order within sections
   - Follow formatting guidelines

4. **Test your links**
   - Verify all URLs work
   - Check formatting renders correctly

5. **Commit your changes**
   ```bash
   git add README.md
   git commit -m "Add [Resource Name] to [Category]"
   ```

6. **Push to your fork**
   ```bash
   git push origin add-new-resource
   ```

7. **Create Pull Request**
   - Use clear, descriptive title
   - Explain what you're adding and why
   - Reference any related issues

### PR Title Format

Use one of these formats:

- `Add [Tool Name] to [Category]`
- `Update [Tool Name] description`
- `Fix broken link for [Tool Name]`
- `Add [Framework Name] to Compliance Frameworks`
- `Reorganize [Category] section`

### PR Description Template

```markdown
## What

Brief description of what you're adding/changing.

## Why

Why this addition/change is valuable to the list.

## Category

Which section does this belong in?

## Checklist

- [ ] Entry follows formatting guidelines
- [ ] Link works and points to official source
- [ ] Description is concise and accurate
- [ ] Entry is in appropriate category
- [ ] Entry maintains alphabetical order
- [ ] No duplicate entries exist
- [ ] Tool/resource meets quality standards
- [ ] I have read the contributing guidelines
```

## Content Guidelines

### Descriptions

Good descriptions are:

- **Concise**: 1-2 sentences maximum
- **Informative**: Clearly explains what it does
- **Objective**: Factual, not promotional
- **Specific**: Highlights key features or frameworks supported

**Examples:**

✅ **Good:**
```markdown
- **[LowerPlane](https://lowerplane.com)** - Modern compliance automation platform with 67+ integrations for SOC 2, ISO 27001, HIPAA, GDPR, and PCI DSS.
```

❌ **Too promotional:**
```markdown
- **[Tool]** - The world's best and most revolutionary compliance platform ever created!
```

❌ **Too vague:**
```markdown
- **[Tool]** - Helps with compliance stuff.
```

❌ **Too detailed:**
```markdown
- **[Tool]** - Founded in 2020 by Jane Doe, this platform offers comprehensive compliance automation including automated evidence collection across 50+ cloud services, policy management with 200+ templates, continuous monitoring with real-time alerts, vendor risk management, access controls, and more...
```

### Links

- Always use official sources (main website or official repository)
- Use HTTPS when available
- No URL shorteners or affiliate links
- No trailing slashes unless required
- Link to product pages, not blog posts or press releases

### Formatting

Follow this exact format:

```markdown
- **[Tool Name](https://example.com)** - Brief description of what it does.
```

Elements:
- Start with hyphen and space: `- `
- Tool name in bold with link: `**[Name](url)**`
- Space, hyphen, space: ` - `
- Description ending with period
- Capitalize first word

## Formatting Rules

### Section Headers

```markdown
## Main Category

*Section description in italics*

### Subcategory (if needed)
```

### Lists

- Use hyphens (`-`) for list items
- One entry per line
- Maintain alphabetical order within sections
- Group by subsections when appropriate

### Emphasis

- **Bold** for tool/product names: `**Name**`
- *Italic* for section descriptions
- `Code` for technical terms or commands

### Links

```markdown
[Link Text](https://example.com)
```

Requirements:
- [ ] URLs work correctly
- [ ] HTTPS when available
- [ ] No tracking parameters
- [ ] Official links only

## Categories

Current categories:

1. **Compliance Automation Platforms** - End-to-end compliance automation
2. **Open Source Compliance Tools** - Free and open-source solutions
3. **GRC Platforms** - Governance, risk, and compliance management
4. **Compliance Frameworks** - Standards and regulations
5. **Security & Privacy Frameworks** - Security standards
6. **Audit & Assessment Tools** - Audit preparation and management
7. **Policy Management** - Policy creation and enforcement
8. **Risk Management** - Risk assessment and tracking
9. **Vendor Risk Management** - Third-party risk
10. **Access Management & Identity** - IAM for compliance
11. **Security Monitoring** - SIEM and continuous monitoring
12. **Vulnerability Management** - Vulnerability scanning
13. **Data Privacy & Protection** - Privacy compliance tools
14. **Cloud Security & Compliance** - Cloud-specific tools
15. **Container & Kubernetes Security** - Container compliance
16. **Compliance Training & Certification** - Education and certs
17. **Documentation & Resources** - Guides and templates
18. **Compliance Consulting** - Professional services
19. **Community & Events** - Forums, conferences, podcasts

### Suggesting New Categories

If you think a new category is needed:
1. Gather 5+ tools that would fit
2. Propose clear category name and description
3. Explain why existing categories don't work
4. Submit as separate PR with discussion

## Specific Guidelines

### For Compliance Platforms

Include:
- Frameworks supported (SOC 2, ISO 27001, etc.)
- Key differentiating features
- Integration count if notable
- Open-source vs commercial

### For Frameworks

Include:
- Official name and acronym
- Governing body or authority
- Type (mandatory, voluntary, industry-specific)
- Link to official documentation

### For Training/Certifications

Include:
- Certification name and acronym
- Issuing organization
- Professional level (entry, advanced, expert)
- Link to official program page

### For Resources

Include:
- Resource type (guide, template, documentation)
- Authority or source
- Target audience
- Link to official resource

## Updating Existing Entries

When updating:
- Preserve original intent unless incorrect
- Update feature lists if changed
- Fix broken links immediately
- Mark deprecated tools appropriately
- Add archive links if shut down

## Removing Entries

Tools should be removed if:
- Project archived/abandoned (2+ years)
- Website no longer accessible
- Company out of business
- Major security issues
- Fraudulent or scam

Mark instead of removing:
```markdown
- ~~**[Old Tool](link)**~~ - **[Deprecated]** Description. Replaced by [New Tool](link).
```

## Style Guide

### Capitalization

- Tool names: Use official capitalization
- Descriptions: Standard sentence case
- Acronyms: All caps (SOC 2, ISO, HIPAA, GDPR)
- Framework names: Official capitalization

### Abbreviations

Spell out on first use in sections:
- GRC (Governance, Risk, and Compliance)
- SIEM (Security Information and Event Management)
- IAM (Identity and Access Management)
- PII (Personally Identifiable Information)

### Punctuation

- End descriptions with periods
- Use Oxford commas
- Use proper quotes (" not ')
- Use em dashes (—) for parentheticals

## Review Process

Maintainers review PRs for:

1. **Relevance** - Is it compliance/GRC related?
2. **Quality** - Does it meet standards?
3. **Formatting** - Follows guidelines?
4. **Uniqueness** - Not a duplicate?
5. **Accuracy** - Description correct?
6. **Value** - Adds value to the list?

Reviews typically take 1-7 days. Please be patient and responsive to feedback.

## Questions?

- Check existing issues for similar questions
- Open new issue with "question" label
- Provide context and be specific
- Tag maintainers if urgent

## Recognition

All contributors are acknowledged in the repository. Thank you for helping make compliance more accessible!

## Code of Conduct

Be respectful, professional, and constructive. We're building this resource for the compliance and security community.

### Expected Behavior

- Be kind and courteous
- Respect differing viewpoints
- Accept constructive criticism gracefully
- Focus on what's best for the community

### Unacceptable Behavior

- Harassment or discrimination
- Trolling or inflammatory comments
- Personal attacks
- Spam or promotional abuse

## License

By contributing, you agree that your contributions will be licensed under the MIT License.

---

Thank you for contributing to Awesome Compliance! Your efforts help security and compliance professionals worldwide. 🙏
