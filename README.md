# .github

Organisation defaults for `rentum-superadmin`: profile README, reusable workflows, issue and PR
templates. Repositories without their own templates inherit these.

## Reusable workflows

| Workflow | Use from a repo |
|---|---|
| `.github/workflows/java-ci.yml` | `uses: rentum-superadmin/.github/.github/workflows/java-ci.yml@main` |
| `.github/workflows/node-ci.yml` | `uses: rentum-superadmin/.github/.github/workflows/node-ci.yml@main` |
| `.github/workflows/pr-title.yml` | Enforces Conventional Commit PR titles (squash merge uses the title) |
