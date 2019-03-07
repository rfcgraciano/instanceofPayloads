Evasion with Wildcards
======
There's a lot of ways to evade filters when doing an pentest. You can use wildcards to evade a lot of them:

```
* = Any number of characters, including none
? = Any single character
[] = Set of characters
- = With [], it denotes a range of characters
~ = Home directory
```

Examples
Cat files
```
cat /etc/passwd
/???/??t /???/p??s??
```