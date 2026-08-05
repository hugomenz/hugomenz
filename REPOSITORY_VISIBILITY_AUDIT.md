# Repository visibility audit

Date: 2026-08-05  
Scope: public GitHub profile, public repositories, profile README, pins, descriptions, topics, homepage links and visible link health.

## Findings

- The profile has 87 repositories: 59 public and 28 private.
- The profile README previously led with “Future FrontEnd Developer”, “Ex-Mechanical Design Engineer”, “Passionate about programming (or atleast trying it)” and “Front End expert on progress”. Those lines understated the industrial/software combination and contained self-deprecating or outdated positioning.
- The profile-level website is `https://mnf.red/hugomenz`. It is reachable and currently presents a CV page, but it is not the strongest commercial destination for the current positioning. The profile README does not link to it.
- Existing pins were `wmt_data`, `smartworks-project-management-tool`, `hopiumfolio`, `MasterFront-LemonCode`, `hugomenz.github.io` and `bom-builder`. Most were older, generic, unrelated, or weakly described for an industrial automation buyer.
- The public RFQ-Copilot repository exists but is empty. It is therefore not presented as implemented evidence.
- No public repository was found to be archived during this audit. No repository was archived or deleted.

## Recommended visibility set

| Repository | Recommendation | Reason |
| --- | --- | --- |
| [automation-landing](https://github.com/hugomenz/automation-landing) | Keep and pin | Current industrial positioning, public site source, explicit RFQ scope and build/verification commands |
| [automation-portfolio](https://github.com/hugomenz/automation-portfolio) | Keep and pin | Current inspectable portfolio with direct case and workflow routes |
| [bom-builder](https://github.com/hugomenz/bom-builder) | Keep and pin | Concrete BOM evidence connected to mechanical assembly work; public demo reachable |
| [ProcureFlow](https://github.com/hugomenz/ProcureFlow) | Keep and pin | Clearly labelled materials/procurement proof of concept with a mock backend |
| [smartworks-project-management-tool](https://github.com/hugomenz/smartworks-project-management-tool) | Keep, optionally pin | Relevant historical mechanical-design project-control prototype; old default branch and no metadata make it secondary evidence |
| [Menz-Automation-RFQ-Copilot](https://github.com/hugomenz/Menz-Automation-RFQ-Copilot) | Keep, deprioritize until populated | Public repository is empty; do not let an empty repository imply current implementation |
| [whatsapp-maler-assistent](https://github.com/hugomenz/whatsapp-maler-assistent) | Keep, deprioritize | Commercial validation notes and hypotheses, not a software proof |
| [wmt_data](https://github.com/hugomenz/wmt_data) | Keep, deprioritize | Older crypto/data-visualization project; it dilutes the industrial automation story |
| [hopiumfolio](https://github.com/hugomenz/hopiumfolio) | Keep, deprioritize | Playful crypto project with an outdated external homepage link |
| Older bootcamp, course, fork and game repositories | Keep unless Hugo chooses otherwise; do not pin | Archive noise in the profile view, but outside this task to archive or delete |

## Metadata recommendations

The following descriptions, topics and homepage URLs were applied to the most relevant public repositories. Changes were intentionally limited to reversible repository metadata.

| Repository | Description | Topics | Homepage |
| --- | --- | --- | --- |
| automation-landing | Industrial automation site for machinery manufacturers: internal RFQ qualification, traceable inputs and human review. | `angular`, `typescript`, `industrial-automation`, `machinery`, `rfq`, `webhooks`, `n8n` | https://www.hugomenz.de/ |
| automation-portfolio | Inspectable automation portfolio with workflow explanations, implementation-status labels and synthetic/test boundaries. | `automation`, `workflow-automation`, `n8n`, `typescript`, `industrial-automation`, `human-in-the-loop`, `synthetic-data` | https://hugomenz.github.io/automation-portfolio/ |
| bom-builder | BOM builder for mechanical assemblies with CSV import/export and PDF generation. | `bill-of-materials`, `bom`, `mechanical-engineering`, `angular`, `typescript`, `csv`, `industrial-automation` | https://hugomenz.github.io/bom-builder/bom-builder/ |
| ProcureFlow | Proof-of-concept Angular/Nx workspace for BOM, purchasing and delivery control in custom machinery projects. | `procurement`, `bill-of-materials`, `purchase-orders`, `industrial-automation`, `angular`, `nx`, `prototype`, `mechanical-engineering` | None; no public demo verified |
| smartworks-project-management-tool | Historical project-control prototype for mechanical design teams using React and .NET. | `mechanical-engineering`, `project-management`, `react`, `dotnet`, `prototype` | None; no public demo verified |

## Link checks

- `https://www.hugomenz.de/` → reachable in the browser; title: “Angebotsprozess im Maschinenbau automatisieren | Hugo Menz”.
- `https://hugomenz.github.io/automation-portfolio/` → reachable in the browser; title: “Hugo Menz · Sistemas que funcionan”.
- `https://hugomenz.github.io/bom-builder/` → redirects to `/bom-builder/bom-builder/`; the final page is reachable but currently has the title “Smartworks”. The profile now links to the observed final route and the repository metadata recommendation uses that route.
- The selected GitHub repository links resolve to their public repositories.
- `https://mnf.red/hugomenz` → reachable and currently presents a CV page. It is not used in the rewritten profile README; changing the GitHub account website field is outside this repository-only change.
- LinkedIn and Xing links were left read-only and unchanged.

## Exact blockers and limitations

- GitHub’s connected repository tools can create the profile branch, update files and open the draft PR, but they do not expose repository metadata or pin-selection mutations.
- The descriptions/topics/homepage URLs and pin set were applied through the GitHub repository settings/profile UI. These changes are reversible and authorized by A07; the account-level website field remains outside the repository-only scope.
- The profile page’s current account website field still points to `https://mnf.red/hugomenz`; it should be reviewed separately before changing it to the canonical site.
