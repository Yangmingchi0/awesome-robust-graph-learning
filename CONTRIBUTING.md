# Contributing to the Community Curation Fork

> **Repository status:** this is the personal curation fork [Yangmingchi0/awesome-robust-graph-learning](https://github.com/Yangmingchi0/awesome-robust-graph-learning). The canonical FinD Lab resource list remains [ICT-FinD-Lab/awesome-robust-graph-learning](https://github.com/ICT-FinD-Lab/awesome-robust-graph-learning). Changes here do not modify the upstream repository or represent an endorsement by its original maintainers.

Thank you for helping keep robust graph learning resources accurate, useful, and reproducible. This guide defines the evidence and metadata expected for additions to this fork.

## What belongs in the collection

Contributions should have a clear connection to at least one of these areas:

- Graph adversarial attacks, backdoors, poisoning, evasion, or model extraction
- Adversarial defenses and certified or empirical robustness
- Graph structure learning under noisy, weak, or corrupted information
- Graph anomaly and outlier detection
- Graph out-of-distribution detection, adaptation, or generalization
- Privacy, fairness, safety, or trustworthy evaluation for graph learning
- Benchmarks, datasets, tutorials, surveys, workshops, and maintained toolkits

A paper or resource should add meaningful coverage rather than duplicate an existing entry with less authoritative metadata.

## Submission checklist

For each proposed paper, provide:

- Full title
- Authoritative paper link: publisher, DOI, OpenReview, or arXiv
- Venue and year
- Primary category and, when useful, a secondary category
- Official code, project page, dataset, or benchmark link if available
- One concise sentence explaining why the work belongs in the collection

For a dataset or toolkit, also provide:

- Maintainer or institution
- Supported tasks and graph types
- License link
- Documentation link
- Most recent release or meaningful update date

For a tutorial, workshop, or course, include the hosting venue, date, speakers or organizers, and an official materials page.

## Evidence rules

1. Prefer publisher pages, DOI records, official conference pages, author project pages, and the authors' source repository.
2. Do not infer venue acceptance from an unverified social post or repository description.
3. Use the archival venue year when available; identify preprints explicitly.
4. Link to the authors' repository instead of an unrelated mirror.
5. Do not copy abstracts or long descriptions. Write a short factual summary.
6. Mark inaccessible, withdrawn, superseded, or archived resources clearly rather than silently removing them.

## Formatting conventions

- Keep titles in the capitalization used by the paper or publisher.
- Use a consistent venue abbreviation, such as NeurIPS, ICML, ICLR, KDD, WWW, AAAI, IJCAI, or CIKM.
- Use HTTPS links whenever the authoritative source supports them.
- Add entries to the most specific existing section.
- Preserve the reference numbering and bibliography mapping used by the README.
- Avoid promotional wording such as “best,” “state of the art,” or “groundbreaking” unless it is part of a quoted title.

## Link and metadata maintenance

The community fork follows this lightweight cycle:

### Monthly review

- Check newly added links and a rotating sample of older links.
- Replace unofficial mirrors with authoritative sources when possible.
- Check whether preprints have received an archival venue or DOI.
- Record new official code, dataset, and project-page links.

### Quarterly review

- Revisit section boundaries and duplicate entries.
- Check major toolkit releases and benchmark status.
- Review whether rapidly growing topics need a dedicated subsection.
- Compare the fork with upstream and document intentional differences.

## Pull request scope

Keep each pull request focused on one topic or a small, reviewable batch. The description should include:

- The section changed
- Sources used to verify metadata
- Whether links were tested
- Any uncertain classification or licensing detail

Large mechanical rewrites, category redesigns, or automated bulk additions should start as an issue in this fork. They will not be pushed to the upstream repository without a separate request and permission from the original maintainers.

## Licensing and attribution

The upstream repository includes an MIT License. Preserve copyright notices and attribution when reusing its material. Linked papers, datasets, websites, and software retain their own licenses and terms; inclusion in this list does not grant redistribution rights.

## Maintainer boundary

This fork is maintained independently to avoid changing repositories owned or led by other FinD Lab members. Questions about the canonical list should go to the [upstream repository](https://github.com/ICT-FinD-Lab/awesome-robust-graph-learning). Suggestions specifically for this community fork may use its issue tracker.

---

Curation policy established: **2026-09-28** · Community maintainer: [Yangmingchi0](https://github.com/Yangmingchi0)
