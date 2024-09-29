# ISFShax

ISFShax exploits boot1 using a specially designed ISFS (SLC filesystem) superblock. 
Once installed, it offers similar capabilities to defuse. 
Since it runs before IOSU, it can apply early patches to IOSU and repair most types of bricks. However, it cannot protect against bricks caused by boot1 corruption, seeprom issues, or installing a faulty ISFShax superblock. 
Additionally, ISFShax cannot help if the Wii U is already bricked.
