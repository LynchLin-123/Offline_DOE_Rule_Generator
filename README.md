# Offline DOE General Rule Generator

A static GitHub Pages style website for Foxconn Testing EPM to generate Offline Lab Routing Rules from DOE Excel and Online Test Rule Excel.

## How to use locally

1. Open `index.html` with Microsoft Edge or Google Chrome.
2. Upload DOE Excel.
3. Upload Online Test Rule Excel.
4. Maintain Offline Team / Alias / Priority Table.
5. Click Generate Rule.
6. Edit/Delete rules if needed.
7. Export Excel.

## GitHub Pages deployment

Repository name suggestion:

```text
offline-doe-rule-generator
```

After enabling GitHub Pages, the URL will look like:

```text
https://your-company.github.io/offline-doe-rule-generator/
```

## Input files

DOE Excel expected fields:

- DOE Number
- Team
- DOE Title
- Est. Lead Time
- FATP Config
- Test Target

Online Test Rule Excel expected fields:

- Date
- Config
- Input Qty
- Test Rule

## Output fields

- Operation
- Config
- Input Date
- Input Qty
- Routing Rule
- Source DOE
