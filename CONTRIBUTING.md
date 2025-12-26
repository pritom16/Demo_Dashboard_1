# Contributing

Thank you for your interest in contributing to this project! The repository is set up to automatically build and deploy the site to GitHub Pages when changes are pushed to the `main` branch.

How to contribute

- Fork the repository.
- Create a feature branch: `git checkout -b feature/my-change`.
- Make your changes, commit, and push to your fork.
- Open a Pull Request against `main` in the original repository.

Notes about deployment

- When a PR is merged into `main`, GitHub Actions will build and deploy the `dist/` output automatically.
- Actions running from forks cannot access repository secrets, so deployments only happen from the original repository after a merge.

If you need help, open an issue describing what you want to change.
