## Submitter Checklist:

- [ ] Submitted a [ticket](https://github.com/repasscloud/RPC-Applications-Manifests/issues) for my issue if one did not already exist.
- [ ] Used Github [auto-closing keywords](https://help.github.com/articles/closing-issues-via-commit-messages/) in the commit message.
- [ ] Added/updated tests for this change (for new code or code which already has tests).
- Verified that these changes build without errors on
  - [ ] Windows
  - [ ] Linux
  - [ ] macOS
  
- Verified that these changes build on
  - [ ] PowerShell 5.1
  - [ ] PowerShell Core 6.x
  - [ ] PowerShell Core 7.x
  
- Verified that these changes pass automated tests (unit, browser, security tests) on
  - [ ] Windows
  - [ ] Linux
  - [ ] macOS
- [ ] Ran `git rebase master` (if needed).
- [ ] Ran `git rebase -i` to squash commits (if needed).
- [ ] Tagged reviewers and labelled the pull request as needed.
- [ ] Requested a security/privacy review as needed.
- [ ] Public documentation has been updated as necessary.

## Test Plan:


## Reviewer Checklist:

- [ ] New files have MPL-2.0 license header.
- [ ] Request a security/privacy review as needed.
- [ ] Adequate test coverage exists to prevent regressions.

## After-merge Checklist:

- [ ] The associated issue milestone is set to the smallest version that the
  changes has landed on.
- [ ] All relevant documentation has been updated.
