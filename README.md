# My Vault

All the files in this repository are CC0 (Public Domain).

Special thanks to sites like [OpenGameArt.org](https://opengameart.org/) for hosting and providing public domain art and audio.

## Disclaimer

Any git configuration tokens are stored LOCALLY and are not tracked or shared in this repository.

## GitHub Tokens

### Fine-Grained Personal Access Tokens

If you choose to use fine-grained tokens on GitHub, note that you cannot use them to create new repositories since the only granular scope that makes sense is "Only Selected Repositories". 

Therefore, you must:
1. **Create the target repository beforehand** on GitHub.
2. Provide the exact name of the target repository when configuring your local git.
3. If you reuse the same fine-grained token for another project, you must provide the repository name for that new project, and remember to create the repository on GitHub and add it to the token's scope.

### Required Scope Configuration

When creating your fine-grained token, set the following scopes:
- **Repository Access**: "Only Selected Repositories"
- **Permissions**:
  - Contents -> Read and Write

### Comparisons

- **Fine-Grained Tokens**: Cannot create repositories if scoped to "Only Selected Repositories". Requires manual repository creation and explicit scope updates per project. Provides significantly better security and granular access control.
- **Classic Tokens**: Can create repositories and have broader access. Easier for initial setup but less secure.
