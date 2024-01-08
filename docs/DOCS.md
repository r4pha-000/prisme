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

All Functions
```diff
> StretchBlt(SRCERASE)

> StretchBlt(SRCPAINT)

> StretchBlt(SRCINVERT)
! === Loop Functions === !
> LoopStretchBlt(SRCERASE, <Seconds>)

> LoopStretchBlt(SRCPAINT, <Seconds>)

> LoopStretchBlt(SRCINVERT, <Seconds>)

> LoopStretchBlt(BLACKNESS, <Seconds>)

> LoopStretchBlt(SRCCAND, <Seconds>)

> LoopStretchBlt(NOTSRCCOPY, <Seconds>)
