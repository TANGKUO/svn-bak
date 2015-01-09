# svn的工作模式（协同合作的两种模式）

- **copy-edit-merge svn默认工作模式**

  适用于纯文本文件的协同工作，TortoiseSVN自动合并 不同成员对同一文件的修改，如果修改有冲突，需要 人工取舍。 此模式适合软件开发这种工作。

- **Lock-Modify-Unlock （锁模式）**
  
  适用于纯文本文件及二进制文件的协同工作。比如 dwg,mcd,doc,ppt,xls等文件格式。 这种模式适合工程设计人员的合作。