# A07 metadata-change ledger

Date: 2026-08-05
Repository/profile owner: Hugo Menz (hugomenz)

This ledger records only reversible GitHub metadata changes. No repository source, visibility, release, default branch or history was changed.

## Repository metadata changes

| Repository | Field | Before | After | Evidence | Rollback |
|---|---|---|---|---|---|
| hugomenz/automation-landing | Description | Empty | Industrial automation site for machinery manufacturers: internal RFQ qualification, traceable inputs and human review. | [Repository About block](https://github.com/hugomenz/automation-landing) | Clear description |
| hugomenz/automation-landing | Homepage | Empty | https://www.hugomenz.de/ | [Repository About block](https://github.com/hugomenz/automation-landing) | Clear homepage |
| hugomenz/automation-landing | Topics | Empty | angular, typescript, industrial-automation, machinery, rfq, webhooks, n8n | [Repository topics](https://github.com/hugomenz/automation-landing) | Remove topics |
| hugomenz/automation-portfolio | Description | Trilingual portfolio of five inspectable automation and workflow case studies. | Inspectable automation portfolio with workflow explanations, implementation-status labels and synthetic/test boundaries. | [Repository About block](https://github.com/hugomenz/automation-portfolio) | Restore prior description |
| hugomenz/automation-portfolio | Homepage | Empty | https://hugomenz.github.io/automation-portfolio/ | [Repository About block](https://github.com/hugomenz/automation-portfolio) | Clear homepage |
| hugomenz/automation-portfolio | Topics | Empty | automation, workflow-automation, n8n, typescript, industrial-automation, human-in-the-loop, synthetic-data | [Repository topics](https://github.com/hugomenz/automation-portfolio) | Remove topics |
| hugomenz/bom-builder | Description | Empty | BOM builder for mechanical assemblies with CSV import/export and PDF generation. | [Repository About block](https://github.com/hugomenz/bom-builder) | Clear description |
| hugomenz/bom-builder | Homepage | Empty | https://hugomenz.github.io/bom-builder/ | [Repository About block](https://github.com/hugomenz/bom-builder) | Clear homepage |
| hugomenz/bom-builder | Topics | Empty | bill-of-materials, bom, mechanical-engineering, angular, typescript, csv, industrial-automation | [Repository topics](https://github.com/hugomenz/bom-builder) | Remove topics |
| hugomenz/ProcureFlow | Description | Empty | Proof-of-concept Angular/Nx workspace for BOM, purchasing and delivery control in custom machinery projects. | [Repository About block](https://github.com/hugomenz/ProcureFlow) | Clear description |
| hugomenz/ProcureFlow | Homepage | Empty | Unchanged; no public demo verified | [Repository About block](https://github.com/hugomenz/ProcureFlow) | N/A |
| hugomenz/ProcureFlow | Topics | Empty | procurement, bill-of-materials, purchase-orders, industrial-automation, angular, nx, prototype, mechanical-engineering | [Repository topics](https://github.com/hugomenz/ProcureFlow) | Remove topics |
| hugomenz/smartworks-project-management-tool | Description | Empty | Historical project-control prototype for mechanical design teams using React and .NET. | [Repository About block](https://github.com/hugomenz/smartworks-project-management-tool) | Clear description |
| hugomenz/smartworks-project-management-tool | Homepage | Empty | Unchanged; no public demo verified | [Repository About block](https://github.com/hugomenz/smartworks-project-management-tool) | N/A |
| hugomenz/smartworks-project-management-tool | Topics | Empty | mechanical-engineering, project-management, react, dotnet, prototype | [Repository topics](https://github.com/hugomenz/smartworks-project-management-tool) | Remove topics |

## Pin selection

| Surface | Before | After | Evidence | Rollback |
|---|---|---|---|---|
| github.com/hugomenz pinned repositories | wmt_data; smartworks-project-management-tool; hopiumfolio; MasterFront-LemonCode; hugomenz.github.io; bom-builder | automation-landing; automation-portfolio; bom-builder; ProcureFlow; smartworks-project-management-tool | [Public profile](https://github.com/hugomenz) | Re-select the previous repositories in Customize your pins |

The live profile may render the same membership in a different display order after save; membership is the authoritative change recorded here.

The BOM Builder homepage uses the canonical route `https://hugomenz.github.io/bom-builder/`; in the browser it redirects to `/bom-builder/bom-builder/` while serving the Stüli Builder page. The direct final route alone returns a GitHub Pages 404.

## Intentionally unchanged / boundary

- hugomenz/hugomenz profile README and audit are delivered in draft PR [#1](https://github.com/hugomenz/hugomenz/pull/1); no merge was performed.
- The GitHub account-level website field remains https://mnf.red/hugomenz. It was not changed because A07's repository-only write boundary does not include account profile settings.
- No repository was archived, deleted, made private/public, released, rebased, force-pushed or changed on its default branch.
- LinkedIn remained read-only.
