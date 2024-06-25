# Fork-Repo-Demo

1. create organization for group project
   - My personal account
2. create new repo within org
   - Public visibility
   - Add README.md file
3. Fork repo to own account // avoid using company’s repository
4. Git clone the forked repo to local device
5. Make Changes to code (README)
   - git add, commit, push
6. Create pull request
   - Click "New Pull Request" from own account in github
7. Merge pull request
   - Rebase and merge
8. Confirm changes in step 5 are present in org cadebase

Security settings of organization ----------------------------

1. branch targeting configure (setting) => bottom add rules
   - Settings in organization
   - Rules > Rulesets > New ruleset
2. Require signed commits (Commits pushed to matching refs must have verified signatures)
3. Require a pull request before merging (Require all commits be made to a non-target branch and submitted via a pull request before they can be merged)
4. Block force pushes
