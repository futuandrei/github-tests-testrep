Steps

- Created repository on Github (https://github.com/futuandrei/github-tests-testrep.git)
- Created readme.md file in repository
- Connected repositories with:
- - Git init
- - Git pull origin main
- Made changes to local repository: Edited readme.md file.
  <<<<<<< HEAD
- Pushed it to remote.
- # Some changes.
- Pushed it to remote with:
- - git status
- - git add readme.md
- - git commit -m "message"
- - git push origin main
- Remote update successful (No conflict)

- Remotelly added ome text to generate conflict.
  > > > > > > > 8a31c3722efcbf5d3a8cb1076bf590522887a284
- Locally made changes to readme.md file
- When pushing changes to remote repository received an error:
  ! [rejected] main -> main (fetch first)
  error: failed to push some refs to 'https://github.com/futuandrei/github-tests-testrep.git'
- Locally solved conflict with:
- - git config pull.rebase false
- - made changes to readme.md
- - pushing changes.
