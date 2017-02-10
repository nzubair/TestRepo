
## -eq
Description: Equal to. Includes an identical value.

Example:

Code:
```PowerShell
"abc" -eq "abc"
```

Output:
```
True
```

Code:
```powershell
"abc" -eq "abc", "def"
```

Output:
```
False
```

Code:
```powershell
"abc", "def" -eq "abc"
```

Output:
```
abc
```

## -ne
Description: Not equal to. Includes a different value.

Example:

Code:
```PowerShell
"abc" -ne "def"
```

Output:
```
True
```

Code:
```powershell
"abc" -ne "abc"
```

Output:
```
False
```

Code:
```powershell
"abc" -ne "abc", "def"
```

Output:
```
True
```

Code:
```powershell
"abc", "def" -ne "abc"
```

Output:
```
def
```
