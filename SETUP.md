# GitHub Profile Setup

1. Create a public GitHub repository named exactly `qucank2006` under account `qucank2006`.
2. Copy `README.md` to the root of the repository.
3. Copy `.github/workflows/breakout.yml` to the same path in the repository.
4. Commit both files to the `main` branch.
5. In Settings > Actions > General, ensure workflows are allowed and workflow permissions permit writing repository contents (the job requests `contents: write`).
6. In Actions > Generate Breakout, choose Run workflow. Wait for both jobs to succeed.
7. The `output-pacman` branch will contain the SVGs referenced in the README. GitHub may take a little time to refresh cached images.

Notes:
- Third-party stats and typing cards depend on external services and may occasionally be rate-limited.
- GitHub language cards reflect repository languages, not proficiency.
- Adjust projects and technology icons in README as your portfolio evolves.
- The workflow is adapted from the public Ericismee/Ericismee example; review third-party Actions before using them.
