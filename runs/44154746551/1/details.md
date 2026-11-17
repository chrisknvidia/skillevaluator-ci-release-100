# SkillEvaluator evaluation report

**Tier 1 scan result: PASSED**

2 skills · 2 passed · 0 failed · 0 incomplete

Errors: 0 · Warnings: 10

## Evaluation scope

Tier 1: executed for 2/2 skills with validator evidence; result PASSED\. Tier 2: Not run\. Tier 3: Not run\.

Recorded LLM stages: skipped\. LLM checks disabled by \-\-no\-llm\.

Static scanner outcomes do not establish behavioral usefulness. Not run tiers are not passes.

[Open full report](https://chrisknvidia.github.io/skillevaluator-ci-release-100/runs/44154746551/1/index.html) · [Workflow run and logs](https://github.com/chrisknvidia/skillevaluator-ci-release-100/actions/runs/44154746551)

**CI run conclusion:** success

**Commit:** a6c903e99311271bb57b1f340ec9b61f25eaad26

**Runtime image:** ghcr\.io/chrisknvidia/skillevaluator\-candidate\-100@​sha256:6d0e40257bebba9f6908bad0164bc5497d6f17e95c2df649746f64d07c456deb

## Skills and scores

| Skill | Tier 1 | Quality / 100 | Grade | Errors | Warnings |
| --- | --- | --- | --- | --- | --- |
| skills/evidence\-table | PASS | 100 | A | 0 | 6 |
| skills/glossary\-builder | PASS | 100 | A | 0 | 4 |

## skills/evidence\-table

[Skill details](https://chrisknvidia.github.io/skillevaluator-ci-release-100/runs/44154746551/1/index.html#skill-001) · [Native HTML](https://chrisknvidia.github.io/skillevaluator-ci-release-100/runs/44154746551/1/skill-001/skillevaluator-tier1.html) · [JSON](https://chrisknvidia.github.io/skillevaluator-ci-release-100/runs/44154746551/1/skill-001/skillevaluator-tier1.json)

### Recorded quality dimensions

| Dimension | Score / 100 | Weight | Issues |
| --- | --- | --- | --- |
| correctness | 100 | 0\.35 | 0 |
| discoverability | 100 | 0\.25 | 0 |
| reliability | 100 | 0\.25 | 0 |
| efficiency | 100 | 0\.15 | 0 |

### Validator outcomes

| Validator | Outcome | Checks recorded | Errors | Warnings |
| --- | --- | --- | --- | --- |
| Schema &amp; Repository Governance | PASS | 11 | 0 | 2 |
| Semantic Version Validation | PASS | 1 | 0 | 0 |
| Security Scan | PASS | 1 | 0 | 0 |
| PII Scan | PASS | 2 | 0 | 0 |
| License Compliance | PASS | 1 | 0 | 0 |
| Code Risk Analysis | NOT APPLICABLE | 1 | 0 | 0 |
| Secrets Detection | PASS | 1 | 0 | 0 |
| Code Integrity &amp; Hygiene | PASS | 4 | 0 | 1 |
| Dependency Vulnerability Audit | NOT APPLICABLE | 1 | 0 | 0 |
| Unicode Smuggling Detection | PASS | 1 | 0 | 0 |
| QUALITY | PASS | 1 | 0 | 0 |
| SCRIPT\_LINT | NOT APPLICABLE | 1 | 0 | 0 |
| Harness Compatibility | PASS | 0 | 0 | 3 |

### Schema &amp; Repository Governance — evidence

**Evidence: manifest\_exists:** Found skill manifest: SKILL\.md

**Evidence metadata:** \{"file\_path": "/workspace/skills/evidence\-table/SKILL\.md"\}

**Evidence: frontmatter\_valid:** Valid frontmatter for skill 'evidence\-table'

**Evidence metadata:** \{"description\_length": 142\}

**Evidence: folder\_hierarchy:** Valid general skill structure: skills/evidence\-table/

**Evidence: naming\_convention:** Folder name 'evidence\-table' follows kebab\-case convention

**Evidence metadata:** \{"name\_length": 14\}

**Evidence: line\_count:** SKILL\.md within line limit \(57/500\)

**Evidence metadata:** \{"limit": 500, "line\_count": 57\}

**Evidence: body\_heading:** Body contains a top\-level heading

**Evidence: body\_recommended\_section:** Found recommended section: '\#\# Instructions' \(or '\#\# Usage'\)

**Evidence: body\_recommended\_section:** Found recommended section: '\#\# Examples'

**Evidence: optional\_files:** Skill directory contains only expected files

**Evidence: name\_consistency:** Directory name matches frontmatter: 'evidence\-table'

**Evidence: author\_format:** Valid author format: SkillEvaluator CI Demo Authors &lt;ci\-demo@​example\.com&gt;

**Finding: description\_trigger \(low\):** Description has its trigger at characters 67\-75; some harnesses show only the first \~60 characters in their skill list

**File:** /workspace/skills/evidence\-table/SKILL\.md

**Suggested fix:** State when to use the skill within the first 60 characters

**Warning:** \[SCHEMA\-LOW\] Description has its trigger at characters 67\-75; some harnesses show only the first \~60 characters in their skill list in /workspace/skills/evidence\-table/SKILL\.md

**Warning:** Workflow scope: llm skipped\. LLM checks disabled by \-\-no\-llm\.

**Scanner message:** \[OK\] manifest\_exists: Found skill manifest: SKILL\.md

**Scanner message:** \[OK\] frontmatter\_valid: Valid frontmatter for skill 'evidence\-table'

**Scanner message:** \[OK\] folder\_hierarchy: Valid general skill structure: skills/evidence\-table/

**Scanner message:** \[OK\] naming\_convention: Folder name 'evidence\-table' follows kebab\-case convention

**Scanner message:** \[OK\] line\_count: SKILL\.md within line limit \(57/500\)

**Scanner message:** \[OK\] body\_heading: Body contains a top\-level heading

**Scanner message:** \[OK\] body\_recommended\_section: Found recommended section: '\#\# Instructions' \(or '\#\# Usage'\)

**Scanner message:** \[OK\] body\_recommended\_section: Found recommended section: '\#\# Examples'

**Scanner message:** \[OK\] optional\_files: Skill directory contains only expected files

**Scanner message:** \[OK\] name\_consistency: Directory name matches frontmatter: 'evidence\-table'

**Scanner message:** \[OK\] author\_format: Valid author format: SkillEvaluator CI Demo Authors &lt;ci\-demo@​example\.com&gt;

### Semantic Version Validation — evidence

**Evidence: version\_semver:** Valid semantic version: 1\.0\.0

**Evidence metadata:** \{"previous\_version": null, "version": "1\.0\.0"\}

**Scanner message:** \[OK\] version\_semver: Valid semantic version: 1\.0\.0

### Security Scan — evidence

**Evidence: skillspector:** No security vulnerabilities detected \(secrets, API keys, credentials\)

**Scanner message:** \[OK\] skillspector: No security vulnerabilities detected \(secrets, API keys, credentials\)

### PII Scan — evidence

**Evidence: pii\_scan\_start:** Scanning 1 files for PII

**Evidence metadata:** \{"file\_count": 1\}

**Evidence: pii\_detection:** No PII detected in 1 files \(emails, SSNs, phone numbers, paths\)

**Evidence metadata:** \{"files\_scanned": 1\}

**Scanner message:** \[OK\] pii\_scan\_start: Scanning 1 files for PII

**Scanner message:** \[OK\] pii\_detection: No PII detected in 1 files \(emails, SSNs, phone numbers, paths\)

### License Compliance — evidence

**Evidence: license\_compliance:** License compliance scan completed \(allowed\)

**Evidence metadata:** \{"license\_status": "allowed"\}

**Scanner message:** Tier 1: Found license declaration in frontmatter \(SKILL\.md\)

**Scanner message:** License: MIT \(ALLOWED \- permissive\)

**Scanner message:** \[OK\] license\_compliance: License compliance scan completed \(allowed\)

### Code Risk Analysis — evidence

**Evidence: code\_file\_discovery:** No code files found \- code risk analysis is not applicable

**Evidence metadata:** \{"file\_counts": \{"js": 0, "py": 0, "sh": 0\}\}

**Scanner message:** \[OK\] code\_file\_discovery: No code files found \- code risk analysis is not applicable

### Secrets Detection — evidence

**Evidence: gitleaks:** No secrets detected by Gitleaks

**Scanner message:** \[OK\] gitleaks: No secrets detected by Gitleaks

### Code Integrity &amp; Hygiene — evidence

**Evidence: dead\_links\_scan:** Checking 1 markdown files for dead links

**Evidence metadata:** \{"file\_count": 1\}

**Evidence: dead\_links:** All relative links valid in 1 markdown file\(s\)

**Evidence metadata:** \{"files\_checked": 1\}

**Evidence: dependencies:** No dependency files found \(requirements\.txt, pyproject\.toml\)

**Evidence: test\_discovery:** No standard Python test\-file candidates found; target tests were not executed and coverage was not measured\. Consider adding tests\.

**Evidence metadata:** \{"coverage\_measured": false, "execution\_performed": false, "patterns": \["test\_\*\.py", "\*\_test\.py"\], "test\_count": 0\}

**Warning:** No standard Python test\-file candidates found; consider adding tests

**Scanner message:** \[OK\] dead\_links\_scan: Checking 1 markdown files for dead links

**Scanner message:** \[OK\] dead\_links: All relative links valid in 1 markdown file\(s\)

**Scanner message:** \[OK\] dependencies: No dependency files found \(requirements\.txt, pyproject\.toml\)

**Scanner message:** \[OK\] test\_discovery: No standard Python test\-file candidates found; target tests were not executed and coverage was not measured\. Consider adding tests\.

### Dependency Vulnerability Audit — evidence

**Evidence: dependency\_file\_discovery:** No dependency files found \- vulnerability audit is not applicable

**Scanner message:** \[OK\] dependency\_file\_discovery: No dependency files found \- vulnerability audit is not applicable

### Unicode Smuggling Detection — evidence

**Evidence: unicode\_scan:** No invisible Unicode characters detected in 1 file\(s\)

**Evidence metadata:** \{"files\_scanned": 1\}

**Scanner message:** \[OK\] unicode\_scan: No invisible Unicode characters detected in 1 file\(s\)

### QUALITY — evidence

**Evidence: quality\_score:** Score: 100\.0/100 \(Grade: A\)

**Evidence metadata:** \{"grade": "A", "overall\_score": 100\.0, "skill\_type": "guide\-only"\}

**Scanner message:** \[OK\] quality\_score: Score: 100\.0/100 \(Grade: A\)

### SCRIPT\_LINT — evidence

**Evidence: lint:** No scripts/ or tools/ directory found

**Scanner message:** \[OK\] lint: No scripts/ or tools/ directory found

### Harness Compatibility — evidence

**Finding: CP\-RELOAD \(info\):** copilot\-cli: New skills appear only after \`/skills reload\` or a restart; edits to existing skills apply at once\.

**File:** /workspace/skills/evidence\-table/SKILL\.md

**Finding metadata:** \{"effect": "advisory", "harness": "copilot\-cli", "verified\_date": "2026\-11\-01", "verified\_version": "1\.0\.105"\}

**Finding: HM\-DESC\-60 \(info\):** hermes: The skill list shows only the first \~60 chars of the description \(57 \+ '\.\.\.' in 0\.16, a word boundary near 59 on main\), and the trigger isn't in them\.

**File:** /workspace/skills/evidence\-table/SKILL\.md

**Suggested fix:** Put the trigger \("Use when …"\) in the first 57 characters\.

**Finding metadata:** \{"effect": "advisory", "harness": "hermes", "verified\_date": "2026\-11\-01", "verified\_version": "main @​ c419cf7c864a \(binary reports 2026\.9\.24\)"\}

**Finding: OC\-RELOAD \(info\):** opencode: Skill list and text are cached at startup; edits need a restart\.

**File:** /workspace/skills/evidence\-table/SKILL\.md

**Finding metadata:** \{"effect": "advisory", "harness": "opencode", "verified\_date": "2026\-11\-01", "verified\_version": "1\.19\.5"\}

**Warning:** \[HARNESS\-INFO\] copilot\-cli: New skills appear only after \`/skills reload\` or a restart; edits to existing skills apply at once\. in /workspace/skills/evidence\-table/SKILL\.md

**Warning:** \[HARNESS\-INFO\] hermes: The skill list shows only the first \~60 chars of the description \(57 \+ '\.\.\.' in 0\.16, a word boundary near 59 on main\), and the trigger isn't in them\. in /workspace/skills/evidence\-table/SKILL\.md

**Warning:** \[HARNESS\-INFO\] opencode: Skill list and text are cached at startup; edits need a restart\. in /workspace/skills/evidence\-table/SKILL\.md

## skills/glossary\-builder

[Skill details](https://chrisknvidia.github.io/skillevaluator-ci-release-100/runs/44154746551/1/index.html#skill-002) · [Native HTML](https://chrisknvidia.github.io/skillevaluator-ci-release-100/runs/44154746551/1/skill-002/skillevaluator-tier1.html) · [JSON](https://chrisknvidia.github.io/skillevaluator-ci-release-100/runs/44154746551/1/skill-002/skillevaluator-tier1.json)

### Recorded quality dimensions

| Dimension | Score / 100 | Weight | Issues |
| --- | --- | --- | --- |
| correctness | 100 | 0\.35 | 0 |
| discoverability | 100 | 0\.25 | 0 |
| reliability | 100 | 0\.25 | 0 |
| efficiency | 100 | 0\.15 | 0 |

### Validator outcomes

| Validator | Outcome | Checks recorded | Errors | Warnings |
| --- | --- | --- | --- | --- |
| Schema &amp; Repository Governance | PASS | 11 | 0 | 1 |
| Semantic Version Validation | PASS | 1 | 0 | 0 |
| Security Scan | PASS | 1 | 0 | 0 |
| PII Scan | PASS | 2 | 0 | 0 |
| License Compliance | PASS | 1 | 0 | 0 |
| Code Risk Analysis | NOT APPLICABLE | 1 | 0 | 0 |
| Secrets Detection | PASS | 1 | 0 | 0 |
| Code Integrity &amp; Hygiene | PASS | 4 | 0 | 1 |
| Dependency Vulnerability Audit | NOT APPLICABLE | 1 | 0 | 0 |
| Unicode Smuggling Detection | PASS | 1 | 0 | 0 |
| QUALITY | PASS | 1 | 0 | 0 |
| SCRIPT\_LINT | NOT APPLICABLE | 1 | 0 | 0 |
| Harness Compatibility | PASS | 0 | 0 | 2 |

### Schema &amp; Repository Governance — evidence

**Evidence: manifest\_exists:** Found skill manifest: SKILL\.md

**Evidence metadata:** \{"file\_path": "/workspace/skills/glossary\-builder/SKILL\.md"\}

**Evidence: frontmatter\_valid:** Valid frontmatter for skill 'glossary\-builder'

**Evidence metadata:** \{"description\_length": 133\}

**Evidence: folder\_hierarchy:** Valid general skill structure: skills/glossary\-builder/

**Evidence: naming\_convention:** Folder name 'glossary\-builder' follows kebab\-case convention

**Evidence metadata:** \{"name\_length": 16\}

**Evidence: line\_count:** SKILL\.md within line limit \(55/500\)

**Evidence metadata:** \{"limit": 500, "line\_count": 55\}

**Evidence: body\_heading:** Body contains a top\-level heading

**Evidence: body\_recommended\_section:** Found recommended section: '\#\# Instructions' \(or '\#\# Usage'\)

**Evidence: body\_recommended\_section:** Found recommended section: '\#\# Examples'

**Evidence: optional\_files:** Skill directory contains only expected files

**Evidence: name\_consistency:** Directory name matches frontmatter: 'glossary\-builder'

**Evidence: author\_format:** Valid author format: SkillEvaluator CI Demo Authors &lt;ci\-demo@​example\.com&gt;

**Warning:** Workflow scope: llm skipped\. LLM checks disabled by \-\-no\-llm\.

**Scanner message:** \[OK\] manifest\_exists: Found skill manifest: SKILL\.md

**Scanner message:** \[OK\] frontmatter\_valid: Valid frontmatter for skill 'glossary\-builder'

**Scanner message:** \[OK\] folder\_hierarchy: Valid general skill structure: skills/glossary\-builder/

**Scanner message:** \[OK\] naming\_convention: Folder name 'glossary\-builder' follows kebab\-case convention

**Scanner message:** \[OK\] line\_count: SKILL\.md within line limit \(55/500\)

**Scanner message:** \[OK\] body\_heading: Body contains a top\-level heading

**Scanner message:** \[OK\] body\_recommended\_section: Found recommended section: '\#\# Instructions' \(or '\#\# Usage'\)

**Scanner message:** \[OK\] body\_recommended\_section: Found recommended section: '\#\# Examples'

**Scanner message:** \[OK\] optional\_files: Skill directory contains only expected files

**Scanner message:** \[OK\] name\_consistency: Directory name matches frontmatter: 'glossary\-builder'

**Scanner message:** \[OK\] author\_format: Valid author format: SkillEvaluator CI Demo Authors &lt;ci\-demo@​example\.com&gt;

### Semantic Version Validation — evidence

**Evidence: version\_semver:** Valid semantic version: 1\.0\.0

**Evidence metadata:** \{"previous\_version": null, "version": "1\.0\.0"\}

**Scanner message:** \[OK\] version\_semver: Valid semantic version: 1\.0\.0

### Security Scan — evidence

**Evidence: skillspector:** No security vulnerabilities detected \(secrets, API keys, credentials\)

**Scanner message:** \[OK\] skillspector: No security vulnerabilities detected \(secrets, API keys, credentials\)

### PII Scan — evidence

**Evidence: pii\_scan\_start:** Scanning 1 files for PII

**Evidence metadata:** \{"file\_count": 1\}

**Evidence: pii\_detection:** No PII detected in 1 files \(emails, SSNs, phone numbers, paths\)

**Evidence metadata:** \{"files\_scanned": 1\}

**Scanner message:** \[OK\] pii\_scan\_start: Scanning 1 files for PII

**Scanner message:** \[OK\] pii\_detection: No PII detected in 1 files \(emails, SSNs, phone numbers, paths\)

### License Compliance — evidence

**Evidence: license\_compliance:** License compliance scan completed \(allowed\)

**Evidence metadata:** \{"license\_status": "allowed"\}

**Scanner message:** Tier 1: Found license declaration in frontmatter \(SKILL\.md\)

**Scanner message:** License: MIT \(ALLOWED \- permissive\)

**Scanner message:** \[OK\] license\_compliance: License compliance scan completed \(allowed\)

### Code Risk Analysis — evidence

**Evidence: code\_file\_discovery:** No code files found \- code risk analysis is not applicable

**Evidence metadata:** \{"file\_counts": \{"js": 0, "py": 0, "sh": 0\}\}

**Scanner message:** \[OK\] code\_file\_discovery: No code files found \- code risk analysis is not applicable

### Secrets Detection — evidence

**Evidence: gitleaks:** No secrets detected by Gitleaks

**Scanner message:** \[OK\] gitleaks: No secrets detected by Gitleaks

### Code Integrity &amp; Hygiene — evidence

**Evidence: dead\_links\_scan:** Checking 1 markdown files for dead links

**Evidence metadata:** \{"file\_count": 1\}

**Evidence: dead\_links:** All relative links valid in 1 markdown file\(s\)

**Evidence metadata:** \{"files\_checked": 1\}

**Evidence: dependencies:** No dependency files found \(requirements\.txt, pyproject\.toml\)

**Evidence: test\_discovery:** No standard Python test\-file candidates found; target tests were not executed and coverage was not measured\. Consider adding tests\.

**Evidence metadata:** \{"coverage\_measured": false, "execution\_performed": false, "patterns": \["test\_\*\.py", "\*\_test\.py"\], "test\_count": 0\}

**Warning:** No standard Python test\-file candidates found; consider adding tests

**Scanner message:** \[OK\] dead\_links\_scan: Checking 1 markdown files for dead links

**Scanner message:** \[OK\] dead\_links: All relative links valid in 1 markdown file\(s\)

**Scanner message:** \[OK\] dependencies: No dependency files found \(requirements\.txt, pyproject\.toml\)

**Scanner message:** \[OK\] test\_discovery: No standard Python test\-file candidates found; target tests were not executed and coverage was not measured\. Consider adding tests\.

### Dependency Vulnerability Audit — evidence

**Evidence: dependency\_file\_discovery:** No dependency files found \- vulnerability audit is not applicable

**Scanner message:** \[OK\] dependency\_file\_discovery: No dependency files found \- vulnerability audit is not applicable

### Unicode Smuggling Detection — evidence

**Evidence: unicode\_scan:** No invisible Unicode characters detected in 1 file\(s\)

**Evidence metadata:** \{"files\_scanned": 1\}

**Scanner message:** \[OK\] unicode\_scan: No invisible Unicode characters detected in 1 file\(s\)

### QUALITY — evidence

**Evidence: quality\_score:** Score: 100\.0/100 \(Grade: A\)

**Evidence metadata:** \{"grade": "A", "overall\_score": 100\.0, "skill\_type": "guide\-only"\}

**Scanner message:** \[OK\] quality\_score: Score: 100\.0/100 \(Grade: A\)

### SCRIPT\_LINT — evidence

**Evidence: lint:** No scripts/ or tools/ directory found

**Scanner message:** \[OK\] lint: No scripts/ or tools/ directory found

### Harness Compatibility — evidence

**Finding: CP\-RELOAD \(info\):** copilot\-cli: New skills appear only after \`/skills reload\` or a restart; edits to existing skills apply at once\.

**File:** /workspace/skills/glossary\-builder/SKILL\.md

**Finding metadata:** \{"effect": "advisory", "harness": "copilot\-cli", "verified\_date": "2026\-11\-01", "verified\_version": "1\.0\.105"\}

**Finding: OC\-RELOAD \(info\):** opencode: Skill list and text are cached at startup; edits need a restart\.

**File:** /workspace/skills/glossary\-builder/SKILL\.md

**Finding metadata:** \{"effect": "advisory", "harness": "opencode", "verified\_date": "2026\-11\-01", "verified\_version": "1\.19\.5"\}

**Warning:** \[HARNESS\-INFO\] copilot\-cli: New skills appear only after \`/skills reload\` or a restart; edits to existing skills apply at once\. in /workspace/skills/glossary\-builder/SKILL\.md

**Warning:** \[HARNESS\-INFO\] opencode: Skill list and text are cached at startup; edits need a restart\. in /workspace/skills/glossary\-builder/SKILL\.md

[Open full report](https://chrisknvidia.github.io/skillevaluator-ci-release-100/runs/44154746551/1/index.html) · [Workflow run and logs](https://github.com/chrisknvidia/skillevaluator-ci-release-100/actions/runs/44154746551)
