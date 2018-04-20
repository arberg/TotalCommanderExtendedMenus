# Clone of Peter Madsens Extended Menus for TC 9.12 - 64 bit

Peter Madsens release page:
http://www.ghisler.ch/board/viewtopic.php?t=33740&postdays=0&postorder=asc&highlight=petermad+github&start=0

v9.12.2 release 64 bit
http://totalcmd.net/plugring/win10amd64_eng.html

The master branch is Peter Madsens release.

The arberg branch is where I have added my own Powershell goodies. The one of the lines I've added will only work on my pc, because I start powershell in admin mode using RunAsSpc which I have placed here on my pc: c:\ToolsData\RunAsSpc\PowershellAdmin.spc

### How to merge new release (notes for myself)

- Checkout master
- Unzip new 64bit version only on top
- Unzip the wcmd_win10amd64_eng.zip into wcmd_win10amd64_eng_unzipped
- Commit
- Merge to arberg branch

Take care to preserve windows newlines format to avoid conflicts.

