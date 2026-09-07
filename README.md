# PRISMA Flow Editor

Interactive PRISMA 2020 flow-diagram editor with draggable boxes and arrows, CAD-style constraints, project JSON save/load, and SVG/PNG export.

The deployed page automatically loads `prisma_flow_project.json`.

The default project uses the supplied September 7, 2026 layout and study counts,
with aligned source boxes, central boxes, and arrow endpoints. An editable
**PICOS Inclusion Criteria** table appears below the flow diagram. Select the
table to edit its title, five criteria, position, dimensions, and text size.
Long criteria wrap automatically, and text shrinks to fit the available height.
The table is included in project JSON, SVG, and PNG exports.

The default figure uses 22 px box/table text, 20 px exclusion text, and 18 px
stage labels. The wider reason column keeps the supplied exclusion criteria on
single lines, with 1.5 line spacing and an additional 14 px between criteria.

Project saves use version 5 for the table's structured rows; earlier projects
remain loadable. The embedded initial state also contains the same default
layout for opening the editor when the default JSON cannot be fetched.

The supplied study counts are preserved: 179 records after duplicate removal,
146 excluded, and 25 included. These do not reconcile (179 − 146 = 33), and the
listed exclusion reasons total 154. Resolve the counts before manuscript use.
