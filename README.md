# Git Workflow Project

A simple project demonstrating Git and GitHub best practices using a structured branching and pull request workflow.

## Project Structure

```text
git-workflow/
├── app/
│   └── index.html
├── docs/
│   └── workflow.md
├── .gitignore
└── README.md
```

## Git Workflow Used

* `main` – Stable production branch
* `dev` – Development branch
* `feature/*` – Feature development branches

### Workflow Process

```text
feature branch
      ↓
     dev
      ↓
    main
```

1. Created the project and initialized Git.
2. Created and pushed the `main` branch.
3. Created the `dev` branch.
4. Created feature branches for project changes.
5. Committed changes with meaningful commit messages.
6. Pushed feature branches to GitHub.
7. Created Pull Requests from feature branches to `dev`.
8. Merged changes into `dev`.
9. Created a Pull Request from `dev` to `main`.
10. Merged the final changes into `main`.
11. Created Git tag `v1.0.0` for the stable release.

## Technologies Used

* Git
* GitHub
* GitHub Pull Requests
* Git Branching
* Markdown
* HTML

## Version

**v1.0.0**
