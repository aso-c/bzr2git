bzr2git
=======

*Simply script for convertion bazaar repository to git one*

  - make checkout bazaar-repositiry from src to work (target) dir,
  - update bazaar repository to first revision
  - and commited this revision into git.`
  - copy .bzrignore into .gitignore & add on it ".bzr" line
      on each loop pass.

Repeat this operation sequentially.

    Commit message & date are extracted from bzr repository with "log" command
    & stored into tmp file 'msg' & 'ti.me' respectively.
    Field 'commit author' is not extracted - I'm is not needed this.


    Author: Solomatov A.A (aso)
    Date:   Sun Oct 19 15:09:27 2014 +0400
    License: GPL v.3
