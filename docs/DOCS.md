# Prisme V Documentation

Before you start:
> The interpreter is case isensitive, that is, you can write mEsSaGeBoX() and it will identify it.

## Includes

```bat
@include <lib>
```
E.g of an lib:
```bat
@include <Encryption>
```
It includes the Encryption lib.

You can use multiples libraries too!
E.g:
```bat
@include <App>
@include <GDI>
@include <Encryption>
@include <Premade>
```

All libraries:
```diff
!  GDI Library - includes Graphics Device Interface in the project, like incredible other malwares effects.
> PREMADE Library - includes pre-made functions, like BSOD(), KillExplorer()...
>  APP Library - includes basics functions, like MessageBox(), Sleep()...
! [BETA] ENCRYPTION Library - includes Encryption/Decryption functions, like Encrypt All Files in a directory...
```

# Library Functions
## GDI Library

You need to include GDI to use it in your project.
```bat
@include <GDI>
```

After including it, you need to initialize it.
```bat
@GDI.Init()
```

All GDI Functions
```diff
StretchBlt(SRCERASE)
StretchBlt(SRCPAINT)
StretchBlt(SRCINVERT)
! === Loop Functions === !
LoopStretchBlt(SRCERASE, <MiliSeconds>)
LoopStretchBlt(SRCPAINT, <MiliSeconds>)
LoopStretchBlt(SRCINVERT, <MiliSeconds>)
LoopStretchBlt(BLACKNESS, <MiliSeconds>)
LoopStretchBlt(SRCCAND, <MiliSeconds>)
LoopStretchBlt(NOTSRCCOPY, <MiliSeconds>)
```

## App Library
You need to include App to use it in your project.
```bat
@include <App>
```

MessageBox
```diff
MessageBox(<Title>, <Description>, <Icon>)
E.g:
MessageBox('Hello', 'World', Information)

! === Icon Types === !
1. Error
2. Information
3. Warning
```
LoopOpenProcess
```diff
LoopOpenProcess(<process>, <time>)
E.g:
LoopOpenProcess(cmd, 3000) --> It will open the Command Prompt (cmd) for 3 seconds (3000 in miliseconds)
```
Sleep
```diff
Sleep(<time>)
E.g:
Sleep(3000) --> Waits 3 Seconds before continue
```
KillProcess
```diff
KillProcess(<process>)
E.g:
KillProcess(explorer) --> Kill Explorer
```
Shutdown
```diff
Shutdown() --> Closes App
```
SetDirectory
```diff
SetDirectory(<path>)
E.g:
SetDirectory(C:\) --> Changes current directory to C:\
```
