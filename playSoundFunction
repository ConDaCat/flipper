function PlaySound {
[CmdletBinding()]
param (	
[Parameter (Mandatory = $True, Position=0, ValueFromPipeline = $True)]
[string]$File
)
$PlaySound=New-Object System.Media.SoundPlayer;$PlaySound.SoundLocation=$File;$PlaySound.playsync()
}
