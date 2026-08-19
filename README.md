# Time zone proxy sync on/off

Timezone proxy sync On: Enable-ScheduledTask -TaskName "Webshare Timezone Sync"

Timezone proxy sync Off: Disable-ScheduledTask -TaskName "Webshare Timezone Sync"; Set-TimeZone -Id "Pacific Standard Time"


current proxy timezone info: Get-Content "C:\Scripts\WebshareTimezoneSync.log"
