# upd1C
В ветках реестра на сервере 1С исправить путь до исполняемого файла "ragent.exe" и "ras.exe" на актуальный "C:\Program Files\1cv8\8.3.xx.xxxx\bin\ragent.exe" и "C:\Program Files\1cv8\8.3.xx.xxxx\bin\ras.exe"
HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Services\1C:Enterprise 8.3 Remote Server\ImagePath
HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Services\1C:Enterprise 8.3 Server Agent (x86-64)\ImagePath
HKEY_LOCAL_MACHINE\SYSTEM\ControlSet002\Services\1C:Enterprise 8.3 Remote Server\ImagePath
HKEY_LOCAL_MACHINE\SYSTEM\ControlSet002\Services\1C:Enterprise 8.3 Server Agent (x86-64)\ImagePath
HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\1C:Enterprise 8.3 Remote Server\ImagePath
HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\1C:Enterprise 8.3 Server Agent (x86-64)\ImagePath

В ветках реестра на сервере лицензий SRVLIC02 исправить путь до исполняемого файла "ragent.exe" на актуальный "C:\Program Files\1cv8\8.3.17.1851\bin\ragent.exe"
HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Services\1C:Enterprise_SrvLic03\ImagePath
HKEY_LOCAL_MACHINE\SYSTEM\ControlSet002\Services\1C:Enterprise_SrvLic03\ImagePath
HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\1C:Enterprise_SrvLic03\ImagePath
