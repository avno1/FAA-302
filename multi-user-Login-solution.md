Using Mimikatz
----
1. Using DWS to disable windows defender.
> https://github.com/Nummer/Destroy-Windows-10-Spying/releases
2. Download main tools
> https://github.com/gentilkiwi/mimikatz  
```
# Adding to shell:startup is necessary (重起會失效啦，幹).
# Adding below cmd to shortcut and sure have the admin privilege.

privilege::debug     
ts::multirdp
```
