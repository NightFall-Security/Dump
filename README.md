```
                             ____                        
                            |  _ \ _   _ _ __ ___  _ __  
                            | | | | | | | '_ ` _ \| '_ \ 
                            | |_| | |_| | | | | | | |_) |
                            |____/ \__,_|_| |_| |_| .__/ 
                                                  |_|    
                
                          ----- a base PE section dumper -----

```

Dump is a base cli tool aiming to easily dump a PE section & view informations about it. It displays basic HEX & ASCII representation of it.

>[!Important]
>This project was developped as a base lib to other tools.

## Struct : 

`pe.hpp` : a base lib containing PE manipulation functions (ReadFile, Load imports, Relocations).
`main.cpp` : base file containe PeViewer class in charge of the dumping process.

---
<img src="https://github.com/NightFall-Security/Dump/blob/main/assets/demo.png" alt="DebugInfo" />