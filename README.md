# GITCONFIG
:panda_face: It's just my [.gitconfig](.gitconfig)

## Alias

* lg1, lg, graph, gp, pg
  * Show the list of git commits with HASH SHA and short date
* lg2
  * Show the list of git commits with HASH SHA and long date
* st
  * _"status"_
* cm
  * _"commit -m"_
  ```bash
  git commit -m "add file"
  # is equal to
  git cm "add file"
  ```
* cmm
  * _"git commit --amend -m"_
* cmd
  * _"git commit --amend"_
* df
  * _"diff"_
* dfs
  * Show the diff of files on the stage.
  * _"diff --staged"_
* co
  * _"checkout"_
* start
  * _flow feature start_
* finish
  * _flow feature finish_
* undo
  * Undo the last commit
  * is _"reset --soft HEAD~1"_
