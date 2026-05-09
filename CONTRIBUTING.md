# Contributing Guidelines

## Branch Strategy

### Main Branch
- The `main` branch contains only approved documents.
- Direct pushes to `main` are not allowed.
- All changes must be merged through Pull Requests.

### Draft Branches
Use the following naming convention for working branches:

`draft/<document-name>`

Examples:
- draft/srs-chapter1
- draft/sds-design
- draft/meeting-notes-week3

### Fix Branches
Use the following naming convention for corrections:

`fix/<issue-number>`

Examples:
- fix/12
- fix/25



## Contribution Workflow

1. Pull the latest changes from `main`
2. Create a new branch
3. Make required changes
4. Commit changes with meaningful messages
5. Push the branch to GitHub
6. Create a Pull Request
7. Wait for at least 1 approval
8. Merge into `main`



## Commit Message Convention

Use clear and meaningful commit messages.

Format:
`<type>: <description>`

Examples:
- docs: added SRS chapter 2
- update: modified use case diagram
- fix: corrected formatting issues



## Pull Request Rules

- PR must be reviewed before merging
- At least 1 approval is required
- Resolve merge conflicts before merging
- Keep PR descriptions clear and concise



## Repository Rules

- Do not upload unnecessary files
- Maintain proper folder structure
- Keep document names meaningful
- Follow version control practices properly