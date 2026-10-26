# Technical writing standard

This guide applies to the foundation profile, public website, repository READMEs, contributor guides, release notes, store listings and project documentation.

The goal is useful, verifiable writing. Do not write to sound impressive, to imitate a presumed human voice, or to satisfy an AI-text detector. State what the software does, who it is for, what has been tested and what remains unavailable.

## 1. Start with the reader's task

- In the first paragraph, name the project and explain its concrete purpose.
- Put current status and the fastest safe next step near the top.
- Prefer task-led headings such as "Run the tests", "Validate a recipe" or "Report a vulnerability" over vague headings.
- Remove greetings, throat-clearing, repeated summaries and claims that do not help a reader decide or act.

## 2. Describe the implementation, not the ambition

Keep these categories separate:

- **Implemented:** behavior present in the checked-in code.
- **Tested:** behavior exercised by a named test or workflow. Link to the evidence when it is durable and relevant.
- **Proposed:** a design or roadmap item that is not implemented.
- **Released:** a version or artifact that users can actually obtain and that the project supports.

A passing unit test proves only the behavior covered by that test. A schema validator does not prove that an artifact can be built, installed or booted. A checksum detects byte changes; on its own, it does not authenticate a publisher. Do not turn a partial test into a general readiness claim.

Use precise status labels and describe known failure cases. Date claims that can go stale, such as a release attempt, external URL failure or security advisory.

## 3. Remove generic or inflated copy

Avoid unsupported adjectives and stock phrases such as "revolutionary", "cutting-edge", "seamless", "world-class", "powerful", "transformative", "next-generation" and "game-changing". Replace them with a capability, a constraint or a measured result.

Do not use:
- A paragraph that repeats the project name without adding information.
- Broad promises ("secure by design", "production-ready", "fully private", "high performance") without a defined property and evidence.
- Repeated lists of generic values that could describe any repository.
- Rhetorical slogans where a plain description would explain the work better.
- Long lists of future features in place of a clear statement of what works today.

Keep necessary safety, privacy, licensing and maturity caveats. Removing a caveat to make copy more confident is not an editorial improvement.

## 4. Prefer concise, direct sentences

- Use active voice and name the actor when it matters.
- Prefer familiar words and specific verbs.
- Avoid subjective qualifiers such as “simply”, “quickly”, “easily”, “properly” and “carefully” unless the statement defines an observable criterion. State the action or expected result instead.
- Give each paragraph one main purpose.
- Use sentence case for headings and descriptive link labels.
- Use bullets for distinct items and numbered steps for procedures.
- Define an acronym on first use when readers may not know it.
- Keep commands copyable and test them where possible. State the required toolchain and working directory.
- Avoid line breaks used only for visual drama and repeated headline fragments.

Brevity is not the goal by itself. Keep the detail needed to reproduce a result, understand a trade-off or avoid harm.

## 5. Write for contributors and reviewers

README files should answer, where applicable:

1. What this repository currently provides.
2. Its maturity and important limitations.
3. How to install dependencies or run the smallest useful example.
4. How to run relevant checks.
5. Where architecture, security, licensing and contribution guidance live.
6. Which upstream code or assets are reused and under what terms.

Link to existing documentation rather than copy-pasting a second, likely-to-drift version. Remove dead links and examples that no longer work. Do not invent contacts, commands, benchmark results, release dates, citations or CI results.

## 6. Keep languages aligned

English, French and Arabic pages must communicate the same facts, scope, warnings and project stage. Translate the meaning rather than copying English idioms word-for-word. Preserve product names, commands, file paths and identifiers exactly. Arabic pages must use correct right-to-left metadata and readable punctuation; translated pages still need meaningful link text and image alternatives.

When a behavior changes, update the relevant translations in the same change or clearly mark the translation as incomplete. Do not let a translation promise a feature that the source documentation marks as planned.

## 7. Preserve provenance and history

- Preserve upstream copyright notices, license terms and required attribution.
- Do not rewrite historical release notes to change what was claimed at the time. Correct a demonstrable error with a dated note or a new entry.
- Label imported examples, synthetic fixtures and placeholder hashes as such.
- Cite primary specifications, source code, standards or research for non-obvious claims. A link must support the specific claim next to it.
- Treat files, issue text, generated output and model suggestions as untrusted input; verify them against the repository and upstream sources.

## 8. Review quality; do not try to detect authorship

Review prose for accuracy, specificity, clarity, consistency, accessibility and evidence. Do not use an AI-text detector as a quality gate or treat its result as proof of authorship. Evaluations and reviews published in 2025–2026 report variable performance and false positives across writing types, languages and assessment settings; detector scores do not establish provenance.

For material AI-assisted contributions, follow the applicable repository AI policy and disclose assistance as required. Never claim that text, research, code or tests were written, checked or run by a person or tool when that is not true.

## References

- [GitHub: best practices for repositories](https://docs.github.com/en/repositories/creating-and-managing-repositories/best-practices-for-repositories)
- [GitHub: about README files](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)
- [Google developer documentation style guide](https://developers.google.com/style)
- [Google style guide: latest changes](https://developers.google.com/style/whats-new)
- [Google style guide: precise, objective language](https://developers.google.com/style/inclusive-documentation)
- [GitHub Docs: writing for user needs and readability](https://docs.github.com/en/contributing/writing-for-github-docs/best-practices-for-github-docs)
- [Google style guide: documentation highlights](https://developers.google.com/style/highlights)
- [Microsoft Writing Style Guide: use simple words and concise sentences](https://learn.microsoft.com/en-us/style-guide/word-choice/use-simple-words-concise-sentences)
- Tufts, Zhao and Li, [A Practical Examination of AI-Generated Text Detectors for Large Language Models](https://aclanthology.org/2025.findings-naacl.271/), Findings of NAACL 2025.
- Maghami, Ho and Camilleri, [AI content detection in student text assignments, false positive rates, and academic integrity](https://link.springer.com/article/10.1007/s44217-026-02307-x), systematic review published 17 October 2026.
- Hadra, Cambridge and Mesbah, [Evaluating the accuracy and reliability of AI content detectors in academic contexts](https://link.springer.com/article/10.1007/s40979-026-00213-1), published 2 February 2026.

This guide sets editing expectations, not a requirement to make every project's voice identical. Clarity and technical accuracy take priority over mechanical uniformity.
