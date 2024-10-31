# Automated GitHub Release Action

This GitHub Action automates the creation of a new release based on the latest tag and commit history, leveraging conventional commits for versioning.

## Workflow Summary

1. **Tag Validation**  
   Checks if the latest tag is a valid release tag.

2. **Version Bumping**  
   Determines the next release version using the latest tag and commit history, following conventional commit standards.

3. **Release Creation**  
   Publishes a new GitHub release with the determined version and adds a comment to relevant pull requests: `"Released in [version]"`.

4. **Release Notes**  
   Generates release notes based on the commit history, incorporating details into the GitHub release.
