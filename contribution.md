# Contributing to git_assessment

Thank you for taking the time to contribute! All changes to this repository go through pull requests.

## Getting started

1. Fork or clone the repository.
2. Run the project to check that it works:

   ```bash
   node index.js
   ```

   It should print `Hello World !!`.

3. Get familiar with the folder layout:

   - `config/` - configuration files.
   - `controllers/` - request handling logic.
   - `db/` - database related code.
   - `public/` - static public assets.
   - `routes/` - route definitions.

## Branching

- `develop` is the integration branch and `main` is the release branch.
- Create your branch from `develop`. Never commit directly to `develop` or `main`.
- Name your branch after the ticket ID, for example `TE-T501`.
- `main` only receives merges from `develop` for releases.

```bash
git switch develop
git pull
git switch -c TE-T501
```

## Commit messages

- Format: `<TICKET-ID> <short imperative description>`, for example `TE-T202 add second change`.
- Keep commits small and focused on a single change.

## Pull requests

- Open the pull request against `develop`.
- Reference the ticket ID in the title or description, and explain what changed and why.
- Keep your branch up to date with `develop` before opening the pull request.
- Request a review and address all review comments before merging.

## Code style

- Keep formatting consistent with the surrounding code.
- Use meaningful names for variables and functions.
- Do not leave stray debug code in your changes.

## Reporting issues

Open a GitHub issue with a clear description of the problem and the steps to reproduce it.
