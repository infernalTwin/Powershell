# Adversary Tactics - Powershell

### Version
(Get-ItemProperty HKLM:\SOFTWARE\Microsoft\PowerShell\*\PowerShellEngine -Name PowerShellVersion).PowerShellVersion

### Execution Policy
You can disable execution policies in a number of ways:
- powershell.exe -exec bypass
- Set-ExecutionPolicy -ExecutionPolicy Bypass -Scope Process
- https://blog.netspi.com/15-ways-to-bypass-the-powershell-executionpolicy/

Get-Command -Name *process*
