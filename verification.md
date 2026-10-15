# Verification

Re-checked 15 Oct 2026. 8 rows were picked at random (seed 20261015) from the 9 in candidates.csv. Each row's first URL was reloaded in a browser and checked for the exact text the row relies on.

## Spot check (8 rows)

- **PASS**: AWS / Aniruddho Mukherjee. Page says `Aniruddho Mukherjee … Analyst Relations Lead EMEA`. https://analystrelations.org/about/iiar-board/
- **PASS**: Google Cloud / Stephanie Look. Page says `AR Professional of the Year 2025, Americas:s*Stephanie Look`. https://analystrelations.org/2025/12/11/and-the-winners-are-celebrating-the-iiar-awards-recipients-for-2025/
- **PASS**: GitLab / Jennifer Malleo. Page says `Media Contact … Jennifer Malleo`. https://about.gitlab.com/press/releases/2024-08-22-gitlab-recognized-as-a-leader-in-inaugural-2024-gartner-magic-quadrant-for-ai-code-assistants/
- **PASS**: GitLab / Laura (lclymer). Page says `lclymer), Director of Market Strategy`. https://gitlab.com/gitlab-com/content-sites/handbook/-/raw/main/content/handbook/marketing/corporate-communications/analyst-relations/_index.md
- **PASS**: GitHub / Rachel Carbino. Page says `Analyst Relations for GitHub`. https://x.com/Rachel_Carbino
- **PASS**: GitLab / Ryan Ragozzine. Page says `ryanragozzine), Staff Analyst Relations Manager`. https://gitlab.com/gitlab-com/content-sites/handbook/-/raw/46417d0228/content/handbook/marketing/brand-and-product-marketing/product-and-solution-marketing/mrnci.md
- **PASS**: GitLab / Gaby (gberkman). Page says `gberkman), Analyst Relations Manager`. https://gitlab.com/gitlab-com/content-sites/handbook/-/raw/main/content/handbook/marketing/corporate-communications/analyst-relations/_index.md
- **PASS**: AWS / Avinash Murthy. Page says `Avinash Murthy.{0,60}AWS`. https://analystrelations.org/2022/12/08/2022-iiar-awards-winners/

Result: 8/8 pass.

## Counts per tier

| Tier | Rows | Vendors with a row |
|---|---|---|
| Tier 1 | 1 | GitHub (1) |
| Tier 2 | 8 | AWS (3), GitLab (4), Google Cloud (1) |
| Tier 2b | 0 | none (Harness, Qodo, Augment Code, Tencent Cloud, IBM checked) |
| Tier 3 | 0 | none |
| Total | 9 | |
