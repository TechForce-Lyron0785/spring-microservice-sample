# Migration TODO

- [x] 1. Mirror copy temp_source to current dir (robocopy /MIR)
- [x] 2. Rewrite all commit authors/committers with git filter-branch
- [ ] 3. Verify rewrite (git log sample)
- [ ] 4. Force-push --all branches and --tags to origin (target GitHub repo)
- [ ] 5. Verify on GitHub (manual)
- [ ] 6. Cleanup temp_source and backup_current
