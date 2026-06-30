# Edumentorix Formula Conditions 2027

Public delivery package for 2027 art-admission formula condition data.

## Files

- `exports/formula_conditions_2027.json` — primary machine-readable export.
- `exports/formula_conditions_2027.csv` — flattened review/integration table.
- `exports/summary.json` — counts by status/season.
- `schema/formula_conditions.schema.json` — JSON Schema for the export.

## Status meanings

- `calculable`: formula structure and required condition data are present.
- `waiting_for_final_table`: the formula structure is present, but final CSAT-year inputs such as university conversion tables or national maximum standard scores must be connected after publication.

