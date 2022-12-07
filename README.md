# Hide_Windows_DriveLetters
 This script hides Windows drive letters from end users.
 
 this script is intended for use in Intune scripts
 
 This script hides Windows driveletters by using registry settings.
 
 	Drives		ValueData
	ShowAll		0
	A			1
	B			2
	C			4
	D			8
	E			16
	F			32
	G			64
	H			128
	I			256
	J			512
	K			1024
	L			2048
	M			4096
	N			8192
	O			16384
	P			32768
	Q			65536
	R			131072
	S			262144
	T			524288
	U			1048576
	V			2097152
	W			4194304
	X			8388608
	Y			16777216
	Z			33554432
	Hide All	67108863
	If you want to hide multiple drives then add the decimal numbers (such as, for Drive D and E use 24).
	
