# VM-370-Games
This is from the VM Workshop 1986 Tools Tape, file 155 in VMARC format. 

The format of the VMARC command is:                                            
```
+----------+------------------------------------------------------------------+
| VMARC    | LIST   infileid [pattern]   [( Options...[)]]                    |
|          | PACK   infileid [outfileid] [( Options...[)]]                    |
|          | UNPACK infileid [pattern]   [( Options...[)]]                    |
|          |                                                                  |
|          | Common options:                                                  |
|          |    FIfo|LIfo   REPlace|NOREPlace   Tap#|Tape   TRace|NOTRace     |
|          | Pack options:                                                    |
|          |    APPend|NOAPPend  BLock nnnn  LZW|STORE|S2  PRinter|PRt|PUnch  |
|          |                                                                  |
|          | Unpack options:                                                  |
|          |    HOld   IGNore|NOIGNore   NEWDate|OLDDate   READer|RDR         |
+----------+------------------------------------------------------------------+
```

More information can be found by typing `HELP VMARC` when logged on to VM/370 CE.
