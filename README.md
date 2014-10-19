Author: Solomatov A.A (aso)
Date:   Sun Oct 19 15:09:27 2014 +0400

Transcoding bzr-repository to git:
 - make checkout bazaar-repositiry from src to work (target) dir,
 - update bazaar repository to first revision
 - and commited this revision into git.

Repeate this operation sequentially.

Copy .bzrignore into .gitignore & add on it ".bzr" line   on each loop pass.
Commit message & date are extracted from bzr repository with "log" command
& stored into tmp file 'msg' & 'ti.me' respectively.
Field 'commit author' is not extracted - I'm is not needed this.
