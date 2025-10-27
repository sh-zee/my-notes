## Major types
![[LSM-Tree strcture.png]]
1. Log structured
	1. Data Structure
		1. Sorted String Tables (SSTables)
		2. LSMTrees (Lon structured merge Trees)
		3. MemTables (Red-Back trees and AVL trees)
	2. Performance:
		1. Very high write throuhput / SLow read
		2. Friendly for Sequentail writes good for Disks.
2. Page Structured
	1. Data Structure
		1. B-Trees (Tree of pages)
	2. Performance:
		1. High read, SLow on wite
		2. Multiple writes due to WAL.
		3. Lightweight Latches for Concurrency-Control.
		

