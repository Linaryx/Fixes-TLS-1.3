# Fixes-TLS-1.3
Fixes TLS 1.3 for working in Russia --> obs twitch, modrinth on launchers, mclogs uploader and more



# Step 1

add the .bat file:
```
cd c:\windows\system32
inetcpl.cpl
```
and run

# Step 2

![image](https://github.com/00Linar00/Fixes-TLS-1.3/assets/99946996/029ac479-f7b9-4ae9-be23-adf53559cec5)

# Step 3

Win + R --> regedit

And find this --> Компьютер\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\SecurityProviders\SCHANNEL\Protocols\

![image](https://github.com/00Linar00/Fixes-TLS-1.3/assets/99946996/3d9fea0e-f56b-43ae-94ec-2329d26a191c)

in this sector -->  Enabled to 1

# Step 4

Restart your PC and enjoy!
