This should be a **signed** commit using GPG.
This is commited but not signed.
This is a signed commit using GPG.
Configured git to sign all commits by default using the command below
```bash
git config --global commit.gpgsign true
```
All commits from here on are signed commits.

**Now...** changed commit signing mode to ssh from gpg
Also change git default commit sign from true (or automatic) to manual using the command below:
```bash
git config --global --unset commit.gpgsign
```

This commit is set to ssh signing but not signed.
This commit is now signed with ssh.