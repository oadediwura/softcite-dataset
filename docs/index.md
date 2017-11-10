---
title: "PDFs for softcite"
---
# Instructions

[First Day Setup](firstDay.md)

[Second Day Setup](secondDay.md)

[Coding Scheme](coding-scheme.html)

[Working on Softcite Data Files](setupInstructions.md)

[Update Snippets](shortcuts.md)

[Understanding Git in our Context](conceptualGit.md)

[Git and Github resources](gitResources.md)

[Asking for Help](askForHelp.md)

<<<<<<< HEAD
=======
# October re-fork

1. Make a backup copy of your repo on howisonlab.

```
$ mv softcite-dataset softcite-dataset.bak
```

2. Delete your fork on Github.

3. Re-fork, go to [howisonlab/softcite-dataset](github.com/howisonlab/softcite-dataset)

4. Clone your fork to howisonlab

5. Move files from your backup to your new clone.

```
diff -qr softcite-dataset.bak/data/individuals-jameshowison/ softcite-dataset/data/individuals-jameshowison/
```

6. Copy over files from .bak

```
$ cp softcite-dataset.bak/data/individuals-jameshowison/jameshowison-PMC....ttl softcite-dataset/data/individuals-jameshowison/
```

7. Check them into the clean softcite-dataset

```
$ git status
$ git add <each file>
$ git commit
$ git push
# --> go to your fork on github and make pull request
```

>>>>>>> 2c405452a0bc214db2014bbb971e97da45d139cc
# Training Group 1

1. [2000-09-CELL.pdf](pdf-files/2000-09-CELL.pdf)
1. [2004-01-NAT_GENET.pdf](pdf-files/2004-01-NAT_GENET.pdf)
1. [2001-16-CELL.pdf](pdf-files/2001-16-CELL.pdf)
1. [2009-28-NANOMEDICINE-UK.pdf](pdf-files/2009-28-NANOMEDICINE-UK.pdf)
1. [2002-29-CELL_RES.pdf](pdf-files/2002-29-CELL_RES.pdf)
1. [2008-16-AQUAT_ECOSYST_HEALTH.pdf](pdf-files/2008-16-AQUAT_ECOSYST_HEALTH.pdf)
1. [2002-39-SYST_BOT.pdf](pdf-files/2002-39-SYST_BOT.pdf)
1. [2000-22-AM_J_BOT.pdf](pdf-files/2000-22-AM_J_BOT.pdf)
1. [2004-09-PHYTOMEDICINE.pdf](pdf-files/2004-09-PHYTOMEDICINE.pdf)

# Training Group 2

1. [2004-40-NAT_GENET.pdf](pdf-files/2004-40-NAT_GENET.pdf)
1. [2008-39-NAT_BIOTECHNOL.pdf](pdf-files/2008-39-NAT_BIOTECHNOL.pdf)
1. [2007-24-SCIENCE.pdf](pdf-files/2007-24-SCIENCE.pdf)
1. [2001-35-NAT_BIOTECHNOL.pdf](pdf-files/2001-35-NAT_BIOTECHNOL.pdf)
1. [2001-40-MOL_ECOL.pdf](pdf-files/2001-40-MOL_ECOL.pdf)
1. [2000-04-MOL_ECOL.pdf](pdf-files/2000-04-MOL_ECOL.pdf)
1. [2007-41-MOL_THER.pdf](pdf-files/2007-41-MOL_THER.pdf)
1. [2009-35-DEV_CELL.pdf](pdf-files/2009-35-DEV_CELL.pdf)
1. [2002-48-TURK_J_ZOOL.pdf](pdf-files/2002-48-TURK_J_ZOOL.pdf)
1. [2008-02-WATERBIRDS.pdf](pdf-files/2008-02-WATERBIRDS.pdf)
1. [2007-48-UNDERSEA_HYPERBAR_M.pdf](pdf-files/2007-48-UNDERSEA_HYPERBAR_M.pdf)
1. [2010-05-BMC_MOL_BIOL.pdf](pdf-files/2010-05-BMC_MOL_BIOL.pdf)
