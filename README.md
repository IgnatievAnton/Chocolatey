# Chocolatey
Инструкция :
1. При использовании CMD для Chocolatey открывайте от имени root'а 
2. Для установки Chocolatey в CMD следующую команду - @"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
3. Скачиваете репозиторий и выполняете в CMD - cinst packages.config -Y
4. DONE 
