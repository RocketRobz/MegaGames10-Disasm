========================================================================================
 Sonic the Hedgehog (W) (REV00) [!].bin - June 2005 Disassembly
========================================================================================
----------------------------------------------------------------------------------------
	Files
----------------------------------------------------------------------------------------
sonic1.asm	Sonic 1 source code, with most chunks of data separated.
split.exe	Extracts data from a Sonic 1 ROM and places it in folders for convenient
		editing. Written by Nemesis.
derecmp.exe	Decompresses all compressed data. Also recompresses it (disabled by
		default to increase compilation speed). Written by Hivebrain.
include.exe	Combines the main ASM file with several external ASM files. Written by
		Hivebrain.
snasm68k.exe	Compiles the ASM file. Written by Cross Products.
rompad.exe	Pads the output ROM so that its size is 2^n. Written by Lightning.
fixheadr.exe	Fixes the checksum of the output ROM. Written by Stealth.
_dlls\		Folder containing KENS compression/decompression DLLs. Written by Magus.
----------------------------------------------------------------------------------------
	How to split a ROM
----------------------------------------------------------------------------------------
1.  Place a Sonic 1 ROM in the same folder as split.bat.
2.  Rename the ROM "s1.bin".
3.  Click on split.bat.
----------------------------------------------------------------------------------------
	How to compile a ROM
----------------------------------------------------------------------------------------
1.  Click on build.bat.
2.  The file s1built.bin is your new ROM.
----------------------------------------------------------------------------------------
	Credits
----------------------------------------------------------------------------------------
Disassembly by Hivebrain.
Thanks: drx, Korama, Lightning, Magus, Nemesis, Stealth
----------------------------------------------------------------------------------------
Remember - always make backups of your ASM files!