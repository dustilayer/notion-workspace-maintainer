# Page design

Use this reference when the user requests dashboard design or visual restructuring, not for an isolated record edit.

## Layout

Start with the action the page should make easy. Put its editable view near the top. Group supporting content beneath clear headings; collapse infrequent reference material. Use columns only when the table remains readable at the user's window width. Carry existing colors and icons through the page; add covers or widgets only when useful.

## Data presentation

Reuse records through linked views. Choose a table for editing, calendar for dated events, board for status transitions, timeline for spans, or gallery for visual material. Show only properties needed for that view's purpose. Connect distinct entities through relations and derive summaries from those relations.

## Apply and check

Change the page within the requested scope, then inspect reading order, table width, and usable controls. Check a narrow viewport where available. Do not hide navigation, add third-party embeds, or relocate records simply for appearance.

Design ideas considered: [Anusara14/notion-pages-skill](https://github.com/Anusara14/notion-pages-skill). This independently written guidance does not redistribute that repository's skill text; no license was stated in the inspected repository.

## Formula and workflow checks

Before adding computed fields, inspect actual property types and status values. Validate a formula on empty relations, missing dates, zero denominators, and completed items as well as ordinary records. Choose whether a result should be a number, percentage, date, or display string before formatting it. Preserve uncertainty instead of manufacturing a numeric result for missing inputs.

Filtering older items into another view does not archive or move records. Describe the actual operation accurately. Before configuring a requested automation, inspect the workspace's available triggers and actions. Do not infer current product support from a third-party example. Confirm duplicate-trigger behavior and avoid notification or external-send actions unless the user requested them.

When asked to build an entire system, choose only the entities needed for the user's work. A project may relate to tasks; a course may relate to sessions. A broad productivity template is not a reason to add unused areas, clients, sprints, or tracking databases.
