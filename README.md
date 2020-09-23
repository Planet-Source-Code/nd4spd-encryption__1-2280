<div align="center">

## Encryption


</div>

### Description

Encrypts and Decrypts a string easily
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[ND4SPD](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/nd4spd.md)
**Level**          |Unknown
**User Rating**    |4.2 (161 globes from 38 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/nd4spd-encryption__1-2280/archive/master.zip)

### API Declarations

```
Public Function Encrypt(text)
For much = 1 To Len(text)
word = Asc(Mid(text, much, 1)) + 10
c$ = c$ & Chr(word)
Encrypt = c$
Next much
End Function
Public Function Decrypt(text)
For many = 1 To Len(text)
jin = Asc(Mid(text, many, 1)) - 10
d$ = d$ & Chr(jin)
Decrypt = d$
Next many
End Function
```


### Source Code

```
'create 3 text boxes
'to encrypt
text2.text=encrypt(text1.text)
'to decrypt
text3.text=decrypt(text2.text)
```

