# ContactPanda Salutation Library

This public repository contains the optional central first-name and salutation library used by ContactPanda Basic.

## Privacy and activation

- The central library is disabled by default.
- An administrator must explicitly enable it and accept the disclaimer in ContactPanda.
- ContactPanda downloads only `salutations.json`.
- No contact, customer, email, or website data is uploaded to this repository.
- Local and manually confirmed assignments always take precedence over central entries.

## Important disclaimer

Name-based salutations are only an aid. They can be incomplete, culturally dependent, or incorrect. Administrators remain responsible for reviewing assignments. Ambiguous names should not be added unless they are intentionally mapped to `neutral`.

## File format

The current data is stored in [`salutations.json`](salutations.json) and validated by [`salutations.schema.json`](salutations.schema.json).

Supported values:

- `mr` — masculine salutation
- `ms` — feminine salutation
- `family` — family salutation
- `neutral` — neutral/no gendered salutation

Example:

```json
{
  "version": "2026.10.18",
  "entries": [
    {
      "first_name": "Anna",
      "salutation": "ms"
    }
  ]
}
```

## Contributions

Corrections and carefully reviewed additions are welcome through pull requests. Please keep entries alphabetical, avoid duplicates, and do not include any customer data or information copied from a private CRM.

## License

The data and documentation are made available under [CC0 1.0 Universal](LICENSE).
