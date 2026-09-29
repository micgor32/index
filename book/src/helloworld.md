# 01101000 01100101 01101100 01101100 01101111 00100000 01110111 01101111 01110010 01101100 01100100

```asm
mov	$0x3f8, %dx
mov	$'H', %al
out	%al, (%dx)
mov	$'e', %al
out	%al, (%dx)
mov	$'l', %al
out	%al, (%dx)
mov	$'l', %al
out	%al, (%dx)
mov	$'o', %al
out	%al, (%dx)
mov	$' ', %al
out	%al, (%dx)
mov	$'W', %al
out	%al, (%dx)
mov	$'o', %al
out	%al, (%dx)
mov	$'r', %al
out	%al, (%dx)
mov	$'l', %al
out     %al, (%dx)
mov	$'d', %al
out     %al, (%dx)
mov	$'\n', %al
out	%al, (%dx)
```
