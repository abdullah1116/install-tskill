# install-tskill
install command prompt command 'tskill' in windows 10 

Run command in powerShell(admin)

iwr -outf tskill.exe "https://github.com/abdullah1116/install-tskill/releases/download/v/tskill.exe";move .\tskill.exe $Env:windir\system32
