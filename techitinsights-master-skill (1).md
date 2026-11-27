---
name: techitinsights-master-engineering
description: Design, develop, modernize, test, review, and maintain the TechITInsights technology publication and professional portfolio. Use when changing its website, content presentation, frontend, integrations, SEO, accessibility, performance, or release process.
---

# TechITInsights Master Engineering Skill

## Mission

Turn TechITInsights into a distinctive, trustworthy, modern technology publication and professional innovation portfolio.

This skill is shared guidance for Claude and GitHub Copilot. It defines the brand, design standards, engineering workflow, quality gates, and collaboration expectations. It does not replace repository-specific instructions, framework documentation, or security policies.

## 1. Brand and project identity

- Brand: TechITInsights
- Website: https://techitinsights.com/
- Owner and public byline: Markandeyulu (Mark)
- Positioning: practical, real-world insights across IT, telecom, enterprise architecture, AI, and software engineering.

### Brand pillars

1. Artificial intelligence, LLMs, and AI agents.
2. AI-assisted workflows and automation.
3. Telecom BSS/OSS and solution architecture.
4. Siebel CRM and enterprise application integration.
5. Enterprise architecture and TOGAF.
6. APIs, integration patterns, and distributed systems.
7. Cloud, DevOps, and developer productivity.
8. Practical engineering tools and experiments.

### Verified public links

Preserve these links when relevant. Check the repository before changing existing destinations.

- Website: https://techitinsights.com/
- YouTube: https://youtube.com/@TechITInsights
- LinkedIn: https://linkedin.com/in/markandeyuluenjam
- GitHub: https://github.com/markandeyuluenjam
- Medium: https://medium.com/@markenjam
- Blog: https://markenjam.blogspot.com/
- X: https://x.com/TechITinsights

Do not invent additional profiles, achievements, employers, certifications, article URLs, statistics, or project outcomes.

## 2. Operating principles

1. Inspect before modifying.
2. Understand the existing stack and deployment model before proposing replacements.
3. Preserve working functionality unless a change is explicitly required.
4. Prefer small, reviewable changes over broad rewrites.
5. Reuse existing components and dependencies where sensible.
6. Separate content data from presentation when it improves maintainability.
7. Make the site useful, readable, fast, accessible, and visually coherent.
8. Never expose secrets or weaken security controls.
9. Validate significant changes with available tests and build commands.
10. Explain assumptions, limitations, and unresolved issues honestly.
11. Do not deploy, publish, delete production data, or make irreversible changes without explicit approval.
12. Do not claim a test passed unless it was actually run and its result observed.

## 3. Initial repository discovery

Before editing:

- Identify the framework, language, package manager, build tool, and runtime.
- Inspect the directory tree and project entry points.
- Read README and repository-specific instruction files.
- Inspect package scripts and dependency versions.
- Identify routing, layouts, shared components, styling approach, assets, and content sources.
- Locate contact forms, analytics, SEO configuration, environment-variable usage, and integrations.
- Identify existing tests, linting, formatting, and build commands.
- Determine how the site is deployed, if the repository documents it.
- Note any uncommitted user changes; do not overwrite them.

Produce a concise discovery report with:
- Existing architecture.
- Important routes and components.
- Existing features that must be preserved.
- Risks and unknowns.
- Recommended implementation sequence.

Do not assume a framework or file path before inspecting the repository.

## 4. Design direction

Create a premium, editorial technology experience rather than a generic portfolio template.

### Desired qualities

- Strong visual hierarchy.
- Distinctive but readable typography.
- A deliberate colour system.
- Carefully controlled gradients.
- Clear content grouping.
- Consistent spacing and alignment.
- High-quality cards and article previews.
- Restrained motion and polished hover states.
- Useful whitespace.
- Strong contrast and legibility.
- Responsive layouts at all common viewport sizes.

### Avoid

- Gradient overload.
- Excessive glassmorphism.
- Tiny low-contrast text.
- Decorative animation that distracts from reading.
- Inconsistent corner radii and shadows.
- Randomly mixed icon styles.
- Oversized hero sections that hide useful content.
- Generic filler copy.
- Fake counters, testimonials, logos, or customer claims.
- Unnecessary carousels.
- Mobile layouts that simply shrink desktop layouts.

### Design decision rule

Every visual element should support at least one purpose:
- Explain the brand.
- Help visitors navigate.
- Help visitors discover content.
- Establish credibility.
- Explain a project or technology.
- Encourage a meaningful next action.

Remove elements that serve no clear purpose.

## 5. Design system

Inspect for an existing design system before creating one. Extend it rather than introducing competing tokens.

Define reusable tokens for:
- Brand and accent colours.
- Background and surface colours.
- Text and muted-text colours.
- Border colours.
- Focus and status colours.
- Typography scale.
- Font weights and line heights.
- Spacing scale.
- Border radii.
- Shadows.
- Content widths.
- Breakpoints.
- Motion durations and easing.

Use CSS custom properties or the repository's existing token mechanism when appropriate.

### Colour guidance

Use a restrained base palette with a few intentional accents. Gradients may distinguish the brand and selected sections, but body text and long-form content should remain comfortable to read.

Check text contrast for normal and large text. Never communicate status through colour alone.

### Typography guidance

Use a clear hierarchy for:
- Display headings.
- Page headings.
- Section headings.
- Card headings.
- Body text.
- Captions and metadata.

Avoid excessive font sizes, long line lengths, and dense paragraphs. Use a readable measure for article content.

## 6. Homepage experience

The homepage should quickly answer:
- What is TechITInsights?
- What topics can visitors explore?
- What is Mark currently exploring or building?
- Where can visitors find articles and connect?

Suggested hero heading:

“Explore Technology. Build Innovation. Shape the Future.”

Suggested supporting copy:

“Real-world insights into Artificial Intelligence, Telecom BSS/OSS, Siebel CRM, Enterprise Architecture, APIs and emerging technologies.”

Potential hero elements:
- Brand introduction.
- One primary call to action, such as Explore Articles.
- One secondary call to action, such as What I'm Working On.
- A relevant visual treatment or technology motif.
- Optional concise topic labels.

Do not crowd the hero with every skill, social link, or project.

## 7. What I'm Working On

This is a priority feature. Build it as a clear, maintainable project showcase.

### Suggested project entries

1. AI Agents & Automation
   - Exploring LLM-powered agents, tool use, workflow automation, and practical AI applications.
2. Telecom BSS/OSS Architecture
   - Exploring telecom architecture, end-to-end solution design, TM Forum concepts, and enterprise integration.
3. Siebel CRM & Integration
   - Exploring Siebel CRM architecture, EAI, REST APIs, Open UI, order management, and integration patterns.
4. AI-Powered Developer Tools
   - Experimenting with coding assistants, MCP integrations, and developer productivity workflows.
5. Enterprise Architecture
   - Exploring TOGAF, architecture governance, solution architecture, and business transformation.

Treat these as editable draft descriptions. Confirm actual current activity with the site owner before presenting a project as active or completed.

### Project data model

Where suitable for the existing stack, represent each project with fields such as:

- `id`: stable unique identifier.
- `title`: concise project name.
- `summary`: short, factual description.
- `status`: controlled status value.
- `technologies`: list of relevant technology labels.
- `image`: optional local or approved image reference.
- `url`: optional verified destination.
- `updatedAt`: optional date, only when accurate.
- `featured`: optional boolean.

Suggested status values:
- Exploring
- Researching
- Experimenting
- In Progress
- Completed
- On Hold

### Project card requirements

Each card should:
- Have a clear title and concise summary.
- Show status as text, not colour alone.
- Use a small number of relevant technology tags.
- Provide a link only if a real destination exists.
- Remain readable on mobile.
- Have consistent heights where appropriate without clipping content.
- Support keyboard focus and interaction.
- Avoid fake progress percentages or fabricated timelines.

Keep project data separate from card markup when doing so makes updates easier. Document how the owner can edit titles, summaries, statuses, tags, and links.

## 8. Technology categories and ecosystem

Create a browsable topic area for:
- Artificial Intelligence and AI Agents.
- Telecom BSS/OSS.
- Siebel CRM.
- Enterprise Architecture.
- APIs and Integration.
- Cloud and DevOps.
- Developer Tools.

An ecosystem section may include labels such as AI, LLMs, AI Agents, Siebel CRM, Oracle, Telecom BSS/OSS, TM Forum, TOGAF, REST APIs, Cloud, MCP, and Automation.

Use real icons from an established icon library already present in the project, where possible. Do not use emoji as a substitute for a consistent icon system.

Do not imply formal partnerships or endorsements through third-party logos.

## 9. Articles and editorial experience

Preserve existing article content, slugs, and working links.

Useful content features may include:
- Featured article.
- Recent articles.
- Topic/category filters.
- Article cards with image, title, summary, category, and publication date.
- Read-time estimate only if calculated reliably.
- Clear article page hierarchy.
- Related articles based on actual categories or tags.
- Share links where appropriate.

Do not fabricate article content, authors, dates, references, or destinations.

If content comes from a CMS, API, Markdown files, or another source, preserve its existing workflow. Do not replace a content source without approval.

### Article page quality

- One clear H1.
- Logical H2/H3 hierarchy.
- Readable line length.
- Accessible images and captions.
- Code blocks that are readable and horizontally scrollable when necessary.
- Descriptive links.
- Consistent metadata.
- Useful related content without distracting from the article.

## 10. About and professional profile

Suggested introduction:

“Hi, I'm Markandeyulu (Mark). I share practical technology insights from IT and Telecom, focusing on Artificial Intelligence, Telecom BSS/OSS, Siebel CRM, Enterprise Architecture and emerging technologies.”

Relevant expertise areas may include:
- CRM technical leadership.
- Telecom solution architecture.
- Siebel CRM.
- Enterprise integration.
- TOGAF and enterprise architecture.
- AI and automation.

Use only claims supported by owner-approved content. Do not invent years of experience, job titles, certifications, client names, or project achievements.

Include a clear, verified LinkedIn link where appropriate.

## 11. Navigation and information architecture

Navigation should be predictable and concise.

Potential destinations:
- Home.
- Articles.
- Topics.
- What I'm Working On.
- About.
- Contact.

Only add routes that exist or are being implemented. Do not leave placeholder links that lead nowhere.

For mobile:
- Provide a clear menu control.
- Support keyboard operation.
- Expose expanded/collapsed state accessibly.
- Close the menu after navigation where appropriate.
- Prevent background content from becoming unusable when a modal menu is open.

## 12. Responsive implementation

Test at representative viewport widths, including:
- Narrow mobile.
- Typical mobile.
- Tablet portrait and landscape.
- Laptop.
- Desktop.
- Wide desktop.

Check:
- No unintended horizontal scrolling.
- No clipped headings or cards.
- Images preserve intended aspect ratios.
- Navigation remains usable.
- Buttons and links have adequate touch targets.
- Grid columns collapse sensibly.
- Text remains readable.
- Fixed and sticky elements do not cover content.

Use the project's existing responsive approach. Do not add arbitrary breakpoints without a reason.

## 13. Motion and interaction

Use motion to clarify state or add subtle polish, not to distract.

Requirements:
- Respect `prefers-reduced-motion`.
- Avoid large, continuous background animations.
- Avoid scroll hijacking.
- Keep hover effects subtle.
- Provide visible focus states independent of hover.
- Ensure essential content is available without animation.
- Avoid layout shifts during transitions.
- Do not make important actions depend only on hover.

## 14. HTML and component engineering

- Use semantic HTML elements.
- Keep components focused and reusable.
- Avoid unnecessary abstraction.
- Avoid duplicated markup where a shared component genuinely helps.
- Keep content and presentation separated where practical.
- Use stable keys for rendered collections.
- Handle empty, loading, and error states.
- Keep forms understandable and resilient.
- Follow the framework's established patterns.
- Do not introduce a second styling or state-management system without justification.

Do not rewrite the entire application to satisfy a local design request.

## 15. Accessibility

Use WCAG principles and the project's accessibility tooling.

Review:
- Semantic landmarks.
- Heading hierarchy.
- Keyboard navigation.
- Visible focus indicators.
- Accessible names for controls.
- Form labels and useful error messages.
- Alternative text for meaningful images.
- Empty alt text for decorative images.
- Colour contrast.
- Reduced-motion support.
- Dialog focus management.
- Link purpose.
- Screen-reader status announcements where needed.

Do not use placeholder text as the only form label.

## 16. SEO and sharing

Inspect existing SEO implementation before changing it.

Review:
- Unique page titles.
- Useful meta descriptions.
- Canonical URLs.
- Robots directives.
- Sitemap.
- Open Graph metadata.
- Social sharing image metadata.
- Structured data only when accurate and appropriate.
- Heading hierarchy.
- Descriptive internal links.
- Image alternative text.
- Crawlable navigation.

Preserve valid existing metadata and avoid duplicate tags. Never add fabricated ratings, reviews, organization details, or article dates to structured data.

## 17. Performance

Measure before optimizing when measurement tools are available.

Review:
- Image dimensions and formats.
- Responsive image delivery.
- Lazy loading below the fold.
- Font loading and font subsets.
- JavaScript bundle size.
- Unused dependencies.
- Layout shifts.
- Render-blocking resources.
- Caching strategy.
- Unnecessary client-side rendering.
- Animation cost.

Do not lazy-load the primary hero image if doing so harms the page's loading experience. Do not add optimization complexity without measurable or clear benefit.

## 18. Security and privacy

- Never commit API keys, passwords, tokens, or private credentials.
- Never print secrets in logs.
- Use environment variables and the repository's established secret-management process.
- Validate untrusted input on the server where applicable.
- Avoid unsafe HTML injection.
- Preserve authentication and authorization controls.
- Use HTTPS destinations.
- Avoid collecting unnecessary personal information.
- Do not weaken CORS, CSP, or other security controls as a shortcut.
- Review dependency changes for risk.
- Do not copy production data into test fixtures.

If a security issue is found, explain its impact and propose a safe correction.

## 19. Contact form and existing integrations

The existing TechITInsights contact form and its automation are important and must not be broken.

Before changing them:
- Locate the current form and submission flow.
- Identify endpoints, Apps Script integrations, or other services.
- Inspect validation and error handling.
- Understand success and failure messages.
- Preserve current behavior unless the requested change requires otherwise.

After changes, test:
- Valid submission.
- Invalid or missing fields.
- Network or service failure handling.
- Success feedback.
- Duplicate submission prevention, if already supported.
- Mobile usability.

Do not change deployed Apps Script projects, credentials, endpoints, or production configuration without explicit approval.

## 20. Testing and quality assurance

Use the tools and scripts already present in the repository.

Run relevant:
- Build.
- Unit tests.
- Integration tests.
- End-to-end tests.
- Lint.
- Type checks.
- Formatting checks.
- Accessibility checks.
- Link checks, if available.

Manually inspect changed routes at desktop and mobile sizes.

Test the contact form and other affected integrations.

Report commands and actual results. If a test cannot be run, say why. Do not report unrun tests as passing.

## 21. Git and change management

- Inspect `git status` before editing.
- Do not discard user changes.
- Keep changes scoped to the task.
- Use clear commit messages if asked to commit.
- Do not force-push.
- Do not rewrite shared history.
- Do not modify deployment workflows without need.
- Summarize changed files and important behavior changes.

## 22. Claude implementation workflow

When acting as the primary implementer:

1. Read this skill and repository instructions.
2. Inspect the actual project.
3. Summarize current architecture and risks.
4. Propose a concise phased plan.
5. Identify files likely to change.
6. Implement the highest-value improvements incrementally.
7. Preserve existing routes and integrations.
8. Run available checks after each meaningful phase.
9. Inspect the visual result if browser or screenshot tools are available.
10. Document how the owner can update project cards and content.
11. Stop before deployment and request approval.

Do not claim browser verification if no browser inspection occurred.

## 23. GitHub Copilot review workflow

When acting as the independent reviewer:

1. Read this skill and the repository's local instructions.
2. Inspect the changes made by the primary implementer.
3. Compare changes against the original requirements.
4. Identify regressions, accessibility issues, responsive problems, and maintainability concerns.
5. Prioritize issues by severity and user impact.
6. Fix genuine defects within the approved scope.
7. Avoid rewriting correct code merely to express a different preference.
8. Run build, tests, lint, and type checks available in the project.
9. Report remaining issues and unverified areas.
10. Do not deploy without explicit approval.

## 24. Severity levels for review findings

- Critical: security exposure, data loss, production outage, or severe functional breakage.
- High: major user journey broken, serious accessibility barrier, or important integration failure.
- Medium: noticeable responsive, usability, SEO, or performance defect.
- Low: minor visual inconsistency, wording issue, or non-blocking maintainability concern.

Every finding should include:
- File or route.
- Observed behavior.
- Why it matters.
- Recommended correction.
- Whether it was fixed and retested.

## 25. Release readiness checklist

Before recommending release, verify as applicable:

- [ ] Build completes successfully.
- [ ] Relevant automated tests pass.
- [ ] No new console errors are known.
- [ ] Main navigation works.
- [ ] Important routes load.
- [ ] Existing articles remain available.
- [ ] What I'm Working On displays accurate project information.
- [ ] Project statuses are editable through the documented source.
- [ ] Contact form still works.
- [ ] Social links are correct.
- [ ] Mobile layout is usable.
- [ ] Keyboard navigation works.
- [ ] Focus indicators are visible.
- [ ] Images have appropriate alternative text.
- [ ] SEO metadata is not duplicated or fabricated.
- [ ] No secrets were added to the repository.
- [ ] Deployment configuration was not changed unexpectedly.
- [ ] Owner approval has been obtained before production deployment.

## 26. Final reporting format

For each substantial task, report:

### Summary
What changed and why.

### Files changed
List the actual modified files and their purpose.

### User-visible improvements
Describe changes in plain language.

### Validation
List commands run and their observed results.

### Risks and limitations
List anything not verified or still needing attention.

### Owner instructions
Explain how to update project content, project status, images, or links.

### Next recommended step
Suggest one practical next step.

## Final quality standard

TechITInsights should feel like a premium, credible technology publication and innovation portfolio.

Prioritize:
- Clear communication over decoration.
- Useful content over filler.
- Consistency over novelty.
- Accessibility over visual tricks.
- Performance over unnecessary effects.
- Reliability over risky rewrites.
- Verified claims over invented marketing language.

Inspect carefully. Design thoughtfully. Implement incrementally. Test thoroughly. Document honestly.

---

# Expanded Operational Playbook

The following check catalogue is intended for implementation planning, code review, and regression testing.
Use only checks relevant to the current task; do not mechanically perform every check for a small change.

## Visual design audit catalogue

- [ ] TII-0001: Inspect visual hierarchy. Record the evidence or explain why the check is not applicable.
- [ ] TII-0002: Check typography scale. Record the evidence or explain why the check is not applicable.
- [ ] TII-0003: Check font loading. Record the evidence or explain why the check is not applicable.
- [ ] TII-0004: Review colour contrast. Record the evidence or explain why the check is not applicable.
- [ ] TII-0005: Review gradient restraint. Record the evidence or explain why the check is not applicable.
- [ ] TII-0006: Check surface hierarchy. Record the evidence or explain why the check is not applicable.
- [ ] TII-0007: Check card consistency. Record the evidence or explain why the check is not applicable.
- [ ] TII-0008: Review border treatment. Record the evidence or explain why the check is not applicable.
- [ ] TII-0009: Review shadow consistency. Record the evidence or explain why the check is not applicable.
- [ ] TII-0010: Check spacing rhythm. Record the evidence or explain why the check is not applicable.
- [ ] TII-0011: Review alignment. Record the evidence or explain why the check is not applicable.
- [ ] TII-0012: Check content width. Record the evidence or explain why the check is not applicable.
- [ ] TII-0013: Review image cropping. Record the evidence or explain why the check is not applicable.
- [ ] TII-0014: Check icon consistency. Record the evidence or explain why the check is not applicable.
- [ ] TII-0015: Review button hierarchy. Record the evidence or explain why the check is not applicable.
- [ ] TII-0016: Check link styling. Record the evidence or explain why the check is not applicable.
- [ ] TII-0017: Review section transitions. Record the evidence or explain why the check is not applicable.
- [ ] TII-0018: Check visual density. Record the evidence or explain why the check is not applicable.
- [ ] TII-0019: Review empty space. Record the evidence or explain why the check is not applicable.
- [ ] TII-0020: Check dark theme legibility. Record the evidence or explain why the check is not applicable.
- [ ] TII-0021: Check light theme legibility. Record the evidence or explain why the check is not applicable.
- [ ] TII-0022: Review focus styling. Record the evidence or explain why the check is not applicable.
- [ ] TII-0023: Check hover styling. Record the evidence or explain why the check is not applicable.
- [ ] TII-0024: Check active styling. Record the evidence or explain why the check is not applicable.
- [ ] TII-0025: Review disabled styling. Record the evidence or explain why the check is not applicable.
- [ ] TII-0026: Check status indicators. Record the evidence or explain why the check is not applicable.
- [ ] TII-0027: Review decorative elements. Record the evidence or explain why the check is not applicable.
- [ ] TII-0028: Check heading wrapping. Record the evidence or explain why the check is not applicable.
- [ ] TII-0029: Review text measure. Record the evidence or explain why the check is not applicable.
- [ ] TII-0030: Check mobile composition. Record the evidence or explain why the check is not applicable.

## Homepage audit catalogue

- [ ] TII-0031: Verify the brand is clear above the fold. Record the evidence or explain why the check is not applicable.
- [ ] TII-0032: Verify the hero heading is concise. Record the evidence or explain why the check is not applicable.
- [ ] TII-0033: Verify supporting copy explains the site's value. Record the evidence or explain why the check is not applicable.
- [ ] TII-0034: Verify the primary call to action. Record the evidence or explain why the check is not applicable.
- [ ] TII-0035: Verify the secondary call to action. Record the evidence or explain why the check is not applicable.
- [ ] TII-0036: Check hero image relevance. Record the evidence or explain why the check is not applicable.
- [ ] TII-0037: Check hero image loading. Record the evidence or explain why the check is not applicable.
- [ ] TII-0038: Check hero height on mobile. Record the evidence or explain why the check is not applicable.
- [ ] TII-0039: Check navigation visibility. Record the evidence or explain why the check is not applicable.
- [ ] TII-0040: Check featured topic discovery. Record the evidence or explain why the check is not applicable.
- [ ] TII-0041: Check What I'm Working On placement. Record the evidence or explain why the check is not applicable.
- [ ] TII-0042: Check featured article placement. Record the evidence or explain why the check is not applicable.
- [ ] TII-0043: Check About section clarity. Record the evidence or explain why the check is not applicable.
- [ ] TII-0044: Check social link placement. Record the evidence or explain why the check is not applicable.
- [ ] TII-0045: Check footer completeness. Record the evidence or explain why the check is not applicable.
- [ ] TII-0046: Check section order. Record the evidence or explain why the check is not applicable.
- [ ] TII-0047: Check duplicate calls to action. Record the evidence or explain why the check is not applicable.
- [ ] TII-0048: Check page length. Record the evidence or explain why the check is not applicable.
- [ ] TII-0049: Check first-visit experience. Record the evidence or explain why the check is not applicable.
- [ ] TII-0050: Check returning-visitor experience. Record the evidence or explain why the check is not applicable.

## What I'm Working On audit catalogue

- [ ] TII-0051: Verify project title accuracy. Record the evidence or explain why the check is not applicable.
- [ ] TII-0052: Verify project summary accuracy. Record the evidence or explain why the check is not applicable.
- [ ] TII-0053: Verify project status accuracy. Record the evidence or explain why the check is not applicable.
- [ ] TII-0054: Verify technology tags are relevant. Record the evidence or explain why the check is not applicable.
- [ ] TII-0055: Verify optional project URL. Record the evidence or explain why the check is not applicable.
- [ ] TII-0056: Verify project URL destination. Record the evidence or explain why the check is not applicable.
- [ ] TII-0057: Verify project image relevance. Record the evidence or explain why the check is not applicable.
- [ ] TII-0058: Verify project image alternative text. Record the evidence or explain why the check is not applicable.
- [ ] TII-0059: Verify project update date. Record the evidence or explain why the check is not applicable.
- [ ] TII-0060: Verify no fabricated completion claim. Record the evidence or explain why the check is not applicable.
- [ ] TII-0061: Verify no fabricated progress percentage. Record the evidence or explain why the check is not applicable.
- [ ] TII-0062: Verify no fabricated delivery date. Record the evidence or explain why the check is not applicable.
- [ ] TII-0063: Verify project card keyboard access. Record the evidence or explain why the check is not applicable.
- [ ] TII-0064: Verify project card focus state. Record the evidence or explain why the check is not applicable.
- [ ] TII-0065: Verify project card mobile layout. Record the evidence or explain why the check is not applicable.
- [ ] TII-0066: Verify project card tablet layout. Record the evidence or explain why the check is not applicable.
- [ ] TII-0067: Verify project card desktop layout. Record the evidence or explain why the check is not applicable.
- [ ] TII-0068: Verify status is conveyed by text. Record the evidence or explain why the check is not applicable.
- [ ] TII-0069: Verify status colour contrast. Record the evidence or explain why the check is not applicable.
- [ ] TII-0070: Verify long project title wrapping. Record the evidence or explain why the check is not applicable.
- [ ] TII-0071: Verify long summary wrapping. Record the evidence or explain why the check is not applicable.
- [ ] TII-0072: Verify missing image fallback. Record the evidence or explain why the check is not applicable.
- [ ] TII-0073: Verify missing URL behavior. Record the evidence or explain why the check is not applicable.
- [ ] TII-0074: Verify empty project list behavior. Record the evidence or explain why the check is not applicable.
- [ ] TII-0075: Verify project ordering. Record the evidence or explain why the check is not applicable.
- [ ] TII-0076: Verify project category labels. Record the evidence or explain why the check is not applicable.
- [ ] TII-0077: Verify project data source. Record the evidence or explain why the check is not applicable.
- [ ] TII-0078: Verify owner editing instructions. Record the evidence or explain why the check is not applicable.
- [ ] TII-0079: Verify project identifiers are stable. Record the evidence or explain why the check is not applicable.
- [ ] TII-0080: Verify no duplicate project identifiers. Record the evidence or explain why the check is not applicable.

## Articles and editorial audit catalogue

- [ ] TII-0081: Verify article title. Record the evidence or explain why the check is not applicable.
- [ ] TII-0082: Verify article slug. Record the evidence or explain why the check is not applicable.
- [ ] TII-0083: Verify article summary. Record the evidence or explain why the check is not applicable.
- [ ] TII-0084: Verify publication date. Record the evidence or explain why the check is not applicable.
- [ ] TII-0085: Verify author attribution. Record the evidence or explain why the check is not applicable.
- [ ] TII-0086: Verify category assignment. Record the evidence or explain why the check is not applicable.
- [ ] TII-0087: Verify article thumbnail. Record the evidence or explain why the check is not applicable.
- [ ] TII-0088: Verify thumbnail crop. Record the evidence or explain why the check is not applicable.
- [ ] TII-0089: Verify image alternative text. Record the evidence or explain why the check is not applicable.
- [ ] TII-0090: Verify article canonical URL. Record the evidence or explain why the check is not applicable.
- [ ] TII-0091: Verify article metadata. Record the evidence or explain why the check is not applicable.
- [ ] TII-0092: Verify article heading hierarchy. Record the evidence or explain why the check is not applicable.
- [ ] TII-0093: Verify article reading width. Record the evidence or explain why the check is not applicable.
- [ ] TII-0094: Verify code block readability. Record the evidence or explain why the check is not applicable.
- [ ] TII-0095: Verify code block overflow. Record the evidence or explain why the check is not applicable.
- [ ] TII-0096: Verify table responsiveness. Record the evidence or explain why the check is not applicable.
- [ ] TII-0097: Verify internal links. Record the evidence or explain why the check is not applicable.
- [ ] TII-0098: Verify external links. Record the evidence or explain why the check is not applicable.
- [ ] TII-0099: Verify related article relevance. Record the evidence or explain why the check is not applicable.
- [ ] TII-0100: Verify article pagination. Record the evidence or explain why the check is not applicable.
- [ ] TII-0101: Verify category filtering. Record the evidence or explain why the check is not applicable.
- [ ] TII-0102: Verify empty category state. Record the evidence or explain why the check is not applicable.
- [ ] TII-0103: Verify search behavior. Record the evidence or explain why the check is not applicable.
- [ ] TII-0104: Verify no invented content. Record the evidence or explain why the check is not applicable.
- [ ] TII-0105: Verify no broken article links. Record the evidence or explain why the check is not applicable.
- [ ] TII-0106: Verify legacy article routes. Record the evidence or explain why the check is not applicable.
- [ ] TII-0107: Verify social preview metadata. Record the evidence or explain why the check is not applicable.
- [ ] TII-0108: Verify article structured data. Record the evidence or explain why the check is not applicable.
- [ ] TII-0109: Verify structured data accuracy. Record the evidence or explain why the check is not applicable.
- [ ] TII-0110: Verify date consistency. Record the evidence or explain why the check is not applicable.
- [ ] TII-0111: Verify long-form mobile reading. Record the evidence or explain why the check is not applicable.

## Responsive design audit catalogue

- [ ] TII-0112: Check narrow mobile viewport. Record the evidence or explain why the check is not applicable.
- [ ] TII-0113: Check standard mobile viewport. Record the evidence or explain why the check is not applicable.
- [ ] TII-0114: Check large mobile viewport. Record the evidence or explain why the check is not applicable.
- [ ] TII-0115: Check tablet portrait viewport. Record the evidence or explain why the check is not applicable.
- [ ] TII-0116: Check tablet landscape viewport. Record the evidence or explain why the check is not applicable.
- [ ] TII-0117: Check small laptop viewport. Record the evidence or explain why the check is not applicable.
- [ ] TII-0118: Check standard desktop viewport. Record the evidence or explain why the check is not applicable.
- [ ] TII-0119: Check wide desktop viewport. Record the evidence or explain why the check is not applicable.
- [ ] TII-0120: Check navigation wrapping. Record the evidence or explain why the check is not applicable.
- [ ] TII-0121: Check mobile menu opening. Record the evidence or explain why the check is not applicable.
- [ ] TII-0122: Check mobile menu closing. Record the evidence or explain why the check is not applicable.
- [ ] TII-0123: Check mobile menu keyboard access. Record the evidence or explain why the check is not applicable.
- [ ] TII-0124: Check mobile menu screen-reader state. Record the evidence or explain why the check is not applicable.
- [ ] TII-0125: Check grid column collapse. Record the evidence or explain why the check is not applicable.
- [ ] TII-0126: Check card width. Record the evidence or explain why the check is not applicable.
- [ ] TII-0127: Check button wrapping. Record the evidence or explain why the check is not applicable.
- [ ] TII-0128: Check heading overflow. Record the evidence or explain why the check is not applicable.
- [ ] TII-0129: Check paragraph width. Record the evidence or explain why the check is not applicable.
- [ ] TII-0130: Check image aspect ratio. Record the evidence or explain why the check is not applicable.
- [ ] TII-0131: Check image overflow. Record the evidence or explain why the check is not applicable.
- [ ] TII-0132: Check horizontal page overflow. Record the evidence or explain why the check is not applicable.
- [ ] TII-0133: Check fixed header overlap. Record the evidence or explain why the check is not applicable.
- [ ] TII-0134: Check sticky element overlap. Record the evidence or explain why the check is not applicable.
- [ ] TII-0135: Check footer stacking. Record the evidence or explain why the check is not applicable.
- [ ] TII-0136: Check form field width. Record the evidence or explain why the check is not applicable.
- [ ] TII-0137: Check touch target size. Record the evidence or explain why the check is not applicable.
- [ ] TII-0138: Check landscape phone layout. Record the evidence or explain why the check is not applicable.
- [ ] TII-0139: Check zoom at 200 percent. Record the evidence or explain why the check is not applicable.
- [ ] TII-0140: Check browser text scaling. Record the evidence or explain why the check is not applicable.
- [ ] TII-0141: Check responsive navigation focus. Record the evidence or explain why the check is not applicable.

## Accessibility audit catalogue

- [ ] TII-0142: Check semantic landmarks. Record the evidence or explain why the check is not applicable.
- [ ] TII-0143: Check one primary page heading. Record the evidence or explain why the check is not applicable.
- [ ] TII-0144: Check heading order. Record the evidence or explain why the check is not applicable.
- [ ] TII-0145: Check keyboard-only navigation. Record the evidence or explain why the check is not applicable.
- [ ] TII-0146: Check visible focus indicator. Record the evidence or explain why the check is not applicable.
- [ ] TII-0147: Check logical tab order. Record the evidence or explain why the check is not applicable.
- [ ] TII-0148: Check accessible button names. Record the evidence or explain why the check is not applicable.
- [ ] TII-0149: Check accessible link names. Record the evidence or explain why the check is not applicable.
- [ ] TII-0150: Check form label association. Record the evidence or explain why the check is not applicable.
- [ ] TII-0151: Check required field indication. Record the evidence or explain why the check is not applicable.
- [ ] TII-0152: Check validation error announcement. Record the evidence or explain why the check is not applicable.
- [ ] TII-0153: Check success message announcement. Record the evidence or explain why the check is not applicable.
- [ ] TII-0154: Check image alternative text. Record the evidence or explain why the check is not applicable.
- [ ] TII-0155: Check decorative image empty alt. Record the evidence or explain why the check is not applicable.
- [ ] TII-0156: Check colour contrast. Record the evidence or explain why the check is not applicable.
- [ ] TII-0157: Check status text alternatives. Record the evidence or explain why the check is not applicable.
- [ ] TII-0158: Check reduced motion preference. Record the evidence or explain why the check is not applicable.
- [ ] TII-0159: Check dialog focus entry. Record the evidence or explain why the check is not applicable.
- [ ] TII-0160: Check dialog focus return. Record the evidence or explain why the check is not applicable.
- [ ] TII-0161: Check escape key behavior. Record the evidence or explain why the check is not applicable.
- [ ] TII-0162: Check skip navigation link. Record the evidence or explain why the check is not applicable.
- [ ] TII-0163: Check table headers. Record the evidence or explain why the check is not applicable.
- [ ] TII-0164: Check link purpose in context. Record the evidence or explain why the check is not applicable.
- [ ] TII-0165: Check non-colour error indication. Record the evidence or explain why the check is not applicable.
- [ ] TII-0166: Check screen-reader navigation. Record the evidence or explain why the check is not applicable.
- [ ] TII-0167: Check accessible mobile menu. Record the evidence or explain why the check is not applicable.
- [ ] TII-0168: Check accessible icon buttons. Record the evidence or explain why the check is not applicable.
- [ ] TII-0169: Check accessible pagination. Record the evidence or explain why the check is not applicable.
- [ ] TII-0170: Check accessible tabs if present. Record the evidence or explain why the check is not applicable.
- [ ] TII-0171: Check accessible accordions if present. Record the evidence or explain why the check is not applicable.

## SEO and metadata audit catalogue

- [ ] TII-0172: Check unique page title. Record the evidence or explain why the check is not applicable.
- [ ] TII-0173: Check useful meta description. Record the evidence or explain why the check is not applicable.
- [ ] TII-0174: Check canonical URL. Record the evidence or explain why the check is not applicable.
- [ ] TII-0175: Check robots directive. Record the evidence or explain why the check is not applicable.
- [ ] TII-0176: Check sitemap coverage. Record the evidence or explain why the check is not applicable.
- [ ] TII-0177: Check robots file. Record the evidence or explain why the check is not applicable.
- [ ] TII-0178: Check Open Graph title. Record the evidence or explain why the check is not applicable.
- [ ] TII-0179: Check Open Graph description. Record the evidence or explain why the check is not applicable.
- [ ] TII-0180: Check Open Graph image. Record the evidence or explain why the check is not applicable.
- [ ] TII-0181: Check social image dimensions. Record the evidence or explain why the check is not applicable.
- [ ] TII-0182: Check Twitter card metadata. Record the evidence or explain why the check is not applicable.
- [ ] TII-0183: Check heading semantics. Record the evidence or explain why the check is not applicable.
- [ ] TII-0184: Check descriptive internal anchors. Record the evidence or explain why the check is not applicable.
- [ ] TII-0185: Check crawlable navigation. Record the evidence or explain why the check is not applicable.
- [ ] TII-0186: Check image alt attributes. Record the evidence or explain why the check is not applicable.
- [ ] TII-0187: Check duplicate metadata. Record the evidence or explain why the check is not applicable.
- [ ] TII-0188: Check accidental noindex. Record the evidence or explain why the check is not applicable.
- [ ] TII-0189: Check redirect behavior. Record the evidence or explain why the check is not applicable.
- [ ] TII-0190: Check trailing slash consistency. Record the evidence or explain why the check is not applicable.
- [ ] TII-0191: Check structured data validity. Record the evidence or explain why the check is not applicable.
- [ ] TII-0192: Check structured data truthfulness. Record the evidence or explain why the check is not applicable.
- [ ] TII-0193: Check article date accuracy. Record the evidence or explain why the check is not applicable.
- [ ] TII-0194: Check organization data accuracy. Record the evidence or explain why the check is not applicable.
- [ ] TII-0195: Check breadcrumbs if present. Record the evidence or explain why the check is not applicable.
- [ ] TII-0196: Check page language metadata. Record the evidence or explain why the check is not applicable.
- [ ] TII-0197: Check favicon metadata. Record the evidence or explain why the check is not applicable.
- [ ] TII-0198: Check page share preview. Record the evidence or explain why the check is not applicable.
- [ ] TII-0199: Check legacy URL handling. Record the evidence or explain why the check is not applicable.
- [ ] TII-0200: Check broken internal links. Record the evidence or explain why the check is not applicable.
- [ ] TII-0201: Check search engine rendering. Record the evidence or explain why the check is not applicable.

## Performance audit catalogue

- [ ] TII-0202: Measure initial page load. Record the evidence or explain why the check is not applicable.
- [ ] TII-0203: Review largest contentful paint. Record the evidence or explain why the check is not applicable.
- [ ] TII-0204: Review cumulative layout shift. Record the evidence or explain why the check is not applicable.
- [ ] TII-0205: Review interaction responsiveness. Record the evidence or explain why the check is not applicable.
- [ ] TII-0206: Inspect JavaScript bundle size. Record the evidence or explain why the check is not applicable.
- [ ] TII-0207: Inspect CSS payload size. Record the evidence or explain why the check is not applicable.
- [ ] TII-0208: Inspect image payload size. Record the evidence or explain why the check is not applicable.
- [ ] TII-0209: Inspect font payload size. Record the evidence or explain why the check is not applicable.
- [ ] TII-0210: Check responsive image sources. Record the evidence or explain why the check is not applicable.
- [ ] TII-0211: Check image dimensions. Record the evidence or explain why the check is not applicable.
- [ ] TII-0212: Check lazy loading below the fold. Record the evidence or explain why the check is not applicable.
- [ ] TII-0213: Check hero image priority. Record the evidence or explain why the check is not applicable.
- [ ] TII-0214: Check unused dependencies. Record the evidence or explain why the check is not applicable.
- [ ] TII-0215: Check duplicate dependencies. Record the evidence or explain why the check is not applicable.
- [ ] TII-0216: Check render-blocking resources. Record the evidence or explain why the check is not applicable.
- [ ] TII-0217: Check font display strategy. Record the evidence or explain why the check is not applicable.
- [ ] TII-0218: Check layout stability. Record the evidence or explain why the check is not applicable.
- [ ] TII-0219: Check animation cost. Record the evidence or explain why the check is not applicable.
- [ ] TII-0220: Check unnecessary client rendering. Record the evidence or explain why the check is not applicable.
- [ ] TII-0221: Check caching headers if configurable. Record the evidence or explain why the check is not applicable.
- [ ] TII-0222: Check compression if configurable. Record the evidence or explain why the check is not applicable.
- [ ] TII-0223: Check third-party scripts. Record the evidence or explain why the check is not applicable.
- [ ] TII-0224: Check analytics overhead. Record the evidence or explain why the check is not applicable.
- [ ] TII-0225: Check repeated network requests. Record the evidence or explain why the check is not applicable.
- [ ] TII-0226: Check route transition cost. Record the evidence or explain why the check is not applicable.
- [ ] TII-0227: Check hydration warnings. Record the evidence or explain why the check is not applicable.
- [ ] TII-0228: Check console warnings. Record the evidence or explain why the check is not applicable.
- [ ] TII-0229: Check mobile network behavior. Record the evidence or explain why the check is not applicable.
- [ ] TII-0230: Check performance regression. Record the evidence or explain why the check is not applicable.
- [ ] TII-0231: Record before-and-after measurements. Record the evidence or explain why the check is not applicable.

## Security and privacy audit catalogue

- [ ] TII-0232: Check for committed secrets. Record the evidence or explain why the check is not applicable.
- [ ] TII-0233: Check environment variable handling. Record the evidence or explain why the check is not applicable.
- [ ] TII-0234: Check server-side input validation. Record the evidence or explain why the check is not applicable.
- [ ] TII-0235: Check client-side validation limits. Record the evidence or explain why the check is not applicable.
- [ ] TII-0236: Check unsafe HTML rendering. Record the evidence or explain why the check is not applicable.
- [ ] TII-0237: Check URL validation. Record the evidence or explain why the check is not applicable.
- [ ] TII-0238: Check external link rel attributes. Record the evidence or explain why the check is not applicable.
- [ ] TII-0239: Check authentication boundaries. Record the evidence or explain why the check is not applicable.
- [ ] TII-0240: Check authorization boundaries. Record the evidence or explain why the check is not applicable.
- [ ] TII-0241: Check sensitive logging. Record the evidence or explain why the check is not applicable.
- [ ] TII-0242: Check error message disclosure. Record the evidence or explain why the check is not applicable.
- [ ] TII-0243: Check dependency advisories. Record the evidence or explain why the check is not applicable.
- [ ] TII-0244: Check content security policy. Record the evidence or explain why the check is not applicable.
- [ ] TII-0245: Check cross-origin configuration. Record the evidence or explain why the check is not applicable.
- [ ] TII-0246: Check form spam controls. Record the evidence or explain why the check is not applicable.
- [ ] TII-0247: Check personal data minimization. Record the evidence or explain why the check is not applicable.
- [ ] TII-0248: Check analytics privacy settings. Record the evidence or explain why the check is not applicable.
- [ ] TII-0249: Check upload validation if present. Record the evidence or explain why the check is not applicable.
- [ ] TII-0250: Check API permission scope. Record the evidence or explain why the check is not applicable.
- [ ] TII-0251: Check webhook verification if present. Record the evidence or explain why the check is not applicable.
- [ ] TII-0252: Check rate limiting if applicable. Record the evidence or explain why the check is not applicable.
- [ ] TII-0253: Check CSRF controls if applicable. Record the evidence or explain why the check is not applicable.
- [ ] TII-0254: Check secure transport. Record the evidence or explain why the check is not applicable.
- [ ] TII-0255: Check cookie flags if applicable. Record the evidence or explain why the check is not applicable.
- [ ] TII-0256: Check production debug settings. Record the evidence or explain why the check is not applicable.
- [ ] TII-0257: Check source map exposure policy. Record the evidence or explain why the check is not applicable.
- [ ] TII-0258: Check redirect allowlists. Record the evidence or explain why the check is not applicable.
- [ ] TII-0259: Check third-party embed permissions. Record the evidence or explain why the check is not applicable.
- [ ] TII-0260: Check secret rotation process. Record the evidence or explain why the check is not applicable.
- [ ] TII-0261: Check incident response notes. Record the evidence or explain why the check is not applicable.

## Contact form and integrations audit catalogue

- [ ] TII-0262: Locate current contact form. Record the evidence or explain why the check is not applicable.
- [ ] TII-0263: Document current submission endpoint. Record the evidence or explain why the check is not applicable.
- [ ] TII-0264: Verify existing automation remains unchanged. Record the evidence or explain why the check is not applicable.
- [ ] TII-0265: Check required fields. Record the evidence or explain why the check is not applicable.
- [ ] TII-0266: Check email format validation. Record the evidence or explain why the check is not applicable.
- [ ] TII-0267: Check server-side validation. Record the evidence or explain why the check is not applicable.
- [ ] TII-0268: Check success feedback. Record the evidence or explain why the check is not applicable.
- [ ] TII-0269: Check failure feedback. Record the evidence or explain why the check is not applicable.
- [ ] TII-0270: Check network timeout handling. Record the evidence or explain why the check is not applicable.
- [ ] TII-0271: Check duplicate submission behavior. Record the evidence or explain why the check is not applicable.
- [ ] TII-0272: Check submit button loading state. Record the evidence or explain why the check is not applicable.
- [ ] TII-0273: Check keyboard form operation. Record the evidence or explain why the check is not applicable.
- [ ] TII-0274: Check mobile form layout. Record the evidence or explain why the check is not applicable.
- [ ] TII-0275: Check spam protection. Record the evidence or explain why the check is not applicable.
- [ ] TII-0276: Check privacy notice. Record the evidence or explain why the check is not applicable.
- [ ] TII-0277: Check integration credentials remain private. Record the evidence or explain why the check is not applicable.
- [ ] TII-0278: Check endpoint configuration. Record the evidence or explain why the check is not applicable.
- [ ] TII-0279: Check error logging privacy. Record the evidence or explain why the check is not applicable.
- [ ] TII-0280: Check integration retry behavior. Record the evidence or explain why the check is not applicable.
- [ ] TII-0281: Check integration health visibility. Record the evidence or explain why the check is not applicable.
- [ ] TII-0282: Check no accidental endpoint replacement. Record the evidence or explain why the check is not applicable.
- [ ] TII-0283: Check test submission process. Record the evidence or explain why the check is not applicable.
- [ ] TII-0284: Check form accessibility. Record the evidence or explain why the check is not applicable.
- [ ] TII-0285: Check field autocomplete attributes. Record the evidence or explain why the check is not applicable.
- [ ] TII-0286: Check long message handling. Record the evidence or explain why the check is not applicable.
- [ ] TII-0287: Check notification delivery if applicable. Record the evidence or explain why the check is not applicable.
- [ ] TII-0288: Check acknowledgement behavior. Record the evidence or explain why the check is not applicable.
- [ ] TII-0289: Check human review path if applicable. Record the evidence or explain why the check is not applicable.
- [ ] TII-0290: Check production configuration changes. Record the evidence or explain why the check is not applicable.
- [ ] TII-0291: Document rollback approach. Record the evidence or explain why the check is not applicable.

## Code quality audit catalogue

- [ ] TII-0292: Review component responsibility. Record the evidence or explain why the check is not applicable.
- [ ] TII-0293: Review component naming. Record the evidence or explain why the check is not applicable.
- [ ] TII-0294: Review file naming consistency. Record the evidence or explain why the check is not applicable.
- [ ] TII-0295: Review import organization. Record the evidence or explain why the check is not applicable.
- [ ] TII-0296: Review duplicate markup. Record the evidence or explain why the check is not applicable.
- [ ] TII-0297: Review duplicated styles. Record the evidence or explain why the check is not applicable.
- [ ] TII-0298: Review unnecessary abstractions. Record the evidence or explain why the check is not applicable.
- [ ] TII-0299: Review unnecessary dependencies. Record the evidence or explain why the check is not applicable.
- [ ] TII-0300: Review state ownership. Record the evidence or explain why the check is not applicable.
- [ ] TII-0301: Review prop contracts. Record the evidence or explain why the check is not applicable.
- [ ] TII-0302: Review error boundaries if applicable. Record the evidence or explain why the check is not applicable.
- [ ] TII-0303: Review loading states. Record the evidence or explain why the check is not applicable.
- [ ] TII-0304: Review empty states. Record the evidence or explain why the check is not applicable.
- [ ] TII-0305: Review null handling. Record the evidence or explain why the check is not applicable.
- [ ] TII-0306: Review list keys. Record the evidence or explain why the check is not applicable.
- [ ] TII-0307: Review type safety. Record the evidence or explain why the check is not applicable.
- [ ] TII-0308: Review lint findings. Record the evidence or explain why the check is not applicable.
- [ ] TII-0309: Review formatting consistency. Record the evidence or explain why the check is not applicable.
- [ ] TII-0310: Review dead code. Record the evidence or explain why the check is not applicable.
- [ ] TII-0311: Review unused assets. Record the evidence or explain why the check is not applicable.
- [ ] TII-0312: Review dependency versions. Record the evidence or explain why the check is not applicable.
- [ ] TII-0313: Review package scripts. Record the evidence or explain why the check is not applicable.
- [ ] TII-0314: Review build warnings. Record the evidence or explain why the check is not applicable.
- [ ] TII-0315: Review console warnings. Record the evidence or explain why the check is not applicable.
- [ ] TII-0316: Review test coverage for changed logic. Record the evidence or explain why the check is not applicable.
- [ ] TII-0317: Review comments for accuracy. Record the evidence or explain why the check is not applicable.
- [ ] TII-0318: Review documentation consistency. Record the evidence or explain why the check is not applicable.
- [ ] TII-0319: Review maintainability. Record the evidence or explain why the check is not applicable.
- [ ] TII-0320: Review framework conventions. Record the evidence or explain why the check is not applicable.
- [ ] TII-0321: Review migration risk. Record the evidence or explain why the check is not applicable.

## Testing and release audit catalogue

- [ ] TII-0322: Inspect repository status before edits. Record the evidence or explain why the check is not applicable.
- [ ] TII-0323: Preserve uncommitted user changes. Record the evidence or explain why the check is not applicable.
- [ ] TII-0324: Run relevant unit tests. Record the evidence or explain why the check is not applicable.
- [ ] TII-0325: Run relevant integration tests. Record the evidence or explain why the check is not applicable.
- [ ] TII-0326: Run end-to-end tests if available. Record the evidence or explain why the check is not applicable.
- [ ] TII-0327: Run lint checks. Record the evidence or explain why the check is not applicable.
- [ ] TII-0328: Run type checks. Record the evidence or explain why the check is not applicable.
- [ ] TII-0329: Run formatting checks. Record the evidence or explain why the check is not applicable.
- [ ] TII-0330: Run production build. Record the evidence or explain why the check is not applicable.
- [ ] TII-0331: Inspect build output. Record the evidence or explain why the check is not applicable.
- [ ] TII-0332: Check affected routes. Record the evidence or explain why the check is not applicable.
- [ ] TII-0333: Check main navigation. Record the evidence or explain why the check is not applicable.
- [ ] TII-0334: Check article routes. Record the evidence or explain why the check is not applicable.
- [ ] TII-0335: Check project showcase. Record the evidence or explain why the check is not applicable.
- [ ] TII-0336: Check contact form. Record the evidence or explain why the check is not applicable.
- [ ] TII-0337: Check external links. Record the evidence or explain why the check is not applicable.
- [ ] TII-0338: Check responsive screenshots if available. Record the evidence or explain why the check is not applicable.
- [ ] TII-0339: Check keyboard operation. Record the evidence or explain why the check is not applicable.
- [ ] TII-0340: Check console errors. Record the evidence or explain why the check is not applicable.
- [ ] TII-0341: Check network failures. Record the evidence or explain why the check is not applicable.
- [ ] TII-0342: Check deployment configuration diff. Record the evidence or explain why the check is not applicable.
- [ ] TII-0343: Check environment configuration. Record the evidence or explain why the check is not applicable.
- [ ] TII-0344: Check generated artifacts. Record the evidence or explain why the check is not applicable.
- [ ] TII-0345: Check git diff. Record the evidence or explain why the check is not applicable.
- [ ] TII-0346: Check accidental secrets. Record the evidence or explain why the check is not applicable.
- [ ] TII-0347: Document tests not run. Record the evidence or explain why the check is not applicable.
- [ ] TII-0348: Document known issues. Record the evidence or explain why the check is not applicable.
- [ ] TII-0349: Request production approval. Record the evidence or explain why the check is not applicable.
- [ ] TII-0350: Prepare rollback notes. Record the evidence or explain why the check is not applicable.
- [ ] TII-0351: Do not deploy without authorization. Record the evidence or explain why the check is not applicable.

## AI collaboration audit catalogue

- [ ] TII-0352: Read the master skill before implementation. Record the evidence or explain why the check is not applicable.
- [ ] TII-0353: Read repository-local instructions. Record the evidence or explain why the check is not applicable.
- [ ] TII-0354: Inspect before suggesting file edits. Record the evidence or explain why the check is not applicable.
- [ ] TII-0355: State assumptions explicitly. Record the evidence or explain why the check is not applicable.
- [ ] TII-0356: Separate verified facts from recommendations. Record the evidence or explain why the check is not applicable.
- [ ] TII-0357: Ask before destructive operations. Record the evidence or explain why the check is not applicable.
- [ ] TII-0358: Avoid inventing repository files. Record the evidence or explain why the check is not applicable.
- [ ] TII-0359: Avoid inventing test results. Record the evidence or explain why the check is not applicable.
- [ ] TII-0360: Keep changes scoped. Record the evidence or explain why the check is not applicable.
- [ ] TII-0361: Explain non-obvious design decisions. Record the evidence or explain why the check is not applicable.
- [ ] TII-0362: Use the existing package manager. Record the evidence or explain why the check is not applicable.
- [ ] TII-0363: Respect existing formatting. Record the evidence or explain why the check is not applicable.
- [ ] TII-0364: Preserve the owner's current work. Record the evidence or explain why the check is not applicable.
- [ ] TII-0365: Summarize modified files. Record the evidence or explain why the check is not applicable.
- [ ] TII-0366: List commands actually executed. Record the evidence or explain why the check is not applicable.
- [ ] TII-0367: Report actual command outcomes. Record the evidence or explain why the check is not applicable.
- [ ] TII-0368: Identify unverified browser behavior. Record the evidence or explain why the check is not applicable.
- [ ] TII-0369: Identify deployment risks. Record the evidence or explain why the check is not applicable.
- [ ] TII-0370: Do not expose credentials in responses. Record the evidence or explain why the check is not applicable.
- [ ] TII-0371: Do not deploy without approval. Record the evidence or explain why the check is not applicable.

## Scenario runbook: new homepage design review

When handling **new homepage design review**, follow this sequence:
1. Confirm the requested outcome and identify the affected user journey.
2. Inspect the current implementation and repository instructions.
3. Identify existing behavior that must remain unchanged.
4. List affected routes, components, styles, data, and integrations.
5. Check whether the repository already has a suitable component or pattern.
6. Describe the smallest safe implementation plan.
7. Implement incrementally and keep the diff focused.
8. Verify keyboard access and responsive behavior where relevant.
9. Run the applicable tests, lint, type checks, and build.
10. Inspect the final diff and report actual results.
11. Document any manual verification that remains.
12. Request explicit approval before production deployment.

Acceptance evidence:
- The requested behavior is present.
- Existing required behavior is preserved.
- No unsupported claims or placeholder destinations were introduced.
- Relevant validation was executed and reported accurately.
- Remaining limitations are disclosed.

## Scenario runbook: What I'm Working On feature implementation

When handling **What I'm Working On feature implementation**, follow this sequence:
1. Confirm the requested outcome and identify the affected user journey.
2. Inspect the current implementation and repository instructions.
3. Identify existing behavior that must remain unchanged.
4. List affected routes, components, styles, data, and integrations.
5. Check whether the repository already has a suitable component or pattern.
6. Describe the smallest safe implementation plan.
7. Implement incrementally and keep the diff focused.
8. Verify keyboard access and responsive behavior where relevant.
9. Run the applicable tests, lint, type checks, and build.
10. Inspect the final diff and report actual results.
11. Document any manual verification that remains.
12. Request explicit approval before production deployment.

Acceptance evidence:
- The requested behavior is present.
- Existing required behavior is preserved.
- No unsupported claims or placeholder destinations were introduced.
- Relevant validation was executed and reported accurately.
- Remaining limitations are disclosed.

## Scenario runbook: article listing redesign

When handling **article listing redesign**, follow this sequence:
1. Confirm the requested outcome and identify the affected user journey.
2. Inspect the current implementation and repository instructions.
3. Identify existing behavior that must remain unchanged.
4. List affected routes, components, styles, data, and integrations.
5. Check whether the repository already has a suitable component or pattern.
6. Describe the smallest safe implementation plan.
7. Implement incrementally and keep the diff focused.
8. Verify keyboard access and responsive behavior where relevant.
9. Run the applicable tests, lint, type checks, and build.
10. Inspect the final diff and report actual results.
11. Document any manual verification that remains.
12. Request explicit approval before production deployment.

Acceptance evidence:
- The requested behavior is present.
- Existing required behavior is preserved.
- No unsupported claims or placeholder destinations were introduced.
- Relevant validation was executed and reported accurately.
- Remaining limitations are disclosed.

## Scenario runbook: article detail page refinement

When handling **article detail page refinement**, follow this sequence:
1. Confirm the requested outcome and identify the affected user journey.
2. Inspect the current implementation and repository instructions.
3. Identify existing behavior that must remain unchanged.
4. List affected routes, components, styles, data, and integrations.
5. Check whether the repository already has a suitable component or pattern.
6. Describe the smallest safe implementation plan.
7. Implement incrementally and keep the diff focused.
8. Verify keyboard access and responsive behavior where relevant.
9. Run the applicable tests, lint, type checks, and build.
10. Inspect the final diff and report actual results.
11. Document any manual verification that remains.
12. Request explicit approval before production deployment.

Acceptance evidence:
- The requested behavior is present.
- Existing required behavior is preserved.
- No unsupported claims or placeholder destinations were introduced.
- Relevant validation was executed and reported accurately.
- Remaining limitations are disclosed.

## Scenario runbook: mobile navigation update

When handling **mobile navigation update**, follow this sequence:
1. Confirm the requested outcome and identify the affected user journey.
2. Inspect the current implementation and repository instructions.
3. Identify existing behavior that must remain unchanged.
4. List affected routes, components, styles, data, and integrations.
5. Check whether the repository already has a suitable component or pattern.
6. Describe the smallest safe implementation plan.
7. Implement incrementally and keep the diff focused.
8. Verify keyboard access and responsive behavior where relevant.
9. Run the applicable tests, lint, type checks, and build.
10. Inspect the final diff and report actual results.
11. Document any manual verification that remains.
12. Request explicit approval before production deployment.

Acceptance evidence:
- The requested behavior is present.
- Existing required behavior is preserved.
- No unsupported claims or placeholder destinations were introduced.
- Relevant validation was executed and reported accurately.
- Remaining limitations are disclosed.

## Scenario runbook: colour and typography system update

When handling **colour and typography system update**, follow this sequence:
1. Confirm the requested outcome and identify the affected user journey.
2. Inspect the current implementation and repository instructions.
3. Identify existing behavior that must remain unchanged.
4. List affected routes, components, styles, data, and integrations.
5. Check whether the repository already has a suitable component or pattern.
6. Describe the smallest safe implementation plan.
7. Implement incrementally and keep the diff focused.
8. Verify keyboard access and responsive behavior where relevant.
9. Run the applicable tests, lint, type checks, and build.
10. Inspect the final diff and report actual results.
11. Document any manual verification that remains.
12. Request explicit approval before production deployment.

Acceptance evidence:
- The requested behavior is present.
- Existing required behavior is preserved.
- No unsupported claims or placeholder destinations were introduced.
- Relevant validation was executed and reported accurately.
- Remaining limitations are disclosed.

## Scenario runbook: new project card addition

When handling **new project card addition**, follow this sequence:
1. Confirm the requested outcome and identify the affected user journey.
2. Inspect the current implementation and repository instructions.
3. Identify existing behavior that must remain unchanged.
4. List affected routes, components, styles, data, and integrations.
5. Check whether the repository already has a suitable component or pattern.
6. Describe the smallest safe implementation plan.
7. Implement incrementally and keep the diff focused.
8. Verify keyboard access and responsive behavior where relevant.
9. Run the applicable tests, lint, type checks, and build.
10. Inspect the final diff and report actual results.
11. Document any manual verification that remains.
12. Request explicit approval before production deployment.

Acceptance evidence:
- The requested behavior is present.
- Existing required behavior is preserved.
- No unsupported claims or placeholder destinations were introduced.
- Relevant validation was executed and reported accurately.
- Remaining limitations are disclosed.

## Scenario runbook: project status editing workflow

When handling **project status editing workflow**, follow this sequence:
1. Confirm the requested outcome and identify the affected user journey.
2. Inspect the current implementation and repository instructions.
3. Identify existing behavior that must remain unchanged.
4. List affected routes, components, styles, data, and integrations.
5. Check whether the repository already has a suitable component or pattern.
6. Describe the smallest safe implementation plan.
7. Implement incrementally and keep the diff focused.
8. Verify keyboard access and responsive behavior where relevant.
9. Run the applicable tests, lint, type checks, and build.
10. Inspect the final diff and report actual results.
11. Document any manual verification that remains.
12. Request explicit approval before production deployment.

Acceptance evidence:
- The requested behavior is present.
- Existing required behavior is preserved.
- No unsupported claims or placeholder destinations were introduced.
- Relevant validation was executed and reported accurately.
- Remaining limitations are disclosed.

## Scenario runbook: contact form visual redesign

When handling **contact form visual redesign**, follow this sequence:
1. Confirm the requested outcome and identify the affected user journey.
2. Inspect the current implementation and repository instructions.
3. Identify existing behavior that must remain unchanged.
4. List affected routes, components, styles, data, and integrations.
5. Check whether the repository already has a suitable component or pattern.
6. Describe the smallest safe implementation plan.
7. Implement incrementally and keep the diff focused.
8. Verify keyboard access and responsive behavior where relevant.
9. Run the applicable tests, lint, type checks, and build.
10. Inspect the final diff and report actual results.
11. Document any manual verification that remains.
12. Request explicit approval before production deployment.

Acceptance evidence:
- The requested behavior is present.
- Existing required behavior is preserved.
- No unsupported claims or placeholder destinations were introduced.
- Relevant validation was executed and reported accurately.
- Remaining limitations are disclosed.

## Scenario runbook: SEO metadata correction

When handling **SEO metadata correction**, follow this sequence:
1. Confirm the requested outcome and identify the affected user journey.
2. Inspect the current implementation and repository instructions.
3. Identify existing behavior that must remain unchanged.
4. List affected routes, components, styles, data, and integrations.
5. Check whether the repository already has a suitable component or pattern.
6. Describe the smallest safe implementation plan.
7. Implement incrementally and keep the diff focused.
8. Verify keyboard access and responsive behavior where relevant.
9. Run the applicable tests, lint, type checks, and build.
10. Inspect the final diff and report actual results.
11. Document any manual verification that remains.
12. Request explicit approval before production deployment.

Acceptance evidence:
- The requested behavior is present.
- Existing required behavior is preserved.
- No unsupported claims or placeholder destinations were introduced.
- Relevant validation was executed and reported accurately.
- Remaining limitations are disclosed.

## Scenario runbook: image optimization change

When handling **image optimization change**, follow this sequence:
1. Confirm the requested outcome and identify the affected user journey.
2. Inspect the current implementation and repository instructions.
3. Identify existing behavior that must remain unchanged.
4. List affected routes, components, styles, data, and integrations.
5. Check whether the repository already has a suitable component or pattern.
6. Describe the smallest safe implementation plan.
7. Implement incrementally and keep the diff focused.
8. Verify keyboard access and responsive behavior where relevant.
9. Run the applicable tests, lint, type checks, and build.
10. Inspect the final diff and report actual results.
11. Document any manual verification that remains.
12. Request explicit approval before production deployment.

Acceptance evidence:
- The requested behavior is present.
- Existing required behavior is preserved.
- No unsupported claims or placeholder destinations were introduced.
- Relevant validation was executed and reported accurately.
- Remaining limitations are disclosed.

## Scenario runbook: animation or transition addition

When handling **animation or transition addition**, follow this sequence:
1. Confirm the requested outcome and identify the affected user journey.
2. Inspect the current implementation and repository instructions.
3. Identify existing behavior that must remain unchanged.
4. List affected routes, components, styles, data, and integrations.
5. Check whether the repository already has a suitable component or pattern.
6. Describe the smallest safe implementation plan.
7. Implement incrementally and keep the diff focused.
8. Verify keyboard access and responsive behavior where relevant.
9. Run the applicable tests, lint, type checks, and build.
10. Inspect the final diff and report actual results.
11. Document any manual verification that remains.
12. Request explicit approval before production deployment.

Acceptance evidence:
- The requested behavior is present.
- Existing required behavior is preserved.
- No unsupported claims or placeholder destinations were introduced.
- Relevant validation was executed and reported accurately.
- Remaining limitations are disclosed.

## Scenario runbook: third-party script addition

When handling **third-party script addition**, follow this sequence:
1. Confirm the requested outcome and identify the affected user journey.
2. Inspect the current implementation and repository instructions.
3. Identify existing behavior that must remain unchanged.
4. List affected routes, components, styles, data, and integrations.
5. Check whether the repository already has a suitable component or pattern.
6. Describe the smallest safe implementation plan.
7. Implement incrementally and keep the diff focused.
8. Verify keyboard access and responsive behavior where relevant.
9. Run the applicable tests, lint, type checks, and build.
10. Inspect the final diff and report actual results.
11. Document any manual verification that remains.
12. Request explicit approval before production deployment.

Acceptance evidence:
- The requested behavior is present.
- Existing required behavior is preserved.
- No unsupported claims or placeholder destinations were introduced.
- Relevant validation was executed and reported accurately.
- Remaining limitations are disclosed.

## Scenario runbook: dependency upgrade

When handling **dependency upgrade**, follow this sequence:
1. Confirm the requested outcome and identify the affected user journey.
2. Inspect the current implementation and repository instructions.
3. Identify existing behavior that must remain unchanged.
4. List affected routes, components, styles, data, and integrations.
5. Check whether the repository already has a suitable component or pattern.
6. Describe the smallest safe implementation plan.
7. Implement incrementally and keep the diff focused.
8. Verify keyboard access and responsive behavior where relevant.
9. Run the applicable tests, lint, type checks, and build.
10. Inspect the final diff and report actual results.
11. Document any manual verification that remains.
12. Request explicit approval before production deployment.

Acceptance evidence:
- The requested behavior is present.
- Existing required behavior is preserved.
- No unsupported claims or placeholder destinations were introduced.
- Relevant validation was executed and reported accurately.
- Remaining limitations are disclosed.

## Scenario runbook: framework component refactor

When handling **framework component refactor**, follow this sequence:
1. Confirm the requested outcome and identify the affected user journey.
2. Inspect the current implementation and repository instructions.
3. Identify existing behavior that must remain unchanged.
4. List affected routes, components, styles, data, and integrations.
5. Check whether the repository already has a suitable component or pattern.
6. Describe the smallest safe implementation plan.
7. Implement incrementally and keep the diff focused.
8. Verify keyboard access and responsive behavior where relevant.
9. Run the applicable tests, lint, type checks, and build.
10. Inspect the final diff and report actual results.
11. Document any manual verification that remains.
12. Request explicit approval before production deployment.

Acceptance evidence:
- The requested behavior is present.
- Existing required behavior is preserved.
- No unsupported claims or placeholder destinations were introduced.
- Relevant validation was executed and reported accurately.
- Remaining limitations are disclosed.

## Scenario runbook: routing change

When handling **routing change**, follow this sequence:
1. Confirm the requested outcome and identify the affected user journey.
2. Inspect the current implementation and repository instructions.
3. Identify existing behavior that must remain unchanged.
4. List affected routes, components, styles, data, and integrations.
5. Check whether the repository already has a suitable component or pattern.
6. Describe the smallest safe implementation plan.
7. Implement incrementally and keep the diff focused.
8. Verify keyboard access and responsive behavior where relevant.
9. Run the applicable tests, lint, type checks, and build.
10. Inspect the final diff and report actual results.
11. Document any manual verification that remains.
12. Request explicit approval before production deployment.

Acceptance evidence:
- The requested behavior is present.
- Existing required behavior is preserved.
- No unsupported claims or placeholder destinations were introduced.
- Relevant validation was executed and reported accurately.
- Remaining limitations are disclosed.

## Scenario runbook: content migration

When handling **content migration**, follow this sequence:
1. Confirm the requested outcome and identify the affected user journey.
2. Inspect the current implementation and repository instructions.
3. Identify existing behavior that must remain unchanged.
4. List affected routes, components, styles, data, and integrations.
5. Check whether the repository already has a suitable component or pattern.
6. Describe the smallest safe implementation plan.
7. Implement incrementally and keep the diff focused.
8. Verify keyboard access and responsive behavior where relevant.
9. Run the applicable tests, lint, type checks, and build.
10. Inspect the final diff and report actual results.
11. Document any manual verification that remains.
12. Request explicit approval before production deployment.

Acceptance evidence:
- The requested behavior is present.
- Existing required behavior is preserved.
- No unsupported claims or placeholder destinations were introduced.
- Relevant validation was executed and reported accurately.
- Remaining limitations are disclosed.

## Scenario runbook: accessibility remediation

When handling **accessibility remediation**, follow this sequence:
1. Confirm the requested outcome and identify the affected user journey.
2. Inspect the current implementation and repository instructions.
3. Identify existing behavior that must remain unchanged.
4. List affected routes, components, styles, data, and integrations.
5. Check whether the repository already has a suitable component or pattern.
6. Describe the smallest safe implementation plan.
7. Implement incrementally and keep the diff focused.
8. Verify keyboard access and responsive behavior where relevant.
9. Run the applicable tests, lint, type checks, and build.
10. Inspect the final diff and report actual results.
11. Document any manual verification that remains.
12. Request explicit approval before production deployment.

Acceptance evidence:
- The requested behavior is present.
- Existing required behavior is preserved.
- No unsupported claims or placeholder destinations were introduced.
- Relevant validation was executed and reported accurately.
- Remaining limitations are disclosed.

## Scenario runbook: performance regression investigation

When handling **performance regression investigation**, follow this sequence:
1. Confirm the requested outcome and identify the affected user journey.
2. Inspect the current implementation and repository instructions.
3. Identify existing behavior that must remain unchanged.
4. List affected routes, components, styles, data, and integrations.
5. Check whether the repository already has a suitable component or pattern.
6. Describe the smallest safe implementation plan.
7. Implement incrementally and keep the diff focused.
8. Verify keyboard access and responsive behavior where relevant.
9. Run the applicable tests, lint, type checks, and build.
10. Inspect the final diff and report actual results.
11. Document any manual verification that remains.
12. Request explicit approval before production deployment.

Acceptance evidence:
- The requested behavior is present.
- Existing required behavior is preserved.
- No unsupported claims or placeholder destinations were introduced.
- Relevant validation was executed and reported accurately.
- Remaining limitations are disclosed.

## Scenario runbook: pre-release review

When handling **pre-release review**, follow this sequence:
1. Confirm the requested outcome and identify the affected user journey.
2. Inspect the current implementation and repository instructions.
3. Identify existing behavior that must remain unchanged.
4. List affected routes, components, styles, data, and integrations.
5. Check whether the repository already has a suitable component or pattern.
6. Describe the smallest safe implementation plan.
7. Implement incrementally and keep the diff focused.
8. Verify keyboard access and responsive behavior where relevant.
9. Run the applicable tests, lint, type checks, and build.
10. Inspect the final diff and report actual results.
11. Document any manual verification that remains.
12. Request explicit approval before production deployment.

Acceptance evidence:
- The requested behavior is present.
- Existing required behavior is preserved.
- No unsupported claims or placeholder destinations were introduced.
- Relevant validation was executed and reported accurately.
- Remaining limitations are disclosed.

## Scenario runbook: Copilot independent code review

When handling **Copilot independent code review**, follow this sequence:
1. Confirm the requested outcome and identify the affected user journey.
2. Inspect the current implementation and repository instructions.
3. Identify existing behavior that must remain unchanged.
4. List affected routes, components, styles, data, and integrations.
5. Check whether the repository already has a suitable component or pattern.
6. Describe the smallest safe implementation plan.
7. Implement incrementally and keep the diff focused.
8. Verify keyboard access and responsive behavior where relevant.
9. Run the applicable tests, lint, type checks, and build.
10. Inspect the final diff and report actual results.
11. Document any manual verification that remains.
12. Request explicit approval before production deployment.

Acceptance evidence:
- The requested behavior is present.
- Existing required behavior is preserved.
- No unsupported claims or placeholder destinations were introduced.
- Relevant validation was executed and reported accurately.
- Remaining limitations are disclosed.

## Scenario runbook: Claude implementation handoff

When handling **Claude implementation handoff**, follow this sequence:
1. Confirm the requested outcome and identify the affected user journey.
2. Inspect the current implementation and repository instructions.
3. Identify existing behavior that must remain unchanged.
4. List affected routes, components, styles, data, and integrations.
5. Check whether the repository already has a suitable component or pattern.
6. Describe the smallest safe implementation plan.
7. Implement incrementally and keep the diff focused.
8. Verify keyboard access and responsive behavior where relevant.
9. Run the applicable tests, lint, type checks, and build.
10. Inspect the final diff and report actual results.
11. Document any manual verification that remains.
12. Request explicit approval before production deployment.

Acceptance evidence:
- The requested behavior is present.
- Existing required behavior is preserved.
- No unsupported claims or placeholder destinations were introduced.
- Relevant validation was executed and reported accurately.
- Remaining limitations are disclosed.

### Engineering decision review 0925 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 0930 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 0935 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 0940 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 0945 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 0950 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 0955 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 0960 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 0965 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 0970 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 0975 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 0980 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 0985 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 0990 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 0995 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1000 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1005 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1010 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1015 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1020 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1025 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1030 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1035 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1040 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1045 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1050 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1055 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1060 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1065 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1070 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1075 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1080 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1085 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1090 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1095 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1100 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1105 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1110 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1115 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1120 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1125 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1130 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1135 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1140 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1145 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1150 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1155 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1160 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1165 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1170 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1175 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1180 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1185 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1190 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1195 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1200 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1205 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1210 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1215 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1220 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1225 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1230 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1235 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1240 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1245 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1250 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1255 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1260 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1265 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1270 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1275 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1280 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1285 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1290 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1295 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1300 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1305 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1310 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1315 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1320 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1325 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1330 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1335 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1340 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1345 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1350 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1355 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1360 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1365 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1370 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1375 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1380 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1385 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1390 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1395 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1400 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1405 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1410 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1415 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1420 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1425 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1430 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1435 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1440 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1445 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1450 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1455 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1460 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1465 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1470 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1475 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1480 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1485 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1490 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1495 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1500 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1505 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1510 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1515 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1520 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1525 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1530 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1535 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1540 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1545 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1550 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1555 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1560 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1565 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1570 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1575 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1580 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1585 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1590 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1595 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1600 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1605 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1610 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1615 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1620 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1625 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1630 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1635 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1640 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1645 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1650 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1655 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1660 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1665 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1670 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1675 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1680 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1685 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1690 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1695 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1700 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1705 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1710 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1715 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1720 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1725 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1730 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1735 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1740 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1745 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1750 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1755 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1760 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1765 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1770 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1775 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1780 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1785 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1790 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1795 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1800 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1805 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1810 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1815 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1820 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1825 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1830 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1835 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1840 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1845 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1850 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1855 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1860 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1865 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1870 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1875 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1880 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1885 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1890 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1895 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1900 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1905 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1910 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1915 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1920 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1925 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1930 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1935 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1940 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1945 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1950 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1955 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1960 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1965 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1970 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1975 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1980 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1985 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1990 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 1995 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2000 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2005 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2010 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2015 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2020 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2025 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2030 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2035 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2040 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2045 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2050 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2055 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2060 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2065 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2070 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2075 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2080 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2085 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2090 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2095 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2100 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2105 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2110 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2115 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2120 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2125 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2130 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2135 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2140 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2145 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2150 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2155 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2160 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2165 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2170 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2175 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2180 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2185 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2190 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2195 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2200 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2205 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2210 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2215 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2220 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2225 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2230 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2235 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2240 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2245 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2250 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2255 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2260 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2265 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2270 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2275 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2280 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2285 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2290 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2295 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2300 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2305 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2310 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2315 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2320 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2325 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2330 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2335 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2340 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2345 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2350 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2355 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2360 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2365 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2370 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2375 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2380 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2385 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2390 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2395 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2400 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2405 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2410 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2415 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2420 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2425 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2430 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2435 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2440 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2445 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2450 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2455 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2460 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2465 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2470 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2475 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2480 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2485 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2490 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2495 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2500 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2505 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2510 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2515 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2520 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2525 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2530 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2535 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2540 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2545 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2550 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2555 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2560 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2565 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2570 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2575 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2580 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2585 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2590 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2595 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2600 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2605 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2610 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2615 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2620 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2625 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2630 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2635 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2640 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2645 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2650 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2655 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2660 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2665 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2670 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2675 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2680 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2685 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2690 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2695 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2700 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2705 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2710 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2715 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2720 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2725 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2730 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2735 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2740 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2745 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2750 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2755 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2760 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2765 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2770 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2775 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2780 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2785 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2790 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2795 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2800 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2805 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2810 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2815 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2820 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2825 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2830 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2835 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2840 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2845 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2850 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2855 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2860 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2865 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2870 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2875 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2880 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2885 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2890 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2895 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2900 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2905 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2910 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2915 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2920 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2925 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2930 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2935 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2940 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2945 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2950 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2955 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2960 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2965 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2970 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2975 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2980 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2985 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2990 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 2995 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3000 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3005 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3010 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3015 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3020 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3025 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3030 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3035 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3040 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3045 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3050 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3055 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3060 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3065 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3070 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3075 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3080 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3085 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3090 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3095 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3100 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3105 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3110 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3115 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3120 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3125 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3130 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3135 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3140 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3145 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3150 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3155 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3160 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3165 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3170 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3175 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3180 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3185 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3190 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3195 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3200 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3205 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3210 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3215 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3220 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3225 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3230 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3235 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3240 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3245 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3250 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3255 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3260 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3265 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3270 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3275 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3280 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3285 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3290 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3295 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3300 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3305 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3310 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3315 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3320 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3325 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3330 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3335 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3340 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3345 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3350 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3355 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3360 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3365 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3370 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3375 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3380 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3385 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3390 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3395 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3400 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3405 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3410 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3415 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3420 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3425 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3430 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3435 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3440 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3445 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3450 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3455 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3460 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3465 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3470 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3475 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3480 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3485 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3490 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3495 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3500 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3505 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3510 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3515 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3520 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3525 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3530 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3535 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3540 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3545 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3550 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3555 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3560 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3565 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3570 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3575 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3580 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3585 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3590 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3595 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3600 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3605 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3610 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3615 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3620 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3625 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3630 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3635 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3640 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3645 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3650 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3655 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3660 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3665 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3670 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3675 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3680 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3685 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3690 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3695 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3700 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3705 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3710 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3715 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3720 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3725 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3730 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3735 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3740 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3745 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3750 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3755 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3760 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3765 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3770 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3775 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3780 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3785 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3790 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3795 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3800 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3805 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3810 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3815 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3820 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3825 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3830 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3835 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3840 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3845 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3850 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3855 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3860 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3865 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3870 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3875 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3880 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3885 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3890 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3895 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3900 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3905 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3910 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3915 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3920 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3925 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3930 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3935 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3940 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3945 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3950 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3955 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3960 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3965 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3970 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3975 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3980 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3985 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3990 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 3995 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4000 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4005 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4010 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4015 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4020 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4025 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4030 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4035 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4040 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4045 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4050 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4055 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4060 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4065 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4070 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4075 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4080 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4085 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4090 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4095 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4100 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4105 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4110 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4115 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4120 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4125 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4130 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4135 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4140 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4145 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4150 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4155 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4160 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4165 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4170 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4175 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4180 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4185 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4190 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4195 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4200 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4205 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4210 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4215 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4220 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4225 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4230 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4235 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4240 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4245 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4250 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4255 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4260 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4265 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4270 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4275 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4280 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4285 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4290 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4295 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4300 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4305 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4310 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4315 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4320 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4325 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4330 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4335 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4340 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4345 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4350 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4355 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4360 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4365 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4370 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4375 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4380 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4385 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4390 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4395 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4400 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4405 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4410 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4415 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4420 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4425 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4430 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4435 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4440 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4445 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4450 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4455 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4460 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4465 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4470 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4475 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4480 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4485 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4490 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4495 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4500 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4505 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4510 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4515 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4520 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4525 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4530 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4535 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4540 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4545 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4550 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4555 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4560 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4565 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4570 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4575 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4580 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4585 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4590 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4595 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4600 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4605 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4610 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4615 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4620 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4625 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4630 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4635 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4640 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4645 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4650 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4655 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4660 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4665 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4670 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4675 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4680 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4685 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4690 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4695 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4700 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4705 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4710 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4715 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4720 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4725 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4730 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4735 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4740 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4745 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4750 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4755 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4760 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4765 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4770 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4775 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4780 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4785 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4790 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4795 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4800 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4805 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4810 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4815 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4820 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4825 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4830 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4835 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4840 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4845 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4850 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4855 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4860 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4865 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4870 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4875 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4880 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4885 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4890 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4895 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4900 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4905 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4910 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4915 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4920 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4925 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4930 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4935 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4940 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4945 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4950 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4955 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4960 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4965 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4970 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4975 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4980 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4985 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4990 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 4995 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5000 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5005 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5010 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5015 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5020 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5025 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5030 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5035 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5040 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5045 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5050 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5055 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5060 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5065 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5070 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5075 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5080 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5085 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5090 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5095 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5100 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5105 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5110 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5115 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5120 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5125 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5130 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5135 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5140 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5145 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5150 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5155 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5160 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5165 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5170 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5175 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5180 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5185 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5190 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5195 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5200 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5205 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5210 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5215 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5220 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5225 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5230 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5235 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5240 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5245 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5250 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5255 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5260 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5265 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5270 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5275 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5280 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5285 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5290 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5295 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5300 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5305 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5310 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5315 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5320 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5325 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5330 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5335 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5340 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5345 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5350 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5355 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5360 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5365 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5370 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5375 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5380 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5385 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5390 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5395 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5400 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5405 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5410 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5415 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5420 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5425 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5430 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5435 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5440 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5445 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5450 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5455 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5460 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5465 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5470 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5475 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5480 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5485 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5490 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5495 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5500 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5505 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5510 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5515 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5520 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5525 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5530 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5535 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5540 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5545 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5550 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5555 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5560 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5565 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5570 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5575 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5580 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5585 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5590 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5595 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5600 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5605 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5610 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5615 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5620 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5625 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5630 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5635 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5640 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5645 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5650 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5655 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5660 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5665 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5670 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5675 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5680 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5685 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5690 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5695 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5700 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5705 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5710 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5715 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5720 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5725 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5730 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5735 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5740 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5745 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5750 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5755 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5760 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5765 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5770 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5775 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5780 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5785 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5790 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5795 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5800 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5805 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5810 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5815 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5820 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5825 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5830 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5835 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5840 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5845 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5850 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5855 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5860 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5865 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5870 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5875 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5880 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5885 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5890 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5895 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5900 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5905 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5910 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5915 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5920 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5925 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5930 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5935 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5940 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5945 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5950 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5955 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5960 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5965 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5970 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5975 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5980 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5985 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5990 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 5995 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6000 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6005 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6010 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6015 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6020 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6025 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6030 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6035 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6040 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6045 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6050 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6055 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6060 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6065 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6070 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6075 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6080 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6085 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6090 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6095 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6100 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6105 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6110 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6115 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6120 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6125 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6130 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6135 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6140 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6145 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6150 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6155 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6160 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6165 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6170 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6175 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6180 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6185 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6190 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6195 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6200 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6205 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6210 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6215 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6220 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6225 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6230 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6235 — AI handoff
- Ask: Are unknowns clearly separated from verified facts?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6240 — Content
- Ask: Is this statement supported by owner-approved information?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6245 — Projects
- Ask: Does the card avoid unsupported completion or progress claims?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6250 — Accessibility
- Ask: Is information conveyed by more than colour alone?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6255 — Security
- Ask: Could this change expose a secret or private user data?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6260 — Testing
- Ask: Which checks were actually run, and what did they return?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6265 — Design
- Ask: Does this visual change improve hierarchy, readability, or discoverability?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6270 — Content
- Ask: Is this article, project, date, or destination verified?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6275 — Navigation
- Ask: Does the link lead to a real, relevant destination?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6280 — SEO
- Ask: Is the metadata unique, accurate, and appropriate to this route?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6285 — Security
- Ask: Is untrusted input validated at the correct boundary?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6290 — Release
- Ask: Can this change be rolled back safely?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6295 — Design
- Ask: Is the colour treatment consistent with the established tokens?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6300 — Content
- Ask: Can the visitor understand the next action without guessing?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6305 — Navigation
- Ask: Can the route be reached using keyboard navigation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6310 — SEO
- Ask: Does structured data describe only facts visible on the page?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6315 — Integration
- Ask: Does this change preserve the current contact-form workflow?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6320 — Release
- Ask: Has the owner explicitly approved production deployment?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6325 — Design
- Ask: Can the content be understood without relying on animation?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6330 — Projects
- Ask: Is the project status current and accurate?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6335 — Accessibility
- Ask: Is the control's accessible name meaningful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6340 — Performance
- Ask: Is there evidence that this optimization is useful?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6345 — Integration
- Ask: Have endpoint and credential changes been explicitly approved?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6350 — AI handoff
- Ask: Are implementation claims backed by inspected files or command output?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6355 — Design
- Ask: Does the mobile layout preserve the intended visual hierarchy?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6360 — Projects
- Ask: Can the owner update this project without editing presentation code?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6365 — Accessibility
- Ask: Is focus visible and logically ordered?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6370 — Performance
- Ask: Does the change avoid unnecessary script or image payload?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
### Engineering decision review 6375 — Testing
- Ask: What is the smallest meaningful regression test for this change?
- Record: evidence, affected file or route, decision, and validation result.
- Rule: if evidence is unavailable, mark the item unverified rather than assuming success.
- Follow-up: make the smallest safe correction or document why no change is required.
# End of TechITInsights Master Engineering Skill — 7,000 lines
