# Git Commit History

## Installation

```bash
    go install
```

## Usage

Will scan that folder and its subdirectories for repositories to scan
```bash
git_commit_history -add "/path/to/folder/containing/local_repositories/"
```

### Then

Will generate a CLI stats graph representing the last 6 months of activity for the passed email.
```bash
git_commit_history -email "your@email.com"
```

### The end result
<img width="1026" alt="Screenshot 2024-06-08 at 10 01 30" src="https://github.com/asare-21/git_commit_history/assets/52238457/70967f20-1984-428a-981c-a5f855785b83">
