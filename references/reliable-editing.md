# Reliable editing

Read when editing nested pages, converting content formats, or importing detailed records in bulk.

## Read completeness

Follow pagination before concluding that a matching record is absent. Inspect child blocks needed for the requested edit; a top-level page summary is not proof that nested content is empty. If a depth or result limit truncates the read, disclose that boundary and do not replace unread content.

Inspect property types before mapping incoming values. Use the current connector's declared value format rather than assuming that a REST example or another tool's shorthand applies. Reuse the connected authentication; do not introduce a second token-based workflow merely because an example uses one.

## Presentation fidelity

For a long page, make secondary sections collapsible and keep navigation from displacing the main editable content. When converting Markdown to blocks, check actual nesting and rendered output. Unsupported syntax can become visible text instead of a functional column or toggle; verify the chosen connector's supported representation first.

## Detailed source records

Keep properties focused on search, filtering, relations, and workflow state. Put explanations, evidence, and long notes in the record's page body. Preserve the source location for consequential claims and separate confirmed facts from interpretation. When importing documents, match existing records using a stable source identifier where available; do not rely solely on similar display titles.

## Recovery

After an uncertain write response, read back the target before retrying a create operation. Retry only the missing part. Distinguish permission failures from absent data, and do not create a replacement database to work around an inaccessible one.

## Sources considered

These are independently written operating rules, not bundled upstream code or skill text:

- [OpenMinis Notion Hub](https://github.com/OpenMinis/MinisSkills/blob/main/notion-hub/SKILL.md): recursive reads, pagination, and schema-aware values; repository license is MIT.
- [TheLobbi Notion Mastery](https://github.com/TheLobbi/Claude-m/blob/main/notion/skills/notion-mastery/SKILL.md): collapsible page organization and block-format awareness; a license for this component was not confirmed.
- [Paper to Notion](https://github.com/Guesswhat-Studio/paper-to-notion-skill): compact indexing, richer record bodies, source identity, and evidence; repository declares MIT. Full paper analysis remains a separate workflow.

Upstream files were reviewed, not installed or executed. Tool names, paths, and product claims from those projects are not runtime guarantees.
