# Edumentorix Formula Conditions 2027

Public delivery package for 2027 art-admission formula condition data.

## Files

- `exports/formula_conditions_2027.json` — primary machine-readable export (`schema_version=forta.edumentorix.formula_conditions.v1.1`).
- `exports/formula_conditions_2027.csv` — flattened review/integration table, including status reasons, grade tables, and rounding rules.
- `exports/summary.json` — counts by status/season plus coverage counters.
- `exports/university_alias_map_2027.json` — canonical 2027 university names and accepted aliases.
- `exports/expected_outputs_2027.json` — one regression-smoke expected-output sample per canonical university where a numeric score is available.
- `schema/formula_conditions.schema.json` — JSON Schema for the export.

## Status meanings

- `calculable`: formula structure and required condition data are present.
- `waiting_for_final_table`: the formula structure is present, but final CSAT-year inputs such as university conversion tables or national maximum standard scores must be connected after publication.
- `not_calculable`: the row is a valid admission-condition row, but it is not a service-calculable CSAT/school-record score conversion formula (for example practical-only or non-CSAT rows).

