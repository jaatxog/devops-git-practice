# Git Hooks
post-update example:
#!/bin/bash
TODAY=$(date +%Y-%m-%d)
git tag -f "release-$TODAY"
