# Lethalize
Lethal Company Mod Loader

For now this repo simply hosts install scripts for Lethal Company Mods.

# BepInEx Mods

## Uninstall Melonloader
You will likely want to uninstall MelonLoader if you are swapping to BepInEx.

`powershell -nop -ExecutionPolicy Bypass -c "Invoke-Command -ScriptBlock ([scriptblock]::Create([System.Text.Encoding]::UTF8.GetString((New-Object Net.WebClient).DownloadData('https://github.com/KrystilizeNevaDies/Lethalize/releases/download/scripts-uninstall-melonloader-0.0.0/Remove-Melonloader.ps1'))))"`

# Install MoreCompany
This also installs BepInEx

`powershell -nop -ExecutionPolicy Bypass -c "Invoke-Command -ScriptBlock ([scriptblock]::Create([System.Text.Encoding]::UTF8.GetString((New-Object Net.WebClient).DownloadData('https://github.com/julian-ladjani/Lethalize/releases/download/0.0.3/Install-MoreCompany.ps1')))) -ArgumentList @('-morecompany','1.6.0', '-latecompany', '1.0.4')"`
