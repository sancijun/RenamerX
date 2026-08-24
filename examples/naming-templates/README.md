# Naming-template starting points

These examples are starting points to recreate in the RenamerX template editor. They are not import files and do not promise that every field can be extracted from every file. Keep only fields supported by the evidence in your files.

## Research documents

```text
{date}-{title}-{source}
```

Useful for papers, reports, course materials, and reference documents. Prefer an ISO-style date and keep the title concise enough to remain readable in Finder and File Explorer.

Example:

```text
2026-08-24-local-first-software-ink-and-switch.pdf
```

## Invoices and receipts

```text
{date}-{organization}-{type}-{identifier}
```

Useful when invoices need to sort chronologically and remain searchable by vendor and invoice number.

Example:

```text
2026-08-24-acme-invoice-inv-1042.pdf
```

## Client deliverables

```text
{project}-{title}-{status}-{version}
```

Use controlled terms for `status` so names do not drift between `final`, `approved`, `done`, and similar words.

Example:

```text
atlas-campaign-landing-page-approved-v03.png
```

## Photos and screenshots

```text
{date}-{project}-{subject}-{location}
```

Keep location optional when GPS or visual evidence is missing. Avoid asking AI to invent a value solely to fill the template.

Example:

```text
2026-08-24-renamerx-template-editor-shanghai.png
```

## Safer template design

- Start with two or three fields and add more only when they improve search or sorting.
- Use one separator consistently.
- Prefer ISO-style dates such as `YYYY-MM-DD`.
- Use controlled terms for fields with a limited vocabulary.
- Review collision handling and filename length on a small batch.
- Keep Review First enabled until the template produces predictable results.
