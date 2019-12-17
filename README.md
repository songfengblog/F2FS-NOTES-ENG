# F2FS Notes
Translated from Chinese from [RiweiPan/F2FS-NOTES](https://github.com/RiweiPan/F2FS-NOTES)
With great help from Google translate.

File names are kept in it's original chinese form for ease during update/merging.

### Setting up Experimental Development Environment
[Installation and Setting-up of Experimental Development Environment](https://github.com/sonic414/F2FS-NOTES/blob/master/F2FS-Experiment/实验环境搭建.md)

### 1. The File System Structure and Layout
1. [F2FS Structural Overview](https://github.com/sonic414/F2FS-NOTES/blob/master/F2FS-Layout/%E6%80%BB%E4%BD%93%E7%BB%93%E6%9E%84.md)
2. [Superblock Structure](https://github.com/sonic414/F2FS-NOTES/blob/master/F2FS-Layout/Superblock%E7%BB%93%E6%9E%84.md)
3. [Checkpoint Structure](https://github.com/sonic414/F2FS-NOTES/blob/master/F2FS-Layout/Checkpoint%E7%BB%93%E6%9E%84.md)
4. [Segment Infomation Table Structure(SIT)](https://github.com/sonic414/F2FS-NOTES/blob/master/F2FS-Layout/Segment%20Infomation%20Table%E7%BB%93%E6%9E%84.md)
5. [Node Address Table Structure(NAT) (Incomplete) ](https://github.com/sonic414/F2FS-NOTES/blob/master/F2FS-Layout/Node%20Address%20Table%E7%BB%93%E6%9E%84.md)
6. [Segment Summary Area Structure (SSA)](https://github.com/sonic414/F2FS-NOTES/blob/master/F2FS-Layout/Segment%20Summary%20Area%E7%BB%93%E6%9E%84.md)

### 2. File Data Storage - Read/Write Process
1. [File Read/Write , Physical Address Mapping](https://github.com/sonic414/F2FS-NOTES/blob/master/Reading-and-Writing/file_data_structure.md)
2. [Read Process](https://github.com/sonic414/F2FS-NOTES/blob/master/Reading-and-Writing/%E8%AF%BB%E6%B5%81%E7%A8%8B.md)
3. [Write Process](https://github.com/sonic414/F2FS-NOTES/blob/master/Reading-and-Writing/%E5%86%99%E6%B5%81%E7%A8%8B.md)

### 3. Creation and Deletion of files and directories
1. [ Creation of general files (unfinished) ](https://github.com/sonic414/F2FS-NOTES/blob/master/File-Creation-and-Deletion/%E6%96%87%E4%BB%B6%E5%88%9B%E5%BB%BA.md)
2. [ Creation of General Catalog (Unfinished) ](https://github.com/sonic414/F2FS-NOTES/blob/master/File-Creation-and-Deletion/%E7%9B%AE%E5%BD%95%E5%88%9B%E5%BB%BA.md)
3. [ Removal of general files (unfinished) ](https://github.com/sonic414/F2FS-NOTES/blob/master/File-Creation-and-Deletion/%E7%9B%AE%E5%BD%95%E5%88%9B%E5%BB%BA.md)
4. [ Removal of general directory (unfinished) ](https://github.com/sonic414/F2FS-NOTES/blob/master/File-Creation-and-Deletion/%E7%9B%AE%E5%BD%95%E5%88%A0%E9%99%A4.md)

### 4. Garbage Collection Process
1. [Analysis of Garbage collection process](https://github.com/sonic414/F2FS-NOTES/blob/master/F2FS-GC/GC%E6%B5%81%E7%A8%8B%E4%BB%8B%E7%BB%8D.md)
2. [Selecting the victim segment](https://github.com/sonic414/F2FS-NOTES/blob/master/F2FS-GC/%E9%80%89%E6%8B%A9victim%20segment.md)

### 5. Data Recovery Process
1. [Principle and Method of Data Recovery](https://github.com/sonic414/F2FS-NOTES/blob/master/F2FS-Data-Recovery/%E6%95%B0%E6%8D%AE%E6%81%A2%E5%A4%8D%E7%9A%84%E5%8E%9F%E7%90%86%E4%BB%A5%E5%8F%8A%E6%96%B9%E5%BC%8F.md)
2. [Rollback Recovery and Checkpoint Function and Implementation](https://github.com/sonic414/F2FS-NOTES/blob/master/F2FS-Data-Recovery/Checkpoint%E6%B5%81%E7%A8%8B.md)
3. [Roll-forward recovery and Recovery role and implementation (unfinished)](https://github.com/sonic414/F2FS-NOTES/blob/master/F2FS-Data-Recovery/Recovery%E7%9A%84%E6%B5%81%E7%A8%8B.md)

### 6. Analysis of Important Functions and Data Structures
1. [Introduction and application of f2fs_summary and f2fs_summary_block](https://github.com/sonic414/F2FS-NOTES/blob/master/ImportantDataStructure/f2fs_summary.md)
2. [The role of seg_entry and sit_info](https://github.com/sonic414/F2FS-NOTES/blob/master/ImportantDataStructure/segment.md) 
3. [The role of f2fs_journal](https://github.com/sonic414/F2FS-NOTES/blob/master/ImportantDataStructure/f2fs_journal.md)
4. [Analysis of f2fs_fill_super](https://github.com/sonic414/F2FS-NOTES/blob/master/ImportantDataStructure/f2fs_fill_super.md)
5. [The role of f2fs_map_block](https://github.com/sonic414/F2FS-NOTES/blob/master/ImportantDataStructure/f2fs_map_blocks.md)
6. [The role of CURSEG](https://github.com/sonic414/F2FS-NOTES/blob/master/ImportantDataStructure/curseg.md)
7. [Realization of physical address addressing](https://github.com/sonic414/F2FS-NOTES/blob/master/ImportantDataStructure/get_dnode.md) 
