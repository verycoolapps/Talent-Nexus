# Boolean and Keyword Search Playbook

These are query-building examples, not searches or promises of results. Adapt to the selected source's own syntax. Operators vary; verify platform documentation and use only permitted manual or tool-mediated access.

## Build a query

1. Start with role/discipline terms and synonyms.
2. Add evidence terms (for example, project, publication, portfolio, talk, repository) tied to relevant work.
3. Add location, language, or seniority only when job-related and necessary.
4. Exclude irrelevant terms sparingly; inspect the query for proxies for protected traits.
5. Split a broad query into several narrow searches rather than collecting at scale.

## Illustrative patterns

```text
("software engineer" OR "software developer") AND (Indonesia OR Jakarta OR Bandung)
("security researcher" OR "security engineer") AND (cloud OR application security) AND (talk OR paper OR project)
("researcher" OR professor) AND (topic OR method) AND (publication OR lab)
(designer OR "visual designer") AND (portfolio OR case study) AND (product OR brand)
```

Example query for a human to adapt to a code-hosting source:

```text
language:TypeScript topic:accessibility (project OR repository)
```

This is illustrative only: syntax may not work on a given platform, and it does not assert that a search was run or returned anyone.

## Keyword bank by evidence

- Engineering: language/framework, shipped project, repository, architecture, testing, reliability.
- Cybersecurity: defensive specialty, responsible disclosure, research publication, conference talk, security tool.
- Research: field, method, publication, lab/institution, dataset or preprint.
- Design: discipline, portfolio, case study, product/brand, accessibility.
- Branding/content: professional writing, campaign, public talk, portfolio, editorial work.
- Career transition: transferable project, coursework, credential, work sample; do not presume readiness or infer personal circumstances.

## Quality and safety

Keep an audit note of query intent and source/method. Do not use protected traits or proxies, private contact details, personal behavior signals, leaked material, or searches designed to expose sensitive data. Search syntax is not authorization. Return query strings separately from observed results.
