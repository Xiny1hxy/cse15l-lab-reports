# Lab Report 5 - Researching Commands 2
## Command1: 

`find . -name "*.txt" -type f` :
This command will search for all regular files (i.e., not directories or other special files) with the extension ".txt" in the current directory and its subdirectories. The . indicates that the search should start in the current directory.

### Example1:

Command:
`find . -name "*.txt" -type f`

Output:
```
xinyihu@XinyideMacBook-Air berlitz1 % find . -name "*.txt" -type f
./HandRLasVegas.txt
./HistoryJapan.txt
./IntroMalaysia.txt
./HandRIstanbul.txt
./HistoryJamaica.txt
./HandRJamaica.txt
./HandRHongKong.txt
./HistoryEgypt.txt
./IntroEdinburgh.txt
./HistoryIsrael.txt
./IntroDublin.txt
./HistoryIndia.txt
./IntroFrance.txt
./IntroMadeira.txt
./WhatToLakeDistrict.txt
./IntroIbiza.txt
./HistoryItaly.txt
./WhereToGreek.txt
./WhereToLakeDistrict.txt
./HistoryDublin.txt
./IntroIsrael.txt
./WhatToIbiza.txt
./HistoryFrance.txt
./WhatToHawaii.txt
./HistoryMallorca.txt
./HistoryJerusalem.txt
./HandRLisbon.txt
./WhereToIndia.txt
./HistoryMadrid.txt
./HistoryHongKong.txt
./IntroMadrid.txt
./IntroLosAngeles.txt
./HistoryIstanbul.txt
./WhereToItaly.txt
./HistoryLasVegas.txt
./HistoryGreek.txt
./HandRMallorca.txt
./JungleMalaysia.txt
./WhatToMadeira.txt
./WhatToFWI.txt
./WhereToMalaysia.txt
./WhatToMalaysia.txt
./WhatToDublin.txt
./WhereToJapan.txt
./HistoryHawaii.txt
./WhatToFrance.txt
./WhereToEgypt.txt
./WhereToEdinburgh.txt
./WhatToIsrael.txt
./HandRLosAngeles.txt
./HistoryMadeira.txt
./IntroJerusalem.txt
./HandRMadeira.txt
./WhereToIsrael.txt
./HandRIbiza.txt
./WhereToFrance.txt
./WhereToDublin.txt
./IntroLasVegas.txt
./IntroIstanbul.txt
./WhereToMallorca.txt
./WhatToMallorca.txt
./IntroHongKong.txt
./IntroFWI.txt
./IntroJamaica.txt
./IntroGreek.txt
./HandRIsrael.txt
./WhatToEdinburgh.txt
./WhereToMadeira.txt
./WhatToGreek.txt
./HandRLakeDistrict.txt
./WhereToIbiza.txt
./WhereToHawaii.txt
./HandRMadrid.txt
./HistoryMalaysia.txt
./IntroItaly.txt
./WhatToIndia.txt
./WhereToLosAngeles.txt
./HandRJerusalem.txt
./HistoryIbiza.txt
./HistoryEdinburgh.txt
./HistoryFWI.txt
./IntroIndia.txt
./WhatToItaly.txt
./HistoryLakeDistrict.txt
./WhereToMadrid.txt
./WhereToJerusalem.txt
./IntroEgypt.txt
./HandRHawaii.txt
./WhatToJapan.txt
./WhatToJamaica.txt
./IntroLakeDistrict.txt
./IntroMallorca.txt
./WhatToHongKong.txt
./WhatToEgypt.txt
./WhereToHongKong.txt
./WhereToFWI.txt
./WhatToIstanbul.txt
./WhereToIstanbul.txt
./IntroJapan.txt
./WhatToLasVegas.txt
./WhatToLosAngeles.txt
```
The command search on all the regular files in `berlitz1`. This command might be useful when you try to distinguish file types.

### Example2:

Command:
`find . -name "*.java" -type f`

Output:
```
xinyihu@XinyideMacBook-Air docsearch-main % find . -name "*.java" -type f
./DocSearchServer.java
./Server.java
./TestDocSearch.java
```
This command is trying to search on all the regular java file in docserach-main directory. This command can distinguish java file from txt files.

## Command2:

`find . -mtime 7` :
Find all files modified exactly 7 days ago

### Example1: 

Command: `find . -mtime -7` :

Output:
```
xinyihu@XinyideMacBook-Air berlitz1 % find . -mtime -7
./HandRLasVegas.txt
./HandRIstanbul.txt
./HandRIbiza.txt
./HandRLakeDistrict.txt
./HandRJerusalem.txt
```

This command find all files modified less than 7 days ago. I deleted some words in several files, to see if this command can find out the file i changed. 

### Example2:

Command:
`find . -mtime +7 -mtime -14` :
Find all files modified between 7 and 14 days ago

Output:
```
xinyihu@XinyideMacBook-Air berlitz1 % find . -mtime +7 -mtime -14
```
This command is not giving me any output, since I didn't modified any thing between 7 and 14 days ago.

## Command3: `find . -name "*.fileType" -type f -exec rm {} \;`

This command searches for all files with the ".fileType" extension, and then executes the rm command on each file that is found. The {} placeholder is replaced with the file name, and the \; is used to terminate the rm command.

### Example1:

Command: `find . -name "*.fileType" -type f -exec rm {} \;`

Output:
![image]()
This command searchese for all the file with ".txt" type and execute `-rm` command which remove those files. Now there are no `.txt` files in my directory.
### Exmaple2:


## Command4:
### Example1:
### Exmaple2:
