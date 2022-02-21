# Clone of Peter Madsens Extended Menus for Total Commander

Version: Total Commander 10.00 - 64 bit

[Extended Menus for TC](http://www.ghisler.ch/board/viewtopic.php?t=33740&postdays=0&postorder=asc&highlight=petermad+github&start=0)
( [Release 64 bit](http://totalcmd.net/plugring/win10amd64_eng.html) )

### Branches

The master branch is Peter Madsens release.

The arberg branch is where I have added my own Powershell goodies (some of which will only work on my pc)

### How to merge new release (notes for myself)

- Checkout master
- Unzip new 64bit version only on top
- Unzip the wcmd_win10amd64_eng.zip into wcmd_win10amd64_eng_unzipped
- Update version in README.md
- Commit
- Merge to arberg branch 
  - If there are merge conflicts, commit a version of .mnu and .ini with windows newliwes, and redo merge

Take care to preserve windows newlines format to avoid conflicts.
