# Magical Maths

- **Category:** REVENG

## Challenge
We have managed to find the assembly code of a script belonging to Jack Corp attackers. Can you work out what it returns?

The flag format is flag{print value}

magical-maths.zip

```
Dump of assembler code for function main:
   0x0000555555555135 <+0>:     push   rbp
   0x0000555555555136 <+1>:     mov    rbp,rsp
   0x0000555555555139 <+4>:     sub    rsp,0x10
=> 0x000055555555513d <+8>:     mov    DWORD PTR [rbp-0xc],0x0
   0x0000555555555144 <+15>:    mov    DWORD PTR [rbp-0x8],0xa
   0x000055555555514b <+22>:    mov    DWORD PTR [rbp-0x4],0x5c
   0x0000555555555152 <+29>:    mov    edx,DWORD PTR [rbp-0x8]
   0x0000555555555155 <+32>:    mov    eax,DWORD PTR [rbp-0x4]
   0x0000555555555158 <+35>:    add    eax,edx
   0x000055555555515a <+37>:    mov    DWORD PTR [rbp-0xc],eax
   0x000055555555515d <+40>:    mov    eax,DWORD PTR [rbp-0xc]
   0x0000555555555160 <+43>:    mov    edx,eax
   0x0000555555555162 <+45>:    shr    edx,0x1f
   0x0000555555555165 <+48>:    add    eax,edx
   0x0000555555555167 <+50>:    sar    eax,1
   0x0000555555555169 <+52>:    mov    DWORD PTR [rbp-0xc],eax
   0x000055555555516c <+55>:    mov    eax,DWORD PTR [rbp-0x8]
   0x000055555555516f <+58>:    sub    DWORD PTR [rbp-0x4],eax
   0x0000555555555172 <+61>:    mov    eax,DWORD PTR [rbp-0xc]
   0x0000555555555175 <+64>:    sub    DWORD PTR [rbp-0x4],eax
   0x0000555555555178 <+67>:    mov    eax,DWORD PTR [rbp-0xc]
   0x000055555555517b <+70>:    imul   eax,DWORD PTR [rbp-0x4]
   0x000055555555517f <+74>:    mov    DWORD PTR [rbp-0xc],eax
   0x0000555555555182 <+77>:    mov    eax,DWORD PTR [rbp-0xc]
   0x0000555555555185 <+80>:    mov    esi,eax
   0x0000555555555187 <+82>:    lea    rdi,[rip+0xe76]        # 0x555555556004
   0x000055555555518e <+89>:    mov    eax,0x0
   0x0000555555555193 <+94>:    call   0x555555555030 <printf@plt>
   0x0000555555555198 <+99>:    mov    eax,0x0
   0x000055555555519d <+104>:   leave  
   0x000055555555519e <+105>:   ret    
End of assembler dump.
```

## Solution



Flag
```

```
