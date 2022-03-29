# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | GB freed | GB free
---|:--------------------:|:-----------------:|:---------------:|---------:|-------:
ubuntu-18.04 |  |  |  | 6 | 42
ubuntu-18.04 |  |  | true | 6 | 42
ubuntu-18.04 |  | true |  | 9 | 45
ubuntu-18.04 |  | true | true | 9 | 45
ubuntu-18.04 | true |  |  | 20 | 56
ubuntu-18.04 | true |  | true | 20 | 56
ubuntu-18.04 | true | true |  | 22 | 58
ubuntu-18.04 | true | true | true | 22 | 58
ubuntu-20.04 |  |  |  | 7 | 39
ubuntu-20.04 |  |  | true | 7 | 39
ubuntu-20.04 |  | true |  | 10 | 42
ubuntu-20.04 |  | true | true | 10 | 42
ubuntu-20.04 | true |  |  | 22 | 54
ubuntu-20.04 | true |  | true | 22 | 54
ubuntu-20.04 | true | true |  | 24 | 56
ubuntu-20.04 | true | true | true | 24 | 56
