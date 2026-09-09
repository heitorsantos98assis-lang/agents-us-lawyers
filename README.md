# 57 Agents for US Lawyers

**57 specialized Claude Code subagents for US-licensed attorneys and small firms practicing in federal + state courts (CA/NY/TX/FL/IL)** — built by senior practitioners, regulated for US business reality.

Each agent is a single drop-in Markdown file you copy into `.claude/agents/`. Claude Code routes work to the right specialist automatically.

---

## What's inside

| # | Agent | Focus |
|---|---|---|
| 01 | 01-docket-monitoring-pacer-state-efile | Specialist in daily docket monitoring across federal PACER/CM/ECF and state e-filing portals (NYSCEF, California Odyssey + coun |
| 02 | 02-deadline-calendaring-frcp-state | Specialist in deadline computation and calendaring under Fed |
| 03 | 03-matter-status-pacer-state-courts | Specialist in pulling current case status across federal CM/ECF/PACER and the major state court e-filing systems (NYSCEF; Calif |
| 04 | 04-notice-and-service-response | Specialist in distinguishing and handling (a) initial service of process under Fed |
| 05 | 05-notice-of-receipt-acknowledgment | Specialist in acknowledgment and non-opposition responses where US practice has no preclusion-triggering "notice of awareness"  |
| 06 | 06-complaint-drafting-federal-state | Specialist in drafting federal and state civil complaints |
| 07 | 07-answer-and-affirmative-defenses | Specialist in drafting answers to federal and state complaints |
| 08 | 08-appellate-strategy-and-brief | Specialist in federal and state appellate practice |
| 09 | 09-legal-memorandum-opinion-letter | Specialist in producing three distinct US legal-writing deliverables — (a) interoffice legal memorandum (associate-to-partner f |
| 10 | 10-engagement-letter-and-notice-of-appearance | Specialist in the two-step US client engagement process — (a) the written engagement letter / retainer agreement, mandatory in  |
| 11 | 11-scotus-circuit-research | Specialist in US case-law research — SCOTUS, US Circuit Courts of Appeals (1st-11th, D.C., Federal), US District Courts, state  |
| 12 | 12-treatises-restatements-secondary | Specialist in US secondary-source research — Restatements (American Law Institute); leading treatises (Wright & Miller Federal  |
| 13 | 13-statutes-and-regulations-research | Specialist in US statutory and regulatory research — U.S |
| 14 | 14-binding-precedent-mdl-class-cert | Specialist in US doctrines that consolidate or coordinate parallel litigation and produce binding effect — (a) MDL (multidistri |
| 15 | 15-case-headnote-knowledge-bank | Specialist in building and maintaining a firm-internal case-law knowledge bank using headnote-style summaries (Westlaw KeyCite  |
| 16 | 16-new-client-matter-intake | Specialist in structured new-client and matter intake |
| 17 | 17-initial-client-counseling | Specialist in the initial client counseling session — translating intake analysis into a counseling conversation that meets ABA |
| 18 | 18-client-onboarding-engagement-iolta | Specialist in the complete client onboarding sequence after engagement letter is signed — (1) final Rule 1.7/1.9/1.10 conflicts |
| 19 | 19-client-communication-cadence | Specialist in client communication cadence and content under ABA Model Rule 1.4 (communication) — "keep the client reasonably i |
| 20 | 20-contract-clause-review-redline | Specialist in reviewing and redlining contract clauses for enforceability, allocation of risk, and one-sided terms |
| 21 | 21-contract-version-comparison-redline | Specialist in comparing two or more versions of the same contract — Microsoft Word track-changes + manual redline; Adobe Acroba |
| 22 | 22-privacy-data-protection-us-state | Specialist in the US privacy patchwork — California CCPA / CPRA (Cal |
| 23 | 23-mergers-acquisitions-due-diligence | Specialist in legal due diligence for M&A transactions |
| 24 | 24-attorney-fee-collection-disputes | Specialist in US attorney-fee collection from non-paying clients and fee-dispute resolution |
| 25 | 25-hearing-deposition-trial-prep-calendar | Specialist in the calendar and preparation choreography for hearings, depositions, settlement conferences, mediation, pretrial  |
| 26 | 26-case-file-summary-deposition-summary | Specialist in producing four distinct US litigation deliverables — (a) case brief / litigation summary (for in-house counsel ha |
| 27 | 27-law-firm-data-security-backup | Specialist in law-firm data security, backup, retention, and incident response |
| 28 | 28-federal-state-civil-appeal | Specialist in federal and state civil appeals |
| 29 | 29-interlocutory-appeal-writ-mandamus | Specialist in immediate appellate review of non-final orders in US courts — federal interlocutory appeals under 28 U.S.C |
| 30 | 30-debt-collection-action-and-monitory | Specialist in attorney-led commercial and consumer debt collection litigation in US courts — breach of contract actions, accoun |
| 31 | 31-employment-plaintiff-complaint-eeoc | Specialist in representing employees and applicants in federal and state discrimination, harassment, retaliation, wage-and-hour |
| 32 | 32-employer-defense-eeoc-flsa-discrim | Specialist in employer-side defense of discrimination, harassment, retaliation, wage-and-hour, and whistleblower claims under T |
| 33 | 33-severance-final-pay-calculation | Specialist in computing and documenting separation pay for US employees — final wages and timing under state-specific final-pay |
| 34 | 34-uncontested-divorce-marital-settlement | Specialist in uncontested divorce filings and marital settlement agreements (MSAs) under US state family-law regimes |
| 35 | 35-contested-divorce-litigation | Specialist in contested divorce litigation under US state family-law regimes — temporary orders pendente lite (custody, support |
| 36 | 36-child-spousal-support-action | Specialist in establishing, modifying, and enforcing child support and spousal support / alimony / maintenance under US state f |
| 37 | 37-probate-non-judicial-and-small-estate | Specialist in non-judicial and simplified probate transfers in US state probate regimes — small-estate affidavits (CA Prob |
| 38 | 38-child-custody-parenting-plan | Specialist in establishing, modifying, and enforcing child-custody and parenting-plan orders under US state family-law regimes |
| 39 | 39-criminal-defense-pretrial-motions | Specialist in pretrial criminal defense in US federal and state courts — initial appearance + bail/detention hearing (Bail Refo |
| 40 | 40-habeas-corpus-federal-state | Specialist in federal and state habeas corpus practice — 28 U.S.C |
| 41 | 41-tax-controversy-irs-state | Specialist in federal and state tax controversy — IRS exam (correspondence / office / field audit), 30-day letter response to A |
| 42 | 42-tax-collection-defense-cdp | Specialist in defending IRS and state tax collection actions — Collection Due Process hearing under IRC §§ 6320 (lien) / 6330 ( |
| 43 | 43-chapter-11-business-bankruptcy | Specialist in Chapter 11 business reorganization under Title 11 U.S.C |
| 44 | 44-llc-corp-formation-operating-agreement | Specialist in US entity formation and governance documents — LLC formation under state RULLCA (Cal |
| 45 | 45-shareholders-stockholders-agreement | Specialist in drafting and negotiating shareholders' / stockholders' agreements and LLC member agreements for US closely-held e |
| 46 | 46-consumer-protection-state-udap | Specialist in US consumer-protection claims under federal and state law — FTC Act § 5 (15 U.S.C |
| 47 | 47-eviction-unlawful-detainer | Specialist in residential and commercial eviction under US state-specific summary process — California (Cal |
| 48 | 48-commercial-lease-renewal-option | Specialist in US commercial-lease renewal, extension, and exit strategy |
| 49 | 49-quiet-title-non-judicial | Specialist in non-judicial title clearance in US real-property matters |
| 50 | 50-adverse-possession-quiet-title-judicial | Specialist in litigated quiet-title and adverse-possession actions in US state courts — Cal |
| 51 | 51-ssa-retirement-disability-claim | Specialist in Social Security Administration retirement and disability claims under Title II OASDI (42 U.S.C |
| 52 | 52-ssi-medicaid-needs-based-benefit | Specialist in US needs-based public benefits — Supplemental Security Income (SSI) Title XVI (42 U.S.C |
| 53 | 53-ssdi-disability-appeals-and-stc-disability | Specialist in disability claims and appeals across the full US disability ecosystem — SSDI Title II (42 U.S.C |
| 54 | 54-judgment-enforcement-collection | Specialist in post-judgment enforcement and collection in US federal and state courts |
| 55 | 55-post-judgment-debtor-defenses | Specialist in defending the judgment debtor against collection in US federal and state courts |
| 56 | 56-judgment-prejudgment-interest-calculation | Specialist in computing post-judgment and prejudgment interest in US federal and state courts — federal post-judgment per 28 U.S.C |
| 57 | 57-services-msa-sow-independent-contractor | Specialist in drafting and negotiating US services agreements — Master Services Agreement (MSA) with Statements of Work (SOW);  |

---

## Install one agent

```bash
cd path/to/your/project
mkdir -p .claude/agents
unzip 01-docket-monitoring-pacer-state-efile.zip
cp 01-docket-monitoring-pacer-state-efile/01-docket-monitoring-pacer-state-efile.md .claude/agents/
```

Restart Claude Code or run `/agents`. Done.

## Install all 57

```bash
unzip completo-57-agents-us-lawyers.zip
for z in [0-9][0-9]-*.zip; do unzip -o "$z"; done
mkdir -p ~/.claude/agents
find . -mindepth 2 -name '*.md' -not -name 'HOW-TO-INSTALL.md' -exec cp {} ~/.claude/agents/ \;
```

## How agents work

Each `.md` has YAML frontmatter defining when it fires. Claude Code reads the `description` and routes automatically — or invoke explicitly:

```
Use the docket-monitoring-pacer-state-efile subagent to ...
```

Each agent:
- Knows its scope (when to fire, when NOT to fire — delegates back to peers)
- Carries reference tables (codes, regulations, forms, formulas)
- Operates with a deliberate workflow (inputs → core deliverable → checklists)
- Cites authority in Bluebook style where regulatory ground matters
- Produces deliverables in `/tmp/` for review before pushing forward

## Requirements

- [Claude Code](https://docs.claude.com/claude-code) installed and logged in
- `unzip` on your machine

## Versioning

**v1.0** (May 2026). Updates ship as new uploads to this repo.

---

© HL. Built by operators for operators. No fluff.
