# pr-approval-persistence

Measures whether an approving review on a pull request survives later commits pushed to its head
branch, and whether a workflow token can satisfy a required status check and then merge.

`attack.yml` performs the sequence and records each observation in its log.
