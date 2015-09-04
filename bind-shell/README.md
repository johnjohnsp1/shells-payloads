###shell_bind.s - 
*Will open bind socket on port 12345, address 0.0.0.0 on SystemZ.*
###sb_shellcode.txt - 
*Slimmed down shellcode version of the above that is XOR encoded to remove nulls and EBCDIC newlines.   Built in decoder bytes in the beginning will decode the payload and jump to it.*

*Full source code for the shellcode+decoder forthcoming shortly*
