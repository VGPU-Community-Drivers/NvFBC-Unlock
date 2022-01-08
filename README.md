# NvFBC-Unlock for LG

In your Windows Guest:
 
Add a system environment with the name:```NVFBC_PRIV_DATA``` and as value: ```AC10C92EA5E6874F8F4BF461F85627E9```
 
Create ```C:\Program Files\Looking Glass (host)\looking-glass-host.ini``` insert:
```
[app]
capture=nvfbc
 ```
If you add the nvfbc in the .ini and forgot the system env variable - or your HW does not support this feature - Looking-Glass will not work!
