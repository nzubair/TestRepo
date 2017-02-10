
## -eq
Description: Equal to. Includes an identical value.

Example:

```PowerShell
PS C:> "abc" -eq "abc"
True

PS C:> "abc" -eq "abc", "def"
False

PS C:> "abc", "def" -eq "abc"
abc
```

## -ne
Description: Not equal to. Includes a different value.

Example:

```PowerShell
PS C:> "abc" -ne "def"
True

PS C:> "abc" -ne "abc"
False

PS C:> "abc" -ne "abc", "def"
True

PS C:> "abc", "def" -ne "abc"
def
```

## -gt
Description: Greater-than.

Example:

```PowerShell
PS C:> 8 -gt 6
True

PS C:> 7, 8, 9 -gt 8
9
```
