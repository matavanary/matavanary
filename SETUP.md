# Matavanary Studio — GitHub Profile Setup

## Files to add to `matavanary/matavanary`

```text
matavanary/
├── README.md
└── .github/
    └── workflows/
        └── snake.yml
```

1. Rename `README-Matavanary-v2.md` to `README.md` and place it at the repository root.
2. Place `snake.yml` at `.github/workflows/snake.yml`.
3. Push both files to the default branch.
4. Open the repository's **Actions** tab and run **Generate Contribution Snake** once using `workflow_dispatch`.
5. After the workflow completes, an `output` branch will contain `github-snake.svg` and `github-snake-dark.svg`.
6. The README already points to those files. The workflow refreshes them automatically every day.

The scheduled cron is `15 18 * * *`, which is 18:15 UTC / 01:15 Thailand time (UTC+7) on the following calendar day.

## Profile repository

For GitHub to display this README on the profile page, the repository must be named exactly the same as the GitHub username:

`matavanary/matavanary`

## Design direction

- Brand: Matavanary Studio
- Theme: dark navy + violet/blue
- Primary accent: `#6C63FF`
- Secondary accent: `#8B83FF`
- Languages: English + Thai
- Positioning: Senior PHP Programmer / Project Owner
- Primary strengths: Backend, API, Business Systems, Integration, Automation
