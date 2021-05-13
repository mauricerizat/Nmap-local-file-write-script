# Nmap-local-file-write-script
This is a simple Lua script that can be used with nmap to write to local files.

### Usage: 
```nmap --script=nmap-write.lua```

### Note: 
The second parameter of the **io.open()** method is set to **"a"** for append. Change it to "w" to overwrite pre-existing files and add **"b"** for binary files.

