# Launch Scenario: ASI as a "Feedback-First" Layer in a Mobile Assistant

> **Status:** an illustrative scenario, not a specification. It shows one possible way to start an ASI node on top of an existing platform. It is not affiliated with, endorsed by, or planned by any company, including the operators of existing assistant platforms.

## Idea in One Paragraph

Instead of launching with "submit any technological idea", start with something every platform already accepts: **user suggestions about the platform's own product**. A user of a mobile assistant says or types: *"I'd like to suggest an improvement to the assistant or the system."* ASI processes the suggestion semantically, and the product team receives structured, deduplicated, ranked proposals instead of a raw stream of comments. As the node proves useful and the audience grows, the scope widens step by step.

## The Problem This Scenario Addresses

The classic "send feedback" form is a collection tool. It was designed for small volumes, where a person can read what arrives. At the scale of a mass-market product the situation is different:

- Thousands of messages a day can no longer be read one by one.
- Tens of thousands of suggestions cannot be sorted, compared, and merged by hand.
- Valuable proposals are buried among complaints, duplicates, and noise, and often never reach the people who could act on them.

Collecting the stream is the easy part. The hard part is **filtering, understanding, and routing it**, and that is exactly what ASI is built to do: it removes noise, recognizes that many people are describing the same mechanism, ranks proposals, and delivers them to the right team.

This is a hypothesis that the first stage of the scenario is designed to test, not a claim about the internal processes of any specific company.

## Why Start with Feedback

- **Lower legal friction.** Suggestions about a company's own product typically fall into a category platforms already handle under their terms, which makes this path easier than open-ended idea submission. The exact terms depend on the jurisdiction and on the platform and must be reviewed by qualified legal counsel.
- **Aligned incentives.** The operator and the recipient are the same team, and the recipient wants this input.
- **Clear value test.** Product teams already drown in feedback. If ASI cannot help there, it will not help anywhere.
- **Simple for the user.** One voice command or one text field, no forms.

## Scope of the First Version

- **Operator:** at this stage the node is run by the owner of the platform, or by a party the owner authorizes. The operator publishes the node's rules, privacy terms, and evaluation criteria, and meets the minimum requirements in Appendix J.2.
- **Submission modes:** open (linked to the account) and anonymous.
- **Protected (patent) model: disabled.** Not needed for product feedback. It can be added later.
- **Pre-evaluation:** removes spam, abuse, and empty messages. If it runs in the cloud, the user is told explicitly, before sending, that the text is processed on the operator's side (see Appendix J.2).
- **Central evaluation:** semantic normalization, mechanism-level deduplication, clustering of similar proposals, scoring by the usual criteria.
- **Analysts:** members of the product team, who receive ranked clusters with explanations (Chapters 16 and 17).
- **Load control:** an optional daily intake cap or dynamic threshold, as described in Chapter 15.3.

## Growth Path

| Stage | Scope | Condition for moving on |
|---|---|---|
| 1 | Suggestions for the assistant and the mobile OS | Analysts regularly find actionable proposals in the shortlist |
| 2 | Suggestions for other products of the same operator | Stable quality and manageable analyst load |
| 3 | Open common flow and connection of other organizations as nodes (Chapter 25). *Requires a separate legal and organizational model, which is outside the scope of this scenario.* | Trust in the node is established and legal profiles are defined |
| 4 | Optional protected model for verified authors | Counsel-approved terms and an open, auditable pre-evaluation module |

Each step is a decision, not an automatic consequence. The scenario may stop at any stage and still be useful.

## What to Measure

- Share of submissions that pass pre-evaluation
- Share of shortlisted proposals that analysts consider actionable
- Reduction of duplicate work compared with raw feedback handling
- Number of proposals that reach a roadmap or a team
- Author return rate and quality of repeat submissions
- Cost of processing one submission

## What This Scenario Is Not

- It is not a promise that any company will adopt it.
- It does not require any specific operator: the same scenario works for any assistant, operating system, or product with a feedback channel.
- It does not change the architecture. It is one configuration of an ASI node, in the spirit of Appendix G.
