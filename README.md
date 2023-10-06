# Multi-account Git

A reminder for Future Me of how I handle having multiple accounts with Git

- Configure separate `Host` entry in `~/.ssh/config` to use for each identity
  - E.g. `corp-github.com`
- Clone the repo using the appropriate Host, or update the remote repo URL for an existing repo
  - `git clone git@corp-github.com ...`
- Configure the repository to use the appropriate committer name and email for the repo
  - `git config user.name "Ian Marcinkowski"
  - `git config user.email "ian@example.com"
