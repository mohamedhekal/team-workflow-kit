# Release process

1. Make sure `main` is green in CI.
2. Choose the next version following semantic versioning.
3. Tag it: `git tag -a vX.Y.Z -m "vX.Y.Z"` and push the tag.
4. Create a GitHub release with notes grouped by change type.
5. Announce it to the team.

Hotfixes use a `fix/` branch and a patch release.
