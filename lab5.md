# Week 5 Lab Report - Arthur
## 3 interesting **find commands**

**find -name**
```
[cs15lfa22en@ieng6-201]:docsearch:160$ find technical -name "biomed"
technical/biomed
[cs15lfa22en@ieng6-201]:docsearch:161$ find technical -name "government"
technical/government
[cs15lfa22en@ieng6-201]:docsearch:163$ find technical -name "plos"
technical/plos
```  
The find -name command is a command that will search a file or directory within the subdirectory of the in the directory system. This command is very useful  if you want to search a file or directory with a specific name.


---
**find -type f**
```
[cs15lfa22en@ieng6-201]:technical:165$ find "plos" -type f
plos/journal.pbio.0020001.txt
plos/journal.pbio.0020010.txt
plos/journal.pbio.0020012.txt
plos/journal.pbio.0020013.txt
[cs15lfa22en@ieng6-201]:technical:166$ find "biomed" -type f
biomed/1468-6708-3-1.txt
biomed/1468-6708-3-10.txt
biomed/1468-6708-3-3.txt
biomed/1468-6708-3-4.txt
[cs15lfa22en@ieng6-201]:technical:167$ find "government" -type f
government/About_LSC/CONFIG_STANDARDS.txt
government/About_LSC/Comments_on_semiannual.txt
government/About_LSC/LegalServCorp_v_VelazquezDissent.txt
government/About_LSC/LegalServCorp_v_VelazquezOpinion.txt
government/About_LSC/LegalServCorp_v_VelazquezSyllabus.txt

```
The find -type f command is a command that will search a file within the directory system. The f command is specific to only search a file not a directory, so it will show a file name within the directory. This command is very useful  if you want to search only a file with a specific name of character.

---
**find -type d**
```
[cs15lfa22en@ieng6-201]:technical:168$ find "plos" -type d
plos
[cs15lfa22en@ieng6-201]:technical:169$ find "biomed" -type d
biomed
[cs15lfa22en@ieng6-201]:technical:170$ find "government" -type d
government
government/About_LSC
government/Alcohol_Problems
government/Env_Prot_Agen
government/Gen_Account_Office
government/Media
government/Post_Rate_Comm
```

The find -type d command is a command that will search a directory within the subdirectory system. The f command is specific to only search a directory not a file, so it will show a directory name within the subdirectory. This command is very useful  if you want to search only a directory with a specific name of character.

