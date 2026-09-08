# Live workflow test results

Tested on an isolated Notion page with five synthetic records. No production records were changed.

## Passed

- Three inline views use one data source: daily personal items, course calendar, and full table.
- Native relative-day UI filter displays the one enabled personal record for the local day; course, tomorrow, undated, and disabled fixtures are excluded.
- Calendar displays the course fixture independently.
- Source-key matching updates an existing record: five records remain after repeated input, with the changed status visible in the linked view.
- Pagination with page size two reads three pages and five distinct records.
- Nested toggle text and detailed record bodies survive readback.
- Formula values render as 0, 0.5, 0.5, 1, and 0, including zero-denominator handling.

## Observed limitations

- Connector querying the native today view returned zero rows while the UI displayed one. The cause is unconfirmed; inspect saved filters, source records, local time zone, and UI before treating an empty response as missing data.
- Formula reads returned opaque formulaResult references; fetching them was unsupported. Values were verified in the UI, not through numeric connector output.
- The full six-column diagnostic table requires horizontal scrolling at the tested desktop viewport; responsive layout was not certified.

## Scope

This tests the current workflow instructions loaded directly from the output package, not automatic Skill discovery in a fresh session. Updating the locally installed Skill was blocked by filesystem access. Upstream scripts, full paper analysis, automations, and every possible property type were not executed. No claim of exhaustive compatibility is made.
